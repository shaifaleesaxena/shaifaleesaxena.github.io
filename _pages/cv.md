---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download CV PDF](/files/Shaifalee_Saxena_CV_030426.pdf)

## Education

- **Ph.D. in Electrical and Computer Engineering**, University of New Mexico, 2024-present
- **B.Tech. in Aerospace Engineering**, Indian Institute of Space Science and Technology (IIST), 2014-2018

## Research Experience

### Graduate Research Assistant, Los Alamos National Laboratory
**Adaptive Machine Learning Group (AOT-IC)** | 2025-present  
Working on reinforcement learning for accelerator tuning and control under the supervision of **Dr. Alexander Scheinker**.

### Research Assistant, University of New Mexico
**MARHES and AgMan Labs** | 2024-present  
Working on hybrid control methods for space robotics under the supervision of **Dr. Rafael Fierro**.

## Current Research Projects

### Robust Deep RL for Time-Varying Control
Developing hybrid learning-control methods that combine deterministic actor-critic reinforcement learning with bounded extremum seeking for robustness under drift and nonstationarity.

### Multi-Task Reinforcement Learning for Robotic Manipulation
Training a single policy to perform multiple manipulation tasks such as push, grasp, and pick-and-place with shared representations and task-conditioned behavior.

### Vision Representation Learning for RL via Autoencoders
Building latent-space control pipelines that compress image observations into compact latent states for downstream reinforcement learning.

### Space Robotics: Solar Panel Deployment Failure Detection and Repair
Developing vision-based failure detection and corrective control strategies for stuck or jammed deployment mechanisms.

## Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Invited Talks

- **Unmanned Aerial Systems (UAS) Autonomy**, Cybosium organised by IEEE RAS Technical Education Program, 2023

## Professional Experience

### Airbus Group Pvt Ltd, India
**Senior Engineer - Control System** | 2021-2024

- Developed Electronic Flight Control System (EFCS) packages for Airbus training simulators.
- Implemented malfunction triggering logic by understanding aircraft control laws.
- Conducted validation activities for control and stability performance.
- Supported technical investigations related to stability and control logic.

### Tata Advanced Systems Ltd, India
**Senior Executive - Flight Dynamics and Control System** | 2018-2021

- Built nonlinear 6-DOF aircraft models for autopilot development.
- Developed Total Energy Control System (TECS) and estimation methods including EKF.
- Worked on system identification, UAV guidance and control, and morphing-wing aircraft problems.
- Developed algorithms for quadcopter swarms, obstacle avoidance, and mission behavior.

## Skills

### Controls and Modeling
System identification, nonlinear dynamics and modeling, discrete-time and continuous-time systems, frequency-domain analysis, filtering, PID and loop-shaping, state-space control, state estimation, observers, and simulation workflows.

### Reinforcement Learning and Machine Learning
Deep reinforcement learning, actor-critic methods, DDPG, hybrid learning-control methods, representation learning, autoencoders, multi-task learning, and data-driven policy evaluation.

### Robotics and Simulation Software
ROS 2, Gazebo, MuJoCo, MATLAB/Simulink, SCADE, ADAMS, and ANSYS.

### Hardware and Sensors
UR5e manipulator, quadcopters, RGB cameras, gimbals, Arduino, Raspberry Pi, ultrasonic sensors, and LiDAR.

## Honors and Awards

- SPOT Award, Airbus, 2022 and 2023
- Best Performer and Team Award, Tata Advanced Systems Ltd, 2019 and 2021
- Second Best Paper Award, ICONS 2018, IIT Madras
- JEE-Advance AIR 3700, 2014
- State Board Topper Merit List, 2014
- Priyadarshini Award, 2013
- National Talent Search Examination (NTSE) Scholar, 2010
