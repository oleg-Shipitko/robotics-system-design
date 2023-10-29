# Robotics System Design 101
The collection of system design patterns and examples to conduct and prepare for Robotics System Design interview.

> **_NOTE:_**  This repo mostly focuses on **mobile robotics**, however some of the patterns are universal among various robotics domains.

## Table of Contents

* [Motivation](#motivation)
* [Autopilot](#autopilot)
    * [Perception](#perception)
    * [Localization and Mapping](#localization-and-mapping)

## Motivation

## Frameworks
### ROS
> **_NOTE:_**  Since ROS1 is going to be deprecated by 2025, we mostly discuss ROS2.

Overall design of the ROS2 is described on the [website](http://design.ros2.org) and [article](https://arxiv.org/pdf/2211.07752.pdf).

#### Communication

#### Client library 

## Autopilot

### Autonomy 2.0
![amount of ml in autonomy](https://media.arxiv-vanity.com/render-output/8036325/x3.png)
![autonomy2.0](https://media.arxiv-vanity.com/render-output/8036325/x1.png)
[Autonomy 2.0: Why is self-driving always 5 years away?](https://arxiv.org/pdf/2107.08142.pdf)

### Perception

#### Fusion
[9 Types of Sensor Fusion Algorithms](https://www.thinkautonomous.ai/blog/9-types-of-sensor-fusion-algorithms/)

By abstraction level:
- Low level - fusing the raw data
- Mid level - fusing the intermediate fusion results (e.g. detections)
- High level - fusing the tracks

![fusion levels](https://app.dropinblog.com/uploaded/blogs/34241363/files/Types_of_Sensor_3.png)

### Localization and Mapping

### Prediction and path planning
- Two layered path planning
![two layered path planning](https://aandds.com/blog/images/robot_path_planning_two_layered.png)
- End-to-end prediction and path planning

### Simulators
- Handcrafted agents
- Learned agents polices
- Log replay
<!-- https://www.youtube.com/watch?v=S59lIhwU4dA -->