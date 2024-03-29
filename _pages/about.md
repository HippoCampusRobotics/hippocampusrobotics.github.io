---
title: "About"
permalink: /about/
layout: splash
excerpt: "About HippoC"
classes: wide
feature_row:
  - image_path: https://www.tuhh.de/t3resources/mum/_processed_/csm_2014-12-05_10.28.15_nocable_small_34d2a69318.jpg
    excerpt: "First prototype of HippoCampus as of 2014."   
  - image_path: images/photos/hippoc_cad.jpg
    excerpt: "CAD rendering of HippoCampus."
  - image_path: images/photos/hippoc_2018.jpg
    excerpt: "Current version of HippoCampus as of 2018." 
---

## The HippoCampus Mission

The HippoCampus is an open-source micro underwater robot for research and hobby applications.
The quad-rotor design makes HippoCampus agile and allows for complex maneuvers.
HippoCampus is built with off-the-shelf components and 3D-printed parts.
It was developed for research in the area of autonomous exploration and monitoring of confined environments.

## The HippoCampus History
The first prototype can be traced back to a project carried out by Axel Hackbarth and Eugen Solowjow in December 2014.
In Spring 2016 Daniel Duecker joined the team.
The first full design revision towards a modular concept was conducted by Tobias Johannink as part of his Bachelor thesis. Since then the design underwent multiple revision towards a fully modular concept.

In the following years Daniel Duecker and many collaborators extended the HippoCampus platform with underwater localization, improved control and pathplanning capabilities.

As by now the HippoCampus firmware is part of the [PX4-Firmware](https://github.com/px4/PX4-Autopilot) stack and is embedded in the related Gazebo-SITL environment.


## HippoCampus Design

The HippoCampus design aims to maximize modularity such that the platform can be easily adopted to new mission requirements.

The hull consist of a base-unit and two acrylic tubes which house the electronics.
The on-board electronics include ESCs, a LiPo battery, telemetry antennas, and system boards.
The 2020 HippoCampus platform features [PixRacer](https://store.mrobotics.io/mRo-PixRacer-R14-Official-p/auav-pxrcr-r14-mr.html) flight computing unit (FCU) as well as a Raspberry Pi4B single board computer (SBC). While the FCU mainly runs the low-level control algorithms the SBC runs high-level planning and localization algorithms in a ROS-framework.

The Firmware design is branched from the [PX4-Firmware](https://github.com/px4/PX4-Autopilot). However, important milestones are contributed to the PX4-Firmware.

The HippoCampus stack allows for remote controlled and autonomous operations.
The HippoCampous control architecture includes state estimators and controllers for various applications.

## Gallery

{% include feature_row %}

