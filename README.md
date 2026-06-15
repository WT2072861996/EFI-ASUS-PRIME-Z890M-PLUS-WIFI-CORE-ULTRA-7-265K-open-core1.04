<p align="center">
  <img src="https://img.shields.io/badge/motherboard-ASUS_PRIME_Z890M_PLUS_WIFI-00A3E0?style=for-the-badge&logo=asus&logoColor=white" alt="主板" />
</p>

# 🖥️ ASUS PRIME Z890M-PLUS WIFI · Intel Core Ultra 7 265K Hackintosh

<p align="center">
  <img src="https://img.shields.io/badge/CPU-Intel_Core_Ultra_7_265K-0071C5?logo=intel&logoColor=white" alt="CPU" />
  <img src="https://img.shields.io/badge/OpenCore-1.0.4-9cf?logo=opencollective&logoColor=white" alt="OpenCore" />
  <img src="https://img.shields.io/badge/RAM-48GB_DDR5_8400MHz-8B5CF6" alt="RAM" />
  <img src="https://img.shields.io/badge/GPU-AMD_RX_580_8GB-ED1C24?logo=amd&logoColor=white" alt="GPU" />
  <img src="https://img.shields.io/badge/Status-Working-success" alt="Status" />
</p>

<div align="center">
  <i>ASUS PRIME Z890M-PLUS WIFI + Intel Core Ultra 7 265K 的黑苹果 OpenCore EFI 配置方案。</i>
  <br>
  <b>Arrow Lake · DDR5 8400MHz · RX 580 · Realtek 2.5G · OpenCore 1.0.4</b>
</div>

---

## ✅ 驱动情况

<table>
<tr>
<td align="center">🔊<br><b>声卡</b></td>
<td align="center">🌐<br><b>网卡</b></td>
<td align="center">🎨<br><b>显卡</b></td>
<td align="center">🔌<br><b>USB</b></td>
</tr>
<tr>
<td align="center">瑞昱 ALC897<br>正常工作 ✅</td>
<td align="center">Realtek 2.5G<br>正常连接 ✅</td>
<td align="center">AMD Radeon RX 580<br>Metal 加速 ✅</td>
<td align="center">所有端口<br>即插即用 ✅</td>
</tr>
<tr>
<td align="center">⚡<br><b>Type-C</b></td>
<td align="center">😴<br><b>睡眠</b></td>
<td align="center">⚙️<br><b>CPU 睿频</b></td>
<td align="center"></td>
</tr>
<tr>
<td align="center">功能完整 ✅</td>
<td align="center">正常唤醒 ✅</td>
<td align="center">频率正常 ✅</td>
<td align="center"></td>
</tr>
</table>

---

## 💻 硬件配置

| 项目 | 规格 |
|------|------|
| **主板** | ASUS PRIME Z890M-PLUS WIFI (LGA 1851) |
| **处理器** | Intel Core Ultra 7 265K (Arrow Lake, 20 核) |
| **内存** | 48 GB DDR5 8400MHz (24GB × 2) |
| **显卡** | AMD Radeon RX 580 Series (8 GB) |
| **网卡** | 瑞昱 Realtek 2.5G 有线网卡 |
| **声卡** | 瑞昱 ALC897 |

---

## ⚙️ BIOS 设置

| 项目 | 状态 |
|------|------|
| **安全启动 (Secure Boot)** | 🔴 关闭 |
| **快速启动 (Fast Boot)** | 🔴 关闭 |
| **启动模式** | UEFI |
| **XHCI Hand-off** | 🟢 开启 |
| **RST (VMD Controller)** | 🔴 关闭 |

---

## 📊 Geekbench 6 跑分

| 项目 | 分数 |
|------|:----:|
| **Single-Core Score** | **2960** |
| **Multi-Core Score** | **20386** |

> 💡 Intel Core Ultra 7 265K 的单核性能接近原生 Mac 水平，多核性能超越多数 Intel Mac 机型。

---

## 📸 系统截图

<a href="https://github.com/user-attachments/assets/45fb1f6c-f2ec-432b-8bb3-d17066b72eff">
  <img src="https://github.com/user-attachments/assets/45fb1f6c-f2ec-432b-8bb3-d17066b72eff" alt="系统信息" width="263" />
</a>

<p><i>⬆️ 点击查看大图</i></p>

---

## 📦 使用说明

### 准备工作

1. **制作启动盘**：使用 [BalenaEtcher](https://www.balena.io/etcher/) 或 Terminal 将 macOS 镜像写入 U 盘
2. **替换 EFI**：用 OpenCore Configurator 挂载 U 盘 EFI 分区，将本项目 EFI 完整复制进去
3. **BIOS 设置**：按照上方 BIOS 设置表调整主板 BIOS
4. **首次启动**：选择 U 盘启动 → OpenCore 菜单 → Install macOS
5. **安装完成后**：将 EFI 复制到系统盘 EFI 分区，即可脱离 U 盘启动

> ⚠️ **注意**：本配置基于 ASUS PRIME Z890M-PLUS WIFI + Intel Core Ultra 7 265K 平台，<br>仅适用于同型号或相似硬件设备。

### 推荐工具

| 工具 | 用途 | 链接 |
|------|------|------|
| OpenCore Configurator | EFI 可视化配置 | [GitHub](https://github.com/OpenCore-Legacy-Patcher/OpenCore-Configurator) |
| Hackintool | 硬件检测与补丁 | [GitHub](https://github.com/dortania/Hackintool) |
| ProperTree | plist 编辑 | [GitHub](https://github.com/corpnewt/ProperTree) |
| CorpNewt 工具集 | USB / 磁盘工具 | [GitHub](https://github.com/corpnewt) |

---

<div align="center">
  <img src="https://img.shields.io/badge/Built_with_❤️_for_the_Hackintosh_Community-FF6B6B" alt="Built with love">
  <br>
  <sub>
  ⭐ Star 这个项目如果它对你有帮助！<br>
  有问题请提交 <a href="https://github.com/WT2072861996/EFI-ASUS-PRIME-Z890M-PLUS-WIFI-CORE-ULTRA-7-265K-open-core1.04/issues">Issues</a>
  </sub>
</div>
