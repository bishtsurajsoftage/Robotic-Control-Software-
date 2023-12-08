# Robotic-Control-Software-

# Modern Robotics: Mechanics, Planning, and Control

# Code Library
This repository contains the code library accompanying [_Modern Robotics: Mechanics, Planning, and Control_](https://modernrobotics.org) (Kevin Lynch and Frank park, Cambridge University press 2017). The [user manual](/doc/MRlib.pdf) is in the doc directory.

The functions are available in 

* Python
* Matlab
* Mathematica

Each function has a commented section above it explaining the inputs required for its use as well as an example of how it can be used and what the output will be. This repository also contains a pdf document that provides an overview of the available functions using MATLAB syntax. Functions are organised according to the chapter in which they are introduced in the book.Basic functions, such as functions to calculate the magnitude of a vector, test if the value is near zero, and perform matrix operations such as multiplication and inverses, are not documented here.

The primary purpose of the provided software is to be easy to read and educational, reinforcing the concepts in the book. The code is optimized neither for efficiency not robustness.

Some unofficial versions in other languages are being developed:
* [C++ version](https://github.com/Le0nX/ModernRoboticsCpp)
* [Julia version](https://github.com/ferrolho/ModernRoboticsBook.jl)
* [Nim Version](https://github.com/Nimbotics/ModernRoboticsNim)


Some libraries built on our:
* [KinematicsFromDescriptionTool](https://github.com/Interbotix/kinematics_from_description), which calculates the kinematics input parameters from a robot's URDF or robot_description parameter using ROS and Python3.
* [mr_urdf_loader](https://github.com/tjdalsckd/mr_urdf_loader), which generates 'M', 'Slist', 'Blist', 'Mlist' and 'Glist' parameters for kinematics and dynamics. It also provides UR5 simulation using 'PyBullet'.

* [tf_rbdl](https://github.com/junhyeokahn/tf_rbdl#tf_rbdl), which refactors the Python version using the package 'tensorflow'.


  Any contibution is welcomed but the maintenance team for this library here doesn't vouch for the reliability of those projects.























