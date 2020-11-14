### 简介
组装一台黑苹果最重要的是硬件的选择， 选择的重点是尽量选择与白苹果一致的配件
在硬件选择的方面有几点需要特别的注意

1. CPU 的选择，CPU尽量选择 Intel 的，7/8/9代 酷睿 i9，i7，i5，i3 都可以， AMD 的CPU 也不是不行， 只不过需要打补丁，折腾的东西比较多
2. 显卡的选择， 白苹果的显卡都是 A 卡， 所以在显卡的选择上直接选择 A 卡即可， 选择 A 卡需要注意的是，直接选择免驱动的 A 卡类型， 首选蓝宝石和微星的，下面列举了一些免驱的 A 卡

- Vega FE （真正免驱，无需搭配集显也可完全硬件加速）
- Vega 64 （真正免驱，无需搭配集显也可完全硬件加速）
- Vega 56 （真正免驱，无需搭配集显也可完全硬件加速）
- Vega Nano （真正免驱，无需搭配集显也可完全硬件加速）
- Pro SSG （真正免驱，无需搭配集显也可完全硬件加速）
- WX 9100 （真正免驱，无需搭配集显也可完全硬件加速）
- WX 8200 （真正免驱，无需搭配集显也可完全硬件加速）
- RX 590
- RX 580 （注意，缩水的阉割版2048SP的RX580马甲卡不是免驱的，标准2304SP才是免驱卡）
- RX 570
- RX 560 （个别型号的HDMI/DVI输出黑屏，需要改FB，DP输出没问题）

3. 主板的选择，华硕，微星，技嘉 的 主板推荐选择， 8/9代酷睿首选Z390/Z370芯片组
4. 硬盘的选择，三星 970 EVO Plus 和 三星 PM981 无法做为macOS系统盘安装原版，不要选择
5. 显示器的选择，首选 4K 显示器，2K 以下的显示器需要开启 HiDPI，而且使用体验不好
6. 无线网卡和蓝牙的选择，主板自带的WI-FI和蓝牙目前都无法驱动， 这个无解， 推荐免驱的 BCM94360CD 或者 BCM943602CS，直接插上即可使用

### 配置
先贴出我本次的黑苹果主机的配置信息， 如下：

| **项目** | **型号**                               | **价格** | **链接**                                                                                          |
|--------|--------------------------------------|--------|-------------------------------------------------------------------------------------------------|
| CPU    | Intel i9-9900K 8核16线程 盒装CPU          | 2899   | https://item.jd.com/100000634429.html                                                           |
| 主板     | 技嘉（GIGABYTE）Z390 AORUS PRO WIFI      | 956    | https://item.jd.com/100000612305.html                                                           |
| 内存     | 金士顿(Kingston) DDR4 3200频 128GB(32G×4) | 4409   | https://item.jd.com/100008221061.html                                                           |
| 硬盘     | 三星970 EVO 1TB M.2接口(NVMe)          | 1087   | https://item.jd.com/7234468.html                                                                |
| 显卡     | 蓝宝石 RX 580 2304sp 8G 满血版 （淘宝二手）      | 1238   | https://item.taobao.com/item.htm?spm=a1z09.2.0.0.661e2e8d5l686T&id=614820302674&_u=425lenq48296 |
| 散热器    | 九州风神大霜塔                              | 179    | https://item.jd.com/689273.html                                                                 |
| 电源     | 长城 750W 全模组金牌电源                      | 490    | https://item.jd.com/8025804.html                                                                |
| 显示器    | 戴尔 U2720QM 27英寸4K                    | 3468   | https://item.jd.com/100011317048.html                                                           |
| 无线网卡   | BCM94360CD                           | 265    | https://item.jd.com/10021401339167.html                                                         |
| 鼠标     | 罗技 MX Master 3 for Mac               | 668    | https://item.jd.com/100014681386.html                                                           |
| 键盘     |  Keychron K6蓝牙双模机械键盘 青轴              | 327    | https://item.jd.com/100007939581.html                                                           |
| 机箱     | 先马（SAMA）剑魔升级版                        | 179    | https://item.jd.com/100007087962.html                                                           |
| 其他     | RGB风扇 x3 / DP 线 1.4版                | 130    | https://item.jd.com/100007577985.html   https://item.jd.com/100008069617.html                  |
| 总计     |                                      | 16295  |                                                                                                 |

