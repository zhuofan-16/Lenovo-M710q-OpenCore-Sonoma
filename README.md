# Hackintosh EFI for Lenovo m710Q

This repository contains the EFI folder necessary for running macOS Sonoma on the Lenovo m710Q as a Hackintosh. 
##### NOTE:PLEASE REMEMBER TO CHANGE THE SMBIOS

## 🚀 Latest Update

### What's New 16/5/2024
- **Updated AirportItlwm**: The kext for Wi-Fi has been updated to the latest version to support Sonoma, enhancing connectivity and stability.
- **Updated Intel Bluetooth kext**: The Bluetooth kext has been upgraded to the newest version to ensure better device compatibility and performance.
- **USB Mapping Remap**: USB ports have been remapped to fix issues related to Bluetooth connectivity.

## 配置 Specification:

| Component         | Specifications                          |
| ----------------- | --------------------------------------- |
| CPU               | Intel® Core™ i7-10750H(ES) (QTJ2)        |
| 显卡 GPU              | Intel® HD Graphics 630                  |
| 内存 RAM              | 2 * 8GB DDR4 2400Mhz                    |
| NVMe              | Samsung PM961 256GB                       |
| 有线网卡          | Intel I219-V / LM                       |
| 声音 Audio             | Realtek ALC233                          |
| Wi-Fi & Bluetooth | Intel AC-8265     |
| SMBIOS            | MacMini8,1                              |
| 引导 Bootloader            | OpenCore 0.9.7                          |

## 可用 Working:

- [x] 英特尔® HD 630 核芯显卡 | Intel HD 630 iGPU DP 接口
- [x] Realtek ALC233
- [x] ALC233 内置喇叭 | ALC233 Audio
- [x] ALC233 3.5mm 接口
- [x] 所有的 USB 接口 | All USB Port 2.0/3.0
- [x] 英特尔 I219-V / LM 有线网卡 | Intel I219-V / LM Card
- [x] 英特尔 Wi-Fi 网卡 /蓝牙 | Intel Wifi Card  - Airdrop 和 Handoff 不能用 需要换网卡 | Airdrop and Handoff not working, need change
- [x] NVRAM

**Note**: This EFI is provided with no guarantees, and you are responsible for any risks associated with its use.
