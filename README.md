# Unscented Kalman Filter Project

This project is for applying Unscented Kalman Filter from LIDAR and RADAR sensors using by C++.

You can find starter code created by the Udacity on [here](https://github.com/udacity/CarND-Unscented-Kalman-Filter-Project).

---

[//]: # (Image References)
[image1]: ./assets/ukf_dataset1.png
[image2]: ./assets/ukf_dataset2.png

## Dependencies
* [Simulator](https://github.com/udacity/self-driving-car-sim/releases)
* [uWebSocketIO](https://github.com/uWebSockets/uWebSockets)
* cmake >= 3.5
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## How to use
1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
    * On windows, you may need to run: `cmake .. -G "Unix Makefiles" && make`
4. Run it: `./UnscentedKF`
5. Run Simulator with Project 1/2: EKF and UKF
6. Select Dataset1 or Dataset2
7. Click Start button

## Result
![Dataset 1][image1]

RMSE for Dataset 1: [0.0774, 0.0859, 0.3591, 0.2510]

![Dataset 2][image2]

RMSE for Dataset 2: [0.0781, 0.0820, 0.6289, 0.3098]
