# Quick Start
## Introduction
The ICBlocks series offers a wide variety of blocks. To help you get started with the ICBlocks products, we have prepared a few simple examples to help you quickly understand the logic behind using ICBlocks.  

## How to use?
### Effect Demonstration:  
![](img2/Introduction01.png)

### Parts Preparation:  
| < img src="img2/Introduction02.png" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction03.png" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction04.png" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction05.png" style="width:auto;height:120px;object-fit:contain;" > |
| :---: | :---: | :---: | :---: |
| Boxy Robot   ×1 | Caster Wheels   ×2 | Axles   ×2 | Wheels   ×2 |


### Assembly Steps  
| Step1: Install the Axles   | |
| :---: | --- |
|< img src="img2/Introduction06.png" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction07.png" style="width:auto;height:120px;object-fit:contain;" > |
| Step2: Install the Wheels   | |
| < img src="img2/Introduction08.png" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction09.png" style="width:auto;height:120px;object-fit:contain;" > |
| Step3: Install the Caster Wheels | |
| < img src="img2/Introduction10.png" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction11.png" style="width:auto;height:120px;object-fit:contain;" > |


## Logic Control - Quick Start  
### Effect Demonstration  
|< img src="img2/Introduction12.gif" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction13.gif" style="width:auto;height:120px;object-fit:contain;" > |
| :---: | :---: |
| Voice-controlled Boxy Robot moves forward.   | Voice-controlled Boxy Robot moves backward.  |


### Parts Preparation  
|< img src="img2/Introduction13.png" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction14.png" style="width:auto;height:120px;object-fit:contain;" > |
| :---: | :---: |
| ICBlocks Boxy Robot   ×1 | Sound Block ×1 |


### Steps:  
#### Power On   
+ Press and hold the power button on the Boxy robot for 2s to turn it on.
+ After powering on, the four status indicators on top of the Boxy Robot will light up, displaying blue and orange colors, corresponding to the blue actuator magnetic interfaces and orange sensor magnetic interfaces, respectively.

![](img2/Introduction15.gif)

#### Connect the Sensor  
Connect the sound block to any orange magnetic interface on the Boxy Robot (orange interfaces are for input; blue interfaces are for output).  

![](img2/Introduction16.gif)



### Effect Demonstration  
The two orange magnetic interfaces are labeled with “+” and “-”. When using the sound block to control the ICBlocks  Boxy Robot:  

+ Connecting to the “+” interface: The Boxy Robot moves **backward** when sound is detected.
+ Connecting to the “-” interface: The Boxy Robot moves **forward** when sound is detected.

|< img src="img2/Introduction17.gif" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction18.gif" style="width:auto;height:120px;object-fit:contain;" > |
| :---: | :---: |
| **“-” Interface** | **Boxy Robot Moves Forward** | **“+” Interface** | **Boxy Robot Moves Backward** |


###  More Logic Control Scenarios  
|< img src="img2/Introduction19.gif" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction20.gif" style="width:auto;height:120px;object-fit:contain;" > |
| :---: | :---: |
| Button Logic Control   | Tilt Logic Control   |
|< img src="img2/Introduction21.gif" style="width:auto;height:120px;object-fit:contain;" > | < img src="img2/Introduction22.gif" style="width:auto;height:120px;object-fit:contain;" > |
| Line-following Robot   | Light-chashing Car   |


## Coding Control - Quick Start  
### Effect Demonstration  
Build a robot by combining LEGO Duplo bricks, use the coding board to control it, light up the LED block, and complete precise movements in a designated map area.  

![](img2/Introduction23.gif)



### Parts Preparation  
|< img src="img2/Introduction24.png" style="width:auto;height:120px;object-fit:contain;" > | <br/><br/>< img src="img2/Introduction25.png" style="width:auto;height:120px;object-fit:contain;" ><br/><br/> | < img src="img2/Introduction26.png" style="width:auto;height:120px;object-fit:contain;" ><br/><br/> |
| :---: | :---: | :---: |
| Boxy Robot ×1 | Coding Board×1 | Color LED Block×1 |
|< img src="img2/Introduction27.png" style="width:auto;height:120px;object-fit:contain;" ><br/> | < img src="img2/Introduction28.png" style="width:auto;height:120px;object-fit:contain;" ><br/> | < img src="img2/Introduction29.png" style="width:auto;height:120px;object-fit:contain;" ><br/> |
| One Step Forward Blocks ×2 | Turn Left 90° Blocks ×1 | Turn Right 90° Block×1 |
|< img src="img2/Introduction30.png" style="width:auto;height:120px;object-fit:contain;" ><br/> | < img src="img2/Introduction31.png" style="width:auto;height:120px;object-fit:contain;" ><br/> | < img src="img2/Introduction32.png" style="width:auto;height:120px;object-fit:contain;" ><br/> |
| Turn On the Light Block×1 |  Round Eye  ×1 |  Single-sided 4-hole Arcs  ×2 |


### Steps:  
#### Power On and Connect Bluetooth  
+ Long press the power buttons on both the Boxy Robot and coding board for 2s to power them on.
+ When the Bluetooth indicator on the coding board stops flashing and remains steady, and the two orange status indicators on the Boxy Robot turn blue, the Bluetooth connection has been successfully established.
+ If the Bluetooth connection fails, refer to the "[Maintenance and Debugging - Bluetooth Unpairing and Pairing](https://icreaterobot-docs.readthedocs.io/en/latest/docs/ICBlocks/06MaintenanceandDebug/04BluetoothUnpairingandPairing.html)" section for troubleshooting.

![](img2/Introduction33.gif)

#### Assemble the Robot  
Connect the color LED block to any magnetic interface on the ICBlocks robot, and use the prepared LEGO bricks to assemble the robot as shown in the diagram below.  

![](img2/Introduction34.gif)

#### Coding
Connect the pre-arranged coding instruction blocks to the coding board in the desired sequence.  

![](img2/Introduction35.gif)

#### Start the Code
Press the “Start” button on the coding board to execute the program in order, from left to right.  

![](img2/Introduction36.gif)





