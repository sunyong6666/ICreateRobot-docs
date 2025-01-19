# Soil Moisture Sensor
## **<font style="color:rgb(13, 13, 13);">Principle</font>**
<font style="color:rgb(13, 13, 13);">The soil humidity sensor operates based on the impact of soil moisture content on its resistance. In dry soil, the lack of moisture as a conductive medium results in high resistance; in moist soil, water dissolves some of the salts in the soil, forming an electrolyte solution that significantly lowers the soil's resistivity. By applying a certain voltage between two electrodes and monitoring the resulting current changes or directly measuring the resistance changes, the moisture level in the soil can be accurately assessed.</font>

## <font style="color:rgb(13, 13, 13);">Specifications</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| <font style="color:rgb(13, 13, 13);">Name</font> | Soil Humidity Sensor |
| Code | B0020017 |
| <font style="color:rgb(13, 13, 13);"> Voltage</font> | 5V－DC |
| <font style="color:rgb(13, 13, 13);">Data Type</font> | <font style="color:rgb(13, 13, 13);"> Analog Signal</font> |
| <font style="color:rgb(13, 13, 13);">Data Range</font> | 0~1023 |
| <font style="color:rgb(13, 13, 13);">Ports</font> | Grove |
|  Dimensions   | 79×24 (mm) |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732789401409-13d86b5b-f627-48d5-bb34-20f852d4e955.png) | | |
| :---: | --- | --- |
| ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732779873060-4327e14d-352f-4afc-8f36-6d0e0ce9b4d6.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732779929854-8b7ea493-4c94-41e3-ba62-00fcafc0de35.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732779955398-37150801-13b4-4034-acff-f52854a90170.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| **<font style="color:rgb(13, 13, 13);">Soil Humidity Sensor Connection Diagram</font>** | | |


<font style="color:rgb(13, 13, 13);">The soil humidity sensor can be connected to the P0, P1, or P2 ports of the micro: bit Intelligent Hub. In the coding environment, you can read the analog values from the soil humidity sensor. The sensor behaves as follows: the higher the soil moisture, the higher the detected value; conversely, the lower the soil moisture, the lower the detected value.</font>

> **<font style="color:rgb(13, 13, 13);">Note</font>**<font style="color:rgb(13, 13, 13);">: Avoid exposing the components to water to prevent damage to the sensor.</font>
>

## **<font style="color:rgb(13, 13, 13);">Modular Coding</font>**
![](https://cdn.nlark.com/yuque/0/2024/webp/46964359/1732871898771-303e41be-6fd8-4c39-bd06-ab17526f5da8.webp)

<font style="color:rgb(13, 13, 13);">In the MakeCode coding environment, by adding the Microbit extension, you can program the system to read the soil humidity sensor signal from the P0 port and visualize the data on the micro: bit's LED display.</font>

