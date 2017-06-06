# HBRSAHandlerLib
RSA静态库制作 使用到的openssl支持bitcode

文中使用到了openssl库，这个库对bitcode是支持的。但是通常openssl对bitcode都是不支持的。
我们可以通过开源的自动编译脚本去编译 openssl库。

这里是方法的介绍
[iOS编译OpenSSL静态库(使用脚本自动编译)](http://www.jianshu.com/p/651513cab181)
[脚本地址](https://github.com/x2on/OpenSSL-for-iPhone)

demo中的openssl是支持8 - 9.0  随着系统的跟新可能后期openssl将不再支持，之后的话就可以参照链接的方法自己编译openssl库

[在此分享打包静态库的一些总结 ](http://note.youdao.com/noteshare?id=3dc7d94434253dc5c4c728973e65daa2)
