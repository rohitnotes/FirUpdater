# FirUpdater [ ![Download](https://api.bintray.com/packages/sfsheng0322/maven/FirUpdater/images/download.svg) ](https://bintray.com/sfsheng0322/maven/FirUpdater/_latestVersion)

Fir.im通道APK更新器，使用简单，让自己的demo快速具备升级功能

<br/>

### 应用截图

<img src="/resources/res.png" >

<br/>

### Gradle:

工程的 build.gradle 添加：

    allprojects {
        repositories {
            maven { url 'https://dl.bintray.com/sfsheng0322/maven' }
        }
    }
    
模块的 build.gradle 添加：

    compile 'com.sunfusheng:FirUpdater:<latest-version>'

<br/>

### 使用

简单升级，一行代码即可：

    new FirUpdater(context, YOUR_FIR_API_TOKEN, YOUR_FIR_APP_ID).checkVersion();
    
如果你需要更多设置，请参考：

    new FirUpdater(context)
        .apiToken(YOUR_FIR_API_TOKEN)
        .appId(YOUR_FIR_APP_ID)
        .apkPath(YOUR_APK_PATH)
        .checkVersion();
    
<br/>

### 扫一扫[Fir.im](https://fir.im/FirUpdater)二维码下载APK

<br/>

<img src="/resources/fir.im.png" style="width: 30%;" alt="s">

<br/>

### 关注我吧，让我们做朋友^_^

<img src="http://ourvm0t8d.bkt.clouddn.com/follow_me.png">

### 打个赏吧，给作者加点油^_^

<img src="http://ourvm0t8d.bkt.clouddn.com/reward_me.png" >

### 关于我

[GitHub: sfsheng0322](https://github.com/sfsheng0322)  

[个人邮箱: sfsheng0322@126.com](https://mail.126.com/)
  
[个人博客: sunfusheng.com](http://sunfusheng.com/)
  
[简书主页](http://www.jianshu.com/users/88509e7e2ed1/latest_articles)
  
[新浪微博](http://weibo.com/u/3852192525) 