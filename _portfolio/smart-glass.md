---
title: "Smart Assistive Glasses for the Visually Impaired"
collection: portfolio
tags: [projects]
permalink: /portfolio/smart-glass/
excerpt: "A wearable system integrating ESP32-S3 smart glasses and a Jetson-based base station to provide real-time obstacle-aware navigation and scene description for visually impaired users."
date: 2025-09-28
venue: "EECS 473 Advanced Embedded Systems – University of Michigan"
pdf: "/files/15_SmartGlass.pdf"
---

![Functional diagram of the base station](/images/smart-glass2.jpg)

**_Group Members_**: **Haobo Fang**, Guanyu Xu, Ruopu Dong, Zhuoyang Chen, Jinlin Li, Yizhe Shen.

**_Project Status_**: In Progress.
For more implementation details, please refer to our [proposal](/files/15_SmartGlass.pdf).

**_Abstract_**: Smart Assistive Glasses address the mobility and safety challenges faced by visually impaired individuals by combining lightweight wearable sensing with local AI computation. The system integrates an ESP32-S3-based glasses module featuring wake word detection, MEMS microphone array, OV2640 camera, vibromotor haptics, and audio feedback, with a Jetson Orin Nano base station running speech recognition, YOLO-based obstacle detection, and a compact vision–language model for scene description. This architecture enables real-time obstacle-aware navigation and contextual awareness without reliance on cloud connectivity, ensuring privacy, low latency, and robust performance. The prototype demonstrates how embedded intelligence in a practical, wearable form factor can enhance independence and quality of life for visually impaired users.
