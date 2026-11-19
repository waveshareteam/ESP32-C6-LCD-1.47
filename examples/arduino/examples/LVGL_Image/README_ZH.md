# LVGL_Image

[English](README.md) | [简体中文](README_ZH.md)

## 功能

从 MicroSD 卡读取并显示 LVGL 图片内容。

## 硬件需求

- ESP32-C6-LCD-1.47 开发板
- 包含所需图片资源的 MicroSD 卡

## 怎么运行

1. 安装 Arduino-ESP32 `3.0.7`。
2. 将原 SD Card File 文件夹中的资源复制到 MicroSD 卡。
3. 打开 `LVGL_Image.ino`，选择 `ESP32C6 Dev Module` 并上传。

## 预期现象

显示屏显示从 MicroSD 卡读取的图片内容。

## 常见问题

上传和测试前必须准备好所需的 SD 卡资源。
