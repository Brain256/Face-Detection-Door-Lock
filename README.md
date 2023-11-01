# Face-Detection-Door-Lock

<img src="https://github.com/Brain256/Face-Detection-Door-Lock/blob/main/photos/LockView.jpg" width="25%" height="33%"> <img src="https://github.com/Brain256/Face-Detection-Door-Lock/blob/main/photos/MainView.jpg" width="25%" height="33%"> <img src="https://github.com/Brain256/Face-Detection-Door-Lock/blob/main/photos/ServerView.jpg" width="25%" height="33%">

## Youtube Video Link

https://www.youtube.com/watch?v=OrecraZhADc

## Component List

* 12V Solenoid Door Lock
* Breadboard Power Supply Module
* Songle 5V Relay
* 12V AA Battery Case
* AA Batteries
* Breadboards
* ESP-32 CAM AI-Thinker
* 9V Power Supply

## Description

This door lock is activated by face detection on the ESP-32 CAM module. The program uses the ESP-32 camera web server example as a base and uses its face-recognition feature to activate a relay that will activate a 12V solenoid door lock, thus unlocking the door. 

The face detection is done through a web server interface hosted on the ESP-32 CAM module, which is accessed through my phone. On the web server, the face recognition option is used to enroll faces that will be able to unlock the door lock. This way only someone who has enrolled their face is able to unlock the door with face recognition. 

Whenever an enrolled face is detected in the program, the 5V relay will be activated, connecting the circuit between the 12V power supply and the 12V solenoid door lock will retract, unlocking the door. After 5 seconds have passed, the relay will deactivate and the door lock will extend out again. 

The ESP-32 microcontroller and the 5V Relay are both powered with 5V from a breadboard power supply module that takes a 9V power supply and turns it into 5V. 

The solenoid lock and main breadboard are mounted on a 3D-printed base taped to the door. 


