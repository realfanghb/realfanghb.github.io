---
title: "Lumen Grid: Competitive Multi-Robot Parking Game"
collection: portfolio
tags: [projects]
permalink: /portfolio/lumen_grid/
excerpt: "A fast-paced multi-robot parking game featuring four Zumo robots on a 4×4 ft LED-marked arena, combining PixyCam-based localization and IMU gesture control with real-time visual and haptic feedback."
date: 2025-01-08
venue: "EECS 373 Intro. to Embedded System Design – University of Michigan"
pdf: "/files/EECS373_Poster_Final.pdf"
order: 2
---

![Poster](/images/EECS373_Poster_Final.png)

<video
  controls
  autoplay
  muted
  loop
  playsinline
  preload="metadata"
  style="width:100%;max-width:900px;border-radius:12px;">
  <source src="{{ '/videos/lumen_grid_compressed.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>

**_Group Members_**: **Haobo Fang**, Guanyu Xu, Xiang Jiang, Varun Agrawal.

**_Project Status_**: Completed.
For more implementation details, please refer to our [github repo](https://github.com/XuGuaaaanyu/Lumen_Grid).

**_Abstract_**: Lumen Grid is a competitive multi-robot parking game that showcases end-to-end embedded integration and real-time multi-agent coordination. Four Zumo robots race on a 4×4 ft LED-marked field where parking spots are randomly generated each round and indicated by dynamic LED patterns. A PixyCam overhead vision pipeline localizes each robot using unique color tags and updates spot occupancy in real time. Players control robots via a handheld STM32-based gesture controller that maps IMU roll/pitch to speed and steering, includes an FSR-triggered emergency stop, and provides haptic feedback alongside an OLED status display. On-board STM32 control uses yaw sensing and PID-based steering to execute smooth parking maneuvers, while Bluetooth links deliver commands and velocity feedback across subsystems.