#enjoy it!

--------------
#DONE
1、支持XCode4 & XCode5
2、集成新浪微博SDK

#TODO
1、发帖、转发、评论

--------------

#首先感谢OSC开源中国,
#无私提供个人1000个私有仓库，受惠良久。
#今天把自己的一点干货拿出来跟大家分享。
#当作是对社区的汇报，以免自己良心不安。

--------------

#SinaMBlogNimbus
--------------

采用[nimbus](https://github.com/jverkoey/nimbus)框架，进行二次构建。

这是一个适用于网络请求后以tableview列表数据展现的一个简单框架，

通过这个框架，大家可以简单、便捷地处理和显示列表数据，

以新浪微博为例子，介绍框架的使用，通过开源的分享，跟大家一起技术交流。

--------------
项目clone到本地后

1、更新submodule：

   git submodule init 
   
   git submodule update
   

2、使用[CocoaPods](http://cocoapods.org)的命令安装其他依赖库：
   
   pod install

#ERROR解决方法

--------------
若出现这个问题：'vendor/SDURLCache' already exists in the index

git rm --cached vendor/SDURLCache

--------------
若出现这个问题：diff: /../Podfile.lock: No such file or directory 
diff: /Manifest.lock: No such file or directory 
error: The sandbox is not in sync with the Podfile.lock. Run 'pod install' or update your CocoaPods installation.

重新pod install