# Feature Overview
## Direct Control Mode  
![](https://cdn.nlark.com/yuque/0/2024/png/51021329/1732780550951-c7a83f28-adf7-4405-9db2-0f857d6c1e1d.png)

The direct control function does not require programming; actuators can be easily controlled via the hub. Users can directly operate actuators connected to different ports by using the up, down, left, and right buttons. Ports 2, 4, 6, and 8 can connect various actuators, offering convenient operation.  

### The Hub Controls Servo Motor   
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732950644055-ea115f13-b01d-4492-a3fe-1dfde686b0ed.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732951427063-2f288a93-4151-4fb5-b196-429df62ea322.gif) |
| --- | --- |
| Motor connected to Ports 2 and 4:  <br/>+ **Up button:** Controls motor reverse rotation.<br/>+ **Down button: **Controls the motor's clockwise rotation. | Motor connected to Ports 6 and 8:<br/>+ **Left button:** Controls motor reverse rotation.<br/>+ **Right button:** Controls the motor's clockwise rotation. |


### The Hub Controls Touch Color LED Sensor
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732951506014-21850bbe-bb77-4d49-a035-075467d04bc3.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732951594792-a8772808-a55e-41f8-a0cc-7d6a1af4f763.gif) |
| --- | --- |
| LED connected to Ports 2 and 4:  <br/>**Up or Down button:** Toggles the LED module on or off.   | LED connected to Ports 6 and 8:<br/>+ **Left or Right button:** Toggles the LED module on or off.   |


## Logic Control Mode
![](https://cdn.nlark.com/yuque/0/2024/png/51021329/1732783730980-018e363d-4cce-40a4-9b1c-19a1e78194c3.png)

The logic control function requires no programming and allows actuators to be controlled effortlessly through various sensors. In this mode, input and output devices must be connected to paired symmetrical ports (e.g., Port 1 for input and Port 2 for output, or vice versa).  

### Encoder Sensor  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732951978580-bd38a493-53f5-421c-98cd-0be72c6c9622.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732952647446-a87432c7-bd63-4613-a74c-1b12265085f9.gif) |
| --- | --- |
| Clockwise rotation: Controls the servo motor's forward rotation.  <br/> Counterclockwise rotation: Controls the servo motor's reverse rotation. <br/>Rotation angle: Adjusts the servo motor's speed.  <br/>Button press: Stops the servo motor. | Button press: Toggles the LED module on/off.   In the "light on" state:<br/>+ Clockwise rotation increases LED brightness.<br/>+ Counterclockwise rotation decreases LED brightness. |


### Gyroscope Sensor  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732952366868-183d6d50-c0c4-41e8-8415-3e36c89cc9f1.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732952933960-04261531-35cf-4ed2-9e60-762b005e132d.gif) |
| --- | --- |
| Horizontal position: Stops the servo motor.<br/>Tilting forward: Controls forward motor rotation.<br/>Tilting backward: Controls reverse motor rotation.<br/>Tilt angle: Adjusts motor speed (greater tilt = higher speed).<br/>Forward/backward tilt: Adjusts LED brightness (greater tilt = brighter LED). | Forward/backward tilt: Adjusts LED brightness (greater tilt = brighter LED).   |


### Distance Sensor  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732952819667-149f5ea7-b39c-4eaf-a7a6-771415311c73.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732952842998-ff444381-bd9d-4516-843c-4875631314ad.gif) |
| --- | --- |
| Detects object proximity to control motor speed and direction.<br/>Closer objects: Faster motor speed, clockwise rotation. | By detecting the distance, you can control the brightness of the color LED sensor, the closer the distance, the higher the brightness. |


### Sound Sensor  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732952361352-939b9c98-0c88-432e-8668-833d547d3591.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732952099633-c3dd97e9-8bf0-4e38-808a-e4739904f3f2.gif) |
| --- | --- |
| Detects sound to trigger:<br/>Servo motor: Rotates clockwise for 1s. | Detects sound to trigger:<br/> LED sensor: Lights up for 5s.   |


### Multifunction Gesture Recognition Sensor  
| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732952384995-ed8e59d2-353f-4b07-8bfd-1ee466f2c1f5.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732953010489-302429d7-057e-443a-a1e2-04fcd21b9bac.gif) |
| --- | --- |
| Controls Servo Motor:       <br/>Left-to-right gesture: Clockwise rotation.<br/>Right-to-left gesture: Counterclockwise rotation.<br/>Upward/downward gesture: Stops the motor. | Controls LED Sensor:  <br/>Left-to-right gesture: Turns the LED on.<br/>Right-to-left gesture: Turns the LED off.<br/>Downward gesture: Turns the LED on.<br/>Upward gesture: Turns the LED off. |


