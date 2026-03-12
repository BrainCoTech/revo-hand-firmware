# Revo Hand Firmware & Tools

Revo 系列灵巧手固件及上位机工具下载汇总。

> 🌐 [English Version](README.md)

支持的通信协议：Modbus / Protobuf / RS-485 / CAN FD / EtherCAT

> 📖 通信协议文档请参考：[Revo Hand Protocol Documentation](https://www.brainco-hz.com/docs/revolimb-hand/revo2/parameters.html)

---

## 上位机

### Revo 1

#### 基础版

| 平台 | 版本 | 下载链接 |
|------|------|---------|
| Windows | V1.1.7 | [BrainCo_Hand_Test_Tool_win_v1.1.7](https://app.brainco.cn/universal/stark-serialport-prebuild/python-tools/BrainCo_Hand_Test_Tool_win_2132_v1.1.7_20250512.7z) |
| Ubuntu | V1.1.7 | [BrainCo_Hand_Test_Tool_linux_v1.1.7](https://app.brainco.cn/universal/stark-serialport-prebuild/python-tools/BrainCo_Hand_Test_Tool_linux_2132_v1.1.7_20250512.7z) |

#### 触觉版

| 平台 | 版本 | 下载链接 |
|------|------|---------|
| Windows | V0.0.11 | [BrainCo_Touch_Hand_Test_Tool_win_v0.0.11](https://app.brainco.cn/universal/stark-serialport-prebuild/python-tools/BrainCo_Touch_Hand_Test_Tool_win_41dd_v0.0.11_20250512.7z) |
| Ubuntu | V0.0.11 | [BrainCo_Touch_Hand_Test_Tool_linux_v0.0.11](https://app.brainco.cn/universal/stark-serialport-prebuild/python-tools/BrainCo_Touch_Hand_Test_Tool_linux_41dd_v0.0.11_20250512.7z) |

### Revo 2

| 平台 | 版本 | 下载链接 |
|------|------|---------|
| Windows | V0.0.19 | [BrainCo_RevoII_Hand_Tool_win_v0.0.19](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/BrainCo_RevoII_Hand_Tool_win_0635_v0.0.19_20251218.7z) |

---

## 固件

### Revo 1（一代）

> [!CAUTION]
> **基础版与触觉版固件不可互刷！** 使用错误的固件升级会导致设备变砖。请务必确认设备型号后再进行固件升级。

#### 基础版

| 通信协议 | 固件版本 | 下载链接 |
|---------|---------|---------|
| Modbus | V0.1.7 | [FW_MotorController_Release_SecureOTA_modbus_0.1.7.ota](https://app.brainco.cn/universal/stark-serialport-prebuild/firmware/modbus/FW_MotorController_Release_SecureOTA_modbus_0.1.7.ota) |
| Protobuf | V9.2.9 | [FW_MotorController_Release_SecureOTA_485_9.2.9.ota](https://app.brainco.cn/universal/stark-serialport-prebuild/firmware/protobuf/FW_MotorController_Release_SecureOTA_485_9.2.9.ota) |

#### 触觉版

| 通信协议 | 固件版本 | 下载链接 |
|---------|---------|---------|
| Modbus | V1.8.32.F | [FW_MotorController_Release_SecureOTA_V1.8.32.F.ota](https://app.brainco.cn/universal/stark-serialport-prebuild/firmware/touch/FW_MotorController_Release_SecureOTA_V1.8.32.F.ota) |

#### 宽压版

| 通信协议 | 固件版本 | 下载链接 |
|---------|---------|---------|
| RS-485 / CAN / CAN FD | TBD | 待更新 |

### Revo 2（二代）

#### 基础版 (Basic)

| 通信协议 | 固件版本 | 下载链接 |
|---------|---------|---------|
| RS-485 / CAN FD | V1.0.20U | [Revo2_V1.0.20.U_2601091030.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.20.U_2601091030.bin) |

> [!WARNING]
> **注意事项一**：Revo 2 基础版通过手腕下方拨码开关实现 CAN FD 和 485 通信接口切换。
>
> **注意事项二**：V0.0.14 及之前版本固件不能直接升级到此版本，升级方式请务必联系 BrainCo 技术人员或者通过网页右上角"帮助"入口提交工单。

#### 进阶版 (Advanced)

| 通信协议 | 板卡类型 | 固件版本 | 下载链接 |
|---------|---------|---------|---------|
| RS-485 / CAN FD | 通用 | V1.0.20U | [Revo2_V1.0.20.U_2601091030.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.20.U_2601091030.bin) |
| EtherCAT / CAN FD | 手腕板 | V0.0.6 | [Revo2Pro_V0.0.6_2508301541_ec.bin](https://app.brainco.cn/universal/bc-stark-sdk/firmware/stark2/Revo2Pro_V0.0.6_2508301541_ec.bin) |
| EtherCAT / CAN FD | 控制板 | V1.0.10.F.1 | [Revo2_V1.0.10.F.1_2510091755.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.10.F.1_2510091755.bin) |

#### 触觉版 (Tactile)

| 通信协议 | 板卡类型 | 固件版本 | 下载链接 |
|---------|---------|---------|---------|
| RS-485 / CAN FD | 通用 | V1.0.20U | [Revo2_V1.0.20.U_2601091030.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.20.U_2601091030.bin) |
| EtherCAT / CAN FD | 手腕板 | V0.0.8 | [Revo2EC_0.0.8_2510211419.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2EC_0.0.8_2510211419.bin) |
| EtherCAT / CAN FD | 控制板 | V1.0.10.F.1 | [Revo2_V1.0.10.F.1_2510091755.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.10.F.1_2510091755.bin) |

---

## 固件文件速查表

下表列出所有独立固件文件及其适用产品范围，方便快速查找：

| 固件文件 | 适用产品 |
|---------|---------|
| `FW_..._modbus_0.1.7.ota` | Revo 1 基础版 |
| `FW_..._V1.8.32.F.ota` | Revo 1 触觉版 |
| `FW_..._485_9.2.9.ota` | Revo 1 基础版 |
| `Revo2_V1.0.20.U_2601091030.bin` | Revo 2 Basic / Advanced / Tactile |
| `Revo2Pro_V0.0.6_2508301541_ec.bin` | Revo 2 Advanced (手腕板) |
| `Revo2EC_0.0.8_2510211419.bin` | Revo 2 Tactile (手腕板) |
| `Revo2_V1.0.10.F.1_2510091755.bin` | Revo 2 Advanced / Tactile (控制板) |

---

## Support

如需技术支持，请通过以下方式联系我们：

- 📋 提交工单：[https://web.static.brainco.cn/work-order](https://web.static.brainco.cn/work-order)
- 🐙 GitHub：[https://github.com/BrainCoTech](https://github.com/BrainCoTech)
