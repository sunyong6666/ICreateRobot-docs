# Feature Overview
## Direct Control Mode  
![](img/featureoverview01.png)

The direct control function does not require programming; actuators can be easily controlled via the hub. Users can directly operate actuators connected to different ports by using the up, down, left, and right buttons. Ports 2, 4, 6, and 8 can connect various actuators, offering convenient operation.  

### The Hub Controls Servo Motor   
| ![](img/featureoverview02.gif) | ![](img/featureoverview03.gif) |
| --- | --- |
| Motor connected to Ports 2 and 4:  <br/>+ **Up button:** Controls motor reverse rotation.<br/>+ **Down button: **Controls the motor's clockwise rotation. | Motor connected to Ports 6 and 8:<br/>+ **Left button:** Controls motor reverse rotation.<br/>+ **Right button:** Controls the motor's clockwise rotation. |


### The Hub Controls Touch Color LED Sensor
| ![]img/featureoverview04.gif) | ![](img/featureoverview05.gif) |
| --- | --- |
| LED connected to Ports 2 and 4:  <br/>**Up or Down button:** Toggles the LED module on or off.   | LED connected to Ports 6 and 8:<br/>+ **Left or Right button:** Toggles the LED module on or off.   |


## Logic Control Mode
![](img/featureoverview06.png)

The logic control function requires no programming and allows actuators to be controlled effortlessly through various sensors. In this mode, input and output devices must be connected to paired symmetrical ports (e.g., Port 1 for input and Port 2 for output, or vice versa).  

### Encoder Sensor  
| ![](img/featureoverview07.gif) | ![](img/featureoverview08.gif) |
| --- | --- |
| Clockwise rotation: Controls the servo motor's forward rotation.  <br/> Counterclockwise rotation: Controls the servo motor's reverse rotation. <br/>Rotation angle: Adjusts the servo motor's speed.  <br/>Button press: Stops the servo motor. | Button press: Toggles the LED module on/off.   In the "light on" state:<br/>+ Clockwise rotation increases LED brightness.<br/>+ Counterclockwise rotation decreases LED brightness. |


### Gyroscope Sensor  
| ![](img/featureoverview09.gif) | ![](img/featureoverview10.gif) |
| --- | --- |
| Horizontal position: Stops the servo motor.<br/>Tilting forward: Controls forward motor rotation.<br/>Tilting backward: Controls reverse motor rotation.<br/>Tilt angle: Adjusts motor speed (greater tilt = higher speed).<br/>Forward/backward tilt: Adjusts LED brightness (greater tilt = brighter LED). | Forward/backward tilt: Adjusts LED brightness (greater tilt = brighter LED).   |


### Distance Sensor  
| ![](img/featureoverview11.gif) | ![](img/featureoverview12.gif) |
| --- | --- |
| Detects object proximity to control motor speed and direction.<br/>Closer objects: Faster motor speed, clockwise rotation. | By detecting the distance, you can control the brightness of the color LED sensor, the closer the distance, the higher the brightness. |


### Sound Sensor  
| ![](img/featureoverview13.gif) | ![](img/featureoverview14.gif) |
| --- | --- |
| Detects sound to trigger:<br/>Servo motor: Rotates clockwise for 1s. | Detects sound to trigger:<br/> LED sensor: Lights up for 5s.   |


### Multifunction Gesture Recognition Sensor  
| ![](img/featureoverview15.gif) | ![](img/featureoverview16.gif) |
| --- | --- |
| Controls Servo Motor:       <br/>Left-to-right gesture: Clockwise rotation.<br/>Right-to-left gesture: Counterclockwise rotation.<br/>Upward/downward gesture: Stops the motor. | Controls LED Sensor:  <br/>Left-to-right gesture: Turns the LED on.<br/>Right-to-left gesture: Turns the LED off.<br/>Downward gesture: Turns the LED on.<br/>Upward gesture: Turns the LED off. |


## Logic Restriction Mode  
![](img/featureoverview17.png)

This mode disables all intelligent functions (direct and logic control), leaving only basic hardware capabilities. It is useful for limiting device behavior, hardware testing, or specific use cases.  

**Activation:**

+ Press and hold the “Power Button,” then press the “Down Button.” A purple breathing light indicates successful activation.

**Deactivation:**

+ Press and hold the “Power Button,” then press the “Down Button” again.

Activation and deactivation require holding the buttons for over 3s. Otherwise, the device will shut down, exiting the mode automatically.

| ![](img/featureoverview18.gif) | ![](img/featureoverview19.gif) |
| :---: | :---: |
| **Activation** | **Deactivation ** |


## Programming Control Mode  
ICBricks offers various programming options to suit users of different skill levels, from beginners to advanced users, ensuring an enjoyable and fulfilling learning experience.  

### ICBricks Mobile Programming Mode  
![](img/featureoverview20.jpeg)

The ICBricks programming software is a mobile graphical programming platform designed for the ICBricks 2.0 Core set. Compatible with Android and iOS devices, it supports sensor and actuator control, Bluetooth remote control, and multiple programming modes, offering a rich programming experience.  

| ![](img/featureoverview21.gif) | ![](img/featureoverview22.gif) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
|                     **Beginner Version**                     |                     **Advanced Version**                     |


For detailed instructions, refer to the [ICBricks Mobile Programming Software Guide](https://www.yuque.com/crystal-vzc6k/cfl3ix/xk5zklboqd93ngc7).  

### ICrobot-Scratch Programming Mode  
ICrobot-Scratch software is also compatible with ICBricks 2.0, providing an intuitive graphical programming interface for PC. Based on Scratch, it enables users to interact with hardware devices and the stage area, seamlessly integrating software and hardware.  

 ![](img/featureoverview23.gif)

For detailed instructions, refer to the [ICrobot-Scratch Programming Software Guide. ](https://www.yuque.com/crystal-vzc6k/cfl3ix/ua0wdq84izd143s5) 

### MicroBlocks Programming Mode  
MicroBlocks is a real-time programming environment designed for rapid development and experimentation. Users can immediately run programs on the hub by simply clicking blocks, receiving instant feedback. This highly interactive environment makes programming intuitive, fast, and engaging. ICBricks 2.0 is fully compatible with MicroBlocks, allowing users to design control logic, operate hardware in real-time, and unleash creativity and flexibility.  

![](img/featureoverview24.gif)

For detailed instructions, refer to the [MicroBlocks Programming Software Guide.  ](https://www.yuque.com/crystal-vzc6k/cfl3ix/ab43ctvaa0k7uzfg)

