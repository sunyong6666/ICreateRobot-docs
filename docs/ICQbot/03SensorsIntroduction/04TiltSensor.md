# Tilt Sensor

## Introduction  

![](img/TiltSensor01.png)



The tilt sensor has a high-precision 3-axis gyroscope and 3-axis accelerometer chip. By calculating the raw data from the gyroscope and accelerometer, it can measure tilt angles in four directions: front, back, left, and right. The built-in MCU chip sends the angle information to the main controller for further logical processing. The sensor detects tilt angles from -90° to 90° and has detection capabilities for two axes (X-axis, Y-axis).  

## Structure  
## ![](img/TiltSensor02.png)
|  No.   | Name |  Description   |
| :---: | :---: | :---: |
| ① |  Right Tilt   | Senses the right tilt angle (0-90°) to provide rotation information, helping determine the clockwise rotation speed of the motor.   |
| ② |  Left Tilt   |  Senses the left tilt angle (0-90°) to provide rotation information, helping determine the counterclockwise rotation speed of the motor.   |
| ③ |  Forward Tilt   |  Senses the forward tilt angle (90°) to provide rotation information, helping determine the counterclockwise rotation of the motor.   |
| ④ |  Backward Tilt   | Senses the backward tilt angle (90°) to provide rotation information, helping determine the counterclockwise rotation of the motor.   |
| ⑤ |  Crystal Connector   |  Designed with an anti-reverse insertion feature, used to connect various components (e.g., sensors, motors, and controllers).   |


## Specifications  
| Item | Description   |
| :---: | :---: |
| Name |  Tilt Sensor   |
| Code | <font style="color:rgb(0, 0, 0);">B0130003</font> |
| Dimensions   | 31×16×11 mm |
| Weight   | 9 g |
| Material   | ABS |
| Communication   | UART |
| Angle   | X-axis: -90° - 90°; Y-axis: -90° - 90° |
|  Compatibility   |  LEGO   |


## Usage Instructions  
|  Mode   |  Description   |
| :---: | --- |
|  Logic Control Mode   | Sensor tilting left or right controls motor rotation. The greater the tilt angle, the faster the motor speed.   |
| Programming Control   | Detects front/back/left/right tilt motion to control motor or character movement. <br/>Detects horizontal and vibration states to control motor or character movement.   |


For detailed instructions, please refer to the function description. [Click on it to learn more.](https://icreaterobot-icqbot-docs.readthedocs.io/en/latest/docs/ICQbot/04Featureoverview/02LogicControlMode.html)

