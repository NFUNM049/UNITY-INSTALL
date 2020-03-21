# UNITY-INSTALL
网新前沿ARVR第一周作业，操作过程

网新前沿VRAR第一周作业：

>  由于作业布置时已完成所有安装内容，故无法给出详细的截图进行展示，所以用文字进行描述。

[发布录屏](https://pan.baidu.com/s/1j9U_2GW-nTYyMVK5bbpPQA)，点击到百度云下载观看。**提取码：2ddf**

## 1.安装Unity3d软件

* 首先安装Unity3d开发平台 - 点击**UnitySetup64-5.6.2f1**这个文件，按照指示进行安装即可。
* 安装**UnityStandardAssetsSetup-5.6.2f1**资源包，直接安装即可。
* 安装完成，打开软件，根据指示进行Unity3d账号注册以及登录。登录账号后如下图所示，即可进行下一步操作。

<img src="F:\E学习资料\大三下\vr\0.1.png" alt="0.1"  />



## 2.安装[JDK](https://baike.baidu.com/item/jdk/1011)（Java Development Kit是 Java 语言的软件开发工具包([SDK](https://baike.baidu.com/item/SDK))。）

* 安装**jdk-8u144-windows-i586_8.0.1440.1**，选择安装路径时请务必记住路径，后面会有所需要。这里还需要注意的是安装的文件夹名**不可出现中文或其他字符**，写英文英文英文！！！否则会安装失败。
* 接下来进行环境变量的配置。
  * 打开系统 -> 高级系统设置 -> 环境变量
  * 新建 -> 变量名"JAVA_HOME"，变量值f***\*:jdk\****（即JDK的安装路径）
  * 编辑->变量名"Path"，在原变量值的最后面加上 ***\*%JAVA_HOME%\bin\****之后点击确定。
* 检验是否安装成功，**打开我的电脑** -> **c盘** -> **输入cmd **-> **在cmd中输入Java -version**，如出现版本号及图片内容，则表示安装成功。

<img src="F:\E学习资料\大三下\vr\0.4.png" alt="0.4"  />

<img src="F:\E学习资料\大三下\vr\0.3.png" alt="0.3"  />

<img src="F:\E学习资料\大三下\vr\0.2.png" alt="0.2"  />



## 3.安装SDK（软件开发工具包）

![image-20200321115852513](C:\Users\林兴泽\AppData\Roaming\Typora\typora-user-images\image-20200321115852513.png)

* 解压sdk文件夹，点击SDK MANAGER进行安装，这里也需要记住安装路径，怕忘记的同学可以更改至熟悉的安装路径。
* 弹出安装页面后，等待资源更新完成，点击install 17 packages进行下载，选择Android SDK License -> accept license -> install，这里需要花费大概40分钟左右的时间安装，请大家耐心等待。

<img src="F:\E学习资料\大三下\vr\0.5.png" alt="0.5"  />

<img src="F:\E学习资料\大三下\vr\0.6.png" alt="0.6"  />



> **配置开发环境**：JDK和SDK都安装完成后，到Unity3d的edit选项卡下方的perference进行设置，点击Browse，找到刚刚安装JDK/SDK的文件夹所在的路径即可。

<img src="F:\E学习资料\大三下\vr\1.png" alt="1"  />

<img src="F:\E学习资料\大三下\vr\2.png" alt="2"  />

## 4.安装Andriod开发环境，目的是生成手机的apk文件。

* 找到**UnitySetup-Android-Support-for-Editor-5.6.2f1**这个文件，点击安装即可。
* 安装完成后，找到file下的build setting，点击andriod，如图所展示则安装成功！

<img src="F:\E学习资料\大三下\vr\3.png" alt="3"  />

<img src="F:\E学习资料\大三下\vr\4.png" alt="4" style="zoom:;" />



## 5.发布文件

* 适配安卓，填写配置信息，最后build之后会生成一个apk文件。

![5](F:\E学习资料\大三下\vr\5.png)



* 将这个apk文件拖入到夜神模拟器中。

![6](F:\E学习资料\大三下\vr\6.png)

 

* 双击这个拖进来的文件即可进行模拟使用。

![7](F:\E学习资料\大三下\vr\7.png)



（完）

