The coupling consists of two parts: **electrical** and **mechanical**. 

### Electrical Part
PCB designed in KiCad 6.0 software represents electrical part. The gripper uses power of 24V (+ -) and serial RS485 communication (485+, 485- and 485 GND). The Gripper interfaces with its coupling via a 10-spring pin (pogo) connector located on its outer surface. The power pins are traced to their respective connector, as are the RS-485 communication pins, according to this configuration. 

<img src="https://github.com/stleraburg/Robotiq-Gripper-Coupling-for-Franka-Emika/blob/main/pinoutView.png" width="800"> 

The PCB layout is depicted below. 

<img src="https://github.com/stleraburg/Robotiq-Gripper-Coupling-for-Franka-Emika/blob/main/PCB.jpg" width="600"> 

I used U2D2 ROBOTIS RS485-USB communication converter to connect the gripper to the PC/robot controller. 

### Mechanical Part
There are three mechanical parts designed in Fusion360. The first one is attached to Franka, next a PCB holder goes, and finally the part to attach the Robotiq gripper. PCB is located between the PCB holder and the gripper part. All parts are screwed with M6 bolts. 

<img src="https://github.com/stleraburg/Robotiq-Gripper-Coupling-for-Franka-Emika/blob/main/fullView.jpeg" width="800"> 
