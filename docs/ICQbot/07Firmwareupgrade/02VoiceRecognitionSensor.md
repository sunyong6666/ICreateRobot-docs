# Voice Recognition Sensor

## Voice Recognition Sensor Firmware Upgrade

Preparation  

1. Software:  
    1.  Download the CH340 driver: 
            1. Windows：[https://www.wch.cn/download/CH341SER_EXE.html/](https://www.wch.cn/download/CH341SER_EXE.html)
            2. Linux：[https://www.wch.cn/download/CH341SER_LINUX_ZIP.html/](https://www.wch.cn/download/CH341SER_LINUX_ZIP.html)
            3. Android：[https://www.wch.cn/download/CH341SER_ANDROID_ZIP.html/](https://www.wch.cn/download/CH341SER_ANDROID_ZIP.html)
            4. MAC：[https://www.wch.cn/downloads/CH34XSER_MAC_ZIP.html/](https://www.wch.cn/downloads/CH34XSER_MAC_ZIP.html)

        b.  Firmware Upgrade Platform：[https://update.icrobot.cn](https://update.icrobot.cn/)

2. Hardware: 

| ![](https://cdn.nlark.com/yuque/0/2024/png/21413468/1732931390830-7ff5b017-5b38-4d0d-a6aa-e0414baf66aa.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/21413468/1732884388071-29e8fcb4-c4c7-4a36-9906-42caf9efcb94.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/21413468/1732931332870-3943ba57-0af8-457d-9080-09cbd377ed74.png) | ![](https://cdn.nlark.com/yuque/0/2024/png/21413468/1732931348402-633b4072-3056-44d1-9156-4c3f7c072ce7.png) |
| :---: | :---: | :---: | :---: |
| ICLink 2.0 Upgrade Tool x1  | USB-C Data Cables x2  | ICQbot Xiao Q Robot ×1  |  Android Tablet ×1 / iOS Tablet ×1  |


Steps:  

| ![](https://cdn.nlark.com/yuque/0/2024/gif/21413468/1732875590211-9ec4e6a2-c437-4a75-b43b-83e55061c8dc.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/21413468/1732875655839-392214f9-c0dc-4ec6-96d8-aaedd9488436.gif) |
| :---: | :---: |
| <font style="color:rgb(0, 0, 0);">①</font>Confirm **ICLink 2.0** Switch: Set to UART / No distinction between forward and reverse sequence.   | <font style="color:rgb(0, 0, 0);">②</font>Use data cables to connect your computer, the voice recognition sensor, and ICLink 2.0. Once connected, the voice sensor will say: "I am Xiao Q, happy to serve you," indicating a successful connection.   |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/21413468/1732875626889-7e8cf551-91bf-411d-beb4-bc8432014076.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/21413468/1732875647096-3620a9b9-382f-4060-9438-08c5f87e8064.gif) |
| <font style="color:rgb(0, 0, 0);">③</font>Click on **ICQbot** and select the firmware to upgrade. Use the dropdown menu to view firmware details.   | <font style="color:rgb(0, 0, 0);">④</font>Click "Connect Device," then choose the corresponding **COM port** in the pop-up serial connection window（③） |
| ![](https://cdn.nlark.com/yuque/0/2024/gif/21413468/1732876365613-83b2b968-c77b-4639-aa56-add3c3d2ea04.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/21413468/1732877325352-4898a6b6-4c79-4a87-97e8-78bcc9a3c102.gif) |
| <font style="color:rgb(0, 0, 0);">⑤After connecting successfully, click the "Upgrade" button to start the process. Once the progress bar is complete, a prompt will indicate the upgrade is finished.  </font> | <font style="color:rgb(0, 0, 0);">⑥Connect the voice sensor to the Xiao Q Robot and test using voice commands like "Hello Xiao Q" or "Voice Version." If Xiao Q responds, "The current module voice version is V*.*," and it matches the upgraded version, the process is complete. </font> |


*③：If no COM port appears or the connection fails, try reinserting the data cable.  

