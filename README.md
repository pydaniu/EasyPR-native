### 说明
+ 此项目是提供车牌识别的java接口，不做源码的任何修改，只在上面增加相关接口
+ [EasyPR][1]为此工程的子模块，没有做任何修改
+ [EasyPR-change](EasyPR-change)替换[EasyPR][1]中的源代码文件，不然无法加载自己定义的路径的模型文件，源代码中有bug
+ [NativeEasyPR](NativeEasyPR)提供c++层的native代码,目前只提供jni
+ [easyprjava](easyprjava)提供EasyPR的java接口
+ git clone代码之后记得git submodule update -f(强制更新一下子模块,然后按照文档替换相关源文件)
+ 或者下载zip包之后去[EasyPR][1],下载最新代码，如果使用我编译好的dll(x64_vc12)，则无需下载和更新[EasyPR][1]

### 本项目地址
+ [github][2]
+ [oschina][3]
+ [coding][4]

### NativeEasyPR中easyprtest-c++测试效果如下
![easyprtes-cpp效果图](NativeEasyPR/easyprtest/shows.png)

具体使用请参见[NativeEasyPR](NativeEasyPR)

### easyprjava EasyPRTest.java测试效果如下
![EasyPRTest.java效果图](easyprjava/shows.png)

具体使用请参见[easyprjava](easyprjava)

### java-web展示效果图如下
![imageDemo效果图](easyprjavaweb/shows.jpg)

具体使用请参见[easyprjavaweb](easyprjavaweb)

[1]: https://git.oschina.net/easypr/EasyPR
[2]: https://github.com/smirkcat/EasyPR-native.git
[3]: https://git.oschina.net/smirkcat/EasyPR-native.git
[4]: https://git.coding.net/smirkcat/EasyPR-native.git