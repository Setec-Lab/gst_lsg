LoRa Sensor Gateway for SETECLab's Ground Station Terminal  
============

### Most recent version of this repository can be found in: ###

* [GitHub](https://github.com/Setec-Lab/gst_lsg)

### What is this repository for? ###

* This repository was created to develop a LoRa Sensor Gateway for the SETECLab's custom GST. 

### HELTEC LoRa 32 board information

* [Documentation page](https://heltec.org/project/wifi-lora-32/)
* [Pinout diagram](https://resource.heltec.cn/download/WiFi_LoRa_32/WIFI_LoRa_32_V2.pdf)
* [Schematic](https://resource.heltec.cn/download/WiFi_LoRa_32/V2/WIFI_LoRa_32_V2(868-915).PDF)
* [ESP32 datasheet](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf) 

### MCP9600 I2C Thermocouple Amplifier

* [Datasheet](https://cdn-learn.adafruit.com/downloads/pdf/adafruit-mcp9600-i2c-thermocouple-amplifier.pdf) 

### Enclousure


### How do I get set up? ###

* Install Git
* Install Arduino IDE
* Install ESP32 Board in the Arduino Boards Manager
Open Arduino IDE, then Select `Tools`->`Board:`->`Boards Manager...`
Search `ESP32` and install it.
* Install Heltec ESP32 Library in the Arduino Library Manager
Open Arduino IDE, then Select `Sketch`->`Include Library`->`Manage Libraries...`
Search `Heltec ESP32` and install it.
* Install Adafruit MQTT Library in the Arduino Library Manager
Open Arduino IDE, then Select `Sketch`->`Include Library`->`Manage Libraries...`
Search `Adafruit MQTT` and install it.
* Install Adafruit MCP9600 Library in the Arduino Library Manager
Open Arduino IDE, then Select `Sketch`->`Include Library`->`Manage Libraries...`
Search `Adafruit MCP9600 Library` and install it.

### Library source code and examples
* [Adafruit_MQTT_Library](https://github.com/adafruit/Adafruit_MQTT_Library)

### Contribution guidelines ###

* If you want to propose a review or need to modify the code for any reason first clone this [repository](https://github.com/DeltaLabo/caminos) in your PC and create a new branch for your changes. Once your changes are complete and fully tested ask the administrator permission to push this new branch into the source.
* If you just want to do local changes instead you can download a zip version of the repository and do all changes locally in your PC. 

### Who do I talk to? ###

* [Juan J. Rojas](mailto:juan.rojas@itcr.ac.cr)
* [Ian Coberly](mailto:cobjim28@gmail.com)
 