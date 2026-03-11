# ICQbot Xiao Q Robot

## Method 1  

 Preparation  

1. Software:  
    1.  Download the CH340 driver:  ：[https://www.wch.cn/download/CH341SER_EXE.html/](https://www.wch.cn/download/CH341SER_EXE.html)
        1. Linux ：[https://www.wch.cn/download/CH341SER_LINUX_ZIP.html/](https://www.wch.cn/download/CH341SER_LINUX_ZIP.html)
        2. Android ：[https://www.wch.cn/download/CH341SER_ANDROID_ZIP.html/](https://www.wch.cn/download/CH341SER_ANDROID_ZIP.html)
        3. MAC ：[https://www.wch.cn/downloads/CH34XSER_MAC_ZIP.html/](https://www.wch.cn/downloads/CH34XSER_MAC_ZIP.html)
    2. Firmware Upgrade Platform：[https://update.icrobot.cn/](https://update.icrobot.cn/)
2.  Hardware  

| ![](img/ICQbotXiaoQRobot01.png) | ![](img/ICQbotXiaoQRobot02.png) | ![](img/ICQbotXiaoQRobot03.png) | ![](img/ICQbotXiaoQRobot04.png) |
| :---: | :---: | :---: | :---: |
| ICLink 2.0 Upgrade Tool x1  | USB-C Data Cables x2  | ICQbot Xiao Q Robot ×1  |  Android Tablet ×1 / iOS Tablet ×1  |


Steps:  

| ![](img/ICQbotXiaoQRobot05.GIF) | ![](img/ICQbotXiaoQRobot06.gif) |
| --- | --- |
| <font style="color:rgb(0, 0, 0);">①</font><font style="color:rgb(31, 31, 31);">Toggle the switch on the </font>**ICLink 2.0**<font style="color:rgb(31, 31, 31);"> to the </font>**SWD/Forward**<font style="color:rgb(31, 31, 31);"> position.  </font> | <font style="color:rgb(0, 0, 0);">②</font>Use cables to connect the Xiao Q Robot, ICLink 2.0, and PC.   |
| ![](img/ICQbotXiaoQRobot07.GIF) | ![](img/ICQbotXiaoQRobot08.GIF) |
| <font style="color:rgb(0, 0, 0);">③</font>Ensure the Xiao Q Robot’s status light is on.   | <font style="color:rgb(0, 0, 0);">④</font>Open the firmware upgrade platform, select “ICQbot,” and the desired firmware.   |
| ![](img/ICQbotXiaoQRobot09.GIF) | ![](img/ICQbotXiaoQRobot10.GIF) |
| <font style="color:rgb(0, 0, 0);">⑤</font>Click “Connect Device,” select the appropriate COM port, and establish a connection.  ① | <font style="color:rgb(0, 0, 0);">⑥</font>Click “Upgrade” to start the process.   |
| ![](img/ICQbotXiaoQRobot11.gif) | ![](img/ICQbotXiaoQRobot12.gif) |
| <font style="color:rgb(0, 0, 0);">⑦When the ICLink 2.0 blue LED stops blinking, the upgrade is complete.  </font> | <font style="color:rgb(0, 0, 0);">⑧Test the upgraded Xiao Q Robot by reconnecting to the tablet via Bluetooth.  </font> |
| ![](img/ICQbotXiaoQRobot13.GIF) | <font style="color:rgb(0, 0, 0);"></font> |
| <font style="color:rgb(0, 0, 0);">⑨Confirm the upgraded firmware version in the app.  </font> | <font style="color:rgb(0, 0, 0);"></font> |


*①：If the COM port is unavailable or the connection fails, try reinserting the cable.  

*Special statement: Only Android tablet software version 2.4.7 and above, and iOS tablet software software version * and above support to view the main controller firmware version

---

##  Method 2  
Preparation  

1. Software:  
    1.  Download firmware from the I Create Robot website. [https://www.icrobot.com/www/cn/index.html#/file/index?type1=%E8%BD%AF%E4%BB%B6%E8%B5%84%E6%96%99](https://www.icrobot.com/www/cn/index.html#/file/index?type1=%E8%BD%AF%E4%BB%B6%E8%B5%84%E6%96%99)
2. Hardware:  

| ![](img/ICQbotXiaoQRobot14.png) | ![](img/ICQbotXiaoQRobot15.png) | ![](img/ICQbotXiaoQRobot16.png) | ![](img/ICQbotXiaoQRobot17.png) |
| :---: | :---: | :---: | :---: |
| ICLink 1.0 Upgrade Tool x1 | USB-C Data Cables x2  | ICQbot Xiao Q Robot ×1  |  Android Tablet ×1 / iOS Tablet ×1 |


Steps:  

| ![](img/ICQbotXiaoQRobot18.gif) | ![](img/ICQbotXiaoQRobot19.GIF) |
| --- | --- |
| <font style="color:rgb(0, 0, 0);">①</font><font style="color:rgb(31, 31, 31);">Connect the </font>**ICLink 1.0**<font style="color:rgb(31, 31, 31);"> to the Xiao  Q Robot using the USB-C cable, then connect the ICLink 1.0 to your PC via USB.  </font> | <font style="color:rgb(0, 0, 0);">②</font>Ensure a new “ICRobot” drive appears in the file explorer with a file named `DETAILS.TXT`.  （②） |
| ![](img/ICQbotXiaoQRobot20.GIF) | ![](img/ICQbotXiaoQRobot21.GIF) |
| <font style="color:rgb(0, 0, 0);">③</font>Log on to the official website> Information download> Find the latest version ICQbot firmware> Click to download | <font style="color:rgb(0, 0, 0);">④</font>Copy and paste the `.bin` file into the “ICRobot” drive.   |
| ![](img/ICQbotXiaoQRobot22.GIF) | ![](img/ICQbotXiaoQRobot23.GIF) |
| <font style="color:rgb(0, 0, 0);">⑤Reconnect the upgraded Xiao Q Robot to the tablet via Bluetooth.  </font> | <font style="color:rgb(0, 0, 0);">⑥Confirm the upgraded firmware version in the app.  </font> |


*②：If a `FAIL.TXT` file appears, reconnect the cable securely.  

*_Special Notice_: Only Android app version 2.4.7+ and iPad app version *+ support firmware version display.  

