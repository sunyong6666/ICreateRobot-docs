# Introduction
## <font style="color:rgb(0, 0, 0);">Coding Kit for BBC micro:bit</font>
![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732929625491-d2f306f1-902a-4996-851e-97ea5ad2b570.png)

<font style="color:rgb(0, 0, 0);">Coding Kit for BBC micro:bit </font><font style="color:rgb(13, 13, 13);">is based on the micro:bit main control board and includes sensors, actuators, and other accessories. The set is perfectly designed to integrate with LEGO parts, making it ideal for students to create micro:bit-based technology and creative projects. This document focuses on the main control board, sensors, actuators, and related software extensions.</font>

## **<font style="color:rgb(13, 13, 13);">Parts List</font>**
| ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774868543-a85a1a56-0b35-4e36-9135-357cf6fd11d5.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732775004487-8809f4b8-70ea-487e-b500-a9db08adedfb.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732775543997-e6acdd6f-16e9-4108-b36d-de4c7d522f29.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732846840996-20201391-86ca-4df6-a60b-5cd62dbd153f.png) |
| --- | --- | :---: | --- |
| micro:bit Smart Hub | Servo Motor | DC Motor |  Geek Servo |
| ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774776383-e75e98c1-2a7f-4bc2-9845-a9d6b56557a7.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774702322-70134097-c5d1-4b3c-80a2-853f3f1d0fd7.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732775154578-56c76686-18bf-4cac-bae4-8e422cbf6c09.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732775308880-371fd7e5-3268-4230-b827-8b95fec56dbc.png) |
| Potentiometer Module |  Rocker Module | RGB LED Module | Fan Module |
| ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732775352663-3cbaed55-8e38-4e73-a8ae-a48dc9c8f231.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732775067134-3ef5428d-5b4a-4c35-8e5e-46e66e0e9ab6.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774167913-66e876f5-329c-42f5-9fdc-ebcf441ad8ca.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732775175194-c1a6deb2-e4c4-46a5-ac34-c8cc5c783ea1.png) |
| Recording Module | OLED Module | Laser Module | Electromagnet Module |
| ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774019528-f03d8a4c-9d0f-4e1c-ba33-424315265d95.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774029566-c36c641a-3195-45dc-afb7-bf595a67fb14.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774034816-67a310b8-d4cd-463f-aa0e-08fdc447bd22.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774037776-55e287ea-66ce-4fcd-be09-f3eacb0aeff8.png) |
| Red LED Module | Yellow LED Module | Blue LED Module | Green LED Module |
| ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732775376183-3adc2c1e-0d15-4530-a908-a924de607a37.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774053471-a6e0a912-c223-4705-b7da-b306a927619e.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774118689-a45bafcb-2d89-4f08-91e5-6b76e54b2265.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774124240-2d132900-6858-4582-a8ab-10a73e5cffc2.png) |
| Ultrasonic Sensor |  MQ-2 Gas Sensor | PIR Sensor | Temperature Sensor |
| ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774197054-7434c6fe-1a73-4ee2-9e6f-65ab7eb64e0a.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774177337-ec0d4547-9c4a-4836-b373-9283215a29b8.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774210094-5b4552a0-6648-41d9-8cd5-597cc20a00c4.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774202359-b38cb9a8-c57e-4f48-9114-4cfd2c436aea.png) |
| Flame Sensor | Hall Sensor | Grayscale Sensor  | Photosensitive Sensor |
| ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774693000-5ed8ac88-9a90-49a5-b836-86bf43830b0a.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774235891-ec7bc324-0b21-4565-8500-f45e9562c00e.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774299435-c0b29a43-b088-402a-af9a-e0297f12f806.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774288490-e5ac62d3-2bab-4197-9f70-6c3683287f01.png) |
| Button Sensor | Soil Moisture Sensor  | Water Level Sensor | Long-Range Photoelectric Sensor |
| ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732866596385-4154a88c-dbcc-424e-ab28-06391f3875ad.png) | | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732935365054-cd1638a6-6542-4fa6-a1a9-ca557b65aedc.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732935275617-4316a6b5-3b85-44b8-b1d2-bfa2b541c623.png) |
| Six way Color&Gray Sensor | | Grove Cable | Grove Male-to-Female Cable |


> <font style="color:rgb(13, 13, 13);">The above shows the modules and sensors included in the set. </font>
>
> <font style="color:rgb(13, 13, 13);">Please refer to the actual product for photos.</font>
>



## <font style="color:rgb(13, 13, 13);">List of electronic components in the kit:</font>
| Item | <font style="color:rgb(13, 13, 13);">AI Coding Set for BBC micro:bit  -V1.0</font> | <font style="color:rgb(13, 13, 13);">AI Coding Set for BBC micro:bit  -V2.0</font> | <font style="color:rgb(13, 13, 13);">BBC micro:bit Innovation Set</font> | <font style="color:rgb(13, 13, 13);">BBC micro:bit  </font>**<font style="color:rgb(13, 13, 13);">Expansion Set</font>** |
| :---: | :---: | :---: | :---: | :---: |
| micro:bit Smart Hub | 1  | 1  | 1 | 1 |
| Servo Motor | â€? | 2  | â€? | â€? |
| DC Motor | 4  | â€? | 4  | â€? |
| Geek Servo | 2  | 2  | 2  | â€? |
| Potentiometer Module | 1  | 1  | 1  | â€? |
| Rocker Module | â€? | 1  | â€? | 1 |
| RGB LED Ring Module | 1  | 1  | â€? | â€? |
| Fan Module  | 1  | 1  | â€? | â€? |
| Recording Module | â€? | 1  | â€? | â€? |
| OLED Module | 1  | 1  | 1  | â€? |
| Laser Module | 1  | 1  | 1  | â€? |
| Electromagnet Module | 1  | 1  | â€? | â€? |
| Red LED Module | 1  | 1  | 1  | â€? |
| Yellow LED Module | 1  | 1  | 1  | â€? |
| Blue LED Module | 1  | 1  | 1  | â€? |
| Green LED Module  | 1  | 1  | 1  | â€? |
| Ultrasonic Sensor  | 1  | 1  | 1  | â€? |
| MQ-2 Gas Sensor | 1  | 1  | â€? | â€? |
| PIR Sensor | â€? | 1  | â€? | â€? |
| Temperature Sensor | 1  | 1  | â€? | â€? |
| Flame Sensor  | 1  | 1  | â€? | â€? |
| Hall Sensor | 1  | 1  | 1  | â€? |
| Grayscale Sensor  | 2  | 2  | 2  | â€? |
| Photosensitive Sensor   | 1  | 1  | â€? | â€? |
| Button Sensor | 1  | 1  | 1  | 3  |
| Soil Humidity Sensor | 1  | 1  | â€? | â€? |
| Water Level Sensor  | 1  | 1  | â€? | â€? |
| Long-range Photoelectric Sensor | 1  | 1  | â€? | â€? |
| Grove Cable | 10  | 10  | 10  | 10  |
| Grove Male-to-Female Cable | 10  | 10  | 10  | â€? |




