# ESP8266 WiFi Test

This project demonstrates how to connect an ESP8266 to a WiFi network. The code is located in the `script.ino` file. Thanks to the original creator of the code; I've optimized some parts to improve readability and functionality.

## Features
- Connects the ESP8266 to a specified WiFi network.
- Prints the device's local IP address upon successful connection.
- Minimal setup for easy testing of WiFi connectivity.

## Usage
1. Clone or download this repository.
2. Open the project in your preferred IDE (e.g., Arduino IDE).
3. Replace the placeholders in `script.ino` with your WiFi credentials:
   ```cpp
   const char* ssid = "YOUR_SSID";
   const char* password = "YOUR_PASSWORD";
