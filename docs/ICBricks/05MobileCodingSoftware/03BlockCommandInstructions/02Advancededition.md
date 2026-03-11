# Advanced edition
## Control
### Wait for ( ) second  / millisecond  
![](img/A01.png)

Execute the following program after waiting for a specified period of time. 

Example：

![](img/A02.png)

When the program starts, wait for 1 second, then turn the color LED module on port 1 to red.  

### Loop
![](img/A03.png)

Repeat the contained program.  

Example：

![](img/A04.png)

At program start, wait 1 second, turn the color LED on port 1 red. Wait another second, then turn it green. Repeat this cycle endlessly.  

### Repeat ( ) times  
![](img/A05.png)

Repeat the inner program block for a set number of times. Default is 3 times.  

Example：

![](img/A06.png)

When the program starts, wait 1 second, then set the color LED module on port 1 to red. Wait another 1 second, then set the color LED module on port 1 to green. Repeat this 3 times.  

###  if ( ) then ( )  
![](img/A07.png)

If the specified condition is true, then execute the contained program.  

Example：

![](img/A08.png)

On start, when a remote control button is pressed, turn the color LED on port 1 green.  

### if ( ) then ( ) else ( )  
![](img/A09.png)

If the specified condition is true, execute the contained program 1; otherwise, execute program 2.  

Example：

![](img/A10.png)

On start, if the remote control button is pressed, turn the color LED on port 1 green; else turn it red.  

### Exit loop  
![](img/A11.png)

Example：

![](img/A12.png)

On start, turn the color LED on port 1 blue. When the remote control button is pressed, turn it red.  

### Exit the program
![](img/A13.png)

 Example：

![](img/A14.png)

On start, turn the color LED on port 1 blue. When the remote control button is pressed, stop all programs.  

## Motor
### Read the angle of the servo motor on port ( ).  
![](img/A15.png)

Read the angle of the servo motor on the selected port.  

Example：

![](img/A16.png)

On start, run servo motor on port 1 clockwise at speed 50. If servo angle on port 1 > 360, stop all programs.  

### Run the servo motor on port ( ) at speed ( ) in ( ) direction.  
![](img/A17.png)

Run the servo motor on the selected port at the specified speed and direction.  

Example：

![](img/A18.png)

On start, run servo motor on port 1 clockwise at speed 50.  

### Run the servo motor on port ( ) at speed ( ) in ( ) direction for ( ) (revolutions/degrees/seconds).  
![](img/A19.png)

Run the servo motor on the selected port at the specified speed, direction, and unit.  

Example：

![](img/A20.png)

On start, run servo motor on port 1 clockwise at speed 50 for 1 rotation.  

### Set the current position of the servo motor on port ( ) to zero.  
Set the current position of the servo motor on the selected port to zero. This helps initialize the position for accurate control later.    

![](img/A21.png)

Example：

![](img/A22.png)

On start, set servo motor position on port 1 to zero, then run at speed 50 to 180°.  

### Run the servo motor on port ( ) at speed ( ) to ( ) degrees.  
![](img/A23.png)

Run the servo motor on the selected port at the specified speed to the target position, achieving precise positioning of the servo motor.  

Example：

![](img/A24.png)

On start, run servo motor on port 1 at speed 50 to 180°. Wait 1 second, then run at speed 50 to 0°.  

### Stop the servo motor on port ( ).  
![](img/A25.png)

Stop the servo motor on the selected port.  

Example：

![](img/A26.png)

On start, run servo motor on port 1 forward at speed 50. Wait 1 second, then stop it.

## Motion
### Set the running motor to ( ) and ( ).  
![](img/A27.png)

Set the running motor port(s). (Set dual motors)  

Example：

![](img/A28.png)

On start, run servo motors on ports 1 and 2 forward at speed 50.  

### Move ( ) running at ( ).  
![](img/A29.png)

Run the motors (default ports 1 and 2) at the specified speed and direction.

Example：

![](img/A30.png)

When the program starts, run the servo motors on ports 1 and 2 forward at speed 50.  

