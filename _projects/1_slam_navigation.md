---
layout: page
title: Visual SLAM Navigation Stack
description: Real-time autonomous navigation for indoor robots using ZED 2i and RGB-D sensing
img: assets/img/slam_preview.gif   # add a GIF or image of your robot navigating
importance: 1
category: research
---
 
Built and maintained a full **visual SLAM-based autonomous navigation stack** for
real-world indoor environments as part of my research at NYU CILVR.
 
**What it does:**
- Real-time 3D mapping and localization using ZED 2i stereo camera (RGB-D)
- Occupancy-grid mapping for environment representation
- A\*/D\*-Lite path planning with pure-pursuit path following
- Runs at 30Hz on Jetson/NUC hardware
 
**Tech Stack:** Python, ROS, ZED 2i, Jetson, Rerun, Viser, A\*/D\*-Lite
 
**Key result:** Point-to-point autonomous navigation in previously unseen
indoor environments with live visualization for real-time debugging and tuning.