## Logic Restriction Mode  
![](https://cdn.nlark.com/yuque/0/2024/png/51021329/1732859110344-6e46ff3d-644d-4a0c-af54-91b7abcd78ea.png)

This mode disables all intelligent functions (direct and logic control), leaving only basic hardware capabilities. It is useful for limiting device behavior, hardware testing, or specific use cases.  

**Activation:**

+ Press and hold the “Power Button,” then press the “Down Button.” A purple breathing light indicates successful activation.

**Deactivation:**

+ Press and hold the “Power Button,” then press the “Down Button” again.

Activation and deactivation require holding the buttons for over 3s. Otherwise, the device will shut down, exiting the mode automatically.

| ![](https://cdn.nlark.com/yuque/0/2024/gif/42941758/1732971560565-a94d17e5-8ec3-4f1e-8bac-eada1393d9c5.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/42941758/1732971616915-ede0fe10-75d6-4197-ad36-7d27ab6865d6.gif) |
| :---: | :---: |
| **Activation** | **Deactivation ** |


## Programming Control Mode  
ICBricks offers various programming options to suit users of different skill levels, from beginners to advanced users, ensuring an enjoyable and fulfilling learning experience.  

### ICBricks Mobile Programming Mode  
![](https://cdn.nlark.com/yuque/0/2024/jpeg/51021329/1732796116209-ed8b539c-39c0-450d-887c-310854077603.jpeg)

The ICBricks programming software is a mobile graphical programming platform designed for the ICBricks 2.0 Core set. Compatible with Android and iOS devices, it supports sensor and actuator control, Bluetooth remote control, and multiple programming modes, offering a rich programming experience.  

| ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732953128832-f01a9fe3-f911-4d8c-8c01-014f1258c397.gif) | ![](https://cdn.nlark.com/yuque/0/2024/gif/51021329/1732953305665-15c12bf0-c66e-482c-96a2-4178b7fd179f.gif) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
|                     **Beginner Version**                     |                     **Advanced Version**                     |


For detailed instructions, refer to the [ICBricks Mobile Programming Software Guide](https://www.yuque.com/crystal-vzc6k/cfl3ix/xk5zklboqd93ngc7).  

### ICrobot-Scratch Programming Mode  
ICrobot-Scratch software is also compatible with ICBricks 2.0, providing an intuitive graphical programming interface for PC. Based on Scratch, it enables users to interact with hardware devices and the stage area, seamlessly integrating software and hardware.  

 ![](https://cdn.nlark.com/yuque/0/2024/gif/42941758/1732968885530-6ebe5088-359f-4c25-8893-9230565723a4.gif)

For detailed instructions, refer to the [ICrobot-Scratch Programming Software Guide. ](https://www.yuque.com/crystal-vzc6k/cfl3ix/ua0wdq84izd143s5) 

### MicroBlocks Programming Mode  
MicroBlocks is a real-time programming environment designed for rapid development and experimentation. Users can immediately run programs on the hub by simply clicking blocks, receiving instant feedback. This highly interactive environment makes programming intuitive, fast, and engaging. ICBricks 2.0 is fully compatible with MicroBlocks, allowing users to design control logic, operate hardware in real-time, and unleash creativity and flexibility.  

![](https://cdn.nlark.com/yuque/0/2024/gif/42941758/1732950849326-47a1ce5b-30b3-4632-b580-ae899606b619.gif)

For detailed instructions, refer to the [MicroBlocks Programming Software Guide.  ](https://www.yuque.com/crystal-vzc6k/cfl3ix/ab43ctvaa0k7uzfg)

