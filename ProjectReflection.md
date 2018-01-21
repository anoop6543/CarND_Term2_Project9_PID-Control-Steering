Reflection


Kp (Proportional gain):

1. Proportional gain guides the car to steer to inwards the lane which proportinates to the crosstrack error
2. Might cause overshoot and/or oscillation

Kd (Derivative gain):
 
1. Tuning derivative gain reduces the overshoting and oscillation

Ki (Integral gain) :
1. Tuning Integral gain guides the vehicle to steer into the path though there is bias.

The final Kp, Ki and Kd values for choosen using the Trial and error method. Due to time constraints complicated methods of tuning was not followed for project submission. After the Project submission, I'll do research on using twiddle method for tuning the parameters with more research on the tuning method.


Tuning Iterations

| Trial  | P(Kp)         | I(Ki)           | D(Kd)           |
|:------:|:-------------:|:---------------:|:---------------:| 
| 1      | **-1**        | **0**           | **0**           | 
| 2      | *-0.5*        | 0               | -0.5            | 
| 3      | *-0.25*       | 0.0001          | -1.0            | 
| 4      | -0.25         | *-0.01*         | -1.0            | 
| 5      | -0.10         | *0.0001*        | -3.0            | 
| 6      | **-0.20**     | **0.0001**      | **-4.0**        | 
| 7      | -0.40         | 0.0001          | -7.0            | 

Some of the iteration values noted down during the tuning has been mentioned in the above table.
Around 16 to 18 Iterations have been done by constantly adjusting one parameter by keeping other two constant.

For the tuning parameters mentioned in the 7th row, the oscillations are not getting reduced though Kd has been increased to a higher value.

The main motto while tuning the parameters was to steer the vehicle to make it stay on the road though some deviations occur. 

David Silvers Project Overview video has helped me follow thr right process using trial and error method. 