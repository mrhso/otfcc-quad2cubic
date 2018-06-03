# otfcc-quad2cubic
[筹划中] 将 TrueType 的 otfcc dump 提取 glyf，输送给 tx 转换为 CFF glyf，并写入新的 otfcc dump 的程序。

## 依赖
- [otfcc](https://github.com/caryll/otfcc)
- [AFDKO](https://github.com/adobe-type-tools/afdko)

## 用法
```
otfccdump input.ttf | otfcc-q2c [OPTIONS] | otfccbuild -o output.otf

-x, --exact : 使用精确（无损）转换，而不优化曲线。
```
