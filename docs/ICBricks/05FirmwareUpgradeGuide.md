# Firmware Upgrade Guide
## ICBricks Hub Firmware Upgrade  
### Method 1:   
Using the Firmware Upgrade Center: [https://update.icrobot.cn/](https://update.icrobot.cn/)

| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732953465762-148f5b7f-f2ca-4fb2-8e4b-0217153387f4.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732957007952-7b87bd0e-d08e-4117-b60b-9c81c23b8320.gif) |
| --- | --- |
| 1、Open the ICBricks section, click on the hub version, and select the desired firmware version to upgrade.   | 2、Prepare a data download cable and connect the hub to your computer.   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732953741375-9b2d7256-f4c6-4ee0-93f0-97574e9d219d.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732954041396-8037b506-9187-47f3-998d-efa1cb2f5490.gif) |
| 3、Click "Connect," select the appropriate serial port in the pop-up window, and close it after a successful connection.   | 4、Click "Upgrade" and wait for the progress bar to complete. Restart the device after the upgrade finishes.   |


### Method 2:  
 Using the Flash Tool  Download Link:  [https://www.icrobot.com/www/cn/index.html#/file/index?type2=ICBricks](https://www.icrobot.com/www/cn/index.html#/file/index?type2=ICBricks)

| ![](https://cdn.nlark.com/yuque/0/2024/gif/43021771/1714198328249-f3ecd7a1-da17-4052-9121-d5e2a514829b.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/43021771/1714198353490-73255d10-dd87-4021-8c67-4733406ee3ae.gif) |
| --- | --- |
| 1、<font style="color:rgb(44, 44, 54);"></font>Connect the hub to your computer and open the flash tool. Select **ESP32** and click “OK.”   | 2、Click the end of the text box to select the desired firmware `.bin` file. Enter "0" in the sector text box, check the box, select the corresponding port at the bottom right, and click "START" to begin the download.   |
| ![](https://cdn.nlark.com/yuque/0/2024/png/43021771/1714198367302-7cbccb21-21e0-4db7-82cc-f8355cacaa26.png?x-oss-process=image%2Fformat%2Cwebp%2Fresize%2Cw_455%2Climit_0) |  |
| 3、Once the progress bar completes, and the green indicator changes to a blue completion mark without any red error messages, the download is successful.   |  |


## Servo Motor Firmware Upgrade  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732958680869-2fab2518-eb5f-4c17-aa98-853a32a6ad79.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732966624337-ef7479a6-a3a0-4acc-84b5-77cee1cb4699.gif) |
| --- | --- |
| 1、<font style="color:rgb(44, 44, 54);">Prepare an </font>IC-Link 2.0 Flasher<font style="color:rgb(44, 44, 54);">, switch the </font>SWD toggle<font style="color:rgb(44, 44, 54);"> to the right side and the </font>Normal/Reverse toggle<font style="color:rgb(44, 44, 54);"> to the left side.  </font> | 2、<font style="color:rgb(44, 44, 54);">Use a </font>grove cable<font style="color:rgb(44, 44, 54);"> to connect the servo motor to the </font>J1 port<font style="color:rgb(44, 44, 54);"> of the Link Flasher, then connect the Link Flasher to your computer.  </font> |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732959046988-d99eaee8-1648-49ba-8d1b-4546e4058447.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732877256197-15b26c30-75bb-4e86-bd37-0109108ae8f8.gif) |
| 3、Long-press the motor’s center button while briefly pressing the reset button on the Link Flasher. The motor indicator light will switch to a rainbow mode.   | 4、<font style="color:rgb(44, 44, 54);">Open the Firmware Upgrade Center, select the servo motor, and choose the firmware version to upgrade.  </font> |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732959197563-7a670bfb-e92a-436e-a437-f25c562ea205.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732959592891-fa8adacf-e243-4a01-beef-cf3ceb87b2cd.gif) |
| 5、<font style="color:rgb(44, 44, 54);">Click "Connect," select the motor's serial port, and close it after a successful connection.  </font> | 6、Click "Upgrade" and wait for the progress bar to complete.   |


