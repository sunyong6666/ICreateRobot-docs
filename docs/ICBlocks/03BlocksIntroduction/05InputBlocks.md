# Input Blocks
## Photoelectric Block
![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732949273391-ca54237e-718a-4cd8-947e-fa8998992276.png)    

### **<font style="color:rgb(38, 38, 38);">Introduction</font>**
The Photoelectric Block is primarily used to detect light intensity and changes. It operates on the principle of the photoelectric effect by measuring the intensity of light received by the sensor to respond to variations in light.

### **Structure**
| ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732960713497-944a1e13-0f55-4e0f-aa23-758a4a27bbb6.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732966553619-4b008660-94c5-462c-91ca-9032e38d471c.png) |
| --- | --- |


| No. |  Name   |  Description   | |
| :---: | :---: | --- | --- |
| **①** | Power Indicator | Indicates whether the block is successfully connected to the Boxy Robot. | |
| **②** | Photoelectric Sensor | Emits and receives light signals to detect objects or changes. | |
| **③** | Magnetic Suction Base | Used for connecting the block to the Boxy Robot, providing stable power and data transmission.  | |


### Specifications
| **Item** | **Description** |
| :---: | :---: |
| **Name  ** | ICBlocks-Photoelectric Block |
| **Code ** | B0010007 |
| **Dimensions ** | 32 x32 x 21.0 mm |
| **Weight** | 12 g |
| **Material ** | ABS |
| ** Valid IDs  ** | 0~54 |
| **Operating Voltage ** | 3.3 V |
| **Connection Method ** | Magnetic |
| **Effective Range** | 1～120mm |


### **Usage Instructions**
| Type | Description |  Example   |
| --- | --- | --- |
| **Logic Control by Boxy Robot **<br/>**** | Single Photoelectric block: Connect the block to the Boxy Robot's orange input terminal to control the built-in motor movement. | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733573119387-fab009d2-759f-467b-9059-024eea28bbd3.gif) |
| | Dual Photoelectric blocks: Connect one block each to the "+" and "-" terminals of the Boxy Robot's orange input. The Boxy Robot enters line-following mode, and all port indicators turn blue. When the photoelectric block detects white, the indicator turns orange, controlling the motor to complete the line-following task. | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733573251897-c11c78fe-c863-4062-8229-21d067fd78cf.gif) |
| **Actuator Logic Control** | Connect the photoelectric block to the Boxy Robot's orange input terminal to control the blue output terminal actuator block. Ensure the "+" and "-" terminals correspond.   Example: Connect the photoelectric block to the orange "+" input terminal to control the blue "+" output terminal motor rotation.   | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733489270988-455d1059-a858-43f3-81f2-8410810d1074.gif) |
| **Block Interactive Coding** | The block can be used with "Until" blocks as a waiting module. When a white object is detected, the Boxy Robot stops executing the "Until" command and waits for a new trigger signal.  | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733620705798-9d1a21c9-57e5-4dbd-a12e-914b3b565dcf.gif) |




#### **Sensitivity Adjustment**
| ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1733382226767-26e26744-a27c-40cc-8b0c-09158882d4ea.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1733382629873-d62d576d-2731-4ff3-ba13-dfc22698c380.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1733382309119-32450a04-83db-4977-812d-c0c0d59207a4.png) |
| --- | --- | --- |
| 1. Connect the photoelectric block to the Boxy Robot using a magnetic extension wire. | 2. Adjust the potentiometer screw at the bottom of the block using a screwdriver, turning clockwise slowly as shown. The indicator turns off when the block detects a black line or obstacle and lights up when no black line is detected. | 3. Block the block's transmitter and receiver with your hand or an object. If the built-in motor stops automatically within 1-2 seconds, the adjustment is complete.   |


_Note:_ Use a screwdriver with an SL2.0 specification. Rotate slowly and avoid large angle adjustments.

## **Light Block**
![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732949250784-48b44951-d193-445b-bd6e-34ddda8ec06c.png)

### **<font style="color:rgb(38, 38, 38);">Introduction</font>**
The Light Block detects changes in ambient light intensity based on the photoelectric effect. It typically he uses photosensitive components (e.g., photoresistors) to sense light intensity and convert the changes into electrical signals for the control system.

### Structure
| ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732963465197-991a0f00-9718-4937-89ec-6a5c4c11f080.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732966624368-e69cf17e-e694-491d-b6f7-14c268c4886c.png) |
| --- | --- |


| No. |  Name   |  Description   | |
| :---: | :---: | --- | --- |
| **①** | Power Indicator | Indicates whether the block is successfully connected to the Boxy Robot. | |
| **②** | Light Sensor | Detects ambient light intensity. | |
| **③** | Magnetic Suction Base | Used for connecting the block to the Boxy Robot, providing stable power and data transmission.  | |


