# ASUS PRIME Z890M-PLUS WIFI · Intel Core Ultra 7 265K Hackintosh

Intel Arrow Lake | DDR5 8400 MHz | RX 580 | OpenCore 1.0.4

![CPU](https://img.shields.io/badge/CPU-Intel_Core_Ultra_7_265K-0071C5)
![OpenCore](https://img.shields.io/badge/OpenCore-1.0.4-9cf)
![RAM](https://img.shields.io/badge/RAM-48_GB_DDR5_8400_MHz-8B5CF6)
![GPU](https://img.shields.io/badge/GPU-AMD_RX_580_8_GB-ED1C24)
![Status](https://img.shields.io/badge/Status-Working-success)

---

## Hardware

| Component | Specification |
|:----------|:--------------|
| Motherboard | ASUS PRIME Z890M-PLUS WIFI (LGA 1851) |
| CPU | Intel Core Ultra 7 265K (Arrow Lake, 20 cores) |
| RAM | 48 GB DDR5 8400 MHz (24 GB × 2) |
| GPU | AMD Radeon RX 580 (8 GB) |
| Ethernet | Realtek 2.5 GbE |
| Audio | Realtek ALC897 |

## Driver Status

| Feature | Status | Feature | Status |
|:--------|:------:|:--------|:------:|
| Audio | ✅ Working | USB | ✅ Working |
| Ethernet | ✅ Working | Type-C | ✅ Working |
| GPU (Metal) | ✅ Working | Sleep | ✅ Working |
| CPU Turbo | ✅ Working | | |

## BIOS Settings

| Setting | Value |
|:--------|:-----:|
| Secure Boot | Disabled |
| Fast Boot | Disabled |
| Boot Mode | UEFI |
| XHCI Hand-off | Enabled |
| RST (VMD) | Disabled |

## Geekbench 6

| Metric | Score |
|:-------|:-----:|
| Single-Core | 2960 |
| Multi-Core | 20386 |

---

## Installation

1. Configure BIOS per above
2. Create bootable USB with macOS
3. Replace EFI on USB EFI partition
4. Boot from USB → OpenCore → Install macOS

## Screenshot

[![System Info](https://github.com/user-attachments/assets/45fb1f6c-f2ec-432b-8bb3-d17066b72eff)](https://github.com/user-attachments/assets/45fb1f6c-f2ec-432b-8bb3-d17066b72eff)
