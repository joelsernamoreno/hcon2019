# hcon2019
Simple hardware keylogger storing keys at internal eeprom

![Alt text](/images/demo.png?raw=true "ProMicro pinout")

**Requirements:**

- Arduino PRO micro 3.3V
- USB host shield

- IDE arduino: http://arduino.cc
- Basic keylogger example code: https://github.com/joelsernamoreno/hcon2019




**Connect:**
![Alt text](/images/connect.png?raw=true "USB Host pinout")


**USB Host pinout:**
![Alt text](/images/usb_host.jpg?raw=true "USB Host pinout")


**Arduino ProMicro pinout:**

![Alt text](/images/promicro.png?raw=true "ProMicro pinout")


**Installation:**

1.- Download the arduino IDE and this repository

2.- Copy the Keyboard library to the arduino library directory

3.- Copy the USB Host library to the arduino libary directory

4.- Open the arduino IDE

5.- Select the "LilyPad Arduino USB" board (Tools -> Board -> LilyPad Arduino USB)

5.- (Optional) Check the connection between ProMicro and USB Host is correct with the example board_qc (File -> Examples -> Custom library examples -> USB Host Shield Library 2.0 -> board_qr)

6.- Open sketch basic_keylogger.ino

7.- Compile and upload




**Demo:**

1.- When the code is uploaded, open the serial monitor

2.- Type Hello World with your physical keyboard connected to the USB Host module

3.- Open a notepad

4.- To view the previously saved Hello World, press the key combination: LEFT_CTRL + LEFT_ALT + A (Hello World should appear in notepad)


If you have any questions, you can contact us by twitter:

@JoelSernaMoreno
@ernesto_xload








