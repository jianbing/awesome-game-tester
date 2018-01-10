# Awesome Game Tester

收集整理了游戏测试人员工作相关的一些资源清单，包括学习资料，测试工具，开源框架，效率工具等。

---

#### 学习资料
- 视频
    - [游戏测试入门(张敬峰)](https://www.imooc.com/learn/880)
    - [游戏测试从入门到精通](https://ke.qq.com/course/127426)（TesterHome出品）
    - [CE嗨入门教程]  (https://www.bilibili.com/video/av10655891/) (B站源)

- 书籍
    - [软件测试的艺术（原书第3版）](https://item.jd.com/10978790.html)（软件测试经典书籍） 
    - [游戏测试精通](https://book.douban.com/subject/2271968/)（Game Testing: All in One 第一版中文翻譯）
    - [Game Testing: All in One（3rd Edition）](https://www.amazon.com/Game-Testing-Charles-P-Schultz/dp/1942270763/ref=sr_1_1?s=books&ie=UTF8&qid=1515405306&sr=1-1&keywords=Game+Testing%3A+All+in+One)
    - [Google软件测试之道](https://item.jd.com/11330792.html) 

  
#### 性能测试
- 安卓客户端
    - [WeTest助手](https://wetest.qq.com/cloud/help/effective)
    - [GT](http://gt.tencent.com/) 
    - [Emmagee](https://github.com/NetEase/Emmagee)
    - [adb](https://developer.android.com/studio/command-line/adb.html)（安卓SDK自带的调试工具，通过adb shell命令获取性能数据）
    - [Monkey](https://developer.android.com/studio/test/monkey.html)（稳定性测试工具）
    
- iOS客户端
    - [Xcode Instruments](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/NavigatingInstruments.html#//apple_ref/doc/uid/TP40004652-CH8-SW1)
    - [WeTest助手](https://wetest.qq.com/cloud/help/effective)（需要越狱）
    - [GT](http://gt.tencent.com/)（需要把GT Framework嵌入工程 ）

- 服务端
    - [LoadRunner](https://software.microfocus.com/zh-cn/software/loadrunner)（老牌压测工具，付费）
    - [Locust](https://www.locust.io/)（开源的压测工具，支持HTTP，可以通过扩展支持自定义协议）

- Unity性能分析
    - [Unity Profiler](https://docs.unity3d.com/Manual/Profiler.html)（Unity自带的Profile工具）
    - [MemoryProfiler](https://bitbucket.org/Unity-Technologies/memoryprofiler/overview)（Unity5.3新增的内存分析工具）
    - [UWA](https://www.uwa4d.com/)(本地测试收费，需要集成SDK)
    - [UPA](http://wetest.qq.com/cube/)(WeTest联合Unity官方打造的性能分析工具 )


#### UI自动化测试
- PC平台
    - [按键精灵](http://www.anjian.com/download.htm)（老牌模拟鼠标键盘操作的软件）
    - [SikuliX](http://www.sikulix.com/)（图形化编程工具）
    - [PyAutoGUI](https://muxuezi.github.io/posts/doc-pyautogui.html)（Python库，模拟鼠标键盘操作）

- 安卓平台
    - [ATX](https://github.com/NetEaseGame/ATX)（基于图像识别，控件定位技术完成游戏的自动化）
    - [GAutomator](https://github.com/Tencent/GAutomator)（针对Unity手游的UI自动化测试框架）
    - [adb](https://developer.android.com/studio/command-line/adb.html)（通过adb shell input命令来完成点击，滑动等操作）
    - [按键精灵手机版](http://www.mobileanjian.com/)
   
- iOS平台
    - [ATX](https://github.com/NetEaseGame/ATX)（基于图像识别，控件定位技术完成游戏的自动化）
    - [按键精灵手机版](http://www.mobileanjian.com/)（需要越狱）

#### 弱网测试
- [clumsy](http://jagt.github.io/clumsy/)（Windows平台下人工造成不稳定的网络状况，方便易用）
- [Network Emulator Toolkit](http://blog.mrpol.nl/2010/01/14/network-emulator-toolkit/)（Windows平台下的弱网模拟工具）  
- [Augmented Traffic Control](https://github.com/facebook/augmented-traffic-control)（Facebook开源的网络模拟工具）
- [Charles](https://www.charlesproxy.com/)（支持HTTP，HTTPS协议的弱网测试）
 
#### 兼容性测试
- 参考数据
    - [腾讯移动分析数据中心](http://mta.qq.com/mta/data/device)
    - [手机CPU性能天梯](http://www.mydrivers.com/zhuanti/tianti/01/)
    
 
#### 安全测试
- 抓包工具
    - WPE（老牌封包编辑器）
    - [tcpdump](http://www.androidtcpdump.com/android-tcpdump/downloads)（安卓抓包）
    - [Wireshark](https://www.wireshark.org/)（网络封包分析软件）
    - [pydivert](https://pypi.python.org/pypi/pydivert/2.0.1)（Python库，WinDivert的Python绑定）
    - [Charles](https://www.charlesproxy.com/download/)（HTTP抓包神器）
    - [Fiddler](https://www.telerik.com/fiddler)（HTTP协议调试代理工具）
    
- 反编译
    - [ApkTool](http://ibotpeaches.github.io/Apktool/)（APK反编译工具）
    - [NET.Reflector](https://www.red-gate.com/products/dotnet-development/reflector/)（Unity安卓DLL代码文件反编译工具）
    
- 内存修改
    - 烧饼修改器（安卓端游戏内存修改工具，需要root）
    - [Cheat Engine](http://www.cheatengine.org/)（PC端内存修改工具）
    
- 书籍
    - [游戏安全——手游安全技术入门](https://item.jd.com/11918839.html)

#### 分发测试
- [TestFlight](https://developer.apple.com/testflight/)（苹果出品）

#### 其他框架
- [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice)（与iOS设备进行通信的跨平台协议库）
- [pymobiledevice](https://github.com/iOSForensics/pymobiledevice)（libimobiledevice的Python绑定）



#### 效率工具
- [Wox](http://www.getwox.com/)（Windows下免费开源的效率启动器）
- [Xmind](http://www.xmindchina.net/)（思维导图编写）
- [ProcessOn](https://www.processon.com/)（在线绘图平台，流程图，思维导图等）
- [Bcompare](http://www.scootersoftware.com/download.php)（文本对比神器）
- Setuna（Windows下的屏幕截图工具）

#### 缺陷管理
- [禅道](http://www.zentao.net/)（国产开源项目管理软件）
- [Redmine](http://www.redmine.org/projects/redmine/wiki/Download)
- [Jira](https://www.atlassian.com/software/jira/download)
- [Quality Center](https://software.microfocus.com/zh-cn/software/quality-center)

---

#### 本项目的参与者
- 贡献者：[煎饼](https://github.com/jianbing)，[jiazurongyu](https://gitee.com/jiazurongyu)

---

#### 如何参与
非常欢迎大家为列表贡献高质量的各种资源，提交PR时请留意：

- 请确保推荐的资源是游戏项目中使用过，且效果不错
- 请注明推荐理由

感谢您的贡献！
