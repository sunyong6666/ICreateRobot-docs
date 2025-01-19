# Quick Start
If you are using this product for the first time, it is recommended to carefully read this section. By completing a few simple practical cases, you can quickly learn how to create with ICBricks. For experienced users, you may skim through or skip to later sections to explore more advanced features and application techniques.  
With these curated examples, you will quickly master ICBricks' operation methods and experience its powerful functionality and creative joy!  

## Power On  
Press and hold the hub’s power button for 2s to turn it on. A short prompt sound will play during startup. Once successfully powered on, the indicator light and button breathing light will remain steady.   

![](https://cdn.nlark.com/yuque/0/2024/gif/42941758/1733477824940-f710cd20-1bc2-4b45-a4f3-ba46ad754d7d.gif)

## Direct Control: Controlling the Motor  
### Preparation
| ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732957136287-458a6c7b-b542-483a-af80-5a0b38cb333a.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732957146760-64af182d-be26-47df-b807-34a335da840a.png) |
| :---: | :---: |
| ICBricks Hub × 1 |  Servo Motors  × 2 <br/>  Servo Motor Adapter Cables × 2   |


### Steps:  
 1.  Connect the Motors  

Power on the main controller. Use the servo motor adapter cables to connect the two motors to ports 2 and 4. When connected successfully, the motors will emit a prompt sound.  

![](https://cdn.nlark.com/yuque/0/2024/png/42941758/1733652910786-bc7fa64b-a7a6-4876-8f67-82b425cc9f53.png)

### Demonstration  
Press the up and down buttons on the hub to observe the movement of the servo motors.  

![](https://cdn.nlark.com/yuque/0/2024/gif/43021771/1732953687861-8fd1dac9-57c1-45cf-ab13-1fb60bb855aa.gif)

## Logical Control: Encoder Sensor Controls Motor  
### ****Preparation
| ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732957136287-458a6c7b-b542-483a-af80-5a0b38cb333a.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732957146760-64af182d-be26-47df-b807-34a335da840a.png) | ![](https://cdn.nlark.com/yuque/0/2024/jpeg/51021329/1732776829172-10935da2-ab63-496d-b715-894a8f22a2b6.jpeg) |
| :---: | :---: | :---: |
| ICBricks Hub × 1 |  Servo Motor × 1<br/>  RJ11 to Grove Cable × 1 |  Encoder Sensor × 1  <br/> 6P Crystal Head Cable × 1   |


###  Connect Sensor and Actuator  
Power on the hub. Use the RJ11 cable to connect the encoder sensor to port 1 of the hub. Connect the servo motor to port 2 using the RJ11 to grove cable.  

![](https://cdn.nlark.com/yuque/0/2024/png/42941758/1733652956506-edd58613-51d8-4590-af43-6b76c3334379.png)

### Demonstration  
Rotate the encoder sensor left and right to observe the movement of the servo motor.  

![](https://cdn.nlark.com/yuque/0/2024/gif/43021771/1732953818887-3e864396-104e-42f2-9eea-3631cb919d3f.gif)

## Programming Control: Remote-Controlled Car  
###  Demonstration Effect:  
![](https://cdn.nlark.com/yuque/0/2024/gif/43021771/1732955569026-139811b6-9753-45cc-b4d2-6908a542f4aa.gif)

###  Hardware Setup:  
#### Preparation
| ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732957136287-458a6c7b-b542-483a-af80-5a0b38cb333a.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732957146760-64af182d-be26-47df-b807-34a335da840a.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732957597420-9dab7a0c-b222-4bf7-9193-e4c0cd543417.png)![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732957597439-3407e5f2-13c8-471f-a974-33a43f6746c9.png) |
| :---: | --- | --- |
| ICBricks Hub × 1 | Servo Motors × 2<br/>  RJ11 to Grove Cables × 2 |  LEGO bricks   |


#### Steps:  
| ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732966448210-8a6221c0-e1cb-45cd-b9cf-cd00776dbf63.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732966448209-0868d3eb-535c-46df-a31f-902edf708ccd.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732966448308-4e7188b9-488b-4023-b48a-4ebe53782858.png) |
| :---: | :---: | :---: |
| Step ① | Step ② | Step ③ |
| ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732966448408-d0996bb8-131d-434c-ad2d-8d394d91b152.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732966448337-3a04d252-a50c-44f7-8762-60bb42f75fae.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732966449200-cab67b44-1fb4-49ba-ad85-8b77564d3660.png) |
| Step ④ | Step ⑤ | Step ⑥ |
| ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732966449298-b4522a97-3d79-4253-9bad-01ad35b38096.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732966449292-0a6dee04-3851-45d5-9486-6a37cb2f4621.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732966449594-f8877f81-0564-4e24-b426-5534781d7fc0.png) |
| Step ⑦ | Step ⑧ | Step ⑨ |


#### Connect Motors  
Connect Motor 1 to port 1 and Motor 2 to port 2 of the hub.  

![](https://cdn.nlark.com/yuque/0/2024/png/42941758/1733483091533-caabfd36-07e2-4a68-a9f9-cae24d28a4f3.png)

### Software Programming  
#### Install the Software  
** Click the following link to download the installation package: **👉** **[**[Software Installation]**](https://www.yuque.com/crystal-vzc6k/cfl3ix/xk5zklboqd93ngc7?singleDoc#%20《软件安装》)**  **

#### Steps for Programming  
**Step 1: Connect Bluetooth  **

Before using the programming software, ensure that location and Bluetooth permissions are enabled, and the hub is powered on.  

Open the ICBricks programming software, tap the Bluetooth button, select the hub's name, and click connect.  

![](https://cdn.nlark.com/yuque/0/2024/gif/43021771/1732787087009-09437d13-c2cf-4ceb-9f66-437c53e1dbe6.gif)



**Step 2: Create a New Project  **

Tap the Beginner Version icon to enter the project interface. Click "New Project" to access the beginner programming interface.  

![](https://cdn.nlark.com/yuque/0/2024/gif/43021771/1732788989671-8da48b89-04f8-4b5a-9b77-9001ad283de8.gif)

**Step 3: Program the Project  **

Use the five remote control buttons (“🔼,” “🔽,” “◀️,” “▶️,” “stop”) to control the car’s forward, backward, left, right, and stop movements.  

1. Select the module shown in the <font style="background-color:#FBDE28;">yellow block</font> and drag it to the programming area. Click the dropdown arrow to select the "🔼" direction.  

![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732871085848-948c861e-a082-4969-b49a-a89cf8fa665e.png)

2. Select the module shown in the <font style="background-color:#81BBF8;">blue block</font> and drag it to the programming area.  

![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732871856728-1a904a99-f347-42e0-a16f-898dfcc4fd6d.png)

3. Similarly, program the other four directions (Backward “🔽,” Left “◀️,” Right “▶️,” and Stop “stop”).    

![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1732872701008-7f65e61c-2154-43e2-8c88-0594df52ad26.png)

**Step 4: Run the Program  **

Click the run button to execute the program. Open the remote control and operate the robot.  

![](https://cdn.nlark.com/yuque/0/2024/png/42941758/1732970283444-9989bdea-b6f0-43c7-825b-3ddfb94f900e.png)

### Demonstration  
By pressing different buttons, you can control the car to perform various movements.  

![](https://cdn.nlark.com/yuque/0/2024/gif/43021771/1732955569026-139811b6-9753-45cc-b4d2-6908a542f4aa.gif)





****

****

