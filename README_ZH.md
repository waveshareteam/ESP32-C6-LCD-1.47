<div align="center">
  <h1>ESP32-C6-LCD-1.47</h1>
  <p><strong>微雪 ESP32-C6 1.47 英寸 LCD 开发板示例和出厂固件</strong></p>
  <p><a href="README.md">English</a> | <strong>简体中文</strong></p>
  <p>
    <a href="https://github.com/waveshareteam/ESP32-C6-LCD-1.47/actions/workflows/build.yml"><img alt="构建" src="https://github.com/waveshareteam/ESP32-C6-LCD-1.47/actions/workflows/build.yml/badge.svg"></a>
    <a href="LICENSE"><img alt="许可证" src="https://img.shields.io/github/license/waveshareteam/ESP32-C6-LCD-1.47"></a>
  </p>
  <p>
    <a href="https://www.waveshare.com/esp32-c6-lcd-1.47.htm">🛒 产品</a> &middot;
    <a href="firmware/">📦 固件</a> &middot;
    <a href="examples/esp-idf/">🧩 ESP-IDF</a> &middot;
    <a href="examples/arduino/examples/">🔧 Arduino</a>
  </p>
</div>

---

## ✨ 概述

本仓库提供微雪 ESP32-C6-LCD-1.47 开发板的 ESP-IDF 和 Arduino 示例，同时提供已实测的出厂固件和硬件资料。

| 功能 | 器件或接口 |
| --- | --- |
| MCU | ESP32-C6 |
| 存储器 | 4 MB Flash，ESP-IDF 工程配置了 Octal PSRAM |
| 显示 | 1.47 英寸 LCD，ST7789T 控制器 |
| 触摸 | 现有工程未记录 |

## 📦 快速开始

恢复出厂演示时，请从[固件目录](firmware/)下载合并镜像，整片擦除目标设备后从 `0x0` 地址烧录。

开发时请进入示例目录并阅读对应 README。

## 🧪 示例

### ESP-IDF

| 示例 | 主要功能 |
| --- | --- |
| [ESP32-C6-LCD-1.47-Test](examples/esp-idf/ESP32-C6-LCD-1.47-Test/) | LVGL 显示、SD 卡和灯带演示 |

### Arduino

| 示例 | 主要功能 |
| --- | --- |
| [LVGL_Arduino](examples/arduino/examples/LVGL_Arduino/) | LVGL 显示演示 |
| [LVGL_Image](examples/arduino/examples/LVGL_Image/) | 从 MicroSD 卡显示 LVGL 图片 |

Arduino 共用库位于 [`examples/arduino/libraries`](examples/arduino/libraries/)。

## 🛠️ 开发环境

| 开发框架 | 版本 | 示例数 |
| --- | --- | ---: |
| ESP-IDF | `v5.3.2` | 1 |
| Arduino-ESP32 | `3.0.7` | 2 |

## 📚 资料

- [产品页](https://www.waveshare.com/esp32-c6-lcd-1.47.htm)
- [出厂固件](firmware/)
- [硬件资料](hardware/)

## 🤝 支持

- [微雪技术支持](https://service.waveshare.com/)

## 📄 许可证

Apache License 2.0，详见 [LICENSE](LICENSE)。
