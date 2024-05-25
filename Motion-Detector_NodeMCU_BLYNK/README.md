# Design and Implementation of Motion Detector with NodeMCU and BLYNK

## Aim
To create an IoT-based mobile application using Blynk for notification, demonstrating Motion Detection using NodeMCU.

## Procedure

### Include ESP8266 Core to Arduino IDE
1. Navigate to 'Preferences' and enter the following URL in Additional Board Manager URLs:
2. Open the Boards Manager (Tools > Board Menu).
3. Search for "esp8266" and install the latest version.
4. Select your board under Tools > Board and define Baud Rate, etc.

### Install Blynk Libraries
1. Install the latest release of the Blynk libraries from GitHub at the following URL:
2. Unpack it.
3. Move the libraries to `C:/User//Documents/Arduino/libraries`.

### Install Blynk App
1. Download the App for iOS or Android.

### Setup in Android or iOS
1. Click 'Create New Project.'
2. Choose your device and connection type (NodeMCU, WiFi).
3. Receive and note down your 'Auth Token.'
4. Open the 'Widget Box' ('+').
5. Add a button.
6. Name it and select switch mode.
7. Define the output pin the LED is connected to (anode Dx, cathode GND).


![image](https://github.com/sohansai/internet-of-things/assets/76840110/a5142e4d-7e0d-4df6-bedb-c8ff86e2a37f)

### Setup in Windows 8/Linux (Arduino IDE)
The client-side code for remote controlling an LED is straightforward.

1. Open the Arduino IDE.
2. Go to Examples > Blynk > Boards_WiFi and select your development board.
3. Enter your 'Auth Token' (`char auth[]`).
4. Enter your WiFi credentials (`char ssid[], char pass[]`).
5. Compile and Upload.
6. Open the Serial Monitor and check whether connecting was successful.
