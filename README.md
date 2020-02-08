# esp32-mega-app
A template for ESP32 apps that take full advatage of stuff available

## Web UI
- Modern Web UI
- Resource stored in a [BlobFS](https://github.com/paulo-raca/BlobFS)
- Setup uses AJAX endpoints with Swagger definitions
- Also compatible with Web-Bluetooth APIs to setup the board without Wifi conectivity
- Should support HTTPS

## Wifi
- WiFiManager-like setup portal
- Configurable via Web UI / Bluetooth
- Support for WPS
- AP may act as either a captive portal or an internet Gateway (With / Without NAT)
- Maybe enable/disable Wifi-STA, Wifi-AP and Bluetooth

## Bluetooth 
 - Should broadcast the URL for the Web UI
 
## OTA
 - Either by Wifi or Bluetooth, from the Web UI
