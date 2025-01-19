# Voice Programming Mode

## Voice Direct Control  

### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732951040325-e1256a8c-7433-43dc-a297-8bc0a6e864da.gif)

### How to control the motor's movement using voice commands?  
Steps:  

1. Preparation  

| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732944850304-4959da90-fdca-4664-bfdb-7c926d1e8576.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732944859586-9321f27d-e07f-44df-9d58-3e98cdfd59b3.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732944856696-d3fb5797-0c02-45fa-a57e-ba393a0be972.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Voice Recognition Sensor ×1 | Motor × 1 |


1. Steps Display

| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732950672163-d7bf2559-9c66-495f-b9c1-d92187b269be.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732935283161-52d3e818-e1af-4ec0-8c52-f1c6f8f09ea5.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.   | 2、Connect the motor to Port 1 (green side).   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732951010690-8e44dc76-670c-4c55-a98f-9de089e3b4da.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732951047483-4abd3e4f-403b-432b-85c9-4cb7047ca053.gif) |
| 3、Connect the voice sensor to Port 1 (blue side).   | 4、Wake up the voice recognition sensor by saying "Hello Xiao Q" and wait for the response.   Say “Motor 1 forward” to rotate the motor. The system will reply, “Motor 1 forward recognized,” and the motor will rotate. Say “Stop” to stop the motor.   |


**Note:**  
The voice command should match the motor's port, as shown below:  

|  Port Connection   |  Command Word<br/> (Motor 1 Forward)   |  Command Word <br/>(Motor 2 Forward)   |
| :---: | :---: | :---: |
|  Port 1 connected to motor   |  Motor rotates   |  Motor does not rotate   |
|  Port 2 connected to motor   |  Motor does not rotate   |  Motor rotates   |
|  Both Port 1 and Port 2 connected to motors   |  Both motors rotate   |  Motor rotates   |


*Other command word effects can be tried on your own. [Click here to learn more command words.  ](#aEc3E)

---

## Voice Programming Control  
### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732958012865-b149ecd3-ac01-4e29-8cad-f21231fc1624.gif)

### How to use voice programming to control the robot's movement?  
1. Preparation

| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732944850304-4959da90-fdca-4664-bfdb-7c926d1e8576.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732944859586-9321f27d-e07f-44df-9d58-3e98cdfd59b3.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732944856696-d3fb5797-0c02-45fa-a57e-ba393a0be972.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Voice Recognition Sensor ×1 | Motors × 2 |


2. Structure Setup  

| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970009610-d1ae1d4c-7e6d-49e0-bbe5-a1109c70f853.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970013703-56512651-8a09-49bb-803b-e6163953ba60.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970015525-4703adeb-f156-445d-87a2-e366781fada4.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970026230-e51e574c-dbc2-4129-af4a-f8302883b878.png) |
| :---: | :---: | :---: | :---: |
| Step 1 | Step 2 | Step 3 | Step 4 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970029386-21da3e23-7a95-4f85-8e9a-d864084d99e0.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970032231-6804397c-88ec-4b33-b292-ebde55963f55.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970035253-23984f0f-5fca-4dad-b8f5-8406391a3036.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970038245-1c54b4ea-dec2-47f9-87e9-9d105f3f61f4.png) |
| Step 5 | Step 6 | Step 7 | Step 8 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970046511-51e0e5cc-3f0c-4e48-a831-d08f6f6b28da.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970050888-54c60adb-122f-4a45-b504-2680f3b86618.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970054723-dee83393-a252-46ba-914d-600bee0ec071.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970058493-366994aa-1c44-4b04-b29c-e58c5ec9016c.png) |
| Step 9 | Step 10 | Step 11 | Step 12 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970067731-e5008bd5-4ae5-4665-bfd2-c11b0f877944.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970069067-1d473903-eb80-4524-9241-a719a67ad110.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970072601-56ef8652-ab7a-44b7-bfbf-93a1951ba0d0.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970072361-b6bdad66-4439-4ea3-a745-dc74e8247cd8.png) |
| Step 13 | Step 14 | Step 15 | Step 16 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970082695-ad29d803-bda0-4f0b-90f9-9d2cde2a3b1e.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732970084965-41918664-35b0-4527-8d38-1ffca6b7aa77.png) |  |  |
| Step 17 | Step 18 |  |  |


