1.下载Node.js
[node官网](http://nodejs.org/)


2.在mac终端运行下面命令，输入密码安装cordova
`sudo npm install －g cordvoa`
![这里写图片描述](http://img.blog.csdn.net/20160723122549452)
sudo是因为需要管理员权限，-g是全局安装
[cordvoa官网命令行帮助](http://cordova.apache.org/docs/en/4.0.0/guide/cli/index.html#The%20Command-Line%20Interface)


3.执行以下代码创建一个cordvoa应用
`cordova create hello com.example.hello HelloWorld`
第一个参数是文件目录，第二个参数是app id, 第三个参数是显示的title
![这里写图片描述](http://img.blog.csdn.net/20160723130325248)


4.定位到hello目录文件夹，为项目安装平台模块
```
cd hello
cordova platform add ios
```
![这里写图片描述](http://img.blog.csdn.net/20160723132039071)

5.打开xcodeproj项目的文件位置双击打开，如果已安装Xcode就能顺利的打开项目了
`hello/platform/ios/`
![这里写图片描述](http://img.blog.csdn.net/20160723132307869)

6.可以用编写html项目的IDE打开www下的index.html查看效果，在浏览器打开即可
![这里写图片描述](http://img.blog.csdn.net/20160723133719281)

7.在Xcode打开iOS 模拟器如果看到以下效果说明环境已经搭建成功
![这里写图片描述](http://img.blog.csdn.net/20160723134047833)
