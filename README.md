# Straight line segment extractor

Simple but efficient/effective line segement detector.
This detector, used in works listed below, extracts line segments from images more effectively than classical Hough transform.

Please cite one of these papers if you use this code in your research:

Lee, Jin Han, et al. "Place recognition using straight lines for vision-based
SLAM." Robotics and Automation (ICRA), 2013 IEEE International Conference on.
IEEE, 2013.

Lee, Jin Han, et al. "Outdoor place recognition in urban environments using
straight lines." Robotics and Automation (ICRA), 2014 IEEE International
Conference on. IEEE, 2014.

Zhang, Guoxuan, et al. "Building a 3-D Line-Based Map Using Stereo SLAM."
Robotics, IEEE Transactions on 31.6 (2015): 1364-1377.

# Dependency
Opencv 2.4.x

Google Flags 2.1.0 ($ sudo apt-get install libgflags-dev)

We have not tested this code with Opencv 3.x but expect that it will also work with the 3.x version.

# Usage

$ mkdir build

$ cd build

$ cmake ../

$ make

$ ./linedetection -i ../img/squre.jpg

You can see the simple usage of this detector in linedetection.cpp.

If you have any question, contact me slslam@incorl.hanyang.ac.kr
