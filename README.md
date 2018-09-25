# AndroidDemo
整理一份自己学习android的合集（现在整理下以前的笔记，写作一个demo作为总结，也是查漏补缺，同时可以比较下以前与现在自己的能力提升了多少！）
- 从2018/1/23开始  新建项目，计划——开始整理；
- 2018/1/26, 常用widget与布局文件；
- 2018/1/27 监听事件、资源文件;
- 2018/1/28 界面跳转、动画过渡 + 1/26布局的补充；
- 2018/1/29 Activity带返回值跳转,界面全屏形式与对话框形式 + Activity启动模式、生命周期;
- 2018/1/30 动画(补间动画、帧动画、属性动画)、动画监听;
- 2018/1/31 Android多线程、异步任务(AsycTask)；
- 2018/2/1 网络、Http协议；
```
3/11将此前网络这里的部分熟悉下,关于网络部分有几个概念以及需要注意的地方，之后会持续更新readme；
```
- 2018/2/2 高级界面01之(RadioButton与CheckBox、菜单Menu、常用对话框)
- 2018/2/3 高级界面02之(Toast、Notification、美化布局(背景选择器、样式)、json（简单打包与解析）)
- 2018/2/4 高级界面03之(自定义View、Canvas画布类、自定义View的事件监听)
```
遗留问题：
1.拖动图片会拖出屏幕，这个问题很严重啊，怎么解决？
2.天气趋势图还没有做！
3.自定义键盘控制图片移动
```
- 2018/2/5 高级界面04之(自定义ViewGroup、SurfaceView)
- 2018/2/6 高级界面05之(Intent补充篇)
```
1.可能还有点遗留问题，待处理，不太重要。
```
- 2018/2/7 服务01之(Service的介绍、服务的创建/注册、服务的启动/终止、服务的生命周期、绑定服务和非绑定服务)
```
1.service里的数据实时更新activity不能处理,这个得近些时日找些资料弥补下,很重要!
2.可以看下以前自己做蓝牙的时候的代码...
```
- 2018/2/8 服务02之(AIDL(跨进程通信)、前台服务、IntentService + SAX解析XML/PULL解析XML)
```
1.对于AIDL的了解尚少，之前看见别的音乐播放器有用到这个,之后再完整去理解！
2.关于解析的部分整理,之后会花时间统一整理,(SAX解析XML/LPULL解析XML/json解析)，应该还有很多不足的地方！
```
- 2018/2/9 广播(广播的发送/创建/接收/注册、有序/无序广播、广播生命周期、系统广播)
```
1.隐式意图跨进程发送广播，但是没实现，待处理;
2.同服务一样，广播的内容如何更新ui界面,待考虑;
3.广播接收器中不能做耗时的操作，广播接收器生命周期最多10s，不要开线程，但是开个线程也没有进崩溃的bug，待处理；
4.常见系统广播：发送短信广播，来电广播，开机广播，手机电量改变广播,这些需要花费时间去写demo测试；
5.在广播中弹出dialog失败，待处理；
```
- 2018/2/10 音乐播放类(MediaPlayer类、音效池SoundPool)
```
1.音乐播放,现今都是网络下载本地、播放,所以方式2(载入sdcard下的音乐文件)显得尤为重要;
2.这里的musicplayer有问题的，而且写法似乎不标准，不建议...
3/12看到这个地方，有时间把音乐播放的部分写一个简易demo；
musicDNA是一款不错的音乐播放器项目(很多开源音乐源码remusic等可以参考)。
```
- 2018/2/11 数据存储(文件存储、sharedPreference存储方式、sqlite3介绍、五大存储方式)
```
1.开始数据存储；
```
- 2018/2/12 内容提供者(ContentProvider、数据库的访问与制作)
```
1. cmd命令行写关于数据的增删改查等命令得加强；
2. 项目-图片管理器（用ContentProvider完成，待完成）；

```
- 2018/2/13 界面优化01(MVC框架介绍(Model/View/Controller)、常用3类适配器、示例：联系人的增删改查)
- 2018/2/14 界面优化02(ListView动态增加删除列表、本地数据库分页显示、实现网络JSON数据分页显示、PullToRefresh下拉刷新控件)
```
1.客户端与服务器的实时聊天通信：
如何实现本地与服务器进行聊天，得看下后台服务器的知识点了；
2.比较差异：自己写的PullToRefresh下拉刷新控件与别人的第三方的不同；
测试了其中一个下拉刷新，哇，好复杂写的！(关于下拉刷新的关键就在与header高度的控制与触摸事件的处理)
以后有时间在理解，否则以后用到直接借用别人的代码吧；
```
- 2018/2/15 界面优化03(GridView/Spinner适配器、ListView使用二级缓存加载网络图片、OOM(Out Of Memory)、Java引用分类(强，软，弱，虚))
```
1.关于Java引用分类(强，软，弱，虚)没有给出实际例子,之后会把这部分进行学习更新；
2.OOM(Out Of Memory)的理解还太浅；
```
- 2018/2/16 界面优化04(Fragment动态加载/静态加载、Fragment的栈管理、Activity与Fragment间的数据传递、
Fragment的动画效果、Fragment的生命周期、ViewPager + Fragment实现向导功能)
- 2018/2/17 界面优化05(Bitmap对象的获取、Bitmap图片变形、Bitmap OOM处理)
```
1.对于Bitmap OOM处理的处理，理解；
```
- 2018/2/18 传感器+webview
- 2018/2/19 多媒体(音频录制、视频录制、视频播放、Android摄像头基础)
- 2018/2/20 屏幕适配、国际化
- 2018/2/21 第三方框架(百度地图、环信、XUtils、Volley)

