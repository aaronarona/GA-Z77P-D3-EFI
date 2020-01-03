# GA-Z77P-D3-EFI EFI for MacOS 10.14.6

戴尔 灵越 15 3000系列 3568 黑苹果安装和日常使用EFI

### 主要配置信息

| 配件名      | 型号    |
| --------- | -------- | 
| CPU    | I5-3450  |
| 显卡     | HD Graphics 2500（platform-id:0x01620007）     |   
| 网卡     | DW1707 | 
| 声卡 | ALC888B）    |
| 显卡 | 蓝宝石RX460 4G 75W（刷RX560 75W Bios）    |
| 硬盘 | ORICO V500 128GB（外加NVME转PCIEX4转接卡）    |
| 内存 | 16G（金邦DDR3）    |
| 显示器 | AOC U2777PQU（27英寸4K）    |


### 说明

此合集本人只在I5-3450使用过，其他CPU型号未测试

### 工作的功能

1、4K显示器直接免驱HIDPI	

2、RX460直接免驱，HD2500仿冒0x01620007，（开机会闪屏一下）

3、休眠正常

4、DP输入喇叭外放最大音量正常，麦克风正未工作，HDMI可能间歇黑屏

5、无线网卡，蓝牙正常（DW1707用远景套路的办法驱动，蓝牙无解，外加CSR8510 A10 USB蓝牙）

6、DP输入声音无法调节

7、小太阳亮度调节正常（用NativeDisplayBrightness软件可F1，F2调节）

8、没有硬解需求，故未测试

 ### 安装说明

1、下载黑果小兵[macOS Mojave 10.14.6(18G103) Installer for Intel and AMD with Clover 5091 and WEPE.dmg镜像](https://mirrors.dtops.cc/iso/MacOS/daliansky_macos/10.14/macOS%20Mojave%2010.14.6%2818G103%29%20Installer%20for%20Intel%20and%20AMD%20with%20Clover%205091%20and%20WEPE.dmg)

2、挂载U盘EFI分区将原本EFI删除，添加本EFI

3、挂载硬盘EFI分区将本EFI放入

4、重启安装，安装好即是中文