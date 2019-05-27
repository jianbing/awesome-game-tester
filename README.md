# Awesome Game Tester

收集整理了游戏测试人员工作相关的一些资源清单，包括学习资料，测试工具，开源框架，效率工具等。

---

## 学习资料

### 视频
- [游戏测试入门](https://www.imooc.com/learn/880)
- [游戏测试从入门到精通](http://study.163.com/course/introduction/1002858009.htm)

### 书籍
- [软件测试的艺术（原书第3版）](https://item.jd.com/10978790.html) - 软件测试经典书籍
- [游戏测试精通](https://book.douban.com/subject/2271968/) - 《Game Testing: All in One》 第一版翻译
- [Game Testing: All in One（3rd Edition）](https://www.amazon.com/Game-Testing-Charles-P-Schultz/dp/1942270763) - 英文版
- [Google软件测试之道](https://item.jd.com/11330792.html)
- [海盗派测试分析](https://item.jd.com/12037941.html)
- [点石成金：访客至上的Web和移动可用性设计秘笈（原书第3版）](https://item.jd.com/11589225.html)

### 社区
- [TesterHome](https://testerhome.com/)


## 性能监控

### 安卓
- [WeTest助手](https://wetest.qq.com/cloud/help/effective) - WeTest平台出品的APP性能数据采集工具，支持Android2.3 - 5.1
- [GT](https://github.com/Tencent/GT) - 腾讯开源的APP的性能监控，调试框架
- [Emmagee](https://github.com/NetEase/Emmagee) - 网易开源的APP性能监控工具，不支持Android 7.0以上版本
- [adb](https://developer.android.com/studio/command-line/adb.html) - 安卓SDK自带的调试工具，通过adb shell命令获取性能数据
- [GameBench](https://www.gamebench.net/) - 收费软件
- [Battery Historian](https://github.com/google/battery-historian) - 生成电量消耗报告
- [Trepn Profiler](https://developer.qualcomm.com/software/trepn-power-profiler) - 用于移动设备上的应用功耗和性能分析工具
- [Snapdragon Profiler](https://developer.qualcomm.com/software/snapdragon-profiler) - 骁龙平台的性能分析软件
- [Tegra Graphics Debugger](http://docs.nvidia.com/tegra-graphics-debugger/) - NVIDIA Tegra的性能分析软件
- [Mali Graphics Debugger](https://developer.arm.com/products/software-development-tools/graphics-development-tools/mali-graphics-debugger)


### iOS
- [Xcode Instruments](https://help.apple.com/instruments/mac/10.0/) - Xcode自带的性能调试工具集
- [GT](http://gt.tencent.com/) - 腾讯开源的APP的性能监控，调试框架，需要接入SDK 
- [iStatistica](https://www.imagetasks.com/system-battery-network-monitor-widget/)
- [WeTest助手](https://wetest.qq.com/cloud/help/effective) - iOS7以上，需要越狱
- [GameBench](https://www.gamebench.net/) - 收费软件

### PC
- [nmon](http://nmon.sourceforge.net/pmwiki.php) - Linux操作系统上广泛使用的监控与分析工具


## 性能分析

### Unity
- [Unity Profiler](https://docs.unity3d.com/Manual/Profiler.html) - Unity自带的Profile工具
- [MemoryProfiler](https://bitbucket.org/Unity-Technologies/memoryprofiler/overview) - Unity5.3新增的内存分析工具
- [UWA](https://www.uwa4d.com/)  - 本地测试收费，需要集成SDK
- [UPA](http://wetest.qq.com/cube/)  - WeTest联合Unity官方打造的性能分析工具，收费 

## 压力测试

### 安卓
- [Monkey](https://developer.android.com/studio/test/monkey.html) - 安卓ADB自带的稳定性测试工具

### PC
- [LoadRunner](https://software.microfocus.com/zh-cn/software/loadrunner) - 老牌压测工具，收费
- [Locust](https://www.locust.io/) - 开源的压测工具，支持HTTP，可以通过扩展支持自定义协议

## 静态分析
- [UnityEngineAnalyzer](https://github.com/vad710/UnityEngineAnalyzer) - 基于微软Roslyn插件，对Unity的代码做静态分析

## UI自动化
### 安卓
- [Airtest](http://airtest.netease.com/index.html) - 网易开源的UI自动化测试工具，适用于游戏和App
- [ATX](https://github.com/NetEaseGame/ATX) - 基于图像识别完成游戏的自动化操作
- [GAutomator](https://github.com/Tencent/GAutomator) - 针对Unity手游的UI自动化测试框架
- [adb](https://developer.android.com/studio/command-line/adb.html) - 通过adb shell input命令来完成点击，滑动等操作
- [按键精灵手机版](http://www.mobileanjian.com/)

### iOS
- [Airtest](http://airtest.netease.com/index.html) - 网易开源的UI自动化测试工具，适用于游戏和App
- [ATX](https://github.com/NetEaseGame/ATX) - 基于图像识别完成游戏的自动化操作
- [按键精灵手机版](http://www.mobileanjian.com/) - 需要越狱
- [facebook-wda](https://github.com/openatx/facebook-wda) - Facebook WebDriverAgent非官方Python客户端

### PC
- [Airtest](http://airtest.netease.com/index.html) - 网易开源的UI自动化测试工具，适用于游戏和App
- [按键精灵](http://www.anjian.com/download.htm) - 老牌模拟鼠标键盘操作的软件
- [SikuliX](http://www.sikulix.com/) - 图形化编程工具
- [PyAutoGUI](https://muxuezi.github.io/posts/doc-pyautogui.html) - Python库，模拟鼠标键盘操作

## 弱网工具
- [clumsy](http://jagt.github.io/clumsy/) - Windows平台下人工造成不稳定的网络状况，方便易用
- [Network Emulator Toolkit](http://blog.mrpol.nl/2010/01/14/network-emulator-toolkit/) - Windows平台下的弱网模拟工具
- [Augmented Traffic Control](https://github.com/facebook/augmented-traffic-control) - Facebook开源的网络模拟工具
- [Charles](https://www.charlesproxy.com/) - 支持HTTP，HTTPS协议的弱网测试
- [Fiddler](https://www.telerik.com/fiddler) - 支持HTTP，HTTPS协议的弱网测试


## 榜单排行
- [七麦数据](https://www.qimai.cn/)
- [TalkingData](http://mi.talkingdata.com/index.html)
- [艾瑞指数](http://data.iresearch.com.cn/iRIndex.shtml)
- [腾讯移动分析数据中心](http://mta.qq.com/mta/data/device)
- [手机CPU性能天梯](http://www.mydrivers.com/zhuanti/tianti/01/)

## 安全测试
### 抓包工具
- WPE - 老牌封包编辑器
- [tcpdump](http://www.androidtcpdump.com/android-tcpdump/downloads) - 安卓抓包
- [Wireshark](https://www.wireshark.org/) - 网络封包分析软件
- [pydivert](https://pypi.python.org/pypi/pydivert/2.0.1) - Python库，WinDivert的Python绑定
- [Charles](https://www.charlesproxy.com/download/) - HTTP抓包神器
- [Fiddler](https://www.telerik.com/fiddler) - HTTP协议调试代理工具

### 动态调试
- IDA Pro - 交互式反汇编器专业版

### 反编译
- [ApkTool](http://ibotpeaches.github.io/Apktool/) - APK反编译工具
- [NET.Reflector](https://www.red-gate.com/products/dotnet-development/reflector/) - Unity安卓DLL代码文件反编译工具
- dnSpy - .net反编译工具
- [AssetStudio](https://github.com/Perfare/AssetStudio) - Unity AssetBundle破解
    
### 内存修改
- 烧饼修改器 - 安卓端游戏内存修改工具，需要Root，同类的还有GG修改器，八门神器等
- [Cheat Engine](http://www.cheatengine.org/) - PC端内存修改工具

### 学习资料
- [游戏安全——手游安全技术入门](https://item.jd.com/11918839.html)
- [游戏安全实验室](http://gslab.qq.com/js/)

## 分发测试
- [TestFlight](https://developer.apple.com/testflight/) - 苹果出品

## 缺陷管理
- [禅道](http://www.zentao.net/) - 国产开源项目管理软件
- [Redmine](http://www.redmine.org/projects/redmine/wiki/Download)
- [Jira](https://www.atlassian.com/software/jira/download)
- [Quality Center](https://software.microfocus.com/zh-cn/software/quality-center)

## 设备管理
- [STF](https://openstf.io/) - 大名鼎鼎的Web端进行批量移动设备管理控制工具
- [ATX-SERVER](https://github.com/openatx/atx-server) - Go语言编写的安卓设备集群管理
- [ShareDevice](https://github.com/sunshine4me/ShareDevice) - .net core开发的轻量级设备共享工具


## 其他工具
- [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - 与iOS设备进行通信的跨平台协议库
    - [pymobiledevice](https://github.com/iOSForensics/pymobiledevice) - libimobiledevice的Python绑定
    - [imobiledevice](http://docs.quamotion.mobi/en/latest/imobiledevice/download.html) - Quamotion提供的libimobiledevice的Windows平台可执行版本
- Cocos2d-x Console模块 - Cocos2d-x 3.0新增的基于TCP的远程调试模块
  - [API文档](https://docs.cocos2d-x.org/api-ref/cplusplus/V3.0/d6/dbe/classcocos2d_1_1_console.html)
  - [参考资料](https://github.com/iOSForensics/pymobiledevice)

## 数据库工具
- [Robo 3T](https://robomongo.org/download) - MongoDB可视化工具

## 效率工具
- [Wox](http://www.getwox.com/) - Windows下免费开源的效率启动器
- [Xmind](http://www.xmindchina.net/) - 思维导图编写
- [ProcessOn](https://www.processon.com/) - 在线绘图平台，流程图，思维导图等
- [Bcompare](http://www.scootersoftware.com/download.php) - 文本对比神器，收费
- [DiffMerge](http://www.sourcegear.com/diffmerge/downloaded.php) - 免费的文本对比工具
- [Snipaste](https://zh.snipaste.com/) - 截图工具
- [AnyDesk](http://www.voidtools.com/) - 远程桌面连接
- [Cmder](http://cmder.net/) - Cmd的替代品
- [QuickLook](https://github.com/QL-Win/QuickLook/releases) - 快速预览

## 编程学习
- [codecademy](https://www.codecademy.com/)
- [实验楼](http://www.xmindchina.net/)
- [慕课网](https://www.imooc.com/)
- [MOOC学院](https://mooc.guokr.com/course/)

---

## 本项目的参与者
- 贡献者：[煎饼](https://github.com/jianbing)，[jiazurongyu](https://gitee.com/jiazurongyu)



---

### 如何参与
非常欢迎大家贡献高质量的资源，可以联系QQ(326333381)，或者提交PR。
