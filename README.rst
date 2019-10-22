vision_opencv
=============

.. image:: https://travis-ci.org/ros-perception/vision_opencv.svg?branch=indigo
    :target: https://travis-ci.org/ros-perception/vision_opencv

Packages for interfacing ROS with OpenCV, a library of programming functions for real time computer vision.

Adapted to work with OpenCV4 on Ubuntuu 18.04.

You may want to make changes in file "cv_bridge/CMakeLists.txt":
- you can use e.g. `set(OpenCV_DIR /usr/share/opencv4)` to specify your opencv4 directory
- in `include_directories(include....` you may want to change `/usr/include/python3.7m/` to whatever python version you are using
