# Motor Driver L298N
This is a python program to control two DC motors with a L298N H-Bridge motor driver.
### Project Homepage
The project homepage with many pictures of my Raspberry Pi robots is as follows:
https://custom-build-robots.com/
## Module L298NHBridge.py
The L298NHBridge.py module has to be imported into your python program to control the two DC motors. The L298NHBridge.py offers the functionality to set the direction and speed of each motor independently. I used a Raspberry Pi and a L298N H-Bridge for my setup. With the RobotControl.py program the speed and direction of the DC motors is set via the keyboard.
### Raspberry Pi robot
![Raspberry Pi robots](https://custom-build-robots.com/wp-content/uploads/2016/04/Robot-with-Mecanum-Wheels-1-768x576.jpg)

The picture belows shows a typical L298N H-Bridge. With the ENA, IN1, IN2, IN3, IN4 and ENB the motor driver board is connected with the Raspberry Pi GPIO pins.
![L298N H-Bridge](https://custom-build-robots.com/wp-content/uploads/2015/12/motor_controller_led-768x825.jpg)
