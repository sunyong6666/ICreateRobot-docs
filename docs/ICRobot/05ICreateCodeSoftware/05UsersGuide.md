# User's Guide
## Interactive Mode（Live Mode）
### Usage Introduction
In Interactive Mode, ICRobot connects to the PC via AP or STA wireless mode for real-time programming and control.

### Steps
| ![](img/UG01.gif) | ![](img/UG02.png) |
| --- | --- |
| Step 1: Power on both the ICRobot and the ICreate Code software. Switch the software to "Interactive Mode", then select the device and connection method (refer to the AP or STA connection instructions). | Step 2: Once successfully connected, the block command area will automatically load ICRobot-related extension blocks. |
| ![](img/UG03.png) | ![](img/UG04.png) |
| Step 3: Drag the blocks into the coding area to start coding. | Step 4: After programming is complete, click the green flag to execute the program and observe the result. |


### Example
#### Scenario
Using AP mode, ICRobot connects to the PC and moves forward at full power for 1 second, then activates its robotic gripper once.

#### Preparation
| ![](img/UG05.png) | ![](img/UG06.png) | ![](img/UG07.png) |
| :---: | :---: | :---: |
| A computer (Windows/macOS) | ICreateCode Software | ICRobot |


#### Steps
| ![](img/UG08.gif) | ![](img/UG09.gif) |
| --- | --- |
|  Step 1:  Power on ICRobot and switch to AP mode via the SET menu. |  Step 2:  Open ICreateCode, check the ICRobot name under PC WLAN settings, and connect via AP mode in the software. |
| ![](img/UG10.png) | ![](img/UG11.png) |
|  Step 3:  Once connected, program the desired behavior. |  Step 4:  Click the green flag to run the program and observe the robot’s actions. |


#### Demonstration
![](img/UG12.gif)

## Download Mode
### Usage Introduction
Programs created in the software can be downloaded to the ICRobot for independent execution. The steps are as follows:

Determine the download location of the programme in the software.

Download the program into one of ICRobot's five internal storage positions.

Based on the program content, the robot will perform the corresponding action commands.

### Steps
| ![](img/UG13.gif) | ![](img/UG14.png) |
| --- | --- |
| Step 1: Power on both the ICRobot and the programming software. In the software, switch the mode to Interaction Mode, select your device, and choose the connection method (refer to AP/STA connection steps). | Step 2: Once connected, the Block Instruction area will automatically load ICRobot-specific extension blocks. |
| ![](img/UG15.gif) | ![](img/UG16.gif) |
| Step 3: Drag blocks into the coding area to begin creating your code. While doing so, the Python Code Area will display corresponding Python syntax in real-time. | Step 4: After completing the code, click the Download option in the Hardware Control Panel.<br/>Use the left/right arrows on the robot to select a program slot (1–5), then confirm download. |


### Example
#### Scenario
Using STA Mode, ICRobot connects to the PC. After downloading, the robot drives forward at maximum power for 1 second, then displays a custom dot-matrix pattern on its LED screen. The program is saved in 3 of ICRobot’s memory.

#### Preparation
| ![](img/UG17.png) | ![](img/UG18.png) | ![](img/UG19.png) |
| :---: | :---: | :---: |
| A computer (Windows/macOS) | ICreateCode Software | ICRobot |


#### Steps
| ![](img/UG20.gif) | ![](img/UG21.gif) |
| --- | --- |
| Step 1: Power on ICRobot. Switch to SET Mode, then select STA Mode. | Step 2: Open ICreateCode and choose STA as the connection method. Generate the corresponding QR code. |
| ![](img/UG22.png) | ![](img/UG23.gif) |
| Step 3: Use the robot's camera to scan the QR code displayed on the screen.<br/>Upon hearing “Connection successful” and seeing “Socket connected” on the screen, the device is ready. | Step 4:<br/>Create the desired program using drag-and-drop blocks. |
| ![](img/UG24.gif) | ![](img/UG25.gif) |
| Step 5: Select Slot 3, then click Download. Wait for the message “Download successful.” | Step 6: Press the robot’s left/right buttons to switch to Program 3, then press the power button to execute the program. |


#### Demonstration
![](img/UG26.gif)

