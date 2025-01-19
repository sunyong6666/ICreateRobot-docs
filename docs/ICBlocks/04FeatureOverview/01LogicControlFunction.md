# Logic Control Function
## Introduction  
When the Boxy Robot is powered on and no Bluetooth connection is established, it defaults to Logic Control Mode. In this mode, you can activate the robot's logic control functions by connecting sensors to the orange magnetic ports or actuators to the blue magnetic ports. Different combinations of sensors and actuators will trigger different logic control functions. For better understanding, the following explains the four categories of logic control functions.  

## Boxy Robot Logic Control
**Definition**: The Boxy Robot uses sensors connected to the orange magnetic ports to control its built-in motor. This functionality is referred to as the logic control function of the robot.  

| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732888452437-1193a1c4-aa41-4a46-8ffe-c7796397afff.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732889278565-5366932d-07c7-4178-8a6d-c52bda17cd99.gif) |
| :---: | :---: |
| Button Logic Control   |  Sound Logic Control   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732888823215-fa6cc4ef-7d22-46b5-bc88-df329594aac2.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732888993225-d36533eb-d4ca-4ce5-b848-fe767ac2f2bd.gif) |
|  Photoelectric Logic Control   | Light-sensitive Logic Control   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732888754639-6e59feb1-a27c-4bbc-a849-49a3cf6e7323.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732889137614-5343ca05-acfc-49e0-a52a-e31a89925d39.gif) |
| Potentiometer Logic Control | Gyro Logic Control |


**Note**: If the sensor is not recognized during use, adjust its sensitivity following the [sensor sensitivity adjustment instructions](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/azbgmyb3i1gp4061/collaborator/join?token=esQ79qKqI4e8WdV6&source=doc_collaborator#%20《Input%20Blocks》).  

## Actuator Logic Control Function  
**Definition**: The Boxy Robot uses sensors connected to the orange magnetic ports to control actuators connected to the blue magnetic ports. This functionality is referred to as the **Actuator Logic Control Function**.  

### Button-Controlled Actuator Functions  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936532615-26d51a96-5288-4b48-a769-afef108a2f39.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936240081-52ea7988-ce09-43a6-b208-cba24316ca6d.gif)  |
| :---: | :---: |
| Button-controlled LED Block   | Button-controlled Record Block |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1733639105271-c264c243-b3f6-4c1f-9729-9d09421d99f3.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936221009-58739424-1f7a-4c4c-b393-8a120dd7e397.gif) |
| Button-controlled Motor | Button-controlled Expression Block  |


### Sound-Controlled Actuator Functions  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936298648-90d4c51c-ad1e-41ed-b8d4-4a9f5d13ddd5.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936312756-17cd10fe-f521-4ba9-8832-0a5f4e007df1.gif) |
| :---: | :---: |
| Sound-controlled LED Block | Sound-controlled Record Block |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936305985-2a849ae1-5b8c-4661-86f3-6c8d706e2315.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936295109-f42aee38-afc6-48f2-83b9-7a7d4d38c556.gif) |
| Sound-controlled Motor | Sound-controlled Expression Block  |


### Light Block Controlled Actuator Functions  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936322050-a462d747-7e08-4bfe-8d99-8cd66515c671.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936335249-abecfee9-8477-423d-9120-59d508363106.gif)  |
| :---: | :---: |
|  Light-sensitive controlled LED Block   | Light-sensitive controlled Record Block  |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936330980-39569f03-00f8-4095-8816-ebb0be76f651.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936319398-1c916186-4d7e-4165-b887-282fabbb81d1.gif)  |
|  Light-sensitive controlled Motor   | Light-sensitive controlled Expression Block   |


### Photoelectric-Controlled Actuator Functions  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936350445-86efa002-31e4-4ca9-95c4-cdbe50381570.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936379072-510e821b-d322-4f3a-b34d-f691b27fc9d3.gif) |
| :---: | :---: |
| Photoelectric-controlled LED Block  | Photoelectric-controlled Record Block |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936360837-7ba5b19b-6d59-4334-9227-3d2568c3ad4c.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936349651-3a32d6fa-83db-4aaa-80ba-24ebb28a21ea.gif) |
| Photoelectric-controlled Motor | Photoelectric-controlled Expression Block |


### Potentiometer-Controlled Actuator Functions  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936412255-054d2c09-76ba-4f9d-8ace-413d9862da8c.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936429897-153cfe41-484f-40ab-8973-2bf51197f8a4.gif) |
| :---: | :---: |
| Potentiometer-controlled LED Block | Potentiometer-controlled Record Block |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936423758-69829575-873a-419e-8fae-71a709966607.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936412712-00629bcc-6138-4dff-9f3d-3ad7221bb675.gif) |
| Potentiometer-controlled Motor | Potentiometer-controlled Expression Block |


### Gyro -Controlled Actuator Functions  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936445902-98fea8b9-0a32-4855-91d1-dfa8817ab2f4.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936455816-6695406e-f5a3-4d9e-9a1e-473fafa80183.gif) |
| :---: | :---: |
| Gyro -Controlled LED Block | Gyro -Controlled Record Block |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936449946-822f177d-cbd1-49bb-ae3c-04ff90f02ef6.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732936438434-c061d9f2-b624-46a7-807d-4650ab734e83.gif) |
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

![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732939557328-d51514d4-f780-4de0-bf81-2ae99144dbaa.gif)

## Special Logic Control Combinations  
To offer more interactive options with the ICBlocks series, two special logic control combinations are available: **Line-following Mode** and **Light-tracking Mode**.  

### Line-following Function  
**Usage**:

+ Connect two photoelectric sensors to the two orange magnetic ports.
+ Leave the blue magnetic ports empty.
+ The Boxy Robot will enter the **Line-following Mode**.

![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732939579900-1ce25d65-d3bb-450d-bcd5-efb077ee4cd1.gif)

 Line-following Robot  

### Light-tracking Function  
**Usage**:

+ Connect two light-sensitive sensors to the two orange magnetic ports.
+ Leave the blue magnetic ports empty.
+ The Boxy Robot will enter the **Light-tracking Mode**.

![](https://cdn.nlark.com/yuque/0/2024/gif/51021531/1732939597866-4d582158-0e75-438c-8a29-63b35c481798.gif)

 Light-tracking Robot  

