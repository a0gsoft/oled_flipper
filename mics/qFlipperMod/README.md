# 🐬 qFlipper (DIY OLED & WeAct STM32WB55 Edition)
This is the customized version of the official **qFlipper** companion desktop application for DIY Flipper Zero boards.

## ✨ Key Features
* **No OTP Programming Required**: You can flash and recover fresh WeAct STM32WB55 boards directly via DFU mode without programming OTP memory beforehand.
* **Neon Blue OLED Theme**: High-contrast dark theme (`#05080F`) with glowing neon ice-blue pixels (`#00D2FF`) matching physical I2C OLED (SSD1306/SH1106) displays.
* **Multi-Palette Support**: Supports Neon Blue OLED, Pure White OLED, and Classic Amber display modes.
* **Region Lock Bypass**: Automatically treats DIY boards as `Region::Dev` to prevent radio/region provisioning blocks.
* **Target `f7` & Version `12` Recognition**: Full compatibility with custom `.tgz` and `.dfu` packages.

## 🚀 How to Use
1. Extract `qFlipperMod.7z` or run `qFlipper.exe`.
2. Connect your DIY Flipper:
   - **Normal Mode**: Connect via USB-C. The device will be detected as `DIY Flipper` with real-time OLED screen mirroring.
   - **DFU Recovery Mode**: Hold `BOOT0` on the WeAct board while plugging into USB, then release `BOOT0`. Click **REPAIR** or **Install from file** to flash custom firmware.

## 🛠️ Source Code & Building
The source code and build instructions for this customized edition are maintained within the [oled_flipper](https://github.com/a0gsoft/oled_flipper) project.