# Factory Firmware

[English](README.md) | [简体中文](README_ZH.md)

This directory stores the tested factory image for ESP32-C6-LCD-1.47.

| File | Purpose |
| --- | --- |
| [ESP32-C6-LCD-1.47_FactoryOnly_20260203.bin](ESP32-C6-LCD-1.47_FactoryOnly_20260203.bin) | Factory recovery firmware for ESP32-C6-LCD-1.47, dated 2026-02-03. Flash from `0x0`. |

Before flashing:

- Back up any device-specific data that must be preserved.
- Confirm the board model and hardware revision.
- Erase the target device before writing the merged image.
- Follow the flashing procedure in the product documentation.

SHA-256: `F13C96D16FAE6EBEFCCD9A456884A94E73ECCA96F1D5604D32F5425EE0D5C40D`

This file is a single merged BIN for factory recovery.
