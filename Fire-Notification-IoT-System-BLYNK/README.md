# Design and Implementation of Fire Notification IoT System with BLYNK

## Aim
The aim of this project is to demonstrate an IoT-based mobile application that receives notifications when a fire is detected by a fire sensor.

## Procedure

### 1. Include ESP8266 Core to Arduino IDE
   1. Go to 'Preferences' and enter the following URL in Additional Board Manager URLs:
      ```
      http://arduino.esp8266.com/stable/package_esp8266com_index.json
      ```
   2. Open the Boards Manager (Tools > Board Menu)
   3. Search for "esp8266" and install the latest version
   4. Select your board under Tools > Board and define Baud Rate, etc.

### 2. Install Blynk Libraries
   1. Install the latest release of the Blynk libraries from GitHub URLs:
      ```
      https://github.com/blynkkk/blynk-library/releases/tag/v0.6.1
      ```
   2. Unpack it
   3. Move the libraries to `C:/User//Documents/Arduino/libraries`

### 3. Install Blynk App
   1. Download the Blynk App for iOS or Android
   2. In Android or iOS, click 'Create New Project'
   3. Choose your device and connection type (NodeMCU, WiFi)
   4. Receive and note down your 'Auth Token'
   5. Open the 'Widget Box' ('+')
   6. Add a Notification
   7. Define the output pin the FireSensor is connected to (anode Dx, cathode GND)

![image](https://github.com/sohansai/internet-of-things/assets/76840110/cfaa8e78-35fe-4c15-84c7-44bd5a182845)

## Components
1. Nodemcu
2. FireSensor
3. FireGenerating Component/MatchBox/High Intensity of Light

## Circuit Diagram
![image](https://github.com/sohansai/internet-of-things/assets/76840110/604076b9-f161-44ac-a957-e7e066737659)
