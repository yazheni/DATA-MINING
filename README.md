# Autonomous Car using Machine Learning and Deep Learning

Objectives:

Understanding Data Mining Techniques and Deep Learning
Become familiar with Python, Keras, Tensorflow and OpenCV
Gain experience with research on autonomous vehicle and data mining

# Phase 1: Assembly an Autonomous Vehicle
we are using "SunFounder PiCar-V Kit V2.0 for Raspberry Pi" . We have assembled the the plate withbatter holder,rear motors, wheels , PCB(motor driver, pwm driver, robot hats and raspberry pi), servo for camera, pan & tilt. We have configured VNC viewer to communicate with raspberry pi ans setup cloud account.The assembly pictures are in IMAGES folders

  Steps to improve dmcar:

* The camera clarity could have been more.
* The the circuit to attach and robot HATS could be a bit lengthier in order to avoid accidentlt breaking the circuit.
* The exposed drivers and circuits could have a covering, as the cuicuits and battery wire sometimes interfere with the tire when car moves.

# Phase 2: Setting up and ideas to improve the connectivity of picar
We are using the  android mobile hotspot to connect to the raspberry pi and at times the iphone's hotspot doesnt work. The home wifi or the university wifi are having connectivity issues while trying to use the wpa_supplicant.conf file. The best way to avoid this is by always have a static IP on your network. We added this to the wpa_supplicant, 
* address 67.84.48.63 # Static IP  
* netmask 255.255.0.0
* gateway 192.168.1.1   # IP of our router. Now ideally the raspberry pi will connect to the wifi. 



