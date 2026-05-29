# e-puck2 Obstacle Avoidance and Swarm Robotics Project

A mobile robotics project based on the e-puck2 robot platform using Webots simulation and Python control algorithms.

This project focuses on obstacle avoidance, reactive robot behaviour, and basic swarm robotics experiments.

---

# Project Overview

The project implements autonomous navigation behaviours for the e-puck2 robot in a simulated Webots environment.

The robot uses onboard distance sensors to detect nearby obstacles and dynamically adjust movement behaviour in real time.

The project also includes BeeClust-inspired swarm behaviour experiments for multi-robot interaction studies.

---

# Features

## Obstacle Avoidance

The robot continuously monitors surrounding obstacles and changes direction to reduce collision risk.

## Reactive Navigation

Implemented real-time reactive control logic for autonomous movement.

## Swarm Behaviour Experiments

The project includes BeeClust-inspired swarm robotics experiments for studying collective robot behaviour.

## Webots Simulation

The entire system is tested and simulated in the Webots robotics simulation environment.

---

# Technologies Used

* Python
* Webots Simulator
* e-puck2 Robot
* Mobile Robotics
* Sensor Processing
* Swarm Robotics

---

# Repository Structure

```text
controllers/
    my_obstacle-Avoidance/
        my_obstacle-Avoidance.py
        BeeClustTest.py

obstacle_avoidance.wbt
```

---

# Main Components

| File                     | Description                                  |
| ------------------------ | -------------------------------------------- |
| my_obstacle-Avoidance.py | Main obstacle avoidance controller           |
| BeeClustTest.py          | BeeClust-inspired swarm behaviour experiment |
| obstacle_avoidance.wbt   | Webots simulation world                      |

---

# How It Works

The robot continuously reads sensor values from the e-puck2 distance sensors and adjusts wheel velocities dynamically.

When obstacles are detected, the robot changes movement direction to avoid collisions and continue autonomous navigation.

The BeeClust experiment demonstrates simple swarm-inspired behavioural rules between robots.

---

# Example Topics Covered

* Obstacle Avoidance
* Reactive Navigation
* Sensor-based Control
* Swarm Robotics
* Mobile Robot Behaviour
* Autonomous Navigation

---

# Future Improvements

* PID motion control
* Multi-robot coordination
* Path planning
* Vision-based navigation
* SLAM integration

---

# Author

WU YICHENG
University of Sheffield
MSc Robotics
