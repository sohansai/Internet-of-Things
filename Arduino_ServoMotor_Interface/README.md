# Arduino Servo Motor Interface

## Aim
Design and simulate servo motor interfacing with Arduino to perform 180-degree movement.

## Components
1. Arduino Uno with USB Cable
2. Male to Male Jumper Cable – 3 Nos
3. Servo Motor

## Procedure
1. Connect the servo motor to the Arduino board following the specified wiring:
   - Orange Wire: PWM output from pin 9 to Motor Control Input
   - Red Wire: +6V supply for Motor
   - Black Wire: 0V (Ground)

2. Connect the Supply to the board (5-12V DC). Connect USB with PC and upload the sketch to the board.
   
3. On connecting the board first time, it’ll ask for the drivers (which can be
downloaded from arduino website).
4. Open Arduino IDE and Create a new Sketch (In Arduino world code/program is called a ‘sketch’).
5. Write the code and ‘verify’ (option on toolbar) it. After verifying it will notify if
there are any errors otherwise ‘Done Compiling’ will be shown.
6. Now Upload the sketch to the Hardware. When sketch is Uploaded, Press Reset on the board. Now connect Servo control Pin at respective Pin and provide supply to it. The Pin9 of PWM port of the board provides motor control.


## Circuit Diagram
![image](https://github.com/sohansai/internet-of-things/assets/76840110/ac8ee452-f4c6-44b6-83ed-4309ae1fc7c6)


