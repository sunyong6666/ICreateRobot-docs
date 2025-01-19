# Servo Motor
![](img/ServoMotor01.png)

## Introduction  
The servo motor is a versatile module that supports multiple rotation control modes, enabling precise control of rotation angles, speed, and position. It uses I²C digital communication for high-speed, latency-free data interaction with controllers. The motor features an I²C address switch button and a status indicator light, allowing users to easily display the current device address and control status. Its plug-and-play terminal connection simplifies wire replacement, addressing the issue of repair difficulties caused by non-detachable wiring.  



**Key Features:  **

+ Standard I²C communication protocol.  
+ Manual I²C slave address switching with 4 selectable addresses and 1 built-in address, supporting multiple motors effortlessly.  
+ Built-in smart speed adjustment algorithm for fast response, precise speed measurement, and position calculation.  
+ High torque output.  
+ Built-in intelligent protection algorithms to automatically detect and protect against abnormal conditions like stalling or over-torque.  
+  Hardware protection to limit output power during overheating or other anomalies.  
+ It has the communication status indication function to view the communication status of the motor and the hub in real time.
+ Control over speed, position, angle, and runtime.  
+ External terminal connection for quick wire replacement.  
+ Multi-directional reserved axle pin connection design.  

## Structural  
![](img/ServoMotor02.png)



| No.   | Name   | Description   |
| :---: | :---: | --- |
| ① | HY2.0-4P Port | Connects to the hub using HY2.0-4P cables.   |
| ②  | Address Switch Button   | Press and hold for 3s to switch the device I²C address. The motor has 4 selectable addresses (0x51, 0x52, 0x53, 0x54) and one built-in address (0x50). Tap to reset the rotation angle and position to 0.   |
| ③  |  Status Indicator Light   | Indicates the I²C device address: red (0x51), green (0x52), blue (0x53), yellow (0x54). When the light matches the corresponding color, it reflects the current address. Flashing indicates communication with the controller, while steady light signals no communication or a connection error.   |
| ④  |  Axle Pin Connection   |  Compatible with building blocks.   |




## Specifications  
| Item | <font style="color:rgb(0,0,0);">Description</font> |
| :---: | --- |
| <font style="color:rgb(0,0,0);"> Name  </font> | <font style="color:rgb(0,0,0);"> Servo Motor  </font> |
| <font style="color:rgb(0,0,0);">Code</font> | <font style="color:rgb(0,0,0);">B0100028</font> |
| <font style="color:rgb(0,0,0);"> Weight  </font> |  Approx. 47 g   |
| <font style="color:rgb(0,0,0);"> Dimensions  </font> | <font style="color:rgb(0,0,0);"> 72 × 24 × 32 mm  </font> |
|  Rated Voltage   | <font style="color:rgb(0,0,0);">5V－DC</font> |
|  Communication   | <font style="color:rgb(0,0,0);">I²C </font> |
| <font style="color:rgb(0,0,0);">  I²C Address  </font> | <font style="color:rgb(0,0,0);">4 switchable addresses (0x51, 0x52, 0x53, 0x54) and 1 built-in address (0x50)  </font> |
| <font style="color:rgb(0,0,0);"> No-load Current  </font> | <font style="color:rgb(0,0,0);"> 210 mA  </font> |
| <font style="color:rgb(0,0,0);">     Stall Current  </font> | <font style="color:rgb(0,0,0);"> 2 A  </font> |
| <font style="color:rgb(0,0,0);"> Stall Protection Activation Time   </font> | <font style="color:rgb(0,0,0);">2s</font> |
| <font style="color:rgb(0,0,0);"> Stall Protection Activation Time  </font> | <font style="color:rgb(0,0,0);">±5°</font> |
| <font style="color:rgb(0,0,0);"> Stall Torque  </font> | <font style="color:rgb(0,0,0);"> 0.2 N·m  </font> |
|  Rated Speed   | <font style="color:rgb(0,0,0);"> 178 RPM  </font> |
| <font style="color:rgb(0,0,0);">Port</font> | <font style="color:rgb(0,0,0);">HY2.0-4P  Port</font> |


## Usage Instructions 
| Type |  Description   |
| :---: | --- |
|  Application Modes   | Direct Control Mode, Logical Control Mode, Programming Control Mode.   |
|  Connection   | Connect to the hub using a "Servo Motor Adapter Cable." The motor emits a beep upon successful connection.   |
|  Direct Control Mode   | <font style="color:rgb(44, 44, 54);">Use the hub's function buttons to change the servo motor's state, including rotation direction and speed.  </font> |
|  Logical Control Mode   | <font style="color:rgb(44, 44, 54);">Control the servo motor's state, including rotation direction and speed, based on input module detection results.  </font> |
|  Programming Control Mode   | <font style="color:rgb(44, 44, 54);">Use programming commands to control the servo motor's state, including rotation direction, speed, angle, and runtime.  </font> |
|  Angle Feedback   | <font style="color:rgb(44, 44, 54);">Obtain the servo motor's rotation angle via programming control, then use it as an input parameter to control other actuators or roles.  </font> |


##Firmware Update 
 **<font style="color:rgb(44, 44, 54);">To update the firmware, please click the link below for detailed instructions.👉  </font>**
  [**[Motor Firmware Update Guide]**](https://www.yuque.com/crystal-vzc6k/cfl3ix/zahe4931hy64b1be)

