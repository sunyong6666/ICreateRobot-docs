# Temperature Sensor
## **<font style="color:rgb(13, 13, 13);">Principle</font>**
The temperature sensor is specifically designed for humid environments. During operation, the sensor converts detected temperature signals into corresponding voltage signals. These voltage signals are then converted into analog signals and transmitted to the main control board for processing.  

## <font style="color:rgb(13, 13, 13);">Specifications</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name | <font style="color:rgb(0,0,0);">Temperature Sensor</font> |
| Code | B0020014 |
| <font style="color:rgb(0,0,0);"> Dimensions  </font> | <font style="color:rgb(0,0,0);">79×24×12 mm</font> |
|  Voltage   | <font style="color:rgb(0,0,0);">5V－DC</font> |
| <font style="color:rgb(13, 13, 13);">Data Type</font> |  Analog<font style="color:rgb(13, 13, 13);"> Signal</font> |
| <font style="color:rgb(13, 13, 13);">Data Range</font> | <font style="color:rgb(0,0,0);">0~1023</font> |
| <font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgb(0,0,0);">Grove</font> |




## Usage


| ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732789935577-b803a4e4-710c-43e7-aeae-916fa884ce80.png) | | |
| :---: | --- | --- |
| ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732779873060-4327e14d-352f-4afc-8f36-6d0e0ce9b4d6.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732779929854-8b7ea493-4c94-41e3-ba62-00fcafc0de35.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732779955398-37150801-13b4-4034-acff-f52854a90170.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| <font style="color:rgb(0,0,0);">Temperature Sensor </font>Connection Diagram | | |


The temperature sensor can connect to **P0**, **P1**, or **P2** ports of the **micro:bit hub**. In the coding environment, the analog values of the sensor can be read. Its characteristics include:  

+ **Temperature increase**: The detected temperature value increases as the ambient temperature rises.
+ **Temperature decrease**: The detected temperature value decreases as the ambient temperature drops.

> **Note**: During use, avoid exposing any parts of the sensor other than the detection head to water to prevent damage.  
>

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
![](https://cdn.nlark.com/yuque/0/2024/webp/46964359/1732871010563-9ef236e6-0f22-43ef-a06f-5c5cd61a4fd5.webp)

<font style="color:rgb(13, 13, 13);">In the MakeCode coding software, by adding the Microbit extension, you can code the system to read the temperature sensor signal from the P0 port and visualize the data on the micro: bit's LED display.</font>

