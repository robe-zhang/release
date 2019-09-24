# Leez P710 android 系统使用记录：


## 硬件：
leez P710 开发板 (小批量生产的，无 EMMC，早期试用的产品 )    
![leez_p710.jpg](https://github.com/robe-zhang/release/blob/master/leez_p710.jpg)


## 下载 android9 系统镜像，和烧录工具
 打开这个页面：https://github.com/leezsbc/resources/wiki/Leez-P710    
 系统镜像：下载 Android9.0   
 烧录工具：下载 SDDiskTool_v1.57_SD卡镜像刷写（Windows环境）  
 下载后解压，如下图：  
![leez_p710.jpg](https://github.com/robe-zhang/release/blob/master/tools_imgfile.PNG)  
 (因为开发板无 emmc，只能使用 sd 卡镜像烧写工具，烧录 sd 卡后从卡启动。)
 
 
## 烧录方法：
windows 系统下，打开烧录软件，如下图确认好，点击  开始创建 ，开始烧录  
![leez_p710.jpg](https://github.com/robe-zhang/release/blob/master/burn_sdcard.PNG)    
确认烧录成功后，关掉烧录工具，拔掉 sd 卡  
(烧录完成，电脑会检测到19个SD卡分区，不要格式化，直接取消不用管，正常的。)  


## 开机：  
插上 sd 卡，接上显示器，上电开机，如下图:     
![leez_p710.jpg](https://github.com/robe-zhang/release/blob/master/android_desktop.jpg)    
开机时间有点长，需要等一下  
(串口输出信息，会显示有一次重启，是正常的，烧机后第一次开机系统重启，之后就不会了。)
(android 系统不响应串口任何输入，不可以通过串口使用。)
