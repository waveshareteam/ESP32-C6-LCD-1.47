# LVGL_Image

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Displays PNG images from a microSD card on the LCD.

## Hardware Required

- ESP32-C6-LCD-1.47 development board
- MicroSD card

## How to Run

1. Install Arduino-ESP32 `3.0.7` and set the Arduino IDE sketchbook location to [`examples/arduino/`](../../) to use the bundled libraries.
2. Copy the PNG files from [`sd-card/`](sd-card/) directly to the microSD card root, then insert the card into the board.
3. Open [`LVGL_Image.ino`](LVGL_Image.ino), select `ESP32C6 Dev Module`, and upload.

## Expected Result

The LCD cycles through the PNG images on the card.

## Troubleshooting

If no images appear, check that the card is detected and that the `.png` files are in its root directory.
