# CarND-Controls-PID
Self-Driving Car Engineer Nanodegree Program

## Term 2 Project 4
# PID Control Steering 

In this project I used the lake race track from the Behavioral Cloning Project(As recommended by Udacity). 
This time, however, I implement a PID controller in C++ to maneuver the vehicle around the track!

The simulator provided me the cross track error (CTE) and the velocity (mph) in order to compute the appropriate steering angle.

The tuning of Kp, Ki and Kd was followed with many inputs from Project Lessons, Peers taking the classes and Project Overview vide by David Silver.

The final succesfully implemented parameters are as following 

* Kp = -0.20;
* Ki = -0.0001;
* Kd = -4.0;

### PID Control implementation to compute steering angle of car using Cross Track Error.

The goals for the PID control project are :

1. Implement PID Controller initialization, updateError and totalError method in PID.cpp
2. Implement PID Control based steering of car in main.cpp
3. Tuning Kp, Ki and Kd such that car stays in middle of track and drive through the lap.
4. To increase the speed as much as possible by tuning the controller parameters.

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./pid`. 

## Project Instructions and Rubric

Note: regardless of the changes you make, your project must be buildable using
cmake and make!

* [Rubric](https://review.udacity.com/#!/rubrics/824/view)

## Reflection

[Project Reflection](./ProjectReflection.md)
