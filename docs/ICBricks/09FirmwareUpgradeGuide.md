# Firmware Upgrade Guide
## ICBricks Hub Firmware Upgrade  
### Method 1:   
Using the Firmware Upgrade Center: [https://update.icrobot.cn/](https://update.icrobot.cn/)

| ![](img/FirmwareUpgradeGuide01.gif) | ![](img/FirmwareUpgradeGuide02,gif) |
| --- | --- |
| 1、Open the ICBricks section, click on the hub version, and select the desired firmware version to upgrade.   | 2、Prepare a data download cable and connect the hub to your computer.   |
| ![](img/FirmwareUpgradeGuide03.gif) | ![](img/FirmwareUpgradeGuide04.gif) |
| 3、Click "Connect," select the appropriate serial port in the pop-up window, and close it after a successful connection.   | 4、Click "Upgrade" and wait for the progress bar to complete. Restart the device after the upgrade finishes.   |


### Method 2:  
 Using the Flash Tool  Download Link:  [https://www.icrobot.com/www/cn/index.html#/file/index?type2=ICBricks](https://www.icrobot.com/www/cn/index.html#/file/index?type2=ICBricks)

| ![](img/FirmwareUpgradeGuide0401.gif) | ![](img/FirmwareUpgradeGuide0402.gif) |
| --- | --- |
| 1、<font style="color:rgb(44, 44, 54);"></font>Connect the hub to your computer and open the flash tool. Select **ESP32** and click “OK.”   | 2、Click the end of the text box to select the desired firmware `.bin` file. Enter "0" in the sector text box, check the box, select the corresponding port at the bottom right, and click "START" to begin the download.   |
| ![](img/FirmwareUpgradeGuide0403.png) |  |
| 3、Once the progress bar completes, and the green indicator changes to a blue completion mark without any red error messages, the download is successful.   |  |


## Servo Motor Firmware Upgrade  
| ![](img/FirmwareUpgradeGuide0502.gif) | ![](img.FirmwareUpgradeGuide0501.gif) |
| --- | --- |
| 1、<font style="color:rgb(44, 44, 54);">Prepare an </font>IC-Link 2.0 Flasher<font style="color:rgb(44, 44, 54);">, switch the </font>SWD toggle<font style="color:rgb(44, 44, 54);"> to the right side and the </font>Normal/Reverse toggle<font style="color:rgb(44, 44, 54);"> to the left side.  </font> | 2、<font style="color:rgb(44, 44, 54);">Use a </font>grove cable<font style="color:rgb(44, 44, 54);"> to connect the servo motor to the </font>J1 port<font style="color:rgb(44, 44, 54);"> of the Link Flasher, then connect the Link Flasher to your computer.  </font> |
| ![](img/FirmwareUpgradeGuide05.gif) | ![](img/FirmwareUpgradeGuide06.gif) |
| 3、Long-press the motor’s center button while briefly pressing the reset button on the Link Flasher. The motor indicator light will switch to a rainbow mode.   | 4、<font style="color:rgb(44, 44, 54);">Open the Firmware Upgrade Center, select the servo motor, and choose the firmware version to upgrade.  </font> |
| ![](img/FirmwareUpgradeGuide07.gif) | ![](img/FirmwareUpgradeGuide08.gif) |
| 5、<font style="color:rgb(44, 44, 54);">Click "Connect," select the motor's serial port, and close it after a successful connection.  </font> | 6、Click "Upgrade" and wait for the progress bar to complete.   |