3. **<font style="color:rgb(42, 43, 46);">Demonstration</font>**

![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1733034966438-639369ea-9056-4e38-a1d7-18fc23a9355e.gif)

4. Steps Display

| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732958684586-1914ccfb-ff7b-4895-b819-59f2064e36ac.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732957678963-0c99a7dd-7861-4179-9635-3b331a379196.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.   Connect the motor modules to Ports 1 and 2 (green side).   | 2、Connect the voice recognition sensor to Port 1 (blue side).   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/50805074/1732958012865-b149ecd3-ac01-4e29-8cad-f21231fc1624.gif) | ![](https://cdn.nlark.com/yuque/0/2024/png/50805074/1732960512160-0253a56a-9ae9-4592-a54c-1a61e8203d4e.png) |
| 3、Wake up the voice recognition sensor by saying "Hello Xiao Q" and wait for the response.   Say the command: “Start programming”, “Turn left”, “Wait for 1 second”, “Stop”, and “End programming.”   Say “Execute program” for the motors to perform the corresponding actions.   | Attached: Detection diagram of the voice recognition sensor. |


*Other command word effects can be tried on your own. [Click here to learn more command words.  ](#aEc3E)

## Voice Command List
| Type | Commands | Responses |
| :---: | :---: | :---: |
| Wake Words   |  Hellow, Xiao Q   |  Xiao Q is here! |  Feel free to speak? | Xiao Q is here; how can I help you?   |
|  Exit Words   |  Exit | Shut up | Close | Turn off | Step back | Stop talking   |  Call me again if you need anything.   |
| Motion Words |  Move forward   | Forward recognized |
| |  Move backward   | Backward recognized |
| |  Turn left   | Turn left recognized |
| |  Turn right   | Turn right recognized |
| |  Stop movement   | Stop movement recognized |
| Motor Control Class Words | Motor one forward rotation | Motor one rotating forward recognized |
| | Motor two forward rotation | Motor two rotating forward recognized |
| | Motor one reverse rotation | Motor one rotating backward recognized |
| | Motor two reverse rotation | Motor two rotating backward recognized |
| | Stop motor one | Motor one stopped recognized |
| | Stop motor two | Motor two stopped recognized |
| Waiting for Class Words | Wait for one second | Wait for one second recognized |
| | Wait for two seconds | Wait for two seconds recognized |
| | Wait for three seconds | Wait for three seconds recognized |
| | Wait for tilt | Wait for tilt recognized |
| | Wait for shake | Wait for shake recognized |
| | Wait for close distance | Wait for close distance recognized |
| | Wait for button one press | Wait for button one pressed recognized |
| | Wait for button two press | Wait for button two pressed recognized |
| | Wait for ten seconds | Wait for ten seconds recognized |
| | Wait for twenty seconds | Wait for twenty seconds recognized |
| | Wait for thirty  seconds | Wait for thirty  seconds recognized |
| <br/>Light Control Class Words | Please turn on the light | Turn on the light | Turn the light on | Turn on the light | Light on recognized |
| | Please turn off the light | Turn off the light | Close the light | Turn off the light | Light off recognized |
| | Red | Red light | Turn on red light | Red light | Red light recognized |
| | Yellow | Yellow light | Turn on yellow light | Yellow light | Yellow light recognized |
| | Green | Green light | Turn on green light | Green light | Green light recognized |
| | Blue | Blue light | Turn on blue light | Blue light | Blue light recognized |
| Voice Coding Words | Start programming | start coding | Start programming recognized |
| | End programming| end coding | End programming recognized |
| | Run program | run code | Run program recognized |
| | Stop program | Program stop | Stop program recognized |
| ICQbot programming Words | Move left | left recognized |
| | Move right | right recognized |
| | Move up | Up recognized |
| | Move down | Down recognized |
| | Jump | Jump recognized |
| | Go home | Go home recognized |
| | Stop | Stop recognized |