- 2018/3/11
1. 补充下mvc/mvp/mvvm的例子-简单的demo
2. Android 5种数据存储方式

- 2018/3/12 继昨天完善数据存储/内容提供者
- 2018/4/8  补充fragment的部分，stack以及事务处理，以及webview，学到了一个好的加载库（AgentWeb，以前就有fork结果以前没怎么留意，啊啊啊）。

- 2018/4/22 重温下自定义view， 完成自定义日历控件。

- 购物车效果(ShoppingCart) 9/13



# 参考文章以及第三方项目
> 安卓UI相关开源项目库汇总:
- https://github.com/opendigg/awesome-github-android-ui 
- https://hndeveloper.github.io/2017/github-android-ui.html GitHub上受欢迎的Android UI Library
- https://github.com/CymChad/BaseRecyclerViewAdapterHelper 一个强大的RecyclerAdapter框架
- https://github.com/Blankj/AndroidUtilCode Android开发不得不收藏的Utils
- https://github.com/LuckyCode1992/recycleviewsummary 上拉加载下拉刷新自定义，左右侧滑自定义
- https://github.com/jaydenxiao2016/AndroidFire 新闻客户端（公司项目参考的框架）
- https://blog.csdn.net/lmj623565791/article/details/45059587 Android RecyclerView 使用完全解析 体验艺术般的控件
- https://github.com/yuzhiqiang1993/zxing 基于zxing的扫一扫，集成简单，速度快，可配置颜色，还有闪光灯，解析二维码图片，生成二维码等功能
- https://github.com/Aspsine/IRecyclerView 下拉刷新库
- https://github.com/fanrunqi/MaterialLogin 用Transition做一个漂亮的登录界面
- https://github.com/yanzhenjie/SwipeRecyclerView RecyclerView侧滑菜单，Item拖拽，滑动删除Item，自动加载更多，HeaderView，FooterView，Item分组黏贴
- https://github.com/EnjoyAndroid/RecyclerviewNestedRecyclerview RecyclerView嵌套RecyclerView An example of a recyclerview nested recyclerview



# 开机导航页效果合集

- https://github.com/JeasonWong/LiulishuoPreview 用VideoView实现英语流利说炫酷引导页





