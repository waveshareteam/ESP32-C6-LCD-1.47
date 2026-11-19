# ESP32-C6-LCD-1.47-Test

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Runs the LVGL display, SD card and LED strip demonstration for the ESP32-C6-LCD-1.47 board.

## Hardware Required

- ESP32-C6-LCD-1.47 development board
- MicroSD card for the SD card functions

## How to Run

```bash
idf.py set-target esp32c6 build flash monitor
```

## Expected Result

The display initializes and shows the LVGL interface. The SD card and LED strip functions are available through the demonstration code.

## Troubleshooting

Copy the required SD card resources before using the SD card image functions.
