# Failure Analysis and Solution
## Boxy Robot
### **Issue:** The robot wobbles and is unstable during movement.  
 Solution:  

1. This issue usually occurs because the robot's base does not have an omnidirectional wheel installed or the wheel is installed in the wrong direction.  
2. **Correct Installation Direction:** Ensure the wheel is installed properly.  

![Correct Installation Direction](https://cdn.nlark.com/yuque/0/2024/png/50993910/1732958683728-27c2ff08-b238-408f-9ac0-e98ec7349b75.png)

### Issue: The top white casing of the Boxy Robot bulges.  
**Solution:**

+ This is likely due to battery damage causing the casing to swell.

### **Issue:** There is a rattling noise from inside the Boxy Robot.  
**Solution:**

+ The speed measurement raster cover inside the Boxy Robot may have come loose due to impact. This can cause a rattling noise.
+ The internal battery of the Boxy Robot may have detached.

### **Issue:** The Boxy Robot cannot move properly.  
**Solution:**

+ Check if the couplers on both sides of the Boxy Robot are cracked. If so, replace them or contact customer service for repairs.
+ Internal hardware damage may require factory repairs.

### **Issue:** Blocks connected to the Boxy Robot are not recognized.  
**Solution:**

+ The block may not be connected to the correct port. For logical control:
    - **Orange Ports:** Connect to sensors (orange blocks).
    - **Blue Ports:** Connect to actuators (blue blocks).
+ There may be debris on the magnetic ports of the Boxy Robot and block.
    - Clean the magnetic ports. Refer to the [Boxy Robot cleaning guide](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/tfkkew9bu0wl26a0/collaborator/join?token=rcDb7PrICdRx9fwl&source=doc_collaborator#%20„ÄäBoxy%20Robot%20Cleaning%20Steps„Ä?) for detailed methods.
+ The magnetic interface pins may be damaged.

## Coding Board
### **Issue:** The Boxy Robot does not execute programmed actions when the start button is pressed, despite a successful Bluetooth connection.  
**Solution:  **

1. The start button may become unresponsive over time. Use the [**ICBlocks Debug Tool**](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/stkanzgvwgry1ags/collaborator/join?token=p3oWga4Obp0fL2j7&source=doc_collaborator#%20„ÄäICBlocks%20Calibration%20and%20Debugging%20Tool%20Guide„Ä?) for the coding board control debugging. Refer to the debugging tool guide for details.
2. The coding block may not have been recognized.  
3. No actuator is connected to the Boxy Robot.  

### **Issue:** A single block in the program does not execute and skips to the next command.  
**Solution:**

1. The coding block may not have been recognized. Reconnect the block.
2. Clean the magnetic pins of the coding block. Refer to [the coding board cleaning guide](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/ax8cit9crtctxg8s/collaborator/join?token=dVGCRmsRckFsu3kn&source=doc_collaborator#%20„ÄäCoding%20Board%20Cleaning%20Steps„Ä?).  
3. The Coding board control firmware version problem, need to go to the firmware upgrade center for firmware upgrade. Refer to [the firmware update guide](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/sn1gzlp8eczwvmtg/collaborator/join?token=NJhFKsFmFvnJVNYm&source=doc_collaborator#%20„ÄäCoding%20Board%20Firmware%20Upgrade„Ä?).



## Motor Block  
### **Issue:** The motor does not rotate despite proper connections.  
 **Solution:**

1. The magnetic port of the motor may not be recognized. Clean the port. Refer to [the product maintenance guide.](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/fe1bgao7mx3v23mq/collaborator/join?token=WpjvwpAdoFI071uz&source=doc_collaborator#%20„ÄäÊ®°ÂùóÊ∏ÖÊ¥ÅÊ≠•È™§„??)
2. The motor cable may be internally broken and needs replacement.
3. Internal hardware damage requires repair through after-sales service.

### **Issue:** The motor rotates only in one direction and cannot reverse.  
**Solution:  **

1. Internal hardware damage requires repair through after-sales service.  
2. The motor may not have been recognized by the Boxy Robot. Reconnect the block.  

### **Issue:** The motor rotates normally but cannot adjust speed.  
**Solution:  **

1. Internal hardware damage requires repair through after-sales service.               

## ICRobot Multifunctional Bluetooth Controller  
### Issue: The controller cannot move the robot when the left or right joystick is pushed after connection.  
**SolutionÔº?**

1. Calibrate the joystick:  
    1. While powered on, press and hold the ‚Ä?-‚Ä? and ‚Ä?+‚Ä? buttons simultaneously. The Home button will flash blue, indicating debug mode.  
    2. Rotate the left and right joysticks in a 360¬∞ motion 3-4 times.  
    3.  Turn off the device.  
    4. Power it back on to resume normal functionality.  

### **Issue:** The robot moves abnormally after connecting the controller.  
**Solution:**

1. Calibrate the joystick following the above steps.

### **Issue:** The Bluetooth controller cannot connect to the robot.  
Solution:  

 If the controller has been paired with other devices, [reset the Bluetooth connection](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/mp6v4re934n0lqv3/collaborator/join?token=Zetdse7a4xle4h44&source=doc_collaborator#%20„ÄäBluetooth%20Controller%20Function„Ä?):

+ Switch to the correct mode if connected to other series devices.

### Debugger Installation and Device Connection  
    1. **Install the Mini RC Debugger Application:  **

Download and install the **Mini RC Debugger** software. [[Debugger Download Link](https://www.icrobot.com/www/cn/index.html#/file/index?type1=%E8%BD%AF%E4%BB%B6%E8%B5%84%E6%96%99&type2=ICRobot%E5%A4%9A%E5%8A%9F%E8%83%BD%E8%93%9D%E7%89%99%E6%89%8B%E6%9F%84)]  

                ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1732959149775-99c86408-1009-4a36-820f-786861e40908.png)

After installation, open the debugger. Use a USB-C cable to connect the controller to the computer's COM port.   Click "Connect Device" and select the corresponding COM port.   The controller will beep, and the Home button will flash continuously, indicating a successful connection. The initial program will appear at the top of the interface.  

     ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1732959177346-0bf7de4c-da9a-4ba5-9639-4b8da4bbedb6.png)

    2. **Set Controller Mode:  **

In the **Mini RC Debugger**, select the "ICBlocks" mode.   Click the "Set Type" button. The controller will beep again, indicating a successful mode switch.  

       ![](https://cdn.nlark.com/yuque/0/2024/png/50993910/1732961493503-01e94df0-646a-4db1-bae4-e21312a7a8a8.png)

    3. **Test Controller Performance:**

After switching modes, test various function buttons or joysticks. If the corresponding operations in the debugging tool match, the controller is functioning correctly.  

 ![](https://cdn.nlark.com/yuque/0/2024/gif/50993910/1732962868395-6bd7037f-706b-421e-8c3b-9d354e374e44.gif)

    4. **Reconnect Device:  **

Press and hold the "T" button for 3s. When the Home button displays blue, the Bluetooth connection is successful. Refer to the [Bluetooth connection guide](https://www.yuque.com/g/crystal-vzc6k/cfl3ix/mp6v4re934n0lqv3/collaborator/join?token=Zetdse7a4xle4h44&source=doc_collaborator#%20„ÄäBluetooth%20Controller%20Function„Ä?) for more details.  

