# Robotics System Design
The collection of system design patterns and examples to conduct and prepare for Robotics System Design interview.

> **_NOTE:_**  This repo mostly focuses on **mobile robotics**, however some of the patterns are universal among various robotics domains.

## Table of Contents

* [Motivation](#motivation)
* [Frameworks](#frameworks)
    * [ROS](#ros)
* [Autopilot software](#autopilot-software)
    * [Autonomy 2.0](#autonomy-20)
    * [Perception](#perception)
        * [Fusion](#fusion)
    * [Localization and Mapping](#localization-and-mapping)
    * [Prediction and path planning](#prediction-and-path-planning)
        * [Two layered path planning](#two-layered-path-planning)
    * [Decision making](#decision-making)
    * [Simulators](#simulators)
    * [Data pipelines](#data-pipelines)
* [Hardware](#hardware)
    * [Autonomous Domain Controller](#autonomous-domain-controller)

## Motivation

## Frameworks
### ROS
> **_NOTE:_**  Since ROS1 is going to be deprecated by 2025, we mostly discuss ROS2.

Overall design of the ROS2 is described on the [website](http://design.ros2.org) and [article](https://arxiv.org/pdf/2211.07752.pdf).

#### Communication

#### Client library 

## Autopilot software

### Autonomy 2.0
<img src="https://media.arxiv-vanity.com/render-output/8036325/x3.png" alt="amount of ml in autonomy" width="500"/>
<img src="https://lh6.googleusercontent.com/AXtgWv1lqFgkOMBtY79HWuyr8wxJda9EOjzfj1Aq8pvZl7ibDvUWzsSJjYgokB5k4UJrepzae3F_U6aU8Fz2MuuhN7xOqh698SVgmI9uj-BfQoNfl9TIgaW4zmCMD8qx0bG9NhdU" alt="autonomy2.0" width="500"/>

[Autonomy 2.0: Why is self-driving always 5 years away?](https://arxiv.org/pdf/2107.08142.pdf)

### Perception

#### Fusion
[9 Types of Sensor Fusion Algorithms](https://www.thinkautonomous.ai/blog/9-types-of-sensor-fusion-algorithms/)

By abstraction level:
- Low level - fusing the raw data
- Mid level - fusing the intermediate fusion results (e.g. detections)
- High level - fusing the tracks

<img src="https://app.dropinblog.com/uploaded/blogs/34241363/files/Types_of_Sensor_3.png" alt="fusion levels" width="500"/>

### Localization and Mapping

### Prediction and path planning
#### Two layered path planning
<img src="https://aandds.com/blog/images/robot_path_planning_two_layered.png" alt="two layered path planning" width="500"/>


- End-to-end prediction and path planning

### Decision making
- Finite state machines
- Behavior trees

<img src="https://habrastorage.org/getpro/habr/post_images/2d6/d07/8b0/2d6d078b0cf90b680b341cb161500752.png" alt="bt vs fsm" width="500"/>

### Simulators
- Handcrafted agents
- Learned agents polices
- Log replay
<!-- https://www.youtube.com/watch?v=S59lIhwU4dA -->

### Data pipelines

 [Autonomous Driving and ADAS Data Lake on AWS](https://aws.amazon.com/blogs/architecture/field-notes-building-an-autonomous-driving-and-adas-data-lake-on-aws/)

<img src="https://d2908q01vomqb2.cloudfront.net/fc074d501302eb2b93e2554793fcaf50b3bf7291/2020/10/12/Autonomous-Driving-Data-Lake-RA-1024x576.jpg" alt="amazon data lake" width="500"/>

## Hardware

###  Autonomous Domain Controller

[An autonomous domain controller is a specialized computer that controls specific groups of functions, or “domains” of activity or features, enabling the entire autonomous driving software stack](https://www.tusimple.com/blogs/developing-a-production-ready-autonomous-domain-controller-with-nvidia/)

<img src="https://www.aptiv.com/images/default-source/feature-stories/domain-controllers.jpg?sfvrsn=f0bff53d_3" alt="adc" width="500"/>
