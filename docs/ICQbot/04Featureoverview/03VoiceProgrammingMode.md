# Voice Programming Mode

## Voice Direct Control  

### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](img/VoiceProgrammingMode01.gif)

### How to control the motor's movement using voice commands?  
Steps:  

1. Preparation  

| ![](img/VoiceProgrammingMode02.png) | ![](img/VoiceProgrammingMode03.png) | ![](img/VoiceProgrammingMode04.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Voice Recognition Sensor ×1 | Motor × 1 |


1. Steps Display

| ![](img/VoiceProgrammingMode05.gif) | ![](img/VoiceProgrammingMode06.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.   | 2、Connect the motor to Port 1 (green side).   |
| ![](img/VoiceProgrammingMode07.gif) | ![](img/VoiceProgrammingMode08.gif) |
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
![](img/VoiceProgrammingMode09.gif)

### How to use voice programming to control the robot's movement?  
1. Preparation

| ![](img/VoiceProgrammingMode10.png) | ![](img/VoiceProgrammingMode11.png) | ![](img/VoiceProgrammingMode12) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Voice Recognition Sensor ×1 | Motors × 2 |


2. Structure Setup  

| ![](img/VoiceProgrammingMode13.png) | ![](img/VoiceProgrammingMode14.png) | ![](img/VoiceProgrammingMode15.png) | ![](img/VoiceProgrammingMode16.png) |
| :---: | :---: | :---: | :---: |
| Step 1 | Step 2 | Step 3 | Step 4 |
| ![](img/VoiceProgrammingMode17.png) | ![](img/VoiceProgrammingMode18.png) | ![](img/VoiceProgrammingMode19.png) | ![](img/VoiceProgrammingMode20.png) |
| Step 5 | Step 6 | Step 7 | Step 8 |
| ![](img/VoiceProgrammingMode21.png) | ![](img/VoiceProgrammingMode22.png) | ![](img/VoiceProgrammingMode23.png) | ![](img/VoiceProgrammingMode24.png) |
| Step 9 | Step 10 | Step 11 | Step 12 |
| ![](img/VoiceProgrammingMode25.png) | ![](img/VoiceProgrammingMode26.png) | ![](img/VoiceProgrammingMode27.png) | ![](img/VoiceProgrammingMode28.png) |
| Step 13 | Step 14 | Step 15 | Step 16 |
| ![](img/VoiceProgrammingMode29.png) | ![](img/VoiceProgrammingMode30.png) |  |  |
| Step 17 | Step 18 |  |  |


3. **<font style="color:rgb(42, 43, 46);">Demonstration</font>**

![](img/VoiceProgrammingMode31.gif)

4. Steps Display

| ![](img/VoiceProgrammingMode32.gif) | ![](img/VoiceProgrammingMode33.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.   Connect the motor modules to Ports 1 and 2 (green side).   | 2、Connect the voice recognition sensor to Port 1 (blue side).   |
| ![](img/VoiceProgrammingMode34.gif) | ![](img/VoiceProgrammingMode35.png) |
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


