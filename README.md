# VitalGard Smart Watch:



## Introduction:
in this repository the device part of the vital gard project is build this device is a smart watch that can measure the heart rate and the body temperature of the user and send the data to the server to be stored and analyzed.

## Components:
ESP32: the main microcontroller of the device. TTGO t-display: the display of the device. 

1)	MAX30102 Sensor: the sensor that is used to measure the heart rate and temperature of the user.
2)	Speacker: to play the sound


## Libraries:


## Project general
This project uses platformio to impliment the software and can be used.
In this project we use OTA (over the air update) with allows us upload new update to the device remotly.
please follow the project structure and add the ota to the next update of the software  
The ip address of the device can be change inside of the platformio.ini file  
