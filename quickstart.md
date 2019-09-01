# OpenMV快速上手教程

## 驱动的下载和安装

### Windows驱动安装

将OpenMV Cam插到电脑上，正常情况Win10系统会自动安装驱动，不需要手动安装，这时在设备管理器中会看到串口：

![串口1](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LlAwaqhtxucm8dEDsGe%2F-LlB8UYD5cDOSt-nCXtM%2F-LlB8q_N_rATVkH9qAn4%2Fimage.png?alt=media&token=83051e6a-6732-4f9e-a8aa-b7631a5d2050)

但是Win7系统驱动不会自动安装驱动，这时在设备管理器中会出现一个叹号，表示没有正常安装驱动，这时就需要自己手动安装。

![串口2](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LlAwaqhtxucm8dEDsGe%2F-LlkAw4ZELnP5iqjapL3%2F-LlkDSdZf6tS00siUd6c%2Fimage.png?alt=media&token=c5a8dcdd-960d-4b49-9096-82b76359a48c)
### 下载驱动

百度网盘下载链接：https://pan.baidu.com/s/1z_unhOWznVESR32ywlj0EQ​

下载完后解压到桌面，然后右键设备管理器中的这个设备，然后选择**更新驱动程序软件**：

![串口3](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LlAwaqhtxucm8dEDsGe%2F-LlkAw4ZELnP5iqjapL3%2F-LlkEydrPhGqv3o-nGSj%2Fimage.png?alt=media&token=3fd531e1-76f3-4b11-ad75-4c623ff65b58)

选择**浏览我的计算机以查找驱动程序软件**

![串口4](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LlAwaqhtxucm8dEDsGe%2F-LlkAw4ZELnP5iqjapL3%2F-LlkDiRDQAVwPDMWv2RU%2Fimage.png?alt=media&token=a872b87d-d76f-41b8-8f19-b89b96738895)

点击**浏览**

![串口4](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LlAwaqhtxucm8dEDsGe%2F-LlkAw4ZELnP5iqjapL3%2F-LlkEMvHylazcBwS_RhL%2Fimage.png?alt=media&token=b6045ce1-5113-4333-bda3-2f49d7d2a1e6)

选中桌面上的**openmv_windows驱动**文件夹。

![串口4](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LlAwaqhtxucm8dEDsGe%2F-LlkAw4ZELnP5iqjapL3%2F-LlkDvbhn1OL4AT-wCxL%2Fimage.png?alt=media&token=f3ef2e38-b36d-4b63-8260-0572a22175cf)

![串口4](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LlAwaqhtxucm8dEDsGe%2F-LlkAw4ZELnP5iqjapL3%2F-LlkE5XMK1dBCgTcv__g%2Fimage.png?alt=media&token=2743cdb2-c943-404f-bd90-9230dc8e9e6d)

选择**始终安装此驱动程序软件**

![串口4](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LlAwaqhtxucm8dEDsGe%2F-LlkAw4ZELnP5iqjapL3%2F-LlkE9UeYCQ96ccfaBzC%2Fimage.png?alt=media&token=5ced2f83-1c88-4197-860e-0474f8c640f1)

这时应该会成功的安装好驱动。但是，如果你遇到下面的情况，就比较麻烦了。

![串口4](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LlAwaqhtxucm8dEDsGe%2F-LlkAw4ZELnP5iqjapL3%2F-LlkEEz_juv13JgeaQ2s%2Fimage.png?alt=media&token=ba3c6b8a-1c46-42a7-aa3e-31e57636f0b9)

驱动安装失败，大部分的情况都是电脑的问题，精简版操作系统和使用了一些优化软件通常是引起此类问题的原因，这是因为精简版的 window 系统删掉了一些不常用的驱动信息引起的。

解决方法：

1、首先可以参考下面的文章试着解决：

https://forum.singtown.com/topic/230​

2、如果不能解决建议重装系统，最好MSDN的纯净的系统。

##  OpenMV IDE的下载和安装
官网下载地址：https://openmv.io/pages/download​

![IDE下载1](C:\Users\steven\Pictures\openmvide下载1.png)

