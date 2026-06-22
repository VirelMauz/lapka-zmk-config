## Lapka Wellum36 + Dongle with OLED

New branch `add-dongle-oled` adds full OLED support (SSD1106 / SH1106) to the dongle, adapted from lily58_dongle in the main zmk-config repo.

### How to use
1. Switch to branch `add-dongle-oled`
2. Build `lapka_wellum36_dongle`
3. For SH1106 uncomment the corresponding section in lapka_wellum36_dongle.overlay
4. Connect OLED to I2C pins (SDA/SCL) on your dongle MCU.

Check the original lily58 implementation for widgets and advanced display features.