### Move ( ) running at ( ) for ( ) (rotation/degree/second).  
![](img/A31.png)

Run the motors (default ports 1 and 2) at the specified speed, direction, and unit.  

Example：

![](img/A32.png)

When the program starts, run the servo motors on ports 1 and 2 forward at speed 50 for 1 rotation.  

### Stop the motor on ( ).  
![](img/A33.png)

Stop the motors on default ports 1 and 2.  

Example：

![](img/A34.png)

On start, run servo motors on ports 1 and 2 forward at speed 50. Wait 1 second, then stop them.  

## Sensor
### Port ( ) compare distance to ( ).  
![](img/A35.png)

Check if the distance sensor value on specified port meets the condition compared to a given value.  

Example：

![](img/A36.png)

On start, if distance sensor on port 1 < 10, touch color LED on port 2 lights red; else lights green.  

### Port ( ) compare Sound to ( ).  
![](img/A37.png)

Check if sound sensor value on specified port meets a given condition compared to another value.  

Example：

![](img/A38.png)

On start, if sound sensor value on port 1 > 50, touch color LED on port 2 lights red; else lights green.  

### Port（）Encoder（）
![](img/A39.png)

Check whether the encoder sensor on the specified port is performing the specified motion.  

Example：

![](img/A40.png)

On start, if encoder sensor on port 1 rotates counterclockwise, touch color LED on port 2 lights red; else lights green.  

### Port（）Gyroscope Sensor（）
![](img/A41.png)

Check whether the gyroscope sensor on the specified port is performing the specified motion.  

Example：

![](img/A42.png)

On start, if the gyroscope sensor on port 1 tilts forward, touch color LED on port 2 lights red; else lights green.  

### Port（）Gesture Sensor（）
![](img/A43.png)

Check whether the gesture recognition sensor on the specified port is performing the specified gesture.

Example：

![](img/A44.png)

On start, if the gesture sensor on port 1 detects swipe up, touch color LED on port 2 lights red; else lights green.  

### Button ( ) on main controller is pressed.  
![](img/A45.png)

Check if the specified button on the main controller is pressed.  

Example：

![](img/A46.png)

On start, if main controller button pressed, touch color LED on port 2 lights red; else lights green.  

### Button ( ) on remote control is pressed.  
![](img/A47.png)

Check if the specified button on the remote control is pressed.  

Example：

![](img/A48.png)

When the program starts, the touch color LED module on port 2 lights up red only when a button on the remote control is pressed; otherwise, it lights up green.  

### Port（）Axis（）
![](img/A49.png)

Detect the tilting value of the gyroscope sensor on the specified port along the specified axis.  

示例：

![](img/A50.png)

When the program starts, the touch color LED module on port 2 lights up red only when the value of tilting the gyroscope sensor on port 1 around the X-axis is greater than 40; otherwise, it lights up green.  

### Port（）Encoder
![](img/A51.png)

Detect the value of the encoder sensor on the specified port.

Example：

![](img/A52.png)

When the program starts, the touch color LED module on port 2 lights up red only when the value detected by the encoder sensor on port 1 is greater than 100; otherwise, it lights up green.  

### Port（）Distance
![](img/A53.png)

Detect the value of the distance sensor on the specified port.  

Example：

![](img/A54.png)

When the program starts, the touch color LED module on port 2 lights up red only when the distance detected by the distance sensor on port 1 is greater than 10; otherwise, it lights up green.  

### Port（）Sound
![](img/A55.png)

Detect the value of the sound sensor on the specified port.  

Example：

![](img/A56.png)

When the program starts, the touch color LED module on port 2 lights up red only when the value detected by the sound sensor on port 1 is greater than 50; otherwise, it lights up green.  

## Light
### Touch LED Module Port（）is（）
![](img/A57.png)

Control the touch color LED module on the specified port to display the lighting effect in the specified color.   

Example：

![](img/A58.png)

When the program starts, the touch color LED module on port 1 lights up red.  

### Indicator Position（）is（）
![](img/A59.png)

Control the indicator light of the main controller at the specified location to display the lighting effect in the specified color.   

Example：

![](img/A60.png)

