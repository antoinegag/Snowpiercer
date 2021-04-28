# Snowpiercer Balloon

Wireless environmental data collection device.

## Hardware

- ESP8266 Controller and interface
- BME280 Environmental data collection

## Setup

### Setting up Arduino IDE

Setup the Arduino IDE to use the ESP8266
Follow the instructions here:
https://github.com/esp8266/Arduino#installing-with-boards-manager

For this projet you will need the following libraries.
Install them using the library manager (Tools -> Manage Libraries...)

- BME280: https://github.com/finitespace/BME280

### Network credentials

Create a file named `psswd.h` and put the following in

```c
#ifndef STASSID
#define STASSID "<YOUR_SSID>"
#define STAPSK  "<YOUR_PASSWORD>"
#endif
```

And replace <YOUR_SSID> for your SSID (Network name that you see your wifi come up as) and <YOUR_PASSWORD>
