---
title: "Autonomous Date-Palm Harvesting"
excerpt: "An end-to-end perception pipeline for a date-palm harvesting robot, running in real time on embedded hardware."
collection: portfolio
date: 2025-09-01
header:
  image: projects/date-palm-harvesting.svg
  teaser: projects/date-palm-harvesting.svg
github: https://github.com/shujahrehman1/Crowd-Detection-Gabor-Filter
tags:
  - Computer Vision
  - Robotics
  - Edge Deployment
---

At KAUST's RISC Lab, I'm building the perception system for a robot that harvests date palms autonomously — from raw camera feed to a 3D pick point the robot arm can act on.

**Dataset.** Starting from thousands of raw video frames captured across working date farms, I use CLIP-based filtering to automatically surface the frames that actually show close-up, in-focus fruit clusters, then cluster and de-duplicate them to build a clean, diverse annotation set of 7,000+ images — cutting out the frames that would otherwise waste annotator time.

**Detection & segmentation.** A YOLO-based instance segmentation model detects and segments ripe dates, female flowers, trunks, and bunches directly in outdoor, variably-lit orchard conditions.

**Real-time inference.** The full pipeline — detection, depth fusion, and 3D backprojection — runs on a Jetson AGX Orin at roughly 30 FPS, using INT8/FP16 quantization and model scaling to hit that budget on embedded hardware.

**Integration.** Detections are fused with depth to produce a 3D pick point in the robot's own coordinate frame, and handed off through a ROS2 pipeline to the manipulation stack for harvesting.
