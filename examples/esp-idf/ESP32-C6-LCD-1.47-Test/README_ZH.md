# ESP32-C6-LCD-1.47-Test

[English](README.md) | [简体中文](README_ZH.md)

## 功能

运行 ESP32-C6-LCD-1.47 的 LVGL 显示、SD 卡和灯带演示。

## 硬件需求

- ESP32-C6-LCD-1.47 开发板
- 使用 SD 卡功能时需要 MicroSD 卡

## 怎么运行

```bash
idf.py set-target esp32c6 build flash monitor
```

## 预期现象

显示屏完成初始化并显示 LVGL 界面，示例代码提供 SD 卡和灯带功能。

## 常见问题

使用 SD 卡图片功能前，需要先复制所需的 SD 卡资源。
