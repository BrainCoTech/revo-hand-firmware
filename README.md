# Revo Hand Firmware & Tools

Download hub for Revo series dexterous hand firmware and desktop software.

> 🌐 [中文版](README.zh.md)

Supported protocols: Modbus / Protobuf / RS-485 / CAN FD / EtherCAT

> 📖 Protocol documentation: [Revo Hand Protocol Reference](https://www.brainco-hz.com/docs/revolimb-hand/revo2/parameters.html)

---

## Desktop Software

### Revo 1

#### Standard Edition

| Platform | Version | Download |
|----------|---------|----------|
| Windows | V1.1.7 | [BrainCo_Hand_Test_Tool_win_v1.1.7](https://app.brainco.cn/universal/stark-serialport-prebuild/python-tools/BrainCo_Hand_Test_Tool_win_2132_v1.1.7_20250512.7z) |
| Ubuntu | V1.1.7 | [BrainCo_Hand_Test_Tool_linux_v1.1.7](https://app.brainco.cn/universal/stark-serialport-prebuild/python-tools/BrainCo_Hand_Test_Tool_linux_2132_v1.1.7_20250512.7z) |

#### Tactile Edition

| Platform | Version | Download |
|----------|---------|----------|
| Windows | V0.0.11 | [BrainCo_Touch_Hand_Test_Tool_win_v0.0.11](https://app.brainco.cn/universal/stark-serialport-prebuild/python-tools/BrainCo_Touch_Hand_Test_Tool_win_41dd_v0.0.11_20250512.7z) |
| Ubuntu | V0.0.11 | [BrainCo_Touch_Hand_Test_Tool_linux_v0.0.11](https://app.brainco.cn/universal/stark-serialport-prebuild/python-tools/BrainCo_Touch_Hand_Test_Tool_linux_41dd_v0.0.11_20250512.7z) |

### Revo 2

| Platform | Version | Download |
|----------|---------|----------|
| Windows | V0.0.19 | [BrainCo_RevoII_Hand_Tool_win_v0.0.19](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/BrainCo_RevoII_Hand_Tool_win_0635_v0.0.19_20251218.7z) |

---

## Firmware

### Revo 1 (1st Generation)

> [!CAUTION]
> **Standard and Tactile edition firmware are NOT interchangeable.** Flashing the wrong firmware will brick the device. Always verify your device model before upgrading.

#### Standard Edition

| Protocol | Version | Download |
|----------|---------|----------|
| Modbus | V0.1.7 | [FW_MotorController_Release_SecureOTA_modbus_0.1.7.ota](https://app.brainco.cn/universal/stark-serialport-prebuild/firmware/modbus/FW_MotorController_Release_SecureOTA_modbus_0.1.7.ota) |
| Protobuf | V9.2.9 | [FW_MotorController_Release_SecureOTA_485_9.2.9.ota](https://app.brainco.cn/universal/stark-serialport-prebuild/firmware/protobuf/FW_MotorController_Release_SecureOTA_485_9.2.9.ota) |

#### Tactile Edition

| Protocol | Version | Download |
|----------|---------|----------|
| Modbus | V1.8.32.F | [FW_MotorController_Release_SecureOTA_V1.8.32.F.ota](https://app.brainco.cn/universal/stark-serialport-prebuild/firmware/touch/FW_MotorController_Release_SecureOTA_V1.8.32.F.ota) |

#### Wide-Voltage Edition

| Protocol | Version | Download |
|----------|---------|----------|
| RS-485 / CAN / CAN FD | TBD | Coming soon |

### Revo 2 (2nd Generation)

#### Basic

| Protocol | Version | Download |
|----------|---------|----------|
| RS-485 / CAN FD | V1.0.20U | [Revo2_V1.0.20.U_2601091030.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.20.U_2601091030.bin) |

> [!WARNING]
> **Note 1:** The Revo 2 Basic uses a DIP switch on the underside of the wrist to toggle between CAN FD and RS-485 interfaces.
>
> **Note 2:** Firmware versions V0.0.14 and earlier cannot be upgraded directly to this version. Please contact BrainCo technical support or submit a ticket for assistance.

#### Advanced

| Protocol | Board | Version | Download |
|----------|-------|---------|----------|
| RS-485 / CAN FD | Main | V1.0.20U | [Revo2_V1.0.20.U_2601091030.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.20.U_2601091030.bin) |
| EtherCAT / CAN FD | Wrist | V0.0.6 | [Revo2Pro_V0.0.6_2508301541_ec.bin](https://app.brainco.cn/universal/bc-stark-sdk/firmware/stark2/Revo2Pro_V0.0.6_2508301541_ec.bin) |
| EtherCAT / CAN FD | Controller | V1.0.10.F.1 | [Revo2_V1.0.10.F.1_2510091755.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.10.F.1_2510091755.bin) |

#### Tactile

| Protocol | Board | Version | Download |
|----------|-------|---------|----------|
| RS-485 / CAN FD | Main | V1.0.20U | [Revo2_V1.0.20.U_2601091030.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.20.U_2601091030.bin) |
| EtherCAT / CAN FD | Wrist | V0.0.8 | [Revo2EC_0.0.8_2510211419.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2EC_0.0.8_2510211419.bin) |
| EtherCAT / CAN FD | Controller | V1.0.10.F.1 | [Revo2_V1.0.10.F.1_2510091755.bin](https://brainco-common-public.oss-cn-hangzhou.aliyuncs.com/web-config/docs-sdk/Revo2_V1.0.10.F.1_2510091755.bin) |

---

### Revo 3

Revo3 main-controller firmware is updated through the SDK OTA/DFU interface over Modbus RTU or CAN FD. Verify the product code, installed firmware version, and transport before updating. Keep device power and communication connected throughout the update.

| Protocol | Firmware | Build time | Download | SHA-256 |
|---------|---------|---------|---------|---------|
| Modbus RTU / CAN FD | V0.1.2 | 2026-09-28 20:36 | [revo23-fw-V0.1.2-2609282036.bin](firmware/revo3/revo23-fw-V0.1.2-2609282036.bin) | `2a423832de5ccd8f0eed6c46d383d1037e46c30af8ba6138d0cabdf62a89c82a` |
| Modbus RTU / CAN FD | V0.1.3 | 2026-10-12 09:34 | [revo23-fw-V0.1.3-2610120934.bin](firmware/revo3/revo23-fw-V0.1.3-2610120934.bin) | `72fe4770b30da3f0b08d167e3308c9de4dff9641e4d58704460ff6f86e37bb` |

> [!WARNING]
> These files are Revo3 main-controller firmware and must not be used on Revo 1 or Revo 2. Select exactly one image per update, then reconnect and verify the reported firmware version. Downgrading from V0.1.3 to V0.1.2 is allowed only when confirmed by the firmware release notes.

## Firmware Quick Reference

| Firmware | Applicable Products |
|----------|-------------------|
| `FW_..._modbus_0.1.7.ota` | Revo 1 Standard |
| `FW_..._V1.8.32.F.ota` | Revo 1 Tactile |
| `FW_..._485_9.2.9.ota` | Revo 1 Standard |
| `Revo2_V1.0.20.U_2601091030.bin` | Revo 2 Basic / Advanced / Tactile |
| `Revo2Pro_V0.0.6_2508301541_ec.bin` | Revo 2 Advanced (Wrist) |
| `Revo2EC_0.0.8_2510211419.bin` | Revo 2 Tactile (Wrist) |
| `Revo2_V1.0.10.F.1_2510091755.bin` | Revo 2 Advanced / Tactile (Controller) |
| `revo23-fw-V0.1.2-2609282036.bin` | Revo 3 main-controller firmware |
| `revo23-fw-V0.1.3-2610120934.bin` | Revo 3 main-controller firmware |

---

## Support

Need help? Reach out through the following channels:

- 📋 Submit a ticket: [https://web.static.brainco.cn/work-order](https://web.static.brainco.cn/work-order)
- 🐙 GitHub: [https://github.com/BrainCoTech](https://github.com/BrainCoTech)
