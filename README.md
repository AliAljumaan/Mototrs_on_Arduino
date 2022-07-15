# Mototrs_on_Arduino
## Brushless Motor
A brushless DC motor (also known as a BLDC motor or BL motor) is an electronically commuted DC motor which does not have brushes. The controller provides pulses of current to the motor windings which control the speed and torque of the synchronous motor.These types of motors are highly efficient in producing a large amount of torque over a vast speed range. In brushless motors, permanent magnets rotate around a fixed armature and overcome the problem of connecting current to the armature. Commutation with electronics has a large scope of capabilities and flexibility. They are known for smooth operation and holding torque when stationary.
## Electronic Speed ControlConnect the battery to the ESC to power up the ESC.
Power the Arduino.
To make a full cycle, the rotor needs to be activated at the correct MOSFETS at each of the six intervals. That's what an ESC does. Electronic speed controls (ESCs) control and regulate an electric motor's speed electronically. Additionally, iConnect the battery to the ESC to power up the ESC.
Power the Arduino.t can reverse the motor and provide dynamic braking. Miniature electronic speed controls are used in electrically powered radio-controlled models.
## List of Components
Arduino UNO
* BLDC outrunner motor (Any other outrunner motor will work fine)
* Electronic Speed Controller (Choose according to the current rating of the motor)
* LiPo Battery (to power the motor)
* Male-Male Jumper cable * 3
* USB 2.0 cable type A/B (To upload the program and power the Arduino).
## Connections
Connect the motor to the output of ESC. Here, the polarity doesn't matter. If you switch any 2 of the 3 wires, the motor will rotate in opposite direction. Connect the '+' & '-' of battery to the Red (+) and Black (-) wires of ESC respectively. From the 3pin servo cable coming out of the ESC, connect the Brown cable to the 'GND' pin on Arduino. Connect the Yellow cable to any digital pin. In our case its digital pin 12. Programming Arduino UNO Connect the Arduino to the PC. Open Arduino IDE and write this code. Under 'Tools' select Board: Arduino/Genuino UNO Port: COM15 (Select appropriate COM port. To find out the COM port open device manager and look for Arduino UNO under 'Ports'). Click Upload button on the upper left corner.
## Run The Motors
* Connect the battery to the ESC to power up the ESC.
* Power the Arduino.
![This is an image](https://user-images.githubusercontent.com/109004035/178165599-2f852d0d-7888-4647-ae89-bb3f815e9574.jpeg)

