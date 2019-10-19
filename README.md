# EFI MSI Z390 Tomahawk OC & Clover

Support Macos 10.15 Catalina

## 兼容情况

### 完美

- [x] macOS 版本
    - [x] 10.14.6 Mojave
    - [x] 10.15 Catalina
- [x] 显卡（DisplayPort & HDMI 接显示器）
    - [x] Intel UHD630 核显 支持HDMI输出
    - [x] AMD RX580

- [x] 睡眠/唤醒
- [x] 有线网卡
- [x] 所有 USB 插口

### 未测试
- [x] 声卡(Realtek ALC1220)
    - [x] 主板后置
    - [x] 机箱前置
    - [x] DisplayPort 声音输出
- [x] 无线 WiFi
- [x] 蓝牙
    - [x] 耳机
    - [x] Trackpad 2
    - [x] Airdrop
    - [x] Handoff

## 安装教程

### 前期准备

开机 F11 进入 BIOS，至少需要做如下修改具体情况还需要看硬件情况：

- VT-d -> Disabled
- XHCI Hand-off -> Enabled

### 机型配置修改：

- OC 自行修改PlatformInfo-Generic里面的参数
- Clover 自行修改SMBIOS和SystemParameters里面的参数