### Specifications
| **Item** | **Description** |
| :---: | :---: |
| **Name  ** | ICBlocks-Light Block |
| **Code  ** | B0010006 |
| **Dimensions  ** | 31.6 x 31.6 x 21.0 mm |
| **Weight** | 13 g |
| **Material** | ABS |
| ** Valid IDs  ** | 55~154 |
| **Operating Voltage  ** | 3.3 V |
| **Connection Method** | Magnetic   |


### Usage Instructions 
| Type | Description   |  Example  |
| --- | --- | --- |
| **Logic Control by Boxy Robot**<br/>**** | Single Light Block: Connect the light block to the Boxy Robot's orange input terminal to control the built-in motor movement. | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733573265158-a2775b87-93bc-495f-8819-ecea47f40cec.gif) |
| | Dual Light Sensors: Connect one light block each to the "+" and "-" terminals of the Boxy Robot's orange input. The controller enters light-tracking mode, and all port indicators turn blue. When the light sensor detects darkness, the indicator turns orange, controlling the motor to complete the light-tracking task.  | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733573262982-7fbab662-e57d-4249-a630-066e2921d368.gif) |
| **Actuator Logic Control**<br/>**** | Connect the light block to the Boxy Robot's orange input terminal to control the blue output terminal actuator module. Ensure the "+" and "-" terminals correspond. <br/>Example: Connect the light module to the orange "+" input terminal to control the blue "+" output terminal motor rotation.  | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733489650318-f261f420-7a73-4baa-b32b-aff2c25579af.gif) |
| **Sensor Interactive Coding** | The block can be used with "Until" blocks as a waiting module. When darkness is detected, the Boxy Robot stops executing the "Until" command and waits for a new trigger signal. | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733489634087-70230441-f3af-442d-b566-1767eab81316.gif) |


#### **Sensitivity Adjustment**
When using the light detection block, if the light block cannot detect the light change or the sensitivity does not meet the requirements, the sensitivity of the block needs to be adjusted according to the following steps.

| ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1733382927977-8b3c5266-93fd-4563-be4d-7a8dd6a78d7b.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1733382629873-d62d576d-2731-4ff3-ba13-dfc22698c380.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1733382939899-10b995be-c24f-4379-aaf1-15f83e18285b.png) |
| --- | --- | --- |
| 1、 Use two magnetic extension wires to connect the light block to the Boxy Robot in light-tracking mode. | 2、Adjust the screw at the indicated position using a screwdriver. | 3、Observe the Boxy Robot's top indicators. When light shines on the block, the indicator changes from blue to orange, indicating successful calibration. |


_Note:_ Use a screwdriver with an SL2.0 specification. Rotate slowly and avoid large angle adjustments.



## Sound Block  
![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732949310668-5072be4d-39ab-456f-b005-1194fa43fc02.png)

###  Introduction:  
The Sound Block collects environmental sounds through a microphone, converts them into electrical signals, and outputs a digital signal after processing, responding to specific sound variations.  

###  Structure:  
| ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732963846832-c6c981e2-df98-4cfc-a70b-48371617f6de.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732966630171-e26f2abd-2e90-4dd0-9b8e-1946ee2c3c41.png) |
| :---: | :---: |


|  Name   |  Name   | **Description** | |
| :---: | :---: | :---: | --- |
| **①** | Power Indicator |   Indicates if the block is successfully connected to the Boxy Robot.  | |
| **②** |  Sound Sensor   |   Picks up ambient sounds and provides sound signal input.   | |
| **③** | Magnetic Suction Base | Used for connecting the block to the Boxy Robot, providing stable power and data transmission   | |


### Specifications
| Item | **Description** |
| :---: | :---: |
| **Name ** | ICBlocks-Sound Block |
| ** Code  ** | B0010004 |
| **Dimensions** | 31.6 x 31.6 x 21.0 mm |
| **Weight** | 13 g |
| **Material ** | ABS |
| ** Valid IDs  ** | 155~244 |
| **Operating Voltage ** | 3.3 V |
| **Connection Method ** |  Magnetic |


### Usage Instructions 
| Type | Description | Example |
| :---: | --- | --- |
| **Logic Control by Boxy Robot ** | Connect the sound block to the orange input port of the Boxy Robot to control motor motion.     | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733573299395-93196fc6-bb87-4dd4-821e-8680d56a70db.gif) |
| **Actuator Logic Control** | Connect the sound block to the orange input port and actuators to the blue output port. Ensure matching "+" and "-" terminals.  <br/> Example: Sound Block "+" connects to the orange input "+" to control the motor via blue output "+" terminal.   | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733489777485-c7ca6457-0dec-4f1c-b409-44b5c3729b1c.gif) |
| **Block Interactive Coding** | Use with "Until" blocks as a wait module. When sound is detected, the Boxy Robot stops the "Until" command and waits for a new trigger signal.   | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733533719488-e854001a-15f9-448e-83d4-8f3afbe6c573.gif) |


