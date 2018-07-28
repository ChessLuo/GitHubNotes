### Android框架学习
  ---
对MVP的看法，引用一个网友的一句话：其实mvp大家可以这样去理解, 首先我们不看接口,只看实现类,第一步我们看presenter这个模块,这个里面做了什么?就是做actiity将要做的事情,我们用登录来说,这个persenter必须有登录是吧?那么好,我们给presenter一个方法 doLogin().那么这个dologin具体在哪里做呢? 在model里面做.那么做完后的回调给谁呢?给presenter,然后presenter把结果告诉activity,activity在去修改ui,那么最后一步,如何去登录? 在acitvity里面的点击时候 去调用我们的presenter,以上是伪代码,大家看看就好


* [google android官方架构项目](https://github.com/googlesamples/android-architecture)
* [安卓架构文章合集（a collection of android Architecture）](https://github.com/CameloeAnthony/AndroidArchitectureCollection)
* [Android-从零开始搭建android框架系列](https://www.jianshu.com/nb/3767449)
* [浅谈 MVP in Android](https://blog.csdn.net/lmj623565791/article/details/46596109)
* [Android MVP架构搭建（一）](http://www.jcodecraeer.com/a/anzhuokaifa/2017/1020/8625.html)
* [Android MVP升级路（二）时尚版](http://www.jcodecraeer.com/a/anzhuokaifa/2017/1024/8636.html)
* [一个整合了大量主流开源项目高度可配置化的 Android MVP 快速集成框架](https://github.com/JessYanCoding/MVPArms/blob/master/MVPArms.md)
































