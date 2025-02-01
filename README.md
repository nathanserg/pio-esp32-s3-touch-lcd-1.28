# pio-waveshare-esp32s3-demo
Demo for the esp32s3 1.28inch display from Waveshare on Platformio

Esp32s3 used: https://www.waveshare.com/esp32-s3-touch-lcd-1.28.htm

This repo contains two demo:
- complete demo: like in the waveshare wiki of the board
- no touch demo: without touch and gyroscope
- TFT_ESPI demo: very basic tft_espi example with config

For the last demo you have to copy the file User_Setup.h to the path below for TFT_ESPI to use the correct pinout and config
/pio-waveshare-esp32s3-demo/tft-espi-demo/.pio/libdeps/waveshare_esp32s3_touch_lcd_128/TFT_eSPI
