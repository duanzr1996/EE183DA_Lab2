# EE183DA_Lab2

This is Lab assignment 2 for EE 183DA. In this lab, I use web interface to control the servo to create "music".

•	Bill of Materials:  
I used a FS90 Servo to control the arm to hit the bottles in different rhythms, therefore creating percussion music; the arm is made of cardboard and a metal screwdriver bit is attached on the front of the arm.

•	Schematics:  
![lab2_schematics](https://cloud.githubusercontent.com/assets/18479261/22621697/998ffe26-eade-11e6-98b8-8a3cb600074a.jpg)

•	Wiring Setup:  
The servo has three wire inputs: data, voltage and ground. I plugged them on number 4 of the motor driver shield.

•	System Design:  
The ESP8266 Microcontroller has a built-in Wi-Fi module, and I created a HTTP Server using the MCU. The website has two buttons on it: Rhythm 1 and Rhythm 2. Once the user click on the corrseponding button, the MCU will write preset rotating commands to the servo. The angle and delay are already specified in these commands, so that the mechanical arm can hit on the bottles with different rhythms.  

•	Further Development:  
For further development, I'd like to enable the user to write the own tempo of the percussion music; the user can specify the speed level, and the MCU can translate it to the servo to customize the tempo.  

