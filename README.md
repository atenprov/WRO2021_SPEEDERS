
You Tube Links
==============
Phase 1:

https://youtu.be/jC56XRlDXWw

https://youtu.be/ro0ebMVTLgs


Engineering materials
====

This repository contains engineering materials of a self-driven vehicle's model participating in the WRO Future Engineers competition in the season 2021.

## Content

* `photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition
* `models` is for the files for models used by 3D printers, laser cutting machines and CNC machines to produce the vehicle elements. If there is nothing to add to this location, the directory can be removed.
* `other` is for other files which can be used to understand how to prepare the vehicle for the competition. It may include documentation how to connect to a SBC/SBM and upload files there, datasets, hardware specifications, communication protocols descriptions etc. If there is nothing to add to this location, the directory can be removed.

## Introduction

               WRO FUTURE ENGINNERS 2021

The speeders.
Our Robot was constructed with the Lego Mindstorms ev3 educational set, and our code was developed in lab view ev3 software development platform. The design of our vehicle includes 2 lego bricks positioned at the top of our robot, connected together using the LEGO Original Electric USB to mini USB cable based on the daisy chain connection. 
There are 3 Ultrasonic sensors used for distance detection among the walls of the race field. Two of them, positioned on the left and the right side of the Robot, are plugged on the respective main  brick’s ports. The third one is on the front side of the robot connected on the secondary brick’s port. A color sensor, connected on the main brick is used in order to identify the color lines positioned on the corner sections of the field track.  
A pixy camera is in gaged in order to identify the traffic lights that are randomly positioned on the track while navigating through the race field.

