# Logic Control Function
## Introduction  
When the Boxy Robot is powered on and no Bluetooth connection is established, it defaults to Logic Control Mode. In this mode, you can activate the robot's logic control functions by connecting sensors to the orange magnetic ports or actuators to the blue magnetic ports. Different combinations of sensors and actuators will trigger different logic control functions. For better understanding, the following explains the four categories of logic control functions.  

## Boxy Robot Logic Control
**Definition**: The Boxy Robot uses sensors connected to the orange magnetic ports to control its built-in motor. This functionality is referred to as the logic control function of the robot.  

| ![](img/LogicControlFunction01.gif) | ![](img/LogicControlFunction02.gif) |
| :---: | :---: |
| Button Logic Control   |  Sound Logic Control   |
| ![](img/LogicControlFunction03.gif) | ![](img/LogicControlFunction04.gif) |
|  Photoelectric Logic Control   | Light-sensitive Logic Control   |
| ![](img/LogicControlFunction05.gif) | ![](img/LogicControlFunction06.gif) |
| Potentiometer Logic Control | Gyro Logic Control |


**Note**: If the sensor is not recognized during use, adjust its sensitivity following the [sensor sensitivity adjustment instructions](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/azbgmyb3i1gp4061/collaborator/join?token=esQ79qKqI4e8WdV6&source=doc_collaborator#%20《Input%20Blocks》).  

## Actuator Logic Control Function  
**Definition**: The Boxy Robot uses sensors connected to the orange magnetic ports to control actuators connected to the blue magnetic ports. This functionality is referred to as the **Actuator Logic Control Function**.  

### Button-Controlled Actuator Functions  
| ![](img/LogicControlFunction07.gif) | ![](img/LogicControlFunction08.gif)  |
| :---: | :---: |
| Button-controlled LED Block   | Button-controlled Record Block |
| ![](img/LogicControlFunction09.gif) | ![](img/LogicControlFunction10.gif) |
| Button-controlled Motor | Button-controlled Expression Block  |


### Sound-Controlled Actuator Functions  
| ![](img/LogicControlFunction11.gif) | ![](img/LogicControlFunction12.gif) |
| :---: | :---: |
| Sound-controlled LED Block | Sound-controlled Record Block |
| ![](img/LogicControlFunction13.gif) | ![](img/LogicControlFunction14.gif) |
| Sound-controlled Motor | Sound-controlled Expression Block  |


### Light Block Controlled Actuator Functions  
| ![](img/LogicControlFunction15.gif) | ![](img/LogicControlFunction17.gif)  |
| :---: | :---: |
|  Light-sensitive controlled LED Block   | Light-sensitive controlled Record Block  |
| ![](img/LogicControlFunction18.gif) | ![](LogicControlFunction19.gif)  |
|  Light-sensitive controlled Motor   | Light-sensitive controlled Expression Block   |


### Photoelectric-Controlled Actuator Functions  
| ![](img/LogicControlFunction20.gif) | ![](img/LogicControlFunction21.gif) |
| :---: | :---: |
| Photoelectric-controlled LED Block  | Photoelectric-controlled Record Block |
| ![](img/LogicControlFunction22.gif) | ![](img/LogicControlFunction23.gif) |
| Photoelectric-controlled Motor | Photoelectric-controlled Expression Block |


### Potentiometer-Controlled Actuator Functions  
| ![](LogicControlFunction24.gif) | ![](img/LogicControlFunction25.gif) |
| :---: | :---: |
| Potentiometer-controlled LED Block | Potentiometer-controlled Record Block |
| ![](img/LogicControlFunction26.gif) | ![](img/LogicControlFunction27.gif) |
| Potentiometer-controlled Motor | Potentiometer-controlled Expression Block |


### Gyro -Controlled Actuator Functions  
| ![](img/LogicControlFunction28.gif) | ![](img/LogicControlFunction29.gif) |
| :---: | :---: |
| Gyro -Controlled LED Block | Gyro -Controlled Record Block |
| ![](img/LogicControlFunction30.gif) | ![](img/LogicControlFunction31.gif) |
| Gyro -Controlled Motor | Gyro -Controlled Expression Block |


## Comprehensive Logic Control Function  
**Definition**: The Boxy Robot has two logic control interfaces. One uses sensors connected to the orange magnetic ports to control the built-in motor, while the other uses sensors connected to the orange magnetic ports to control actuators on the blue magnetic ports. This is referred to as the **Comprehensive Logic Control Function**.  

### Control Logic Description  
**Example**: 

The Boxy Robot's two logic control interfaces are marked with “+” and “-” symbols.

+ The “+” interface controls the built-in motor through sensors connected to the orange magnetic ports.
+ The “-” interface controls actuators connected to the blue magnetic ports via sensors connected to the orange magnetic ports.
+ Sensors on the “+” interface control the built-in motor.
+ Sensors on the “-” interface control actuators on the blue magnetic ports.

![](img/LogicControlFunction32.gif)

## Special Logic Control Combinations  
To offer more interactive options with the ICBlocks series, two special logic control combinations are available: **Line-following Mode** and **Light-tracking Mode**.  

### Line-following Function  
**Usage**:

+ Connect two photoelectric sensors to the two orange magnetic ports.
+ Leave the blue magnetic ports empty.
+ The Boxy Robot will enter the **Line-following Mode**.

![](img/LogicControlFunction33.gif)

 Line-following Robot  

### Light-tracking Function  
**Usage**:

+ Connect two light-sensitive sensors to the two orange magnetic ports.
+ Leave the blue magnetic ports empty.
+ The Boxy Robot will enter the **Light-tracking Mode**.

![](img/LogicControlFunction34.gif)

 Light-tracking Robot  

