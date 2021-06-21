---
layout: archive
title: "Current Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---


---


My PhD study has been focusing on the development of a cable-driven soft-bodied robot manipulator for surgical blood suction. 

My research involves the full-stack development of a surgical-orientated soft robot, including mechanism design, prototyping, modeling, control, testing, and application, as well as other related techniques such as computer vision and ergonomics. My research contributes
- A **unique**, **miniaturized**, and **dexterous** soft-bodied robot with kinematically predictable motion.
- A **specific** solution to meet the requirement of fluid suction in (R)-MIS.
- An **intuitive** master-follower control system to control a redundant soft robot in real-time.


### Design & Prototyping of A Cable-Driven Soft-Bodied Robot

In this project, the first-gen of the soft robot was made from 
Polydimethylsiloxane (PDMS) elastomer, and the second-gen was fabricated from Agilus30 resin using stereolithography 3D printing, both of which feature a small diameter down to 9 mm with a 100 mm length and actuated by nylon cables that are attached to the independent servo.

<img src="/images/segment.jpg" width="300" />
<img src="/images/rnd_motion.gif" width="300" />



### Curvature Tracking of A Signle Segment Soft Robot

It has been tested that the cylindrical soft segment would deform as a constant curvature within a certain range of bending. In this project, plenty of visual measurement techniques were used.

<img src="/images/seg_bending.gif" width="500" />

J. Lai, [A Novel Wire Driven Soft Robot Manipulator with Visual Servoing Control](/img/me_poster.png), <font color = red>The 5th PolyU Mechanical Engineering Research Pitch Competition</font>, 2019.

### Vision-Based Adaptive Configuring of A Soft Robot

Based on the visual feedback in real-time, we proposed an eye-to-hand visual servoing method that could adaptively correct the robot pose in the presence of a payload. An interactive GUI that enables the user to assign the robot pose using specified key-points was developed.

<img src="/images/aim_demo.gif" width="500" />

[[Full video]](https://youtu.be/_yy3LjOx5cc)

J. Lai, K. Huang, B. Lu and H. K. Chu, [Toward Vision-based Adaptive Configuring of A Bidirectional Two-Segment Soft Continuum Manipulator](https://ieeexplore.ieee.org/document/9158975), <font color = red>IEEE/ASME Int. Conf. Adv. Intell. Mechatron. (AIM)</font>, 2020.


### 3D Sensing of A Soft Robot based on RGB-D Vision

A 3D sensing platform was built based on the image segmentation, RGB-D vision, and matrices transformation.

<img src="/images/rgbd_sensing.gif" width="500" />

### Verticalized-Tip Trajectory Tracking of A 3D-Printed Soft Robot for Blood Suction Automation

Based on the actual need for blood suction in MIS, an opposite-bending configuration was proposed to decouple the position and orientation of the tip frame. Based on this configuration constraint, a depth vision-enhanced trajectory tracking task with a vertical tip pose can be achieved. A point-cloud searching algorithm was proposed which could rapidly solve the IK. The tip can track the designated trajectory accurately and timely. On top of that, an image-based trajectory generation method was proposed to enable suction automation from detection to execution.

<img src="/images/suction_circle.gif" width="300" />
<img src="/images/suction_auto.gif" width="300" />

[[Full video]](https://youtu.be/_5zb7vnvwkA)

J. Lai, K. Huang, B. Lu, Q. Zhao and H. K. Chu, [Verticalized-Tip Trajectory Tracking of A 3D-Printable Soft Continuum Robot: Enabling Surgical Blood Suction Automation](), <font color = red>IEEE/ASME Trans. Mechatron. (T-MECH)</font>. 2021.

### Variable-Stiffness Control of A Dual-Segment Soft Robot using Depth Vision

A variable-stiffness control method based on pure cable actuation was proposed. With the aid of RGB-D visual feedback which monitors the positional deviation of the tip w.r.t. the model-predicted position caused by the undesired perturbation, the soft robot can be stiffened accordingly.

<a href="http://https://youtu.be/hS9taWGyeVc"><img src="http://img.youtube.com/vi/hS9taWGyeVc/0.jpg"
alt="A cable shaping robot" width="400" height="300" border="10" /></a>


J. Lai, B. Lu and H. K. Chu, [Variable-Stiffness Control of A Dual-Segment Soft Robot using Depth Vision](https://ieeexplore.ieee.org/document/9427246), <font color = red>IEEE/ASME Trans. Mechatron. (T-MECH)</font>. 2021.

### Constrained Motion Planning of A Cable-Driven Soft Robot with Compressible Curvature Modeling

J. Lai, B. Lu, Q. Zhao and H. K. Chu, [Constrained Motion Planning of A Cable-Driven Soft Robot with Compressible Curvature Modeling](https://arxiv.org/abs/2106.08250), <font color = red>IEEE Robot. Autom. Lett. (RA-L)</font>. 2021. (Under Review)

### A Steerable Soft-Bodied Robot Based on Real-Time Gesture Control

J. Lai, B. Lu, and H. K. Chu, [GesSo: A Steerable Soft-Bodied Robot Based on Real-Time Gesture Control](), <font color = red>IEEE Trans. Biomed. Eng. (T-BME)</font>, 2021. (Under Review)

