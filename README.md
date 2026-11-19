# Привіт! 👋 / Hi there!

Роблю саморобні пристрої на **ESP32 / ESP8266**: ретро-консоль, смарт-дисплей з погодою,
квадрокоптер з керуванням геймпадом, міст для кондиціонерів TCL у Home Assistant.
Усе — з повною прошивкою, схемами й інструкціями збирання.

DIY hardware on **ESP32 / ESP8266**: a handheld retro console, a weather smart display,
a gamepad-controlled drone, a TCL air-conditioner bridge for Home Assistant.
Every project comes with full firmware, wiring diagrams and build notes.

## Проєкти / Projects

| Проєкт | Що це | Залізо |
|---|---|---|
| 🎮 [retro-console-esp32s3](https://github.com/AlexGerUA/retro-console-esp32s3) | Портативна ретро-консоль: NES/Dendy, Game Boy, Sega Master System / Game Gear на базі Retro-Go. 3D-корпус, схема, оверлей прошивки. <br>*Handheld retro game console (NES, Game Boy, SMS) with 3D-printed case.* | ESP32-S3, ILI9341 2.4", MAX98357A |
| 🌦️ [smart-display-esp32s3](https://github.com/AlexGerUA/smart-display-esp32s3) | Смарт-дисплей: годинник, погода, курс крипти, біржа, пінг, очі котика. Налаштування через веб, OTA. <br>*Smart display: clock, weather, crypto, markets, web setup, OTA.* | ESP32-S3 Super Mini, ST7789 240×280 |
| 📺 [smalltv-cube](https://github.com/AlexGerUA/smalltv-cube) | Відкрита прошивка для кубика SmallTV з AliExpress: годинник, погода Open-Meteo без ключа, крипта, ваші фото. UA/EN + Android-додаток. <br>*Open firmware for the AliExpress SmallTV cube: clock, weather (no API key), crypto, photos.* | ESP8266, ST7789 240×240 |
| 🚁 [esp32-s3-gamepad-drone](https://github.com/AlexGerUA/esp32-s3-gamepad-drone) | Саморобний квадрокоптер на колекторних моторах, керування геймпадом Xbox через Bluepad32. Стабілізація з Espressif esp-drone. <br>*DIY brushed quadcopter flown with an Xbox controller (Bluepad32), Mahony AHRS + PID.* | ESP32-S3 Super Mini, MPU6050 |
| ❄️ [tcl-bridge-firmware](https://github.com/AlexGerUA/tcl-bridge-firmware) | Міст між кондиціонером TCL і Home Assistant: локальне керування без хмари, штатний Wi-Fi модуль працює паралельно. Оновлення по повітрю. <br>*TCL air conditioner ↔ Home Assistant bridge: local control via ESPHome, OTA updates.* | ESP32-S3 |

## Чим користуюсь / Tools

ESP-IDF · Arduino · PlatformIO · ESPHome · Home Assistant · LVGL · KiCad · KOMPAS-3D

---

<sub>Ключові слова / keywords: ESP32, ESP32-S3, ESP8266, ретро консоль esp32,
смарт дисплей, смарт годинник, retro console, NES emulator, smart display,
SmallTV, quadcopter, drone, Home Assistant, ESPHome, TCL air conditioner, DIY.</sub>
