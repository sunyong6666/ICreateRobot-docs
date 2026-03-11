# ICRobot Block Guide
## Motion
### Robot (moves forward、moves backward、turns left、turns light) at ( ) % power
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B1.png)

Controls the robot to move in the specified direction with the given power.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B2.png)



### Robot (moves forward、moves backward、turns left、turns light) at ( ) % power ( ) Seconds
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B3.png)

Controls the robot to move in the specified direction with a given power for a certain number of seconds. This is a blocking block.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B4.png)



### Robot (moves forward、moves backward、turns left、turns light) at ( ) % power for ( ) cm
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B5.png)

Controls the robot to move in the specified direction with a given power for a specified distance. This is a blocking block.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B6.png)

### Robot (turns left、turns light) at ( ) % power for () degrees until done
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B7.png)



Controls the robot to turn left or right with the specified power until the target angle is reached. This is a blocking block.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B8.png)

### Robot's left wheel rotates at ( ) % power, right wheel rotates at ( ) % power
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B9.png)

Independently control the power of the left and right wheels.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B10.png)

### Robot's motor (left wheel / right wheel) with ( )% power for ( ) (Seconds / cm)
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B11.png)

Controls a single wheel to move with the specified power for a given time or distance.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B12.png)



### Robot's motor (left wheel / right wheel) rotates at ( ) % power indefinitely
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B13.png)

Continuously control a single wheel to move with the specified power.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B14.png)



### Stop Movement
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B15.png)

Stop the robot's motion.

## Display (Matrix LED)
### Set display brightness to (1–10)
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B16.png)

Set the display brightness of the robot's dot-matrix screen, the value is 1-10, the larger the value the brighter it is.

Example:

 <!-- 这是一张图片，ocr 内容为： -->
![](IMG/B17.png)

### (Static / Right to Left / Left to Right / Top to Bottom / Bottom to Top) Display () for () seconds
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B18.png)

Setting the static or dynamic display of the set dots for a given length of time

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B19.png)

### (Static / Right to Left / Left to Right / Top to Bottom / Bottom to Top) Display ( )
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B20.png)

Set static or dynamic display of a given dot matrix all the time

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B21.png)

### Display Text ()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B22.png)

Display a text string on the matrix; if the string exceeds the matrix width, it scrolls; otherwise, it displays statically.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B23.png)

### Light up x() y()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B24.png)

Turn on the LED at coordinate (x, y); (0, 0) is bottom-left.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B25.png)

### Only light up x() y()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B26.png)

Light up only the LED at (x, y), turning off all others.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B27.png)

### Turn off x() y()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B28.png)

Turn off the LED at coordinate (x, y).

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B29.png)

### Toggle x() y()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B30.png)

Switch the LED at (x, y) between on and off.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B31.png)

### Set tail light color（）
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B32.png)

Change the tail light to a selected color.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B33.png)

### Set tail light color to R() G() B()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B34.png)

Set RGB values for the tail light.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B35.png)

### Turn off display
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B36.png)

Turn off the matrix display.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B37.png)

## Audio
### Upload Audio File
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B38.png)

Choose and upload a custom audio file, and assign a filename.

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B39.png)

### Set volume to ()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B40.png)

Set playback volume (range: 0–10).

### Play music () until finished
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B41.png)

Play selected audio file; wait until it finishes before continuing the next action.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B42.png)

### Play music ()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B43.png)

Play the selected audio file immediately.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B44.png)

### Stop playback
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B45.png)

Stop the current audio.

### () Play local audio ()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B46.png)

Play an uploaded audio file in real-time.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B47.png)

## Actuators
### Robot's gripper at port ( ) (open/close)
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B48.png)

ontrol the gripper at the selected port.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B49.png)

### Robot's gripper at port ( ) (open/close) until done
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B50.png)

Control the gripper and wait until action completes before next step.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B51.png)

### Robot's launcher at port ( ) shoots (number) ball
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B52.png)

Launch specified number of marbles from selected port.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B53.png)

### Robot's launcher at port ( ) shoots ( ) ball until done
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B54)

Launch and wait until finished before proceeding.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B55.png)

## Sensors
### Button (A/B) pressed
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B56.png)

Detect if left or right button is pressed.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B57.png)

### Sound（）（）
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B58.png)

Check if detected sound is greater/less than/equal to a value.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B59.png)

### Current sound level
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B60.png)

Return the detected sound level.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B61.png)

### Current battery level
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B62.png)

Return remaining battery.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B63.png)

### （）current speed
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B64.png)

Get current speed of each wheel.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B65.png)

### Privacy switch status
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B66.png)

Return status of privacy switch.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B67.png)

### （）movement distance
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B68.png)

Return the movement distance.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B69.png)

### Set line-following sensor to () mode
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B70.png)

Choose binary/gray/color  mode.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B71.png)

### Run Line Following Sensor Binary Learning
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B72.png)

Set Line Following Sensor to binary mode learning.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B73.png)

### Run  Line Following Sensor Learning () Colour
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B74.png)

Learn a specific color.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B75.png)

### Value detected by the roving sensor probe ( )
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B76.png)

Get value from probe (L1, L2, M, R2, R1).

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B77.png)

### Line Following probe () detects ()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B78.png)

Check if probe detects specific color.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B79.png)

### Line Following probe () value () ()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B80.png)

Whether the detected value is greater than/less than/equal to the specified value

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B81.png)

### Turn off Line Following sensor
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B82.png)

Disable Turn off Line Following sensor.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B83.png)

### Start auto line following at () speed
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B84.png)

Allow robots to automatically patrol lines at low/medium/high speeds

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B85.png)

### Start auto line following at () speed until state is ()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B86.png)

Controls the robot to start auto-touring at low/medium/high speeds until the value of the five probes is the set value and then stops auto-touring.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B87.png)

### Stop auto line following
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B88.png)

Stop line-following behavior.

Example:

<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B89.png)

## External Microbit Module
### Port () Servo rotates to () degrees
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B90.png)

Set servo rotation degree

### **Port ()** Set the servo motor to **()**
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B91.png)

Set servo motor mode

### **Port ()** Servo motor rotates at a speed of **()**
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B92.png)

Set motor rotation speed

### **Port ()** Servo motor rotates at a speed of **() for () seconds**
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B93.png)

 Set motor rotation speed and time

### Port () Servo motor rotates at speed **()** to **()** degrees  
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B94.png)

Set motor rotation speed and rotate to a fixed angle

### Port () servor motor rotates at speed () for () degrees
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B95.png)

Set motor rotation speed and angle

### Port () servor motor stop
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B96.png)

Set motor to stop rotation

### Port () Get current angle
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B97.png)

Get current angle

### **Port ()** Laser sensor set to **() **brightness **()**
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B98.png)

Set laser sensor brightness and switch state

### Port () fan runs at a speed of () ()
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B99.png)

Set fan speed and switch state

### Port（）（）（sensor）
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B100.png)

Set sensor switch state

### **Port ()** Detects joystick **()**
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B101.png)

Judge joystick state

### Port () Joystick () direction
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B102.png)

Get joystick X or Y direction value

### Port () Ultrasonic sensor distance
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B103.png)

Get ultrasonic sensor distance value

### **Port ()** Potentiometer
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B104.png)

Get potentiometer sensor value

### Port () Hall sensor
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B105.png)

Get Hall sensor value

### Port () PIR sensor
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/B106.png)

Get human infrared sensor value





