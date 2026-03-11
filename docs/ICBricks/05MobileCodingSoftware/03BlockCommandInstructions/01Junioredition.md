# Junior edition
## Yellow (Trigger Category)  
### When Program Starts  
![](img/J01.png)

When program start button is clicked, run the following building blocks

**Example**:  

![](img/J02.png)

 When the program starts, the motor rotates clockwise.  

### When Gyroscope Sensor ()  
![](img/J03.png)

Executes the following blocks when the gyroscope sensor tilts to a specified position.  

**Example**:

![](img/J04.png)

When the gyro sensor tilts left, the motor rotates clockwise; when it tilts right, the motor rotates counterclockwise.  

### When Gesture Sensor Detects ()
![](img/J05.png)

Executes the following blocks when the gesture sensor detects the specified gesture.  

**Example**:  

![](img/J06.png)

When the gesture sensor detects a "swipe left" gesture, the motor rotates clockwise.  

### When Encoder Sensor ()  
![](img/J07.png)

Executes the following blocks when the encoder sensor detects a specified action.  

Example:

![](img/J08.png)

When the encoder sensor rotates clockwise, the motor rotates clockwise.  

### When Sound Sensor Detectes ()
![](img/J09.png)

Executes the following blocks when the sound sensor detects sound levels above 80.  

Example:

![](img/J10.png)

When the sound sensor detects a sound, the motor rotates clockwise.  

### When Distance Sensor Detects ()  
![](img/J11.png)

Executes the following blocks when the distance sensor detects a specified range (close: n ≤ 5; medium: 5 < n ≤ 10; far: n > 10).  

Example:

![](img/J12.png)

When the distance sensor detects a close range, the motor rotates clockwise.  

### When Button () is Pressed  
![](img/J13.png)

Executes the following blocks when the specified button on the remote control is pressed.  

Example:

![](img/J14.png)

When the "Up" button is pressed, the motor rotates clockwise.  

## Blue (Motor Category)  
### Set Motor Speed to ()  
![](img/J15.png)

Sets the motor speed to the specified value (this block does not directly control motor movement).  

Example:

![](img/J16.png)

When the program starts, set the motor speed to high, and the motor rotates clockwise.  

### Motor () Rotates Clockwise  
![](img/J17.png)

Controls the selected port motor to rotate clockwise; if no port is selected, all ports are used by default. 

Example:

![](img/J18.png)

When the program starts, the motor rotates clockwise.  

### Motor () Rotates Counterclockwise  
![](img/J19.png)

Controls the selected port motor to rotate counterclockwise; if no port is selected, all ports are used by default.  

Example:

![](img/J20.png)

 When the program starts, the motor rotates counterclockwise.  

### Motor () Stops Rotating  
![](img/J21.png)

Stops the motor at the selected port; all ports are used by default if none are selected.  

Example:

![](img/J22.png)

When the "A" button is pressed, the motor rotates clockwise; when the "B" button is pressed, the motor stops.  

### Move Forward  
![](img/J23.png)

Controls the robot to move forward (requires two motors: left motor connected to Port 1, right motor connected to Port 2).  

Example:

![](img/J24.png)

When the program starts, the robot moves forward.  

### Move Backward  
![](img/J25.png)

Controls the robot to move backward (requires two motors: left motor connected to Port 1, right motor connected to Port 2).  

Example:

![](img/J26.png)

When the program starts, the robot moves backward.  

### Turn Left  
![](img/J27.png)

Controls the robot to turn left (requires two motors: left motor connected to Port 1, right motor connected to Port 2).  

Example:

![](img/J28.png)

When the program starts, the robot turns left.  

### Turn Right  
![](img/J29.png)

 Controls the robot to turn right (requires two motors: left motor connected to Port 1, right motor connected to Port 2).  

Example:

![](img/J30.png)

When the program starts, the robot turns right.  

### Stop  
![](img/J31.png)

Stops the robot's movement.  

Example:

![](img/J32.png)

When the "A" button is pressed, the robot moves forward; when the "B" button is pressed, the robot stops.  





## Purple (Lighting Category)  
### Set Touch LED Sensor to Color ()  
![](img/J33.png)

Sets the touch LED sensor to the selected color.  

Example:

![](img/J34.png)

When the program starts, the touch LED sensor lights up red.  

## Orange (Control Category)  
### Wait () Seconds  
![](img/J35.png)

Waits for the specified amount of time before executing the following blocks.  

Example:

![](img/J36.png)

When the program starts, wait 1 second, then the motor rotates clockwise.  

### Repeat () Times  
![](img/J37.png)

Repeats the enclosed program for the specified number of times (default is 4).  

Example:

![](img/J38.png)

When the program starts, wait 1 second, the motor rotates clockwise, wait 1 second again, and the motor stops. Repeat 4 times.  

### Repeat Continuously  
![](img/J39.png)

Continuously repeats the enclosed program.  

Example:

![](img/J40.png)

When the program starts, wait 1 second, the motor rotates clockwise, wait 1 second again, and the motor stops. Repeat infinitely.  

