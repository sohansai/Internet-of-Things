# Arduino 7-Segment Display Interfacing

## Aim

Design and simulate LED 7-Segment Display interfacing with Arduino. The project aims to demonstrate the functionality of a 7-segment display controlled by an Arduino microcontroller.

## Procedure

### A) Procedure for Connecting 7 Segment:

1. **Common Anode Connection:**
   - Connect all LED pins of the 7-segment display to Arduino GPIO.
   - Connect Vcc pin of the 7-segment display to Common.
   - Use a 220 Ohm resistor to connect the 7-segment display anode to power (3.3V).

2. **Common Cathode Connection:**
   - Connect all LED pins of the 7-segment display to Arduino GPIO.
   - Connect Ground pin of the 7-segment display to Common.
   - Use a 220 Ohm resistor to connect the 7-segment display anode to power (3.3V).

3. **Arduino IDE Setup:**
   - Open the Arduino IDE on your computer.
   - Write the program.

4. **Compile and Upload:**
   - Compile the program to check for errors.
   - Upload the program to the Arduino board.

5. **Observation:**
   - Observe the 7-segment display to ensure it updates as expected.

### Components

1. Arduino Uno with Microcontroller (ATMEGA328P) - 1
2. 7-Segment Display - 1
3. 220 Ohm Resistor (Resistance is represented by Red, Red, Black code.) - 1
4. Bread Board - 1
5. USB B Data Cable - 1
6. Male to Male Jumper Cables (As required)

## Code

The Arduino code is available in the [code](https://github.com/sohansai/internet-of-things/blob/main/Arduino_7Segment_Display/Arduino_7Segment_Display.txt) directory.

## Circuit Diagram

![image](https://github.com/sohansai/internet-of-things/assets/76840110/e76c8bf8-f13e-45f4-bdfe-f3bcda4594fb)

![image](https://github.com/sohansai/internet-of-things/assets/76840110/192e724e-1516-438f-ade8-5e0050c53c1b)

Figure.1.1  " 7 Segment to display numbers from 0 to 9 "

![image](https://github.com/sohansai/internet-of-things/assets/76840110/6fbf7b5f-6f08-4ef6-a8c9-73b9935e3dd2)

Figure: 1.2 Circuit Diagram for 7 Segment Common Cathode to connect to Arduino

![image](https://github.com/sohansai/internet-of-things/assets/76840110/1cca225e-b261-4c6d-bf06-37437c013907)

Figure: 1.2 Circuit Diagram for 7 Segment Common Cathode to connect to Arduino



## Conclusion

This project demonstrates the interfacing of a 7-segment display with Arduino, showcasing its ability to display different digits. Feel free to modify the code or experiment with different displays to enhance your learning experience.

