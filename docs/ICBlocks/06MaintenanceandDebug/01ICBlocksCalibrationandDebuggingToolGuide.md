# ICBlocks Calibration and Debugging Tool Guide
## Introduction  
The ICBlocks Calibration and Debugging Tool is a dedicated software designed for ICBlocks Boxy Robots and coding boards. It assists users in monitoring device status and addressing practical issues during use effectively.  

## Software Installation  
Download the ICBlocks Debugging Software installation package from the official website [[Download Link](https://www.icrobot.com/www/cn/index.html#/file/index?type1=%E8%BD%AF%E4%BB%B6%E8%B5%84%E6%96%99&type2=ICBlocks)]. Transfer the installation package to your Android device for installation.

## Interface Guide  
The software includes five pages: the Home Interface, Bluetooth Connection Interface, Boxy Robot Debugging Interface, Boxy Robot Calibration Interface, and Coding Board Debugging Interface. Below are detailed descriptions:  

## Home Interface  
![](https://cdn.nlark.com/yuque/0/2024/png/42947223/1732843225377-146db6c9-2b05-4b0e-b8c8-d7b11bafac39.png)

|  No.   |  Name   | Description |
| :---: | :---: | :---: |
| â‘? |  "Boxy Robot Debugging Mode"   |  Enters the Bluetooth Connection Interface if no device is connected.   |
| | |  Enters the Boxy Robot Debugging Interface if a device is connected.   |
| â‘? |  "Coding Board Debugging Mode"   |  Enters the Bluetooth Connection Interface if no device is connected.   |
| | |  Enters the Coding Board Debugging Interface if a device is connected.   |
| â‘? |  Device Connection Status   |  Displays the device connection status on the Home Interface.   |
| â‘? |  Device Connection Indicator   |  Indicates connection status across all pages   |
| | |  Blue for connected, Grey for disconnected.   |
| â‘? |  "Boxy Robot Calibration"    |  Enters the Bluetooth Connection Interface if no device is connected.   |
| | |  Enters the Boxy Robot Calibration Interface if a device is connected.   |
| â‘? |  Software Version   |  Displays the current software version.   |


## Bluetooth Connection Interface  
![](https://cdn.nlark.com/yuque/0/2024/png/42947223/1732846182991-cc7da057-7819-469e-819b-f8c597d2320d.png)

|  No.   |  Name   | Description |
| :---: | :---: | :---: |
| â‘? | Interface Title   | Displays the name of the current interface.   |
| â‘? | Device List   |  Shows the names and addresses of detected devices.   |
| â‘? |  "Refresh"   |  Refreshes the device list when clicked.   |
| â‘? | Device Connection |  Indicates connection status across all pages   |
| | |  Blue for connected, Grey for disconnected.   |
| â‘? |  "Back"   |  Exits the Bluetooth Connection Interface.   |
| â‘? |  "Disconnect"   |  Disconnects the currently connected device.   |


## Boxy Robot Debugging Interface  
![](https://cdn.nlark.com/yuque/0/2024/png/42947223/1732847764877-92c5add7-ab49-4dfe-bb52-7597671eadee.png)

|  No.   |  Name   | Description |
| :---: | --- | :---: |
| â‘? | Interface Title   | Displays the name of the current interface.   |
| â‘? |  Back Button   |  Exits the current interface.   |
| â‘? |  Data Display Area   | Displays information about attached blocks during debugging.   |
| â‘? |  "Start Debugging"   |  Activates debugging mode.   |
| â‘? |  Coding Block Debug   |  Allows control of the Boxy Robot by sending specific commands during debugging.   |
| â‘? | Actuator Block Debug |  Allows control of the Boxy Robot by sending specific commands during debugging.  |
| â‘? |  Device Connection   |  Indicates connection status across all pages   |
| | |  Blue for connected, Grey for disconnected.   |
| â‘? |  "Stop Debugging"   |  Exits debugging mode.   |


## Boxy Robot Calibration Interface  
![](https://cdn.nlark.com/yuque/0/2024/png/42947223/1732850352526-0b5c2a56-93a3-4b51-abb3-b2d5eb423505.png)

|  No.   |  Name   | Description |
| :---: | :---: | :---: |
| â‘? |  Back Button |  Exits the current interface.   |
| â‘? |  Title   | Displays the calibration action, e.g., "One Step Forward Block."   |
| â‘? |  Previous Offset   |  Shows the last configured offset value.   |
| â‘? | â€?-â€? |  Decreases the current offset value by one unit per click.   |
| â‘? |  "Forward Test"   | Click to realize the control of the Boxy Robot forward further |
| â‘? |  "Backward Test"   | Click to realize the control of the Boxy Robot to take a step back |
| â‘? |  "Left Turn Test"   | Click to realize the control of the Boxy Robot to turn left 90Â° |
| â‘? |  "Right Turn Test"   | Click to realize the control of the Boxy Robot to turn right 90Â° |
| â‘? |  "Reset to Factory"   | Resets the Boxy Robot's offset values to factory defaults.   |
| â‘? |  Offset Input Field   | Opens a soft keyboard for direct input of offset values.   |
| â‘? | â€?+â€? | Increases the current offset value by one unit per click.   |
| â‘? |  Unit   | Shows the unit of the offset value, such as millimeters or degrees.   |
| â‘? |  "Save Data"   | Saves the current offset configuration to the Boxy Robot.   |


## Coding Board Debugging Interface  
![](https://cdn.nlark.com/yuque/0/2024/png/42947223/1732868691578-b1dba378-7113-43ac-bbf8-9c03b3673146.png)

|  No.   |  Name   | Description |
| :---: | :---: | :---: |
| â‘? | Data Display   | Displays the block information attached to the coding board via magnets.   |
| â‘? |  Simulation   | Highlights the simulation button red when the start button is pressed.   |


# Boxy Robot Debugging and Calibration Steps  
To calibrate or debug the ICBlocks Boxy Robot using the ICBlocks Calibration and debugging tool, follow these steps:

## Connecting Devices to Software  
Long press the Boxy Robot's power button to turn it on.  

![](https://cdn.nlark.com/yuque/0/2024/gif/42947223/1732959934482-77ac9286-71eb-424f-9230-6e8962c10941.gif)

<font style="color:#DF2A3F;"></font>

<font style="color:#DF2A3F;"></font>

Open the ICBlocks Calibration Debugging Tool and click "Boxy Robot Debugging" or "Boxy Robot Calibration" on the Home Interface. Select the device name from the device list on the Bluetooth Connection Interface to connect.  

![](https://cdn.nlark.com/yuque/0/2024/gif/42947223/1732961500394-48b7d00f-1110-4c51-8381-c78241a953e6.gif)

<font style="color:#DF2A3F;"></font>

__**Note**_: Ensure Bluetooth and Location permissions are enabled for the software.  _

## Boxy Robot Debugging  
Click "Boxy Robot Debugging Mode" on the Home Interface to enter the debugging interface.  

### Check the connected blocks
In the "Boxy Robot Debugging Interface," click the "Start Debugging". Then attach an orange or blue block to the corresponding magnetic interface on the Boxy Robot. The "Data Display Area" will show relevant information about the attached block, including its original ID, block name, and signal value.

If an orange block is attached to the blue interface of the Boxy Robot, the block name displayed in the corresponding position within the software will show as "undefined."

![](https://cdn.nlark.com/yuque/0/2024/gif/42947223/1732966234511-09cc818f-46f4-4426-b5bb-d3e662903c32.gif)



When the motor of the Boxy Robot moves, the area of the upper and lower wheels in the "Boxy Robot Debugging Interface" - "Data Display Area" will feed back the motion data and status (speed/blocking, etc.).

![](https://cdn.nlark.com/yuque/0/2024/gif/42947223/1732871006476-91cb6f2c-7b70-4732-928a-b9e3a89760a9.gif)

### Controlling the Boxy Robot to Execute Actions  
Click the buttons in the "Coding Block Debug " and "Actuator Block Debug" to make the Boxy Robot execute the corresponding commands immediately.  

## Calibrating the Precision of the Boxy Robot Motor Movements  
On the "Home Interface," click the "Boxy Robot Calibration" button to enter the "Boxy Robot Calibration Interface."  

In the "Boxy Robot Calibration Interface," click the "Forward Test" button to check whether the Boxy Robot moves forward by 12.8 cm (or the desired distance). If the distance is not as required, modify the value in the "Offset Input Field" and click Save to reset the offset.  

![](https://cdn.nlark.com/yuque/0/2024/gif/42947223/1732966352127-e2315019-dc96-4d07-b487-804c4b84cf6a.gif)

<font style="color:#DF2A3F;"></font>

The method for adjusting the left/right 90Â° rotation offset (angle) is the same as above.

![](https://cdn.nlark.com/yuque/0/2024/gif/42947223/1732966446202-1113af61-8a2e-49c2-bf8d-9704c2162b3a.gif)

# Coding Board Debugging Method  
To calibrate the ICBlocks coding board using the ICBlocks Calibration and Debugging Tool, follow these steps:  

## Connecting the Device to the Software  
Press and hold the "Start" button on the coding board while also holding down the "Power" button to make the ICBlocks Calibration and Debugging Tool discover the device.  

![](https://cdn.nlark.com/yuque/0/2024/gif/42947223/1732959829643-bfd98513-9a9f-4453-bc5b-fcf7910ea558.gif)

<font style="color:#DF2A3F;"></font>

Open the ICBlocks Calibration and Debugging Tool. On the Software Home Page, click the "Coding Board Debugging Mode". In the Bluetooth Connection Interface, select the device name from the device list to establish a connection.  

![](https://cdn.nlark.com/yuque/0/2024/gif/42947223/1732966555569-b2da0deb-5cca-438b-b9d8-451e09c78847.gif)

## Coding Board Debugging  
On the Software Home Interface, click the "Coding Board Debugging Mode" to enter the "Coding Board Debugging Interface."  

In this interface, the status of the coding board is displayed in real-time, including attached blocks and whether the Start button is pressed.  

+ If a green block is attached, a green dashed frame will appear around the block information in the corresponding position on the interface.
+ If an orange block is attached, an orange dashed frame will appear around the block information.
+ Blue blocks are not compatible with the coding board.

![](https://cdn.nlark.com/yuque/0/2024/gif/42947223/1732966912226-04dcbe2a-5498-4304-b9c3-3bd9160e0c8a.gif)

<font style="color:#DF2A3F;"></font>







