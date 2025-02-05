# Calculating-the-needed-torque-for-robot-arm-s-motors.
Calculating the needed torque for each motor in the robot arm.

The arm of the robot:

![image](https://github.com/user-attachments/assets/9597a823-f18a-4ad9-99f4-ffe5da8ef318)

The required task:
![image](https://github.com/user-attachments/assets/e2201960-b6e7-4529-b35e-1a5423c4b70d)




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

2) 
First motor (base - includes the entire arm)
Joint 1, d1 = 0.15 + 0.10 + 0.04 = 0.29 m
= 9.81 × 0.29 = 2.845 N.m


Second motor (middle joint - includes only the front part)
Joint 2, d2 = 0.10 + 0.04 = 0.14 m
= 9.81 × 0.14 = 1.375 N.m


Third motor (end of the arm - includes only the gripper)
Joint 3, d3 = 0.04 m
= 9.81 × 0.04 = 0.392 N.m

_________________________________________________________________________________________________

Based on the calculated torques, the following motors are recommended:

For Joint 1, d1 (Base): Select a motor with a torque rating greater than ( 2.845 Nm ).

For Joint 2, d2 (Middle): Select a motor with a torque rating greater than ( 1.375 Nm ). 

For Joint 3, d3 (End-Effector): Select a motor with a torque rating greater than ( 0.392 Nm ).

For Joint 3: Consider the MG996R Servo Motor and for Joints 1 and 2: Choose higher-torque motors based on the calculated requirements.


Companies and Websites to Buy Motors:

---> https://www.amazon.com/s?k=MG996R  , 

---> https://www.amazon.com/s?k=high+torque+servo+motor
