# LVGL_Image

[English](README.md) | [简体中文](README_ZH.md)

## 功能

从 MicroSD 卡读取 PNG 图片并在 LCD 上显示。

## 硬件需求

- ESP32-C6-LCD-1.47 开发板
- MicroSD 卡

## 怎么运行

1. 安装 Arduino-ESP32 `3.0.7`，将 Arduino IDE 的项目文件夹位置设为 [`examples/arduino/`](../../)，以使用随仓库提供的库。
2. 将 [`sd-card/`](sd-card/) 中的 PNG 文件直接复制到 MicroSD 卡根目录，再将卡插入开发板。
3. 打开 [`LVGL_Image.ino`](LVGL_Image.ino)，选择 `ESP32C6 Dev Module` 并上传。

## 预期现象

LCD 循环显示卡中的 PNG 图片。

## 常见问题

如果屏幕未显示图片，请确认开发板已识别存储卡，并检查 `.png` 文件是否位于卡的根目录。
