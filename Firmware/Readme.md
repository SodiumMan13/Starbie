In Arduino IDE, open File • Preferences, and add this to Additional Boards Manager URLs:

```https://espressif.github.io/arduino-esp32/package_esp32_index.json```

Open Tools • Board • Boards Manager, search for esp32, and install esp32 by Espressif Systems.

Select Tools • Board • ESP32 • XIAO_ESP32C3, and select the board's port under Tools → Port.

Open Sketch • Include Library • Manage Libraries, and install:

Adafruit GFX Library
Adafruit SSD1306
Adafruit MPU6050
DHT sensor library
If Arduino asks to install dependencies, choose Install All.
