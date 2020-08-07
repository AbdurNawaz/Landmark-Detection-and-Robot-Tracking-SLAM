# Landmark Detection & Robot Tracking (SLAM)

This repo contains the implementation of SLAM (Simultaneous Localization and Mapping) for a 2D world. This project combines robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems. 

*Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using *only* sensor and motion data collected by that robot.*

<p align="center">
  <img src="./images/robot_world.png" width=50% height=50% />
</p>

The project is broken broken into three Python notebooks.

__Notebook 1__ : Robot Moving and Sensing

__Notebook 2__ : Omega and Xi, Constraints 

__Notebook 3__ : Landmark Detection and Tracking

This project has been inspired from the P3 of the [Computer Vision nadnodegree at Udacity](https://www.udacity.com/course/computer-vision-nanodegree--nd891).
