# Linearpad

A custom macropad project featuring a 3x3 key matrix with rotary encoder and OLED display.

## Features

- 9-key matrix layout (3x3)
- Rotary encoder with volume control
- OLED display with layer information
- RGB LED support (6 LEDs)
- Media key functionality

## Pin Configuration

### Matrix
- COL_PINS: [PA02_A0_D0, PA04_A1_D1, PA10_A2_D2]
- ROW_PINS: [PB08_A7_D7, PA09_A8_D8, PA11_A3_D3]

### Encoder
- ENC_SWA: D14
- ENC_SWB: D10
- ENC_A: PA06_A10_D10_MISO
- ENC_B: PA07_A9_D9_MOSI
- ENC_C: GND

### OLED
- OLED_SCL: PA09_A8_D8_SCK
- OLED_SDA: PA08_A4_D4_SDA
- OLED_VCC: VCC
- OLED_GND: GND

### LED
- LED_PIN: PA03_A3_D3

### Power
- VCC_3V3: VCC
- VCC_5V: PA14_A5_D5
- GND: GND 