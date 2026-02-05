---
title: "Embedded Control Systems: Adaptive Cruise Control with Haptic Interface"
collection: portfolio
permalink: /portfolio/eecs461-acc/
tags: [projects]
excerpt: "Course-long exploration of embedded control using NXP S32K144 microcontroller and haptic wheel interface, culminating in an Adaptive Cruise Control (ACC) system with automatic steering."
date: 2025-04-20
venue: "EECS 461 Embedded Control Systems – University of Michigan"
pdf: "/files/EECS461_ACC_Final_Report.pdf"
order: 3
---

![Haptic wheel and Simulink-based ACC framework](/images/eecs461-acc.jpg)

**_Group Members_**: **Haobo Fang**, Guanyu Xu.

**_Project Status_**: Completed (Winter 2025).
For more details, see our [project manual](/files/EECS461_ACC_Project_Manual.pdf) and [final report](/files/EECS461_ACC_Final_Report.pdf).

---

**_Abstract_**:
This course project integrated concepts from embedded systems, digital/analog interfacing, and control theory through progressive lab modules and a final system design. Using the NXP S32K144 microcontroller and a haptic wheel interface, we implemented low-level I/O, PWM motor control, interrupts, virtual worlds with dynamics, CAN bus networking, and Simulink-based autocode generation.

The capstone project was the design of an **Adaptive Cruise Control (ACC) system** with automatic steering. The ACC maintained a desired vehicle speed and adapted to traffic by switching between speed control and gap-keeping mode via CAN bus communication with up to six simulated vehicles. A PID-based steering controller guided the vehicle along a road, while the haptic wheel reflected steering forces through self-aligning torque feedback.  

This integration of **hardware, embedded C programming, and model-based design** demonstrated how advanced automotive features can be prototyped on a real-time embedded platform, preparing us for work in cyber-physical systems, automotive engineering, and robotics.