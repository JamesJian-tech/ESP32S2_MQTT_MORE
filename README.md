
# ESP32S2_MQTT_MORE
ESP32S2_C_python

# ESP32-S2 

![WeChat Image_20210502010647 (Small)](https://user-images.githubusercontent.com/49461855/116786660-46f9b480-aae3-11eb-8bfa-baaa6b0bb925.jpg)


https://learn.adafruit.com/building-circuitpython/esp32-s2-build

https://github.com/adafruit/circuitpython/releases

# ESP32-S2 vs ESP32
Compared with ESP32-S2 and ESP32, the difference is explained as follows
Module|ESP32 | ESP32-S2|
----|----|----|
Microcontroller | Xtensa dual-core 32-bit LX6 | Xtensa single-core 32-bit LX7 |
Clock Frequency | 160/240 MHz | 160/240 MHz|
Co-processor | ULP   |  ULP (RISC-V)|
SRAM | 520 KB| 320 KB |
ROM | 448 KB| 128 KB |
RTC Memory | 16 KB| 16 KB |
External SPIRAM | Up to 16MB| Up to 128MB |
External Flash | No| Up to 1G |
Wi-Fi (802.11 b/g/n) | HT20 | HT20 |
ESP-MESH | Yes| Yes |
Bluetooth | BT 4.2 BR/EDR & BLE |  No |
Ethernet | 10/100 Mbps| No |
CAN | 2.0| No |
Time of Flight |  No | Yes |
GPIO (total) | 34| 43 |
Touch Sensors | 10 | 14 |
SPI | 4| 4 (OSPI) |
I2C | 2| 2 |
I2S | 2| 1 |
UART | 3 | 2 |
ADC | 18 (12-bit)| 20 (12-bit) |
DAC | 2 (8-bit)| 2 (8-bit) |
PWM (soft) | 16 | 8 |
SDMMC | Yes| No |
RMT (remote control) | Yes| Yes |
USB OTG | No| Yes |
LCD Interface | No| Yes |
Camera Interface | No| Yes |
Temperature sensor | Yes| Yes |
Hall sensor | Yes| No |
Security | Secure boot Flash encryption 1024-bit OTP| Secure boot Flash encryption 4096-bit OTP |
Crypto | AES, SHA-2, RSA, ECC, RNG| AES-128/192/256, SHA-2, RSA, RNG, HMAC, Digital Signature|
Low Power Consumption | 10uA deep sleep| Automatic RF power management 5uA in idle mode 24uA at 1% duty cycle |
