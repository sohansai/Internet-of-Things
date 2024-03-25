# Ultrasonic Sensor and LCD Interfacing with Arduino

## Aim
To design and simulate ultrasonic sensor and LCD interfacing with Arduino for distance measurement using the SR04 Ultrasonic distance sensor.

## Procedure
![image](https://github.com/sohansai/internet-of-things/assets/76840110/4c3e63e6-6dcb-4898-9aef-f6c1d79b1a6d)



### I2C (Inter-Integrated Circuit)
1. Connect the Ultrasonic Sensor SR04 to Arduino UNO using jumper wires.
2. Attach the 16x2 LCD (HDD44780 driver based) to the I2C board using jumper wires.
3. Power the system using a 6V battery or a 5V USB power source.
4. Ensure the LiquidCrystal I2C library is installed.


## Install Library - LiquidCrystal I2C
Make sure to install the LiquidCrystal I2C library for the Arduino IDE. You can do this by following these steps:
1. Open the Arduino IDE.
2. Go to Sketch -> Include Library -> Manage Libraries.
3. In the Library Manager, type "LiquidCrystal I2C" in the search bar.
4. Select the "LiquidCrystal I2C" library and click "Install."

Now you are ready to run the ultrasonic sensor and LCD interfacing code on your Arduino UNO.

### Components
- Arduino UNO
- Ultrasonic Sensor SR04
- 16x2 LCD (HDD44780 driver based)
- 6V battery or 5V USB power source (Mobile adapter/laptop)
- I2C Board
- Jumper wires
- Breadboard

### Circuit Diagram

![image](https://github.com/sohansai/internet-of-things/assets/76840110/baa4e1c2-ac50-422e-9950-b98edc0ac7b9)

