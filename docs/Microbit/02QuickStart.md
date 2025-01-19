# QuickStart

<font style="color:rgb(13, 13, 13);">This tutorial helps you quickly get started with the </font>**<font style="color:rgb(13, 13, 13);">micro: bit Smart Hub</font>**<font style="color:rgb(13, 13, 13);"> and guides you through application development with a practical example. In this example, we will show how to control the fan and the red LED using button presses.</font>

+ **Press the button**<font style="color:rgb(13, 13, 13);">: The fan starts, and the red LED lights up.</font>
+ **Release the button**<font style="color:rgb(13, 13, 13);">: The fan stops, and the red LED turns off.</font>

## <font style="color:rgb(42, 43, 46);">Hardware Preparation</font>
| ![](https://cdn.nlark.com/yuque/0/2024/png/46964359/1732779929854-8b7ea493-4c94-41e3-ba62-00fcafc0de35.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774693000-5ed8ac88-9a90-49a5-b836-86bf43830b0a.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732935365054-cd1638a6-6542-4fa6-a1a9-ca557b65aedc.png) |
| :---: | :---: | :---: |
| micro: bit Smart Hub×1 | Button Sensor×1 | Grove Cables ×3 |
| ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732775308880-371fd7e5-3268-4230-b827-8b95fec56dbc.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732774019528-f03d8a4c-9d0f-4e1c-ba33-424315265d95.png) |  |
| Fan Module×1 | Red LED Module×1 |  |


