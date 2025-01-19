# Logic Control Mode

## Distance Sensor Controls Motor  

### Single Distance-Controlled Motor:  
#### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](img/LogicControlMode01.gif)

#### How to use the distance sensor to control the motor's movement?  
 Steps:  

1. Preparation  

| ![](img/LogicControlMode02.png) | ![](img/LogicControlMode03.png) | ![](img/LogicControlMode04.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Distance Sensor × 1 | Motor × 1 |


2. Step Display

| ![](img/LogicControlMode05.gif) | ![](img/LogicControlMode06.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.   | 2、 Connect the distance sensor to Port 1 (blue side).   |
| ![](img/LogicControlMode07.gif) | ![](img/LogicControlMode08.gif) |
| 3、Connect the motor to Port 1 (green side).   | 4、Use the distance sensor to control the motor's counterclockwise rotation based on detected distance.   |
| ![](img/LogicControlMode09.gif) | ![](img/LogicControlMode10.png) |
| 5、 The same operation applies to Port 2 for clockwise motor movement.   | Attached: Distance sensor detection diagram. |

---

### Dual Distance-Controlled Motor (Line-Following Mode):  
#### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](img/LogicControlMode11.gif)



#### How to use the distance sensors for line-following?  
Steps:  

1. Preparation

| ![](img/LogicControlMode12.png) | ![](img/LogicControlMode13.png) | ![](img/LogicControlMode14.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Distance Sensors × 2 | Motor × 1 |


1. Structure Setup 

| ![](img/LogicControlMode15.png) | ![](img/LogicControlMode16.png) | ![](img/LogicControlMode17.png) | ![](img/LogicControlMode18.png) |
| :---: | :---: | :---: | :---: |
| Step 1 | Step 2 | Step 3 | Step 4 |
| ![](img/LogicControlMode19.png) | ![](img/LogicControlMode20.png) | ![](img/LogicControlMode21.png) | ![](img/LogicControlMode22.png) |
| Step 5 | Step 6 | Step 7 | Step 8 |
| ![](img/LogicControlMode23.png) | ![](img/LogicControlMode24.png) | ![](img/LogicControlMode25.png) | ![](img/LogicControlMode26.png) |
| Step 9 | Step 10 | Step 11 | Step 12 |
| ![](img/LogicControlMode27.png) | ![](img/LogicControlMode28.png) | ![](img/LogicControlMode29.png) | ![](img/LogicControlMode30.png) |
| Step 13 | Step 14 | Step 15 | Step 16 |
| ![](img/LogicControlMode31.png) | ![](img/LogicControlMode32.png) | ![](img/LogicControlMode33.png) | ![](img/LogicControlMode34.png) |
| Step 17 | Step 18 | Step 19 | Step 20 |
| ![](img/LogicControlMode35.png) | ![](img/LogicControlMode36.png) | ![](img/LogicControlMode37.png) |  |
| Step 21 | Step 22 | Step 23 |  |




2. Display

![](img/LogicControlMode38.gif)

3. Steps Display

| ![](img/LogicControlMode39.gif) | ![](img/LogicControlMode40.gif) |
| --- | --- |
| 1、Connect the distance sensors to Ports 1 and 2 (blue side).   | 2、Connect the motor to Ports 1 and 2 (green side).   |
| ![](img/LogicControlMode41.gif) | |
| 3、Press and hold the power button on the Xiao Q Robot for 3s, then place the line-following car on the track to begin line-following.  <br/>**Note:** If line-following does not work, try switching the motor ports.   | |


*If you have other problems, please refer to [fault analysis and troubleshooting](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/mt3pio89d0wmgysa/collaborator/join?token=6haNKiSj5A3tLXuI&source=doc_collaborator#%20《硬件类故障》) to learn more.

---

## Tilt Sensor Control Motor  
### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](img/LogicControlMode42.gif)

### How to use the tilt sensor to control the motor's movement?  
Steps:

1. Preparation

| ![](img/LogicControlMode43.png) | ![](img/LogicControlMode44.png) | ![](img/LogicControlMode45.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot ×1 | Tilt Sensor × 1 | Motor × 1 |


2. Steps Diaplay

| ![](img/LogicControlMode46.gif) | ![](img/LogicControlMode47.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.   | 2、 Connect the tilt sensor to Port 1 (blue side).   |
| ![](img/LogicControlMode48.gif) | ![](img/LogicControlMode49.gif) |
| 3、 Connect the motor module to Port 1 (green side).   | 4、Tilt the sensor to the left or right to control the motor's rotation direction. The greater the tilt angle, the faster the motor will rotate.   |
| ![](img/LogicControlMode50.gif) |  |
| 5、Port 2 operates similarly to Port 1.  （Attached: tilt sensor can control motor only left and right, not control front and back) |  |


*If the tilt sensor cannot control the movement of the motor in both directions, please refer to [the fault analysis and troubleshooting](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/mt3pio89d0wmgysa/collaborator/join?token=6haNKiSj5A3tLXuI&source=doc_collaborator#%20《硬件类故障》) click for more information.

