# Design and Implementation of Raspberry Pi Home Security System with Camera and PIR Sensor with Email Notifications

## Aim

To capture a picture and save it in the system when an intrusion is detected by the PIR sensor and send an email notification.

## Procedure

1. Use a 5MP Raspberry Pi 3 Model B Camera Module with a flexible cable designed for attachment with Raspberry Pi 3 Model B.
2. Connect the camera to the BCM2835 processor on the Pi via the CSI bus. The CSI bus is a higher bandwidth link carrying pixel data from the camera back to the processor. This bus travels along the ribbon cable that attaches the camera board to the Pi.
3. Without providing power to the Raspberry Pi, connect the Raspberry Pi camera:
    - Face the terminal line towards the HDMI direction.
    - Connect the blue color to the USB direction.
    - Connect the PIR output to Raspberry Pi GPIO 4.
    - Connect GND to any GND on Raspberry Pi.
    - Connect Vcc to 5V at the top right of Raspberry Pi.
4. Open the Thonny editor, type the program code, and save it as a Python 3 file (e.g., `file_name.py`). Press Enter. Click on the run button to execute the code.

## Components
  1. Raspberry Pi 3 with SD Card loaded with Raspberry Pi OS
  2. HDMI Cable for Raspberry Pi 3 or Micro HDMI Cable for Raspberry Pi 4
  3. Power up with USB Cable for Raspberry Pi 3 or power up with USB C for Raspberry Pi 4
  4. PIR Module with (GND, DATA, VCC)
  5. Female to Female Jumper Cables – 3 Nos

## Circuit Diagram :
![image](https://github.com/sohansai/internet-of-things/assets/76840110/56b83844-52d9-4e79-bcbf-8d6dcd96dc56)
![image](https://github.com/sohansai/internet-of-things/assets/76840110/4824f3bb-0c21-4b93-867c-29f2e4b6b978)