### <font style="color:rgb(13, 13, 13);">Power on the micro: bit Smart Hub</font>
![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732930320288-5d5a3714-4b58-4c40-886d-d622ffe11ae6.png)![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732930307278-1f895509-968a-4fe8-9347-207d97740016.png)![](https://cdn.nlark.com/yuque/0/2024/png/26790072/1732930336910-e2c05e8c-2d67-462a-8ca0-d4436dab8e44.png)



<font style="color:rgb(13, 13, 13);">Press and hold the power button to turn on the device. Once powered up, check the battery status. The device has four indicator LEDs representing the following battery levels: 25%, 50%, 75%, and 100%. If only one LED is blinking, it indicates a low battery. In that case, use the micro USB cable to connect the device to a charger for recharging. All four LEDs will be solid when fully charged, indicating that the battery is full.</font>

### <font style="color:rgb(13, 13, 13);">Connect the Potentiometer, Fan, and Red LED Modules to the Smart Hub</font>
<font style="color:rgb(13, 13, 13);">When connecting, ensure that the Grove cables are connected correctly, paying attention to the orientation. These cables are designed to prevent reverse insertion, so ensure that they are fully plugged in with proper contact.</font>

![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732932117157-107dd6c4-c66e-4490-8fe8-99a2b14fb89b.png)



<font style="color:rgb(13, 13, 13);">At this point, the hardware </font><font style="color:rgb(42, 43, 46);">Preparation</font><font style="color:rgb(13, 13, 13);"> for the quick start example is complete. Now, let’s proceed with coding the </font>**<font style="color:rgb(13, 13, 13);">micro: bit Smart Hub</font>**<font style="color:rgb(13, 13, 13);">.</font>  


## <font style="color:rgb(26, 26, 26);"></font><font style="color:rgb(13, 13, 13);">Software </font><font style="color:rgb(42, 43, 46);">Preparation</font>
<font style="color:rgb(13, 13, 13);"></font>**<font style="color:rgb(13, 13, 13);">Get the Software</font>**<font style="color:rgb(13, 13, 13);">The </font>**<font style="color:rgb(13, 13, 13);">micro: bit Smart Hub</font>**<font style="color:rgb(13, 13, 13);"> is based on the micro: bit</font><font style="color:rgb(13, 13, 13);"> core board, and any software supporting micro: bit</font><font style="color:rgb(13, 13, 13);"> can be used for programming. This tutorial uses </font>**<font style="color:rgb(13, 13, 13);">Microsoft MakeCode for micro: bit</font>**<font style="color:rgb(13, 13, 13);">.</font>

### **Get the Software**
<font style="color:rgb(13, 13, 13);">You can use the programming software in two ways: online through the </font>[cloud platform](https://makecode.microbit.org/#editor)<font style="color:rgb(13, 13, 13);">, or by downloading and installing the </font>[offline software](https://makecode.microbit.org/offline-app)<font style="color:rgb(13, 13, 13);">. In this tutorial, we will use the online programming platform.</font>

<font style="color:rgb(13, 13, 13);">Click the link above to access the online programming platform, where you will see the main interface as shown below.</font>



![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732776711832-ff36cfac-9fdb-4fc9-89b8-1d036e86842c.png)



### **<font style="color:rgb(13, 13, 13);">Get the Extension</font>**
<font style="color:rgb(13, 13, 13);">The </font>**<font style="color:rgb(13, 13, 13);">MakeCode</font>**<font style="color:rgb(13, 13, 13);"> coding platform has a dedicated </font>**<font style="color:rgb(13, 13, 13);">Microbit extension</font>**<font style="color:rgb(13, 13, 13);"> for the </font>**<font style="color:rgb(13, 13, 13);">micro: bit Smart Hub</font>**<font style="color:rgb(13, 13, 13);">. You can add this extension to both the online and offline versions of the platform. Click </font>[here](https://www.icrobot.com/www/cn/index.html#/file/index?type1=%E8%BD%AF%E4%BB%B6%E8%B5%84%E6%96%99&type2=micro%EF%BC%9Abit)<font style="color:rgb(13, 13, 13);"> to download the latest version of the </font>**<font style="color:rgb(13, 13, 13);">Microbit extension</font>**<font style="color:rgb(13, 13, 13);">, and extract it to your computer.</font>

### **<font style="color:rgb(13, 13, 13);">Add the Extension</font>**
<font style="color:rgb(13, 13, 13);">Follow the steps below to add the </font>**<font style="color:rgb(13, 13, 13);">Microbit extension</font>**<font style="color:rgb(13, 13, 13);"> to the </font>**<font style="color:rgb(13, 13, 13);">MakeCode</font>**<font style="color:rgb(13, 13, 13);"> platform:</font>

**<font style="color:rgb(13, 13, 13);">Step 1:</font>**

![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732795214379-bdbdeaf9-f66f-40e5-9f5b-3e580316dd9c.png)

**<font style="color:rgb(13, 13, 13);">Step 2:</font>**

![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732779216307-93f2315d-d2ce-4b5e-beed-8a79192e274b.png)

**<font style="color:rgb(13, 13, 13);">Step 3:</font>**

![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732780026838-503d56af-075e-48ac-b812-e9b58963dd60.png)

**<font style="color:rgb(13, 13, 13);">Step 4:</font>**

![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732780285605-1c026fbf-9a4c-4be1-b38d-233fed3af474.png)

**<font style="color:rgb(13, 13, 13);">Step 5:</font>**

![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732780441787-e1c0420c-213e-4072-934a-be32ba699da3.png)

The overall process for adding an extension is as follows:

![](https://cdn.nlark.com/yuque/0/2024/gif/43021412/1732781080116-5b9a81fd-f662-4e94-8add-f6ff5168e626.gif)

<font style="color:rgb(13, 13, 13);">Once you’ve completed these steps, the extension will be successfully added.</font>



### <font style="color:rgb(13, 13, 13);">Start Coding</font>
<font style="color:rgb(13, 13, 13);">Now let’s write a sample program on the programming platform.</font>

![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732788837055-ce31df12-e9ec-4e9c-b5c5-fd5c3c0fe92f.png)

<font style="color:rgb(13, 13, 13);">This program will allow the fan and the red LED to turn on when the button is pressed, and turn off when the button is released.</font>



<font style="color:rgb(13, 13, 13);">The coding process is as follows:</font>

![](https://cdn.nlark.com/yuque/0/2024/gif/43021412/1732790215789-df5bdb41-314c-43cc-a97e-a36c1b319212.gif)



## <font style="color:rgb(26, 26, 26);">Program Download</font>
Now you can connect the hub to your computer and download the program

**Step 1**<font style="color:rgb(13, 13, 13);">: Use a microUSB cable to connect the hub to your computer.</font>

![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732954995103-b799cad1-5338-442e-b28e-abbf569fc50c.png)

**Step 2**<font style="color:rgb(13, 13, 13);">: Connect the device on the coding platform and download the program</font>

![](https://cdn.nlark.com/yuque/0/2024/gif/43021412/1732793468339-bf3c5f5a-05e8-405e-979a-695df9fd25fc.gif)



<font style="color:rgb(13, 13, 13);">Notes:</font>

<font style="color:rgb(13, 13, 13);">Sometimes, due to an unstable USB connection, the download may fail. As shown below, the left side shows a successful download, while the right side shows a failed download. If the download fails, the program will be saved as a </font>`**<font style="color:rgb(13, 13, 13);">.hex</font>**`<font style="color:rgb(13, 13, 13);"> file on your computer. In case of failure, please reconnect the USB cable between the computer and the hub, and repeat Step 2.</font>

| ![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732794189545-bd101e44-a164-40cf-83cd-8ac34d8a0299.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/43021412/1732794036653-8f051977-c599-4fe0-a20c-cc69d7aef352.png) |
| :---: | :---: |
| **Successful Download**<font style="color:rgb(13, 13, 13);">: When the message “Downloaded” appears.</font> | **Failed Download**<font style="color:rgb(13, 13, 13);">: When the message “Download Complete” appears, and the file is saved to your computer via the browser.</font> |


## <font style="color:rgb(13, 13, 13);">Run the Program</font>
![](https://cdn.nlark.com/yuque/0/2024/gif/43021412/1732933092305-c5a38d83-3b78-4e00-a620-b9b04b1ef913.gif)

