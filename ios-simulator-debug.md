# iOS模拟器调试技巧

iOS设备众多，前端同学在开发过程中难免会遇到兼容性问题。这个时候手头又没有特定的机型，该如何复现bug呢，其实Mac系统当中就内置了调试工具，而且很好用，
复现bug的成本瞬间就小了很多，让我们来看看是怎么实现的。

#### 准备

- Mac 系统
- 电脑上需要安装 xcode，可以通过apple store或者在线下载的方式安装。

#### 下载

打开 Xcode -> Preferences -> Components 
选择你需要的ios版本下载


#### 创建目录

```
~/Library/Caches/com.apple.dt.Xcode/Downloads/
```

#### 常见版本模拟器下载地址

```
8
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK8_1-8.1.1.1434581536.dmg
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK8_2-8.2.1.1434581536.dmg
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK8_3-8.3.1.1434581536.dmg
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK8_4-8.4.1.1435785476.dmg
9
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK9_0-9.0.1.1443554484.dmg
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK9_1-9.1.1.1446593668.dmg
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK9_2-9.2.1.1451951473.dmg
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK9_3-9.3.1.1460411551.dmg
10
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK10_0-10.0.1.1474488730.dmg
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK10_1-10.1.1.1476902849.dmg
https://devimages-cdn.apple.com/downloads/xcode/simulators/com.apple.pkg.iPhoneSimulatorSDK10_2-10.2.1.1484185528.dmg
```

如果没有mac怎么办
有两种办法用虚拟机在虚拟机里面装一个Mac系统，或者用Xamarin去运行iOS模拟器。
