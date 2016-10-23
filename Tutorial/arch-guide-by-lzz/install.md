# 前言

安装Arch Linux并不像安装其他的Linux发行版那样简单（例如：Debian & Ubuntu & Fedora），您需要一定的操作Linux的技巧来完成安装，总结起来无非以下几点。

* 会使用Linux的基本命令，如`ls`, `cd`。
* 在任何时候您必须清楚自己在做什么，否则任何操作都可能对您或您的设备有害。
* 具有基本的解决问题的能力。

需要注意的是，本教程只针对**安装Arch Linux单系统**。

让我们开始安装Arch Linux吧！

# Step 1 - 准备安装工具

为了安装Arch Linux，请确保您拥有

1. 互联网
2. 一台计算机
3. 一个容量大于等于4GiB的USB存储设备（例如U盘）

# Step 2 - 准备安装镜像

「镜像」指的是Arch Linux的LiveCD，它是一个小型的Linux环境，我们将使用这个环境，将Arch Linux装入我们的计算机。

我们将把镜像刻录进您的USB设备，值得注意的是，在刻录过程中，USB设备中的**所有数据**都会被**彻底清除**，**所以务必在您进行以下操作前备份（复制您USB存储设备中的数据到计算机磁盘中）您的USB存储设备。**

备份完数据后，请对您的USB存储设备进行格式化操作。

* Windows用户请打开计算机，选择您的USB存储设备，右键，选择「格式化」，然后单击「开始」和「确定」。
* Linux用户请在终端运行`mkfs.ntfs <您的USB设备>`

接下来，我们要开始从Arch Linux官网下载LiveCD镜像。