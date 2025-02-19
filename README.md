# This repository will include all data for both TDM-2205 SIM7600CE-ESP32-DEV-KIT and TDM-2202 A7600C-DEV-KIT module
---
__Advertisement__
#### Order easy online at:
- __[TDM-SIM7600CE-M1S](https://linhkienthuduc.com/module-4g-3g-2g-gps-simcom-sim7600ce-m1s-lte-cat-4-ra-chan)__ - 2G/3G/4G LTE CAT 4 GPS BREAKOUT MODULE
- __[TDM-A7600C-L1](https://linhkienthuduc.com/module-4g-3g-2g-simcom-a7600c-l1-lte-cat-1-ra-chan)__ - 2G/3G/4G LTE CAT 1 BREAKOUT MODULE.
- __[TDM-A7670C-LASS](https://linhkienthuduc.com/module-4g-simcom-a7670c-lass-da-ra-chan-thay-the-module-sim800l)__ - 4G LTE CAT 1 BREAKOUT MODULE.
----
This repo will provide you all data for these module!
---

### TDM-SIM7600CE-ESP32-DEV-KIT Module Specifications:

+ General data::
  - Supply voltage range on 5V PIN: 5Vdc
  - Control Via AT Commands
  - Operation temperature: -40℃ to +85℃
  - Weight: : 5.7 ± 0.2g
  - GNSS:GPS/GLONASS/BeiDou
  - Frequency:
    * LTE-FDD B1/B3/B5/B8
    * UMTS/HSDPA/HSPA+ B1/B8
    * GSM/GPRS/EDGE 900/1800MHz
---
### TDM-A7600C-L1 Module Specifications:

+ General data::
  - Supply voltage range on 5V PIN: 5Vdc
  - Control Via AT Commands
  - Operation temperature: -40℃ to +85℃
  - Weight: : 5.7 ± 0.2g
  - Frequency:
    * LTE-FDD B1/B3/B5/B8
    * UMTS/HSDPA/HSPA+ B1/B8
    * GSM/GPRS/EDGE 900/1800MHz

---
## AT Command Test GUI:

[User Guide ( Vietnamese)](https://linhkienthuduc.com/at-command-test-cho-cac-dong-module-sim)

[DOWNLOAD HERE](https://github.com/TDLOGY/ATCommand_Test)

See more our product at  [makerspace](https://tdlogy.com/en/makerspace/)
---
## Example code with ESP32:

[ESP32 PPPOS Test](https://github.com/TDLOGY/esp32_pppos)

[ESP32 MQTT with 4G module example code](https://linhkienthuduc.com/huong-dan-su-dung-module-4g-voi-esp32-mqtt)

---

## Examples firmware

See in **example_firmware**

## Pin Tables
| Name| Description |
| ------ | ----------- |
| USB-ESP32 | Serial programing for ESP32, can use as power supply for module with USB-3.1 port (1A max)|
| GND| GND power |
| U-TX| TX ESP32 UART for programing |
| U-RX| RX ESP32 UART for programing|
| PCM ports| SIM PCM ports|
| I2C| SIM I2C ports|
| IO16| SIM TX - ESP32 RX PIN internal connection|
|I017| SIM RX - ESP32 TX PIN internal connection|
| IO0..IO36| ESP32 Pin Out|
| 3V3| Internal LDO power supply|
| 5V| USB/External power supply for KIT|
| EN| Enable pin of ESP32|
| IO15| Enable pin for Power Up SIM Module, active low|

- ### Pin  Out Diagram

![Pinout](https://github.com/TDLOGY/HW_TDM-SIM7600CE-ESP32-DEV-KIT/blob/main/PINOUT_ESP32_SIM7600X-DEVKIT.JPG)

- ### Module Dimension

![Dimension](https://github.com/TDLOGY/HW_TDM-SIM7600CE-ESP32-DEV-KIT/blob/main/Dimension_ESP32_SIM7600X-DEVKIT.JPG)

