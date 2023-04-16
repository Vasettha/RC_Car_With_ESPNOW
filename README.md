# RC_Car_With_ESPNOW
This repository contains the code and documentation for building an RC Car using an ESP32 microcontroller on the robot and an ESP8266 microcontroller for the controller.

## Getting Started:

### Hardware used:
#### Car
1. ESP32
2. Motor driver (I've used L298n)
3. 2x motors

#### Controller
1. ESP8266
2. 4x Buttons
3. 4x 10k Pull-Down Resistors

Note: You can use ESP32 for the controller or ESP8266 for the Car, But a code modification is required as they need different WiFi library

### Overview:
1. To use the controller code, you need to find out the receiver's MAC address.
2. To find out, upload the code to print out the esp's MAC address.
3. After getting the MAC address, input it to the MAC address in the controller's code.
