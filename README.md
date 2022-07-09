# 概述
本文将教学linux系统的Manjaro kde发行版的安装和美化。
# 目录
# 安装
## 1.准备材料：
+ u盘  
先移存u盘的东西，在制作启动盘的时候会清理盘内所有东西。
+ iso镜像  
[Manjaro官网](https://manjaro.org/)，选择对应版本。  
## 2.制作启动盘：
采用Rufus进行刻录，选择下载好的iso镜像，其他默认，完成退出即可。  
## 3.重启，用u盘启动，进入安装界面：    
设置中文，设置shanghai时区，分盘：  
|文件系统|大小|标记|挂载点|
|:--:|:--:|:--:|:--:|
|linuxswap|根据RAM大小设置，如果是8g内存这里就是8g|无|/swap|
|AT32|300M|勾选/boot，有esp也勾选|/boot/efi|
|ext4|剩下全部|无|/|