# 参考文章以及第三方项目

> 安卓UI相关开源项目库汇总:

- https://github.com/opendigg/awesome-github-android-ui 

- https://hndeveloper.github.io/2017/github-android-ui.html GitHub上受欢迎的Android UI Library

- https://github.com/CymChad/BaseRecyclerViewAdapterHelper 一个强大的RecyclerAdapter框架

- https://github.com/Blankj/AndroidUtilCode Android开发不得不收藏的Utils

- https://github.com/LuckyCode1992/recycleviewsummary 上拉加载下拉刷新自定义，左右侧滑自定义

- https://github.com/jaydenxiao2016/AndroidFire 新闻客户端（公司项目参考的框架）

- https://blog.csdn.net/lmj623565791/article/details/45059587 Android RecyclerView 使用完全解析 体验艺术般的控件

- https://github.com/yuzhiqiang1993/zxing 基于zxing的扫一扫，集成简单，速度快，可配置颜色，还有闪光灯，解析二维码图片，生成二维码等功能

- https://github.com/Aspsine/IRecyclerView 下拉刷新库

- https://github.com/fanrunqi/MaterialLogin 用Transition做一个漂亮的登录界面

- https://github.com/yanzhenjie/SwipeRecyclerView RecyclerView侧滑菜单，Item拖拽，滑动删除Item，自动加载更多，HeaderView，FooterView，Item分组黏贴

- https://github.com/EnjoyAndroid/RecyclerviewNestedRecyclerview RecyclerView嵌套RecyclerView An example of a recyclerview nested recyclerview

- https://github.com/piscessu/BaseQuickAdapter 简单封装了下RecyclerViewAdapter，避免每次都要写一堆重复代码


# 动画效果项目合集
- https://github.com/ChengangFeng/TickView 一个精致的打钩小动画，模仿轻芒杂志标记已读的动画



# 快速开发框架篇
- https://github.com/chengyuchun/androidRapid
- https://github.com/qiaoyhh/AndroidProjectHelper （公司项目参考的框架）
- https://github.com/songzhixiang/BasePro 快速开发框架

# 异常问题及解决办法:
- 1.解决kotlin.KotlinNullPointerException以及问题分析 https://blog.csdn.net/BigBoySunshine/article/details/79299065 
- 2.解决gradle "Error:Cause: unable to find valid certification path to requested target" https://blog.csdn.net/hzh_csdn/article/details/60572145
- 3.异常:
```
Error:Execution failed for task ':app:transformClassesWithDexForDebug'.
  com.android.build.api.transform.TransformException: com.android.ide.common.process.ProcessException: java.util.concurrent.ExecutionException: com.android.dex.DexException:
 Multiple dex files define Landroid/support/design/widget/CoordinatorLayout$Behavior;
 - 解决办法:修改app的SdkVersion版本一致
 ```
 - 4.AS异常:
 ```
 Error:Could not find support-fragment.jar (com.android.support:support-fragment:27.1.1).
Searched in the following locations:
    https://jcenter.bintray.com/com/android/support/support-fragment/27.1.1/support-fragment-27.1.1.jar

Please install the Android Support Repository from the Android SDK Manager.
<a href="openAndroidSdkManager">Open Android SDK Manager</a>
 ```
 解决办法：https://blog.csdn.net/qq_16768763/article/details/81780982
 - 5.AS异常
 ```
 找不到AsyncTaskCompatl类 NoClassDefFoundError: support/v4/os/AsyncTaskCompat 
 ```
 https://blog.csdn.net/qq_26467059/article/details/79336276
 


# 未完成的部分以及待学习的地方
- 1.MultiScrollDemoActivity页面显示存在滑动冲突问题；
- 2.https://www.jianshu.com/p/2badfbb3a33b RxJava1.X升级到RxJava2.X笔记

# 后台管理系统
-1.https://github.com/lenve/vhr  微人事是一个前后端分离的人力资源管理系统，项目采用SpringBoot+Vue开发。