### 效果图
![效果图-1](http://image.joylau.cn/blog/%E6%95%88%E6%9E%9C%E5%9B%BE-1.JPG)

![效果图-2](http://image.joylau.cn/blog/%E6%95%88%E6%9E%9C%E5%9B%BE-2.JPG)

![系统信息](http://image.joylau.cn/blog/%E7%B3%BB%E7%BB%9F%E4%BF%A1%E6%81%AF.png)

![设备信息](http://image.joylau.cn/blog/%E8%AE%BE%E5%A4%87%E4%BF%A1%E6%81%AF.png)

![CPU得分](http://image.joylau.cn/blog/CPU%20%E5%BE%97%E5%88%86.png)

![CPU超频](http://image.joylau.cn/blog/%E8%B6%85%E9%A2%91.png)

Power 显示的是当前 CPU 的功率；

Frequency 显示当前 CPU 的频率；

Temperature 显示当前 CPU 的温度，此温度是内核温度；

Utilization 显示当前 CPU 的占用率。

![显卡 Metal 得分](http://image.joylau.cn/blog/%E6%98%BE%E5%8D%A1%E5%BE%97%E5%88%86-Metal.png)

![显卡 OpenCL 得分](http://image.joylau.cn/blog/%E6%98%BE%E5%8D%A1%E5%BE%97%E5%88%86-OpenCL.png)

![磁盘速度](http://image.joylau.cn/blog/%E7%A3%81%E7%9B%98%E9%80%9F%E5%BA%A6.png)


### 步骤

#### 准备工作
1. 一个容量大于等于 16G 的 U 盘
2. 一台macOS操作系统的主机
3. 下载 Mac 版的软件 balenaEtcher (https://www.balena.io/etcher/)
4. 软件 Hackintool (https://github.com/headkaze/Hackintool)

#### 准备安装镜像
1. App Store 下载最新的操作 MacOS 操作系统,下载完成之后就可以在“应用程序”中找到
2. 创建DMG文件: 打开“磁盘工具”，创建空白镜像,命名为 MyMacOS, 根据所下载的镜像的大小，分配一个合理的镜像大小,格式选择日志式，分区选择 GUID 分区类型，权限选择读写
3. macOS 系统上的主机上 插入 U 盘，输入以下命令格式化 U 盘

```bash
    diskutil partitionDisk /dev/{YOUR_DISK_ID} GPT JHFS+ "USB" 100%
```

4. 双击打开 MyMacOS.dmg 文件进行挂载，输入如下命令,将下载的系统镜像文件写入 DMG 镜像中

```bash
    sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume /Volumes/MyMacOS
```

5. 使用 balenaEtcher 将 MyMacOS.dmg 镜像刷入 U 盘中
6. 使用 Hackintool 挂载 U 盘的 UEFI 分区，将我已经配置好的 `USB_EFI` 整个目录拷贝进去， 并且重命名为 `EFI`，之后卸载分区

#### BIOS 配置
在技嘉官网下载最新版 Z390 主板的 BIOS 固件（https://www.gigabyte.cn/Motherboard/Z390-AORUS-PRO-WIFI-rev-10/support#support-dl-driver）并刷入

当前最新版本 **F12j**
进行如下配置：

- Load Optimized Defaults
- Settings -> IO Ports -> Internal Graphics -> Enabled
- Settings -> IO Ports -> DVMT Pre-Allocated -> 32M
- Settings -> IO Ports -> Wi-Fi -> Disabled
- Settings -> IO Ports -> Above 4G Decoding -> Enabled
- Settings -> IO Ports -> Wake on LAN Enable -> Disabled
- Settings -> IO Ports -> USB Configuration -> Legacy USB Support -> Disabled
- Settings -> IO Ports -> USB Configuration -> XHCI Hand-off -> Enabled
- Settings -> Miscellaneous -> Software Guard Extensions(SGX) -> Disabled
- Settings -> Miscellaneous -> Trusted Computing -> Security Device Support -> Disabled
- Boot -> CFG Lock -> Disabled

#### 安装
1. 插入 U 盘，启动时按 `F12` 进入启动设备选择， 选择 `OpenCore`， 之后选择安装 MacOS 选项
2. 耐心等待跑码安装完毕， 之后会进入 MacOS 的安装界面， 先进入磁盘工具， 将要安装系统的那个硬盘抹掉， 格式选择 APFS，之后再安装 MacOS 系统， 之后等待重启
3. 重启依然要使用 U 盘进行引导，进入硬盘里的 MacOS 系统
4. 到这里整个系统的安装以及完成了一半了
5. 注意此时进入系统是千万不要登入自己的 iCloud 账号进行使用，需要在下面生成并注入了序列号之后才可以安全的登录


### 后续完善
#### 更换 EFI
使用 Hackintool 挂载 硬盘的 UEFI 分区，并且将我配置好的 `EFI` 目录复制进去，进行覆盖

#### USB 端口的配置
有 MacOS 系统的限制， 最多只允许开始使用 15个端口， 我这里就 Z390 的主板进行下面端口的开启
![背面端口图](http://image.joylau.cn/blog/back_panel.png)
![主板接口图](http://image.joylau.cn/blog/internal_io.png)


使用 Hackintool, 修改端口， 并导出， 注意保留 `USBPorts.kext` 文件以放入 Kexts 目录下， 我这里开启的端口如下配置
![启用的端口](http://image.joylau.cn/blog/%E5%90%AF%E7%94%A8%E7%9A%84%E7%AB%AF%E5%8F%A3.png)


#### 关闭啰嗦模式
找到 配置文件中的

```xml
    <key>boot-args</key>
    <string>-v keepsyms=1 agdpmod=pikera slide=0 shikigva=80</string>
```

去掉 -v

#### 生成序列号
使用 Hackintool 生成序列号，选择的类型为 `iMac (Retina 5K, 27-inch, 2019)`
之后到官网查询，如果提示序列号不合法，则该序列号可用，这时候可以将其注入以下部分

```xml
    <dict>
        <key>AdviseWindows</key>
        <false/>
        <key>SystemMemoryStatus</key>
        <string>Auto</string>
        <key>MLB</key>
        <string>M0000000000000001</string>
        <key>ProcessorType</key>
        <integer>0</integer>
        <key>ROM</key>
        <data>ESIzRFVm</data>
        <key>SpoofVendor</key>
        <true/>
        <key>SystemProductName</key>
        <string>iMac19,1</string>
        <key>SystemSerialNumber</key>
        <string>W00000000001</string>
        <key>SystemUUID</key>
        <string>00000000-0000-0000-0000-000000000000</string>
    </dict>
```

分别是 `MLB`，`SystemSerialNumber`，`SystemUUID`



### OpenCore 配置列表

#### OpenCore EFI

Download OpenCore **RELEASE** from [here](https://github.com/acidanthera/OpenCorePkg/releases/latest)


#### ACPI 
- SSDT-EC-USBX.aml
- SSDT-PLUG.aml
- SSDT-HPET.aml
- SSDT-PMC.aml

#### Driver
- [HfsPlus.efi](https://github.com/acidanthera/OcBinaryData/raw/master/Drivers/HfsPlus.efi)
- OpenRuntime.efi - Included in OpenCore package

#### Kext - Make sure to download RELEASE version
- [Lilu.kext](https://github.com/acidanthera/Lilu/releases/latest)
- [VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC/releases/latest)
- [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases/latest)
- [AppleALC.kext](https://github.com/acidanthera/AppleALC/releases/latest)
- [IntelMausi.kext](https://github.com/acidanthera/IntelMausi/releases/latest)
- [USBInjectAll.kext](https://bitbucket.org/RehabMan/os-x-usb-inject-all/downloads/RehabMan-USBInjectAll-2018-1108.zip) - Only needed for installation media
- USBPorts.kext - [Refer post installation](POST_INSTALL.md)
- SMCProcessor.kext - Included in VirtualSMC package
- SMCSuperIO.kext - Included in VirtualSMC package

#### Tools
- [modGRUBShell.efi](https://github.com/datasone/grub-mod-setup_var/releases/download/1.1/modGRUBShell.efi)
- OpenShell.efi - Included in OpenCore package
- ResetSystem.efi - Included in OpenCore package
- CleanNvram.efi - Included in OpenCore package

#### config.plist

- Use `config_usb.plist` for installation media(USB). Rename it to `config.plist`.
- Use `config.plist` for internal boot disk.

#### EFI Folder Structure

##### USB

``` text
EFI
├── BOOT
│   └── BOOTx64.efi
└── OC
    ├── ACPI
    │   ├── SSDT-EC-USBX.aml
    │   ├── SSDT-HPET.aml
    │   ├── SSDT-PLUG.aml
    │   └── SSDT-PMC.aml
    ├── Bootstrap
    │   └── Bootstrap.efi
    ├── Drivers
    │   ├── HfsPlus.efi
    │   └── OpenRuntime.efi
    ├── Kexts
    │   ├── AppleALC.kext
    │   ├── IntelMausi.kext
    │   ├── Lilu.kext
    │   ├── SMCProcessor.kext
    │   ├── SMCSuperIO.kext
    │   ├── USBInjectAll.kext
    │   ├── VirtualSMC.kext
    │   └── WhateverGreen.kext
    ├── OpenCore.efi
    ├── Tools
    │   ├── CleanNvram.efi
    │   ├── OpenShell.efi
    │   ├── ResetSystem.efi
    │   └── modGRUBShell.efi
    └── config.plist
```

##### SSD/NVME/HDD

``` text
EFI
├── BOOT
│   └── BOOTx64.efi
└── OC
    ├── ACPI
    │   ├── SSDT-EC-USBX.aml
    │   ├── SSDT-HPET.aml
    │   ├── SSDT-PLUG.aml
    │   └── SSDT-PMC.aml
    ├── Bootstrap
    │   └── Bootstrap.efi
    ├── Drivers
    │   ├── HfsPlus.efi
    │   └── OpenRuntime.efi
    ├── Kexts
    │   ├── AppleALC.kext
    │   ├── IntelMausi.kext
    │   ├── Lilu.kext
    │   ├── SMCProcessor.kext
    │   ├── SMCSuperIO.kext
    │   ├── USBPorts.kext
    │   ├── VirtualSMC.kext
    │   └── WhateverGreen.kext
    ├── OpenCore.efi
    ├── Tools
    │   ├── CleanNvram.efi
    │   ├── OpenShell.efi
    │   ├── ResetSystem.efi
    │   └── modGRUBShell.efi
    └── config.plist

```

### 工作状态
目前一切都正常工作，包括声卡，网卡，Wi-Fi，蓝牙，Airdrop，随航，接力，显示分辨率，睡眠，关机，重启

### 遇到的坑
1. 我买的主板CPU针脚上有一个针脚弯曲了， 导致有2 个内存插槽无法读取， 如下图

![CPU针脚](http://image.joylau.cn/blog/CPU%E9%92%88%E8%84%9A.JPG)

![CPU针脚弯曲](http://image.joylau.cn/blog/%E9%92%88%E8%84%9A%E5%BC%AF%E6%9B%B2.JPG)

这种情况的具体表现是只有插在主板的 DDR4_A1 槽或者 DDR4_A2 槽或者 2 个槽都插时才能短接进入 BIOS 界面,
插入全部 4 根内存条或者只要插入 DDR4_B2 或者 DDR4_B1 时将无法进入 BIOS 界面且主板无限重启,显示器无输出且 DRAM 指示灯常亮

后来我用镊子将其矫正就可以了

2. 主板的 `CSM Support` 选项不能关闭， 关闭会导致无法进入 BIOS， 且主板上的 VGA 等常亮

### 最后
目录中的 `EFI` 和 `EFI_USB` 都是我已经修改好的引导了，可以直接使用，其中 `EFI` 是复制到硬盘上用来引导系统的， `EFI_USB` 是复制到 U 盘上用来进行 U 盘引导的

引导下载地址见： https://github.com/JoyLau/Hackintosh-GIGABYTE-Z390-AORUS-PRO-WIFI-i9-9900K-RX580-BCM94360CD-OpenCore

### 参考资料
- http://blog.daliansky.net
- https://www.tonymacx86.com
- https://github.com/shiruken/hackintosh#prepare-install-media
- https://www.youtube.com/watch?v=hUMFJjxQO7A
- https://www.insanelymac.com/forum/topic/337837-glasgoods-macos-mojave-successguide-for-aorus-z390-pro