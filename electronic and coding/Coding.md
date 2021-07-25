#### Introduction

In this document, you are going to read about how to write code and what's our code this year about. 

#### Writing code

To write your code, you should first find out the function you want in the documentation.

https://robotpy.readthedocs.io/en/stable/guide/index.html

This link is the documentation(python) for you to read, and this is the one we are mainly using now. For some exception you meet when using the function, you may go to the CTRE or rev package file to check.

https://docs.wpilib.org/en/stable/

This link is the documentation(Java) we used before, and it is more mature than the former one. You can check this link if you can't find anything useful in the former one. There are also many example code you would like to read in this link.

After finding the function, you would like to initualize a variable in the robotInit part, and then define a function for something you want to attain.



#### Code 2021(without CV)

Our code is devided into following part drivetrain, solenoid, intake, rotater, shooter, hook, and climber. Each of these functions are devided in one or two groups. 

In the drivetrain, we have two Neo on the either sides in the back, so we put two Neo on the same side into a group and use arcade drive in the DifferentialDrive module to manipulate them.

Solenoid is the function that we define to extend or retract the in take part. Their are two solenoids used and they are on and off in the same time.

Intake controls the rolling of the intake stick, and it can both rolling positive and negative.

Rotater controls the turntable in the middle part of the robot to send ball to the shooter. It can be either on or off.

Shooter controls the shooting module in the robot. It can be either on to shoot the ball or off.

Hook controls the tape in the robot which will help send the rope onto the stick. It can be either on to extend or off to retract to tight the rope.

Climber controls the rope to extend or retract same as the hook..

There are also two document called constants and MotorConstants which contains the constant in the code to make it easier to modify



