# Design and Implementation to Upload Light Sensor (TSL) Data to Cloud Through Raspberry Pi

## Aim
To simulate the automatic glow of LED when the intensity of light is LOW using LDR.

## Procedure

1. An LDR (Light Dependent Resistor) or a photo resistor is a photoconductive sensor. It is a variable resistor that changes its resistance in proportion to the light exposed to it. Its resistance decreases with the intensity of light.

2. Connect the LDR:
    - Connect one leg of the LDR with 3.3v.
    - Connect the other leg of the LDR with the positive leg of the 10UF capacitor.
    - Connect the other leg of the capacitor with the ground.
    - Take a wire from the middle and connect it with pin number 7 of the Raspberry Pi.

3. Connect the LED:
    - Connect the LED with pin number 11.

4. The RC circuit is connected with pin number 7.

## Components
- Raspberry Pi
- LDR
- Female to Male Jumper Wires (2 Nos)
- Breadboard

## Circuit Diagram

![image](https://github.com/sohansai/internet-of-things/assets/76840110/26fe4ba0-6b43-4232-9308-ab90ffc97bc9)
![image](https://github.com/sohansai/internet-of-things/assets/76840110/a7ec2d81-4cba-4d24-b592-77cc604841e1)


