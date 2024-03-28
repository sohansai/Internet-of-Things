
# Design and Implementation of Humidity and Temperature Monitoring Using NodeMCU

## Aim
To get temperature and humidity data from the DHT11 Module using NodeMCU microcontroller and upload the data to Adafruit MQTT cloud.

## Procedure

### Introduction
This example demonstrates how to report temperature and humidity data collected by the DHT11 sensor to the MQTT service in the cloud through the MQTT protocol and the NodeMCU based on ESP8266. It also shows how the application subscribes to and processes the data. MQTT protocol is chosen for its lightweight and energy-saving nature, making it suitable for Internet of Things (IoT) scenarios. Major public cloud providers like AWS and Azure have opened IoT hub services based on the MQTT protocol.

### Overall Architecture
The overall architecture includes:
- Hardware Configuration
- Arduino IDE Configuration
![image](https://github.com/sohansai/internet-of-things/assets/76840110/f2601e1b-4737-46ce-9a19-c12c7574aee1)

### Hardware Configuration
- NodeMCU board x 1: An open-source IoT platform running on ESP8266 Wi-Fi SoC.
- DHT11 temperature/humidity sensor x 1: A composite sensor with calibrated digital signal output.
- Breadboard x 1
- Several jumper wires
- Arduino IDE Configuration

### Arduino IDE Configuration
1. Download and install CH340G USB driver.
2. Install ESP8266 module: Set the preferences URL: [https://arduino.esp8266.com/stable/package_esp8266com_index.json](https://arduino.esp8266.com/stable/package_esp8266com_index.json).
3. Install AdaFruitMQTT library (by Adafruit):
   - Sketch -> Include Library -> Manage Libraries…
   - Type AdaFruitMQTT in the Search field.
   - Install AdaFruit MQTT with Client Service.

### Connecting to Adafruit MQTT Cloud
1. After successfully collecting data through NodeMCU, it needs to be sent to the MQTT cloud service. This example uses the MQTT cloud service provided by Adafruit.
2. Register and sign in at [Adafruit](https://www.adafruit.com/).
3. Click on IO -> MyKey and collect API Authentication Key and User Name.
4. Choose Feeds -> View All -> Create New Feed, give a name to the feed, then press OK to create the feed.
5. Repeat the process for creating feeds and update the feed names in the code provided for the Adafruit MQTT client program to be uploaded into the NodeMCU device.

### Components
1. NodeMCU – 1 No
2. DHT11 - 1 No
3. Breadboard - 1 No
4. Jumper Cables - 3 No
5. USB Cable – 1 No

### Circuit Diagram
![image](https://github.com/sohansai/internet-of-things/assets/76840110/9e55defe-de12-4cdb-a49d-0637ad6252d3)
