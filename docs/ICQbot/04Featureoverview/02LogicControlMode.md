# Logic Control Mode

## Distance Sensor Controls Motor  

### Single Distance-Controlled Motor:  
#### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732950560957-88cc106b-b263-44ec-a529-6e6d70333a66.gif)

#### How to use the distance sensor to control the motor's movement?  
 Steps:  

1. Preparation  

| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732936141629-e2018c87-f2b4-4ec8-b11e-e1be20de1fc6.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732936160608-d1e46625-ea10-4da3-a671-e6509c6c5219.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732936216371-6392efe9-03d2-4bae-b7b7-9f5558cfcf95.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Distance Sensor × 1 | Motor × 1 |


2. Step Display

| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732950672163-d7bf2559-9c66-495f-b9c1-d92187b269be.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732950680667-5cc2bf78-50fd-4269-b4b6-18489bad5f75.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.   | 2、 Connect the distance sensor to Port 1 (blue side).   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732935283161-52d3e818-e1af-4ec0-8c52-f1c6f8f09ea5.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732950780667-406805c8-d744-4830-bf42-0f4f27fed429.gif) |
| 3、Connect the motor to Port 1 (green side).   | 4、Use the distance sensor to control the motor's counterclockwise rotation based on detected distance.   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732950790564-09fd9cfa-9105-49be-9b53-5f5839f13adf.gif) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732936087912-099f6866-9594-4c44-96ed-e4414ec1a31a.png) |
| 5、 The same operation applies to Port 2 for clockwise motor movement.   | Attached: Distance sensor detection diagram. |

---

### Dual Distance-Controlled Motor (Line-Following Mode):  
#### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732970643433-41942e50-f75d-4fd1-827e-73dbe24db11f.gif)



#### How to use the distance sensors for line-following?  
Steps:  

1. Preparation

| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732944807418-73822d93-609c-45fe-9364-aaa04a356256.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732936160608-d1e46625-ea10-4da3-a671-e6509c6c5219.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732936216371-6392efe9-03d2-4bae-b7b7-9f5558cfcf95.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Distance Sensors × 2 | Motor × 1 |


1. Structure Setup 

| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1733476942705-69906ac5-fabb-49c2-b6a1-ae19e914ef11.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969657309-448078af-7959-4ca1-9a34-014e42716780.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969659527-957fbc77-1c27-4b9a-93eb-c60b98d9a18d.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969667196-75d0d031-99d6-495f-854a-130710e343b0.png) |
| :---: | :---: | :---: | :---: |
| Step 1 | Step 2 | Step 3 | Step 4 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969670751-985b5104-121a-4692-b472-d518759a6d03.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969673938-1112cebd-a863-4f98-99a7-dd98fa64b821.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969676956-43914d74-b010-496f-bd94-40f726fd08f0.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969684769-b97846cc-aa9b-4108-9bda-80e4361574e0.png) |
| Step 5 | Step 6 | Step 7 | Step 8 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969707142-53939090-7050-4ff5-a96e-4e9b57335354.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969708406-9389eda5-c81b-4ee1-961c-b442feba6073.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969711476-f56bea2d-d43c-430b-b713-1b448c7f092a.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1734492064860-baf91389-cd30-4e0a-88e9-843185dd2b6b.png) |
| Step 9 | Step 10 | Step 11 | Step 12 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969722881-1d5773bd-518d-4a00-a994-a2f46e2d1d62.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969725025-6bb766c6-297e-4c9e-89e0-ef9045f06743.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969729857-7da43856-a35c-4f0c-aa00-f7e0aa669545.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969767310-4b6bdeb2-705a-41e0-bc9c-34e09189ceaa.png) |
| Step 13 | Step 14 | Step 15 | Step 16 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969772749-7d2125ac-f6eb-4a87-a532-20bc6dbae743.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969775038-475fc646-76e7-44ec-ad00-c74d8f00e8a8.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969773737-50cfb291-7d35-4c2c-89bd-cf5b3cf3b308.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969779269-e7ba86a1-2b59-46cb-8eef-3c54b7c966d9.png) |
| Step 17 | Step 18 | Step 19 | Step 20 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969787573-8ab5846a-c6b7-4f15-add6-73ae8bc0c5af.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969788357-c49f1665-5a93-4c76-a9db-5860b004bbf8.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732969793024-c0545d54-6efe-4d3a-8675-594b3f281cc1.png) |  |
| Step 21 | Step 22 | Step 23 |  |




2. Display

![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732958212641-89eb44d2-6b7f-4747-bb5d-adf009a4f827.gif)

3. Steps Display

| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732959405098-dda9fc7c-227f-46d9-86fb-9523c00d8841.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732959459359-398ccd72-595e-49e4-abbb-f83e5fb87f0c.gif) |
| --- | --- |
| 1、Connect the distance sensors to Ports 1 and 2 (blue side).   | 2、Connect the motor to Ports 1 and 2 (green side).   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732959769304-a47ac62f-9bdb-4d0d-8b19-a0d9bf96d2a8.gif) | |
| 3、Press and hold the power button on the Xiao Q Robot for 3s, then place the line-following car on the track to begin line-following.  <br/>**Note:** If line-following does not work, try switching the motor ports.   | |


*If you have other problems, please refer to [fault analysis and troubleshooting](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/mt3pio89d0wmgysa/collaborator/join?token=6haNKiSj5A3tLXuI&source=doc_collaborator#%20《硬件类故障》) to learn more.

---

## Tilt Sensor Control Motor  
### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732950888053-8ba59aac-6f48-4423-8bdc-77d0ac1f08ac.gif)

### How to use the tilt sensor to control the motor's movement?  
Steps:

1. Preparation

| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732937364242-51860798-d006-4282-b3b8-e3484870d801.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732937374819-9fb9ab8f-8b43-4ca5-952c-80c0b2255d2d.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732937379956-cadf9eaf-7718-4f3b-b648-acd75b9c8a5c.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot ×1 | Tilt Sensor × 1 | Motor × 1 |


2. Steps Diaplay

| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732950672163-d7bf2559-9c66-495f-b9c1-d92187b269be.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732935283161-52d3e818-e1af-4ec0-8c52-f1c6f8f09ea5.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.   | 2、 Connect the tilt sensor to Port 1 (blue side).   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732950680667-5cc2bf78-50fd-4269-b4b6-18489bad5f75.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732959319064-1e916813-80d9-4522-af68-247b6d410bb7.gif) |
| 3、 Connect the motor module to Port 1 (green side).   | 4、Tilt the sensor to the left or right to control the motor's rotation direction. The greater the tilt angle, the faster the motor will rotate.   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732951003499-0e5cae33-64df-4c67-ad9a-bab8d96b0c12.gif) |  |
| 5、Port 2 operates similarly to Port 1.  （Attached: tilt sensor can control motor only left and right, not control front and back) |  |


*If the tilt sensor cannot control the movement of the motor in both directions, please refer to [the fault analysis and troubleshooting](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/mt3pio89d0wmgysa/collaborator/join?token=6haNKiSj5A3tLXuI&source=doc_collaborator#%20《硬件类故障》) click for more information.

