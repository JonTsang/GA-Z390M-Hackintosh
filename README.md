# Gigabyte Z390M Gaming Hackintosh
Hackintosh EFI (GIGABYTE Z390 M GAMING + i7 8700K + RX590)

## macOS版本

**macOS Catalina 10.15 19A602 **

## BootLoader

**Clover_v2.5k_r5073**

##配置

| 类型      | 型号                                                         |
| --------- | ------------------------------------------------------------ |
| 主板      | Gigabyte Z390M Gaming                                        |
| CPU       | Intel i7 8700k                                               |
| 显卡      | Sapphire RX 590 8G D5 超白金版 OC（免驱）                    |
| 网卡&蓝牙 | FV-T919 BCM94360CD（免驱）                                   |
| 内存      | Kingston HyperX Predator DDR4 3000 16Gx2                     |
| 固态硬盘  | Samsung 970evo 500G、Plextor M9PeGn 256G、SanDisk Ultra 3D 1T |
| 机械硬盘  | WD Blcak 7200RPM 1T、Seagate 酷鱼 2T 7200RPM、Seagate 酷鱼 4T 5400RPM |
| 显示器    | Dell P2418D 2K                                               |
| 电源      | GreatWall 650W G6 全模金牌                                   |
| 散热      | USCORSAIR H100i PRO RGB 240mm                                |
| 风扇      | SAMA 冰洞套装（12cm x 3个）                                  |
| 机箱      | CoolerMaster MasterBox NR400 M-ATX                           |
| 鼠标      | Logitech MX Master                                           |
| 键盘      | Varmilo MAC双系统机械键盘 87键 茶轴                          |


## BIOS
**BIOS版本：F7**

- Save & Exit
  - Load Optimized Defaults then make (or confirm) the following settings -- important settings in **bold**:
- M.I.T.
  - Extreme Memory Profile (X.M.P.) → **Profile 1**
- BIOS
  - Windows 8/10 Features → **Other OS**
  - CSM Support → **Disabled**
  - Secure Boot → **Disabled**
- Peripherals
  - Initial Display Output → PCIe Slot 1. If your discrete graphics card is in Slot 2, change this appropriately.
  - Intel Platform Trust Technology (PTT) → **Disabled**
  - Thunderbolt(TM) Configuration
    - TBT Vt-d Base Security → **Disabled**
    - Thunderbolt Boot Support → **Disabled**
    - Security Level → **No Security**
  - USB Configuration
    - Legacy USB Support → **Enabled**
    - XHCI Hand-off → **Enabled**
  - Network Stack Configuration
    - Network Stack → **Disabled**
- Chipset
  - Vt-d → **Disabled**
  - Internal Graphics → **Enabled**
  - DVMT Pre-Alloc → **64M**
  - DVMT Total Gfx Mem → **256M**
  - Audio Controller → **Enabled**
  - Above 4G Decoding → **Enabled**
- Power
  - ErP → **Disabled**
  - RC6 (Render Standby) → **Enabled**

## 正常功能：

- WIFI
- 有线网络
- 蓝牙
- 声音
- 麦克风
- USB 3.0、USB-TypeC
- 睡眠唤醒
- iMessage
- Siri
- 隔空投送
- 接力
- 独显硬件加速
- Apple Watch 解锁

## 待完善：

- 没有第六代以上iPad ，所以随航（Sidecar）功能未测试
- 仍然使用OsxAptioFix2Drv-free2000.efi，使用计算slide值的方法似乎也没用，等有空再解决



![](https://raw.githubusercontent.com/JonTsang/Figurebed/master/img/Snipaste_2019-10-16_20-19-53.png)