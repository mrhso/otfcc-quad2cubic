# otfcc-quad2cubic
[筹划中] 将 TrueType 的 otfcc dump 提取 glyf，输送给 tx 转换为 CFF glyf，并写入新的 otfcc dump 的程序。

## 依赖
- [otfcc](https://github.com/caryll/otfcc)

## 用法
```
otfccdump input.ttf | otfcc-q2c [OPTIONS] | otfccbuild -o output.otf

-x, --exact : 使用数学上的方法转曲，而不简化曲线。
```

## 计划
目前程序无能力制作，企待有能力者编写。
