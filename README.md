<div align="center">
  <h1>ESP32-C6-LCD-1.47</h1>
  <p><strong>Waveshare ESP32-C6 1.47-inch LCD development board examples and factory firmware</strong></p>
  <p><strong>English</strong> | <a href="README_ZH.md">简体中文</a></p>
  <p>
    <a href="https://github.com/waveshareteam/ESP32-C6-LCD-1.47/actions/workflows/build.yml"><img alt="Build" src="https://github.com/waveshareteam/ESP32-C6-LCD-1.47/actions/workflows/build.yml/badge.svg"></a>
    <a href="LICENSE"><img alt="License" src="https://img.shields.io/github/license/waveshareteam/ESP32-C6-LCD-1.47"></a>
  </p>
  <p>
    <a href="https://www.waveshare.com/esp32-c6-lcd-1.47.htm">🛒 Product</a> &middot;
    <a href="firmware/">📦 Firmware</a> &middot;
    <a href="examples/esp-idf/">🧩 ESP-IDF</a> &middot;
    <a href="examples/arduino/examples/">🔧 Arduino</a>
  </p>
</div>

---

## ✨ Overview

This repository provides ESP-IDF and Arduino examples for the Waveshare ESP32-C6-LCD-1.47 development board, together with its tested factory firmware and hardware resources.

| Feature | Device / interface |
| --- | --- |
| MCU | ESP32-C6 |
| Memory | 4 MB Flash, Octal PSRAM configured by the ESP-IDF project |
| Display | 1.47-inch LCD with ST7789T controller |
| Touch | Not documented in the supplied project |

## 📦 Quick Start

To restore the factory demonstration, download the merged image from the [firmware directory](firmware/) and flash it from `0x0` after erasing the target device.

For development, open an example directory and follow its README.

## 🧪 Examples

### ESP-IDF

| Example | Main feature |
| --- | --- |
| [ESP32-C6-LCD-1.47-Test](examples/esp-idf/ESP32-C6-LCD-1.47-Test/) | LVGL display, SD card and LED strip demonstration |

### Arduino

| Example | Main feature |
| --- | --- |
| [LVGL_Arduino](examples/arduino/examples/LVGL_Arduino/) | LVGL display demonstration |
| [LVGL_Image](examples/arduino/examples/LVGL_Image/) | LVGL image display from a MicroSD card |

Shared Arduino libraries are provided in [`examples/arduino/libraries`](examples/arduino/libraries/).

## 🛠️ Development Environment

| Framework | Version | Examples |
| --- | --- | ---: |
| ESP-IDF | `v5.3.2` | 1 |
| Arduino-ESP32 | `3.0.7` | 2 |

## 📚 Resources

- [Product page](https://www.waveshare.com/esp32-c6-lcd-1.47.htm)
- [Factory firmware](firmware/)
- [Hardware resources](hardware/)

## 🤝 Support

- [Waveshare support](https://service.waveshare.com/)

## 📄 License

Apache License 2.0. See [LICENSE](LICENSE).
