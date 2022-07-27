# MS-H610ITX-Hackintosh  页面编辑中


# OC更新日志

1.更新至0.8.2版，支持Catalina 10.15.x、bigsur 11.6.x、Monterey 12.x、MacOS 13 beta 2

2.默认config.plist 支持只有大核心的CPU型号；有小核心的CPU型号，需开启provideCurrentCpuInfo；

3. 支持所有Navi核心独立显卡并支持其温度监控（需要自己去勾选RadeonSensor.kext和SMCRadeonGPU.kext，OS13已不需要）

#  下载地址 （在右侧的Releases）

https://github.com/Xmingbai/MS-H610ITX-Hackintosh/releases



# 测评主机配置：

主板：铭瑄 MS-H610ITX

CPU：i5-12490F

显卡： RX5500

内存：威刚D50 32G DDR4 3200  16x2

硬盘： SN750 500G

无线网卡：BCM94360CS2+转接卡


# 功能完善程度 99%

CPU 睿频正常

2.5G有线网卡支持；

音频前后3.5输出正常；

wifi 蓝牙正常 ，隔空投送接力正常、支持通用控制；

睡眠与唤醒正常，支持USB设备唤醒


# BIOS设置

默认BIOS设置即可安装 但是建议做一下修改

开启XMP 

开启 CPU功耗墙设置为手动  修改PL1 PL2 这里的数字 168000 代表限定为168W

开启Resize-BAR，有助于提升windows下显卡性能

关闭串口

关闭安全启动 security boot
