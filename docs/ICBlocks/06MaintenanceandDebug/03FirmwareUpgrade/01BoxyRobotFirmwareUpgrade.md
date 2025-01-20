# Boxy Robot Firmware Upgrade
## Online Upgrade  
### Preparation  
1. Upgrade website: [https://update.icrobot.cn/](https://update.icrobot.cn/)  
_(Recommended browsers: Chrome or Microsoft Edge)_
2. Hardware Preparation  

| ![](img/BoxyRobotFirmwareUpgrade01.png) | ![](img/BoxyRobotFirmwareUpgrade02.png) | ![](img/BoxyRobotFirmwareUpgrade03.png) |
| --- | :---: | :---: |
| ICBlocks  Boxy Robot x1   |  USB-C Data Cables x2   |  ICLink 2.0 Upgrade Tool x1   |


### Upgrade Steps  
| ![](img/BoxyRobotFirmwareUpgrade0304.gif) | ![](img/BoxyRobotFirmwareUpgrade04.gif) |
| --- | --- |
| â‘?<font style="color:rgb(31, 31, 31);">Toggle the switch on the </font>**ICLink 2.0**<font style="color:rgb(31, 31, 31);"> to the </font>**SWD/Forward**<font style="color:rgb(31, 31, 31);"> position.  </font> | â‘?<font style="color:rgb(31, 31, 31);">Connect the ICLink 2.0 to the Boxy Robot using one Type-C cable, then connect the ICLink 2.0 to your PC via USB using the second USB-C cable.  </font> |
| ![](img/BoxyRobotFirmwareUpgrade05.gif) | ![](img/BoxyRobotFirmwareUpgrade06.png) |
| â‘¢Once connected, the Boxy Robot's indicator light will show a charging status.   | â‘£Open the firmware upgrade platform in **Chrome** or **Microsoft Edge**, and select the **ICBlocks Series** from the left panel.   |
| ![](img/BoxyRobotFirmwareUpgrade07.gif) | ![](img/BoxyRobotFirmwareUpgrade08.gif) |
| â‘¤Locate the **Boxy Robot** on the right panel. Expand the dropdown list to view available firmware upgrades.   | â‘¥Click **"Connect Device"**. If no device is detected, check the connections or ensure the steps above were correctly followed. Once connected, select the device.   |
| ![](img/BoxyRobotFirmwareUpgrade09.gif) | ![](img/BoxyRobotFirmwareUpgrade10.gif) |
| â‘¦Click **"Upgrade"** and wait for the page to display **"Upgrade Successful."** Observe the blue indicator light on the ICLink 2.0 for confirmation of completion.   | â‘§Connect the upgraded Boxy Robot to the ICBlocks Calibration and Debugging Tool.   |
| ![](img/BoxyRobotFirmwareUpgrade11.png) |  |
| â‘? On the **Home Interface** of the software, check the **device connection status** at the bottom to verify the firmware version. Firmware versions below **2.8.3** do not support software version checking.   |  |


## Local Upgrade  
### Preparation  
1.  Software Preparation
2. Firmware download link: [[Click Here](https://www.icrobot.com/www/cn/index.html#/file/index?type1=%E8%BD%AF%E4%BB%B6%E8%B5%84%E6%96%99&type2=ICBlocks)]  
3.  Hardware Preparation  

| ![](img/BoxyRobotFirmwareUpgrade12.png) | ![](img/BoxyRobotFirmwareUpgrade13.png) | ![](img/BoxyRobotFirmwareUpgrade14.png) |
| --- | :---: | :---: |
| ICBlocks  Boxy Robot x1   |  USB-C Data Cable x1   | ICLink 1.0 Upgrade Tool x1 |


### Upgrade Steps  
| ![](img/BoxyRobotFirmwareUpgrade15.gif) | ![](img/BoxyRobotFirmwareUpgrade16.png) |
| --- | --- |
| â‘? <font style="color:rgb(31, 31, 31);">Connect the </font>**ICLink 1.0**<font style="color:rgb(31, 31, 31);"> to the Boxy Robot using the USB-C cable, then connect the ICLink 1.0 to your PC via USB.  </font> | â‘?<font style="color:rgb(31, 31, 31);"> Open </font>**File Explorer**<font style="color:rgb(31, 31, 31);"> and check for a drive labeled </font>**"ICRobot."** |
| ![](img/BoxyRobotFirmwareUpgrade17.gif) | ![](img/BoxyRobotFirmwareUpgrade18.gif) |
| â‘? <font style="color:rgb(31, 31, 31);">Use your browser to navigate to the company website and download the desired firmware.  </font> | â‘£Extract the downloaded ZIP file and copy the firmware file to the **"ICRobot"** drive. Ensure the drive contains only the **"DETAILS.TXT"** file. If a **"FAIL.TXT"** file appears, reconnect the ICLink 1.0 to the USB port and repeat the process.   |
| ![](img/BoxyRobotFirmwareUpgrade19.gif) | ![](img/BoxyRobotFirmwareUpgrade20.gif) |
| â‘? Wait for the copying to complete and observe the green indicator light on the ICLink 1.0 for confirmation of completion.   | â‘? Connect the upgraded Boxy Robot to the ICBlocks Calibration and Debugging Tool.   |
| ![](img/BoxyRobotFirmwareUpgrade21.png) |  |
| â‘¦On the **Home Interface** of the software, check the **device connection status** at the bottom to verify the firmware version. Firmware versions below **2.8.3** do not support software version checking.   |  |




