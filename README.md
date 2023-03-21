# Ball-Balancing-using-PID-controler


The goal of this project is to build a model-based PID ball balancing system using Arduino UNO and MATLAB Simulink. The system is fairly straightforward. The way this system functions is that it should sense the position of the ball on a track by using the ultrasonic sensor. A subtraction operation between the set point, center of the track used, and the value read by the ultrasonic sensor produces the error distance. The error distance of the ball is then fed into the Proportional-Integral-Derivative (PID) Controller which then signals the servo motor that is placed under the track to move either up or down in order to balance the ball and bring it back to the center of the track.

![My Image](picture1.png)