OpenMV IDE是与OpenMV Cam一起使用的首选集成开发环境。 它具有强大的文本编辑器，调试终端和带有直方图显示的帧缓冲查看器。 OpenMV IDE可以轻松编程OpenMV Cam。OpenMV IDE支持跨平台的，分为Windows，MAC OS，Ubuntu和Rasberry PI的系统，最新的版本为v2.2.0。下面我们用Windows版本和Ubuntu版本为例讲解。

### Windows版本IDE的下载和安装

在官网上下载IDE安装包，


 下载的IDE安装包是一个exe文件，


双击exe文件，然后一直点击下一步安装，


正常安装完成后如下图：

### Ubuntu版本IDE的下载和安装
在官网上下载IDE安装包，


下载的IDE安装包是一个.run可执行文件，


用下面的命令安装：

chmod +x openmv-ide-linux-x86_64-2.2.0.run
./openmv-ide-linux-x86_64-2.2.0.run
这时会出现图形化界面，然后一直点击下一步安装，


正常安装完成后如下图：

## OpenMV IDE的使用
### 运行Helloworld例程
用MicroUSB线将OpenMV Cam与电脑连接后，此时电脑上会弹出一个U盘。OpenMV先比较快的闪绿灯，然后亮一下白灯，最后一直慢闪蓝灯。打开IDE，默认打开的是HelloWorld的例程，点击左下角的连接按钮，先闪几下红灯，然后熄灭，还会弹出来三个对话框，提示要注册，都点击No就行，不影响使用，然后按绿色箭头按钮运行，右上角的图像缓冲区就会有图像显示出来。

注：如果不想每次连接弹出这三个对话框，也可以购买官方的license来注册，一个15美金，约合100人民币，捐助支持OpenMV项目。




 如果没有右侧的图像缓冲区，窗口最右侧有一个三角按钮，点击一下就可以弹出。

### 阈值编辑器

阈值编辑器，用于色块识别，主要为了方便调参用。可以通过拖动滑块， 来得到比较理想的效果， 然后再把threshold放到色块识别的代码里面。

### 色块识别的例程

工具 Tool -> 机器视觉 Machine Vison -> 阈值编辑器 threshold editor


左图是FrameBuffer中截取的图片

右图是我们根据下方的阈值设定出来的二值化图像，其中白色的区域是255 代表1

黑色区域是0 代表0 。

所以调节的目标就是要让你想要的那个区域尽可能的变白。

复制导出的 LAB Threshold ， 在我们演示图片中，这个值为（8，50, 34, 54, -5, 40）

red_threshold_01   = (0, 35, 0, 50, -10, 40)
red_threshold_02   = (8，50, 34, 54, -5, 40)
blobs = img.find_blobs([red_threshold_01, red_threshold_02], area_threshold=150)

### 串口终端连接
连接串口终端进行交互式编程，要先将OpenMV和IDE的连接断开。

工具 -> Open Terminal

然后选择创建一个新的终端, 或者之前创建好的.

create_terminal
创建一个新的终端连接

选择 connect to serial port(默认)

new_terminal_01
选择COM口, 模特率默认为115200, 完成创建

进入终端页面

run_terminal_01
点击三角形, 连接终端

run_terminal_02
### 固件的升级
如果你的OpenMV固件不是最新版本的话，在IDE下方会有[out of data - click here to upgrade]，如下图


点击这里，会弹出一个对话框：是否升级到最新固件？点击OK


会弹出一个对话框：是否擦除内部的文件系统？点击Yes或No都可以。

如果想擦除文件系统，选择Yes，如果想保留文件，选择No。




这个过程大概需要几分钟，OpenMV的绿灯会一直闪，

出现下面这个对话框，就说明固件升级成功了，


这样就升级到最新的固件了，如下图，

### 脱机运行
在IDE里面执行运行程序的时候， 代码并不会复制到openmv的文件系统中，也就是说，下一次上电运行时还是之前文件系统中的程序。所以如果想脱机运行， 需要将文件复制到SD卡或者Flash的根目录的main.py中。如果要自己定义主文件，需要修改boot.py中的入口文件。

### 注意事项