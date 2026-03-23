---
title: "Underwater LiDAR & Time-of-Flight Camera System"
collection: projects
permalink: /projects/underwater-lidar
date: 2019-10-27
excerpt: "Modified commercial ToF cameras for underwater situational awareness and object detection in turbid water environments."
tags:
  - Python
  - PyQt
  - LiDAR
  - Time-of-Flight
  - Computer Vision
  - Image Processing
  - Signal Processing
  - Hardware
---

Modified commercial Time-of-Flight (ToF) cameras have been used to accurately and reliably measure scene depth with high resolution. This project adapts this technology for applications in underwater environments.

## Time-of-Flight Basics
![tof_basics](/files/TOF_BASICS.png)

## Underwater Challenges
The underwater environment poses a challenge for optical sensing due to high amounts of signal scattering and absorption.
![tof_uw](/files/UWTOF_SCATTER.png)

## Hardware Modifications
The stock ToF camera was modified by using the camera's pulsed CW signal to drive a 525nm 1 Watt laser diode.
![tof_hardware](/files/UWTOF_HARDWARE.png)

## Data Capture GUI
A GUI made with PyQt is used for viewing data from the ToF camera over a TCP connection.
![gui](/files/gui_gif.gif)

## Experimental Setup
![experiments](/files/UWTOF_Experiments.png)

## Results
Range images from close-range experiments, processed with digital filtering and TV-L1 regularization:
![exp_results_close](/files/UWTOF_CLOSE_TVL1.png)

### Related Publications
* [Time-of-Flight (ToF) Cameras for Underwater Situational Awareness](/publications/OCEANS19_Conference)
* [Restoration of Underwater ToF Images](/publications/SPIE21_Conference)
