# ESP32-1732S019 "RoboKot"

ESP32-S3 N16R8 board with built-in 1.9" ST7789 (170x320) display, used in landscape (320x170, buttons/USB on the left).

Audio (same as bread-compact-wifi):
- INMP441 mic: WS=GPIO4, SCK=GPIO5, SD=GPIO6
- MAX98357A amp: DIN=GPIO7, BCLK=GPIO15, LRC=GPIO16

Display (built-in): MOSI=13, SCLK=12, CS=10, DC=11, RST=1, BL=14

Emotions: animated cat-eye GIFs in eyes/ (300x100, dark theme).
CI builds this board with --language ru-RU --wake-word wn9_himiaomiao_tts.
