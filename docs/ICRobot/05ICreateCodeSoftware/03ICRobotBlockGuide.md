# ICRobot Block Guide
## Motion
### Robot (moves forward、moves backward、turns left、turns light) at ( ) % power
![](img/B1.png)

Controls the robot to move in the specified direction with the given power.

Example:

![](img/B2.png)



### Robot (moves forward、moves backward、turns left、turns light) at ( ) % power ( ) Seconds
![](img/B3.png)

Controls the robot to move in the specified direction with a given power for a certain number of seconds. This is a blocking block.

Example:

![](img/B4.png)



### Robot (moves forward、moves backward、turns left、turns light) at ( ) % power for ( ) cm
![](img/B5.png)

Controls the robot to move in the specified direction with a given power for a specified distance. This is a blocking block.

Example:

![](img/B6.png)

### Robot (moves forward、moves backward、turns left、turns light) at ( ) % power for () degrees until done
![](img/B7.png)



Controls the robot to turn left or right with the specified power until the target angle is reached. This is a blocking block.

Example:

![](img/B8.png)

### Robot's left wheel rotates at ( ) % power, right wheel rotates at ( ) % power
![](img/B9.png)

Independently control the power of the left and right wheels.

Example:

![](img/B10.png)

### Robot's motor (left wheel / right wheel) with ( )% power for ( ) (Seconds / cm)
![](img/B11.png)

Controls a single wheel to move with the specified power for a given time or distance.

Example:

![](img/B12.png)



### Robot's motor (left wheel / right wheel) rotates at ( ) % power indefinitely
![](img/B13.png)

Continuously control a single wheel to move with the specified power.

Example:

![](img/B14.png)



### Stop Movement
![](img/B15.png)

Stop the robot's motion.

## Display (Matrix LED)
### Set display brightness to (1–10)
![](img/B16.png)

Set the display brightness of the robot's dot-matrix screen, the value is 1-10, the larger the value the brighter it is.

Example:

 ![](img/B17.png)

### (Static / Right to Left / Left to Right / Top to Bottom / Bottom to Top) Display () for () seconds
![](img/B18.png)

Setting the static or dynamic display of the set dots for a given length of time

Example:

![](img/B19.png)

### (Static / Right to Left / Left to Right / Top to Bottom / Bottom to Top) Display ( )
![](img/B20.png)

Set static or dynamic display of a given dot matrix all the time

Example:

![](img/B21.png)

### Display Text ()
![](img/B22.png)

Display a text string on the matrix; if the string exceeds the matrix width, it scrolls; otherwise, it displays statically.

Example:

![](img/B23.png)

### Light up x() y()
![](img/B24.png)

Turn on the LED at coordinate (x, y); (0, 0) is bottom-left.

Example:

![](img/B25.png)

### Only light up x() y()
![](img/B26.png)

Light up only the LED at (x, y), turning off all others.

Example:

![](img/B27.png)

### Turn off x() y()
![](img/B28.png)

Turn off the LED at coordinate (x, y).

Example:

![](img/B29.png)

### Toggle x() y()
![](img/B30.png)

Switch the LED at (x, y) between on and off.

Example:

![](img/B31.png)

### Set tail light color（）
![](img/B32.png)

Change the tail light to a selected color.

Example:

![](img/B33.png)

### Set tail light color to R() G() B()
![](img/B34.png)

Set RGB values for the tail light.

Example:

![](img/B35.png)

### Turn off display
![](img/B36.png)

Turn off the matrix display.

Example:

![](img/B37.png)

## Audio
### Upload Audio File
![](img/B38.png)

Choose and upload a custom audio file, and assign a filename.

![](img/B39.png)

### Set volume to ()
![](img/B40.png)

Set playback volume (range: 0–10).

### Play music () until finished
![](img/B41.png)

Play selected audio file; wait until it finishes before continuing the next action.

Example:

![](img/B42.png)

### Play music ()
![](img/B43.png)

Play the selected audio file immediately.

Example:

![](img/B44.png)

### Stop playback
![](img/B45.png)

Stop the current audio.

### () Play local audio ()
![](img/B46.png)

Play an uploaded audio file in real-time.

Example:

![](img/B47.png)

## Actuators
### Robot's gripper at port ( ) (open/close)
![](img/B48.png)

ontrol the gripper at the selected port.

Example:

![](img/B49.png)

### Robot's gripper at port ( ) (open/close) until done
![](img/B50.png)

Control the gripper and wait until action completes before next step.

Example:

![](img/B51.png)

### Robot's launcher at port ( ) shoots (number) ball
![](img/B52.png)

Launch specified number of marbles from selected port.

Example:

![](img/B53.png)

### Robot's launcher at port ( ) shoots ( ) ball until done
![](img/B54.png)

Launch and wait until finished before proceeding.

Example:

![](img/B55.png)

## Sensors
### Button (A/B) pressed
![](img/B56.png)

Detect if left or right button is pressed.

Example:

![](img/B57.png)

### Sound（）（）
![](img/B58.png)

Check if detected sound is greater/less than/equal to a value.

Example:

![](img/B59.png)

### Current sound level
![](img/B60.png)

Return the detected sound level.

Example:

![](img/B61.png)

### Current battery level
![](img/B62.png)

Return remaining battery.

Example:

![](img/B63.png)

### （）current speed
![](img/B64.png)

Get current speed of each wheel.

Example:

![](img/B65.png)

### Privacy switch status
![](img/B66.png)

Return status of privacy switch.

Example:

![](img/B67.png)

### （）movement distance
![](img/B68.png)

Return the movement distance.

Example:

![](img/B69.png)

### Set line-following sensor to () mode
![](img/B70.png)

Choose binary/gray/color  mode.

Example:

![](img/B71.png)

### Run Line Following Sensor Binary Learning
![](img/B72.png)

Set Line Following Sensor to binary mode learning.

Example:

![](img/B73.png)

### Run  Line Following Sensor Learning () Colour
![](img/B74.png)

Learn a specific color.

Example:

![](img/B75.png)

### Value detected by the roving sensor probe ( )
![](img/B76.png)

Get value from probe (L1, L2, M, R2, R1).

Example:

![](img/B77.png)

### Line Following probe () detects ()
![](img/B78.png)

Check if probe detects specific color.

Example:

![](img/B79.png)

### Line Following probe () value () ()
![](img/B80.png)

Whether the detected value is greater than/less than/equal to the specified value

Example:

![](img/B81.png)

### Turn off Line Following sensor
![](img/B82.png)

Disable Turn off Line Following sensor.

Example:

![](img/B83.png)

### Start auto line following at () speed
![](img/B84.png)

Allow robots to automatically patrol lines at low/medium/high speeds

Example:

![](img/B85.png)

### Start auto line following at () speed until state is ()
![](img/B86.png)

Controls the robot to start auto-touring at low/medium/high speeds until the value of the five probes is the set value and then stops auto-touring.

Example:

![](img/B87.png)

### Stop auto line following
![](img/B88.png)

Stop line-following behavior.

Example:

![](img/B89.png)


