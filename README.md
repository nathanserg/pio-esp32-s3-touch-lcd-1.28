# pio-waveshare-esp32s3-demo
Demo for the esp32s3 1.28inch display from Waveshare on Platformio

Esp32s3 used: https://www.waveshare.com/esp32-s3-touch-lcd-1.28.htm

This repo contains two demo:
- complete demo: like in the waveshare wiki of the board
- no touch demo: without touch and gyroscope
- WIP minimal demo: very basic tft_espi example with config

The reasons for the no touch and minimal demo are:
- I found it really hard to undersand the code from the wiki
- The config is spread everywhere with a lot of unnecessary definitions
- I want the libraries to not be directly in the projet but imported
