# S210H-i910980HK-Hackintosh

### S210H i9 10980HK 主机配置

> 两个系统都是单系统直接启动，主题文件就不传了

> PlatformInfo一定要配置一下

|主机|S210H|
|--|--|
|CPU|i9 10980HK QS版本（与正版无差别）|
|GPU|intel UHD 630|
|内存|威刚16G 3200MHz x 2 = 32G|
|网卡|Intel AX200（WiFi和蓝牙正常）|
|储存|东芝240G SATA（好穷）|
|显示器|飞利浦4K|
|系统|MacOS 12|
|型号|iMac19,1|
|引导|OC 0.7.9|

### 完善情况

单系统引导，进系统不卡顿，HDMI输出，4k正常，显示器声音亮度使用monitorcontrol软件控制，AX200的WiFi和蓝牙驱动正常，锁定屏幕、睡眠正常唤醒

### 其他说明

- MacOS 12的系统USB一定要定制，使用Hackintool就行（不然可能睡眠后鼠键无法唤醒）
- 如果进入系统卡顿就是选择的PlatformInfo型号不对，可以试试iMac和Macmini这两种CPU和你的CPU架构一样的
- 如果进入系统画面被压瘪或者分辨率不对劲，就是DeviceProperties的显卡驱动配置参数有问题
- 如果睡眠无法唤醒，也是DeviceProperties的显卡驱动配置参数有问题
- PlatformInfo一定要刷一个官网查询不到的序列号

### NUC8 i5 8259U 主机配置

|主机|NUC8BEH|
|--|--|
|CPU|i5 8259U（与2018款Mac mini同款U）|
|GPU|intel UHD 655|
|内存|威刚16G 2666MHz + 8G 2666MHz = 24G|
|网卡|BCM94360CS2 + M.2转换器（WiFi、蓝牙、投送全正常）|
|储存|金士顿240G SATA（好穷）|
|显示器|飞利浦4K|
|系统|MacOS 11|
|型号|Mac mini8,1|
|引导|OC 0.6.x|

### 完善情况

单系统引导，进系统不卡顿，type-c雷电输出，4k正常，显示器声音亮度使用monitorcontrol软件控制，苹果拆机卡BCM94360CS2的WiFi、蓝牙和投送驱动全正常，很完美，锁定屏幕、睡眠正常唤醒
