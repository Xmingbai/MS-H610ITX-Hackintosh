# MS-H610ITX-Hackintosh  更新中



1.更新至0.8.2正式版，支持Catalina 10.15.x、bigsur 11.6.x、Monterey 12.x、MacOS 13 beta 2

2.默认config.plist 支持只有大核心的CPU型号；有小核心的CPU型号，需开启provideCurrentCpuInfo；

支持所有Navi核心独立显卡并支持其温度监控（需要自己去勾选RadeonSensor.kext和SMCRadeonGPU.kext，OS13已不需要）

4.引导默认支持PCIEx1 的博通WIFI和蓝牙，板载 intel WiFi 需自己手动添加对应驱动

5,重新定制15个USB端口



测评主机配置：

主板：铭瑄 MS-H610ITX

CPU：i5-12490F

显卡： RX5500

内存：威刚D50  DDR4 3200  16x2

硬盘： SN750 500G

无线网卡：BCM94360CS2


# BIOS设置

默认BIOS设置即可安装 但是建议做一下修改
开启XMP 
开启 CPU功耗墙设置为手动  修改PL1 PL2 这里的数字 1680000 代表限定为168W
开启Resize-BAR，有助于提升显卡性能
关闭串口
关闭安全启动 security boot
