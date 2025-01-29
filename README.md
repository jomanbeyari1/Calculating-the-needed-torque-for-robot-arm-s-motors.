# Calculating-the-needed-torque-for-robot-arm-s-motors.
Calculating the needed torque for each motor in the robot arm.

The arm of the robot:

![image](https://github.com/user-attachments/assets/9597a823-f18a-4ad9-99f4-ffe5da8ef318)

The required task:
![image](https://github.com/user-attachments/assets/c1ce1511-ac21-4a6b-b999-624d8b1d569b)



Given Data:
Mass of the object: 1 kg
Length of the first arm: 10 cm = (0.1 m)
Length of the second arm: 15 cm = (0.15 m)
Distance from the motor to the center of mass: 4 cm = (0.04 m)

_________________________________________________________________________________________________

1) Calculate the Force:
To calculate the force due to weight:
Force = mass × g
---> g is the acceleration due to gravity (9.81 m/s^2):
Force = 1 kg × 9.81 m/s^2 = 9.81 N

__________________________________________________________________________________________________

2) Calculate the Torque:
Torque is calculated using the formula:
Torque = Force × Distance


a. Torque at the first motor:
The distance from the first motor to the center of mass is the length of the first arm (10 cm or 0.1 m): Torque(1) = 9.81 N × 0.1 m = 0.981 N\cdotpm


b. Torque at the second motor ---> Using the Distance to the Center of Mass: 
The distance from the second motor to the center of mass is the sum of the lengths of both arms (10 cm + 15 cm = 25 cm or 0.25 m):
Torque(2) = 9.81 N × 0.25 m = 2.4525 N\cdotpm

When Using the Distance from the Motor to the Point of Force Application:
If you use the distance from the second motor to the point of force application (which is 15 cm):
Torque(2) = 9.81 N × 0.15 m = 1.4715 N\cdotpm
_________________________________________________________________________________________________

The Results:
First motor: Required torque of at least 0.981 N·m
Second motor: Required torque of at least 2.4525 N·m
_________________________________________________________________________________________________

Companies and Websites to Buy Motors:
- ElectroCraft ---> https://www.electrocraft.com/
- Amazon ---> https://www.amazon.com/
- RobotShop ---> https://www.robotshop.com/