When the program starts, the indicator light of the main controller at the top-left corner lights up red.  

## Operator
### （）+（）
![](img/A61.png)

Perform addition operation.  

Example：

![](img/A62.png)

When the program starts, the servo motor on port 1 runs clockwise at a speed equal to the result of (30 + 20).  

### （）-（）
![](img/A63.png)

Perform subtraction operation.  

Example：

![](img/A64.png)

When the program starts, the servo motor on port 1 runs clockwise at a speed equal to the result of (100 - 50).  

### （）*（）
![](img/A65.png)

Perform multiplication operation.  

Example：

![](img/A66.png)

When the program starts, the servo motor on port 1 runs clockwise at a speed equal to the result of (25 * 2).  

### （）/（）
![](img/A67.png)

Perform division operation.  

Example：

![](img/A68.png)

When the program starts, the servo motor on port 1 runs clockwise at a speed equal to the result of (200 ÷ 4).  

### （）>（）
![](img/A69.png)

Determine whether the value of a specified parameter is greater than another specified value.  

Example：

![](img/A70.png)

When the program starts, the touch color LED module on port 2 lights up red only when the value detected by the sound sensor on port 1 is greater than 50; otherwise, it lights up green.

### （）<（）
![](img/A71.png)

Determine whether the value of a specified parameter is less than another specified value.  

Example：

![](img/A72.png)

When the program starts, the touch color LED module on port 2 lights up red only when the distance detected by the distance sensor on port 1 is less than 20; otherwise, it lights up green.  

### （）=（）
![](img/A73.png)

Determine whether the value of a specified parameter is equal to another specified value.  

Example：

![](img/A74.png)

When the program starts, the touch color LED module on port 2 lights up red only when the value detected by the encoder sensor on port 1 is equal to 0; otherwise, it lights up green.  

### （）and（）
![](img/A75.png)

Determine whether the two specified conditions are both true.  

Example：

![](img/A76.png)

When the program starts, the touch color LED module on port 2 lights up red only when the tilt sensor on port 1 detects a forward tilt and the tilt sensor on port 3 detects a backward tilt; otherwise, it lights up green.  

### （）or（）
![](img/A77.png)

Determine whether at least one of the two specified conditions is true.  

Example：

![](img/A78.png)

When the program starts, the touch color LED module on port 2 lights up red only when the tilt sensor on port 1 detects a forward tilt or the tilt sensor on port 3 detects a backward tilt; otherwise, it lights up green.  

###   not（）
![](img/A79.png)

Determine whether the specified condition is not true.  

Example：

![](img/A80.png)

When the program starts, the touch color LED module on port 2 lights up red only when the tilt sensor on port 1 does not detect a forward tilt; otherwise, it lights up green.  

###  Generate a random number between ( ) and ( )
![](img/A81.png)

Generate a random number within the specified range.  

Example：

![](img/A82.png)

When the program starts, the servo motor on port 1 runs clockwise at a speed of 50 and stops after running for a random number of seconds between 1 and 10.  

##  Variable
### Create a variable.  
Create a variable to use in the program. Notice that no operation blocks except the "Create variable" itself will appear in the "variable" category unless at least one variable has been created first. In other words, creating a variable is always the first step before using any variable-related functions. In this case, I created the variable named "test".

![](img/A83.png)

### Assign（）to（）
![](img/A84.png)

![](img/A85.png)

Set the variable to the specified number.  Notice that the input field comes from the "operator" category. 

Example：

![](img/A86.png)

When the program starts, the variable "test" is set to 100.  

###  Change / Increase () by ()
![](img/A87.png)

Increase the variable by the specified number.  

Example：

![](img/A88.png)

When the program starts, the variable "test" is set to 100, then after waiting for 1 second, the variable "test" is increased by 20.  Notice that the input field also accepts negative numbers, which represent a decrease.  

### Variable name
![](img/A89.png)

The name you set for your variable — here, I set the variable name as "test".  

Example：

![](img/A90.png)

When the program starts, the variable "test" is set to 100, and the servo motor on port 1 runs clockwise at the speed of variable "test".  