### Sensitivity Adjustment  
| ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1733383865273-a45fc1cd-7a3f-4fb8-842d-6f1690858070.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1733382629873-d62d576d-2731-4ff3-ba13-dfc22698c380.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1733383898206-4046770b-e5a1-435b-95af-9b999ddd7408.png) |
| --- | --- | --- |
| 1. First, connect the Boxy Robot to the sound block with the magnetic extension wire. | 2. a Use a screwdriver to turn the potentiometer screw at the bottom clockwise until the indicator light turns off.   | 3. Test by producing sounds near the detection hole. If the sensitivity is unsatisfactory, repeat steps 2 and 3 until achieving the desired sensitivity.   |


Note: Recommended screwdriver size is SL2.0. Adjust slowly without large rotations.  

## Button Block  
![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732949331893-18c3037c-52c5-4a81-9522-08fa103083e6.png)

### Introduction
The Button Block changes the circuit state by pressing the switch, sending a signal to the controller to trigger preset actions or responses.  

### Structure  
| ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732964247190-829bb441-ae6e-41a5-b774-7e14e938744a.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732966634371-b6c2c003-dd9f-49a9-92e5-b91e6b5b8610.png) |
| --- | --- |


| No. |  Name   |  Description    | |
| :---: | :---: | :---: | --- |
| **①** | Power Indicator | Indicates whether the block is successfully connected to the Boxy Robot or the coding board. | |
| **②** |  Button Sensor   |  Detects button press as an input signal for the Boxy Robot or actuators.    | |
| **③** | Magnetic Suction Base | Used for connecting the block to the Boxy Robot or coding board, providing stable power and data transmission.  | |


### Specifications
| **Item** | **Description** |
| :---: | :---: |
| **Name** | ICBlocks-Button Block |
| **Code ** | B0010003 |
| **Dimensions ** | 31.6 x 31.6 x 22.9 mm |
| **Weight** | 13 g |
| **Material ** | ABS |
| **  Valid IDs  ** | 245~334 |
| **Operating Voltage ** | 3.3 V |
| **Connection Method ** | Magnetic |


### **Usage Instructions**
| Type | Description |  Example   |
| :---: | --- | --- |
| **Logic Control by Boxy Robot** | Connect the button block to the orange input port of the Boxy Robot to control motor motion.   | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733573313964-55229026-7dcd-4778-b42c-dd8edc146588.gif) |
| **Actuator Logic Control** | Connect the button block to the orange input port and actuators to the blue output port. Ensure matching "+" and "-" terminals.  <br/>Example: Button Block "+" connects to orange input "+", controlling motor rotation via blue output "+".   | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733533778168-88fe32b1-24d4-4a27-a782-9194e6fa7c4a.gif) |
| **Block Interactive Coding** | Use with "Until" blocks as a wait module. When the button is pressed, the Boxy Robot stops the "Until" command and waits for a new trigger signal.   | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733533995049-16e31942-3c5d-44a6-a64d-b24869adefcb.gif) |


## Potentiometer Block  
![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732870125285-ef58a467-4a39-4f6e-816f-a03f462ce814.png)

###  Introduction  
The Potentiometer Block detects rotation angles and directions (clockwise/counterclockwise) using a rotary encoder, converting analog signals into digital signals for Boxy Robot adjustment or operation.  

### Structure  
| ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732964395729-a14816a8-f134-4d81-a777-667c6852cbcb.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732966637615-d7c6f696-168c-4f78-b7b3-fecf72a448e4.png) |
| :---: | :---: |


| No. |  Name   |  Description   | |
| :---: | :---: | :---: | --- |
| **①** | Power Indicator |  Indicates whether the block is successfully connected to the Boxy Robot or the coding board. | |
| **②** |  Rotary Potentiometer   |   Detects rotation angle and direction.   | |
| **③** | Magnetic Suction Base | Used for connecting the block to the Boxy Robot, providing stable power and data transmission.  | |


### Specifications
| **Item** | **Description** |
| :---: | :---: |
| **Name  ** | ICBlocks-Potentiometer Block |
| **Code ** | B0010008 |
| **Dimensions ** | 31.6 x 31.6 x 35.3 mm |
| **Weight** | 117 g |
| **Material ** | ABS |
| ** Valid IDs  ** | 460~560 |
| **Operating Voltage ** | 3.3 V |
| **Connection Method** | Magnetic |


