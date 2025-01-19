# Rocker Module
## Introduction  
<font style="color:rgba(0, 0, 0, 0.85);">The rocker module is a commonly used electronic input device, primarily designed for directional and amplitude control. It consists of a movable rocker and an internal potentiometer. When the rocker is tilted, its position changes the resistance value of the potentiometer.  </font>

## Specifications  
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name | <font style="color:rgba(0, 0, 0, 0.85);">Rocker Module</font> |
| Code | B0020029 |
| <font style="color:rgb(0,0,0);"> Dimensions  </font> | <font style="color:rgb(0,0,0);">51×24×34 mm</font> |
| <font style="color:rgb(0,0,0);"> Voltage  </font> | <font style="color:rgb(0,0,0);">5V－DC</font> |
|  Control Signal   | I²C |
|  X / Y Axis Detection Range   | -100~100 |
| <font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgb(0,0,0);">Grove</font> |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| ![](https://cdn.nlark.com/yuque/0/2024/png/51021612/1732954292068-31d6ecbb-9d9c-49a1-adb4-b86ea17cc125.png) | | |
| :---: | --- | --- |
| ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732851056039-50b7e766-b325-48ba-be7f-f9b158feae06.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732779929854-8b7ea493-4c94-41e3-ba62-00fcafc0de35.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732851070638-4002f462-9ab2-4af0-b680-062481a2602a.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| Rocker Module Connection Diagram | | |


<font style="color:rgba(0, 0, 0, 0.85);">The rocker module can be connected to the </font>**I²C interface**<font style="color:rgba(0, 0, 0, 0.85);"> of the </font>**micro: bit hub**<font style="color:rgba(0, 0, 0, 0.85);">. In the coding environment, the position of the rocker can be read and utilized.  </font>

![](https://cdn.nlark.com/yuque/0/2024/gif/46964359/1732934332249-347d3445-5f73-47cf-890e-596a494d4fed.gif)

If the rocker module exhibits accuracy deviations, calibration can be performed using tweezers: Short-circuit the calibration pads with tweezers. The indicator light will start flashing, indicating calibration mode. Perform a full **360° rotation** of the rocker. After completing the rotation, remove the tweezers. When the indicator light turns solid, calibration is successful.

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
![](https://cdn.nlark.com/yuque/0/2024/webp/46964359/1732881275074-2f09bf22-6e86-4015-8602-fe81a7ed25ce.webp)

Using the **MakeCode** coding software, the Microbit extension allows:

<font style="color:rgb(13, 13, 13);">Reading directional signals from the rocker module through the </font>**I²C port**<font style="color:rgb(13, 13, 13);"> and displaying them on the </font>**micro: bit LED matrix**<font style="color:rgb(13, 13, 13);">.</font>

![](https://cdn.nlark.com/yuque/0/2024/webp/46964359/1732881554516-16f2d719-3d5a-4204-ab7e-f328d0991be6.webp)

<font style="color:rgb(0,0,0);">Reading positional values from the rocker module through the </font>**I²C port**<font style="color:rgb(0,0,0);"> and writing them to the serial port.  </font>

