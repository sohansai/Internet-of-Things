# Gas Sensor Data to ThingSpeak Cloud using NodeMCU

## Aim
Design and implement a system to capture gas sensor data using the MQ135 sensor with NodeMCU and send the data to ThingSpeak cloud for air quality monitoring.

## Components
1. NodeMCU
2. Gas Sensor MQ135
3. Breadboard
4. Male to Male Jumper Cables – 3 Nos

## Circuit Connection
1. Connect NodeMCU D0 Pin to MQ135 Gas Sensor D0 Pin.
2. Connect NodeMCU 3.3V Vcc to 3.3V on MQ135.
3. Connect NodeMCU GND to GND on MQ135.

## ThingSpeak Cloud Setup
1. Create an account on ThingSpeak cloud at [https://thingspeak.com/](https://thingspeak.com/).
2. Obtain your ThingSpeak API Key.

## Arduino IDE Setup
1. Install the Arduino IDE on your computer.
2. Open the Arduino IDE, go to File -> Preferences, and add the following URL to the "Additional Boards Manager URLs": `http://arduino.esp8266.com/stable/package_esp8266com_index.json`
3. Go to Tools -> Board -> Boards Manager, search for "esp8266," and install the package.
4. Select "NodeMCU 1.0 (ESP-12E Module)" as the board from Tools -> Board menu.
5. Install the required libraries for the MQ135 sensor.

## Code
Upload the Arduino sketch (`GasSensor_NodeMCU.txt`) provided in this folder to your NodeMCU. Update the Wi-Fi credentials and ThingSpeak API Key in the sketch.

## Circuit Diagram
![image](https://github.com/sohansai/internet-of-things/assets/76840110/dacbe720-7847-4e51-bd28-29e9ac70a475)


