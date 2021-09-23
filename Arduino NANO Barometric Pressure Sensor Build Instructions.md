# Arduino NANO Barometric Pressure Sensor Build Instructions

The Arduino NANO is a useful microcontroller for small, power and space efficient applications.  These instructions will walk us through how to build the electronics for a borometric pressure logger to be mounted on a rocket.

**IMPORTANT: READ THIS ASSIGNMENT IN IT’S ENTIRETY BEFORE STARTING.  IF YOU DON’T, YOU RISK SOLDERING PINS YOU MAY HAVE TO UN-SOLDER, WHICH IS A PAIN**

### 1. Solder the headers to the NANO SHIELD exactly as shown. 

![Figure 1.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_1.1.jpg?raw=true)

![Figure 1.2](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_1.2.jpg?raw=true)

___Make Sure the Buffolo is on top.___

![Figure 1.3](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_1.3.jpg?raw=true)

___NOTE: The pins that have traces You want to start on the pins that DON’T HAVE TRACES, use those to practice, then move on to the pins with traces when you are confident you can make a good joint.___

![Figure 1.4](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_1.4.jpg?raw=true)

___Decent solder joint, “Hershey’s kiss”___

![Figure 1.5](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_1.5.jpg?raw=true)

___SUPER SPECIAL NOTE:  BE CAREFUL!!!! One of the header outlines isn’t quite right, make sure you offset by one pin like this: (one of the 10-pin headers)___

![Figure 1.6](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_1.6.jpg?raw=true)

___The rest of the header outlines are correct___

### 2. Solder one 330 Ohm resistor as shown.  Direction of resistor does not matter.

___Use pliers to pull leads through back side tight so resistor sits flatter:___

![Figure 2.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_2.1a.jpg?raw=true)

___Trim leads on back side___

![Figure 2.4](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_2.4.jpg?raw=true)

### 3. Insert and solder the 2- pin power connector exactly as shown, note that we want the pins sticking through the tiny-est amount possible, you may need to use a coin or something to hold the board up.  You’ll see why in the next step, please read forward:

___Note the connector sits in the set of holes closest to the board edge.___

![Figure_3.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_3.1%20(1).jpg?raw=true)

### 4. Carefully bend the 2 pin connector as shown:

![Figure_4.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_4.1%20(1).jpg?raw=true)

___When you go to plug in the battery pack, you need to pay attention to POLARITY.  The “+” side of the battery is marked with the red shrink-wrap.  The “-“ side is marked with black shrink wrap.  You need to make sure the the red is plugged into “VIN2” on the board, and the black is plugged into “GND3” on the board.  If you’d like, to avoid confusion, you could put a mark on the connector with nail polish or some sort of permanent marker.  BUT BE CAREFUL WHEN YOU PLUG YOUR BATTERY PACK IN, EACH TIME!___

![Figure 4.2](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_4.2.jpg?raw=true)

### 5. Install Arduino NANO as shown, note direction of power connector, you may have to carefully bend headers to get it to fit:

![Figure 5.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_5.1.jpg?raw=true)

### 6. Install the SparkFun Openlog as shown, note which side the pins plug into, and that the Openlog needs to snuggle right up to the NANO:

![Figure 6.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_6.1.jpg?raw=true)

### 7. Install the barometric pressure sensor.  Note that the pins insert on the opposite side of the Openlog pins:

![Figure 7.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_7.1.jpg?raw=true)

### 8. Insert the LED.  Note the “+” lead, or the longer one needs to go into the “LED +” header hole marked on the bottom side.  Also note that the LED inserts into holes 4 and 5 looking left-to-right:

![Figure 8.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_8.1.jpg?raw=true)

### 9.	Insert SD card into SparkFun OpenLog.  Make sure gold contacts are facing UP as shown:

![Figure 9.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_9.1.jpg?raw=true)

### 10. Here is the completed NANO package:

![Figure 10.1](https://github.com/WindsorHSRobotics/2021_Rocket_Lab/blob/main/Images/Figure_10.1.jpg?raw=true)

