Engineering materials
====

This repository contains engineering materials of a self-driven vehicle's model participating in the WRO Future Engineers competition in the season 2023.

## Content

* `t-photos` contains 2 photos of the team (an official one and one funny photo with all team members)
* `v-photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `video` contains the video.md file with the link to a video where driving demonstration exists
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition
* `models` is for the files for models used by 3D printers, laser cutting machines and CNC machines to produce the vehicle elements. If there is nothing to add to this location, the directory can be removed.
* `other` is for other files which can be used to understand how to prepare the vehicle for the competition. It may include documentation how to connect to a SBC/SBM and upload files there, datasets, hardware specifications, communication protocols descriptions etc. If there is nothing to add to this location, the directory can be removed.

## Introduction

_The robot is a small, four-wheeled vehicle with a camera mounted on top. The camera is used to detect the track borders and other obstacles, and the robot's software uses this information to control the wheels and keep the robot on track. The robot also has a sensor that detects the finish line, and when it reaches the finish line, it stops._

_The robot is programmed to drive the track in a specific direction. The direction is determined by a coin toss before the match begins. The robot starts at a random section of the track, and the distance between the track borders is determined by another coin toss._

_The robot is allowed to make one repair per match. If the robot breaks down, the team can ask for permission to take it out of the track, fix it, and put it back in. The match timer does not stop during a repair._

_The robot is scored based on how quickly it completes the track and how many times it hits obstacles. The fastest robot with the fewest hits wins the match._