### **Usage Instructions**
| Type | Description | Example |
| :---: | --- | --- |
| **Logic Control by Boxy Robot ** | Connect the potentiometer to the orange input port to detect rotation direction: clockwise for forward and counterclockwise for backward motion.   | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733573338934-685e113b-8578-4688-a1b4-8414a94b1340.gif) |
| **Actuator Logic Control** | Connect the potentiometer to the orange input and actuators to the blue output port. Ensure matching "+" and "-" terminals.  <br/>Motor: Connect the potentiometer to the orange input "+" to control the blue output "+".   Clockwise rotation: Controls the motor to reverse; the larger the rotation angle, the faster the motor speed.   Counterclockwise rotation: Controls the motor to rotate forward; the larger the rotation angle, the faster the motor speed.      | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733534652137-7a59df6b-4d41-44a9-90a3-1e99bf4c2738.gif) |
| **Block Interactive Coding**<br/>**** | Used in conjunction with the "until" type block as a waiting module, when the potentiometer block is detected to rotate to the right, the Boxy Robot stops the execution of the "until" command and waits for a new trigger signal.<br/>  | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733534729295-6235eec2-2366-49b0-9d12-82171f897bc9.gif) |
| | Used in conjunction with the motion block and the stop block, the potentiometer block senses the rotation direction and controls the robot motion:<br/>1. When rotating clockwise, the robot advances;<br/>2. When rotating counterclockwise, the robot moves backward. | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733574497369-813c338f-ba51-4d01-821c-d4b013330278.gif) |


## Gyro Block  
### ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732870176036-f06d8281-03bb-428f-8193-8b10b053c080.png)
### **<font style="color:rgb(38, 38, 38);">Introduction</font>**
The Gyro Block can detect tilt angles in four directions: forward, backward, left, and right, with each direction ranging from 0° to 180°. By sensing changes in tilt angles through a built-in three-axis gyroscope sensor, it can control the robot's movements. This block measures and detects rotation angles and angular velocity in three-dimensional space, commonly used for tracking rotation, tilt, or directional changes. It converts angular velocity into digital signals for theBoxy Robot to manage direction and angle control.  

### Structure
| ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732965637895-8eecdcd6-32b7-4d6c-916a-6c5a2d66a433.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/51022723/1732966666390-069fdf04-f822-45e4-b566-5fad6f627bdc.png) |
| :---: | :---: |


| No. | Name   |  Description   | |
| :---: | :---: | :---: | --- |
| **①** | Power Indicator | Indicates whether the block is successfully connected to the Boxy Robot or the coding board.  | |
| **②** |  Backward |  Indicates if the module detects a backward tilt   | |
| **③** |  Left |  Indicates if the module detects a leftward tilt   | |
| **④** |  Right |  Indicates if the module detects a rightward tilt   | |
| **⑤** |  Forward   |   Indicates if the module detects a forward tilt   | |
| **⑥** | Magnetic Suction Base |  Used for connecting the block to the Boxy Robot or coding board, providing stable power and data transmission.  | |


### Specifications
| **Item** | **Description** |
| :---: | :---: |
| **Name  ** | ICBlocks-Gyro Block |
| **Code  ** | B0010005 |
| **Dimensions  ** | 31.6 x 31.6 x 21.0mm |
| **Weight** | 12 g |
| **Material** | ABS |
| ** Valid IDs  ** | 335~424 |
| **Operating Voltage  ** | 3.3V |
| **Connection Method** | Magnetic   |


### Usage Instructions 
| Type | Description |  Example  |
| :---: | --- | --- |
| **Logic Control by Boxy Robot** | Connect the Gyro Block to the orange input port of the Boxy Robot using a magnetic extension wire. Place the block horizontally. When tilted, the robot will perform corresponding actions.   | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733573395367-777c8371-ad64-4699-a7d6-77c3bb9a65d2.gif) |
| **Actuator Logic Control** | Connect the Gyro Block to the orange input port and use it to control the actuator block connected to the blue output port. Ensure the "+" and "-" terminals align.     **Example:** Motor Module: Connect the Gyro Block to the orange input "+" and control the blue output "+". Forward/Left Tilt: Motor rotates forward; Backward/Right Tilt: Motor reverses.   | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733535001142-2a923a5d-e713-4515-af7d-7929d95b8e5e.gif) |
| **Sensor Interactive Coding** | Used with motion modules, the Gyro Block detects tilt direction (forward, backward, left, right) and controls the robot to move accordingly.     | ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1733535042914-f826a4ec-32a9-4205-98c0-26f9a9b97a02.gif) |




## 
