---
title: Activity
nav:
  order: 1
  tooltip: Lab news
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Activity

## 12.2024:
Our first PhD student at HKU, Rui Peng, has successfully defended his PhD thesis!

{% capture col1 %}
{%
  include figure.html
  image="images/news/2024-12-pengrui_single.png"
  caption="Dr. Rui Peng!"
%}
{% endcapture %}

{% capture col2 %}
{%
  include figure.html
  image="images/news/2024-12-pengrui_supervisor.png"
  caption="Dr.Rui Peng and Prof. Peng Lu"
%}
{% endcapture %}

{% capture col3 %}
{%
  include figure.html
  image="images/news/2024-12-pengrui_teammates.png"
  caption="ArcLab teammates"
%}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}



Have you ever seen an aerial continuum manipulator that can perform various challenging tasks?
We introduce Aerial Elephant Trunk (AET), which can perform dexterous manipulation tasks in complex environments that are filled with obstacles.
The paper has been accepted by [Nature Communications](https://www.nature.com/ncomms/).
More details will follow:

{% capture col1 %}
{%
  include figure.html
  image="images/news/2024-12-AET_NC.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}



Navigating in a highly dynamic and cluttered environment is a very complex task for UAVs. We propose FAPP, a fast and adaptive perception and planning framework for drones.
Check our latest [IEEE Transactions on Robotics](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8860) paper for more details:

Paper: FAPP: Fast and Adaptive Perception and Planning for UAVs in Dynamic Cluttered Environments.

Video: [FAPP](https://www.youtube.com/watch?v=-0l-_cR8NkQ).

{% capture col1 %}
{%
  include figure.html
  image="images/news/2024-12-FAPP_fig.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}




## 11.2024:
We are honored to have [Prof. Yunhui Liu](https://www4.mae.cuhk.edu.hk/peoples/liu-yun-hui/) visiting our lab.




## 9.2024:
We are honored to have [Prof. Toshio Fukuda](https://uni-obuda.hu/prof-dr-toshio-fukuda-en/) visiting our lab.

{% capture col1 %}
{%
  include figure.html
  image="images/news/2024-9-fukuda1.jpg"
%}
{% endcapture %}

{% capture col2 %}
{%
  include figure.html
  image="images/news/2024-9-fukuda2.jpg"
%}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
 

## 8.2024:

How to use Deep Reinforcement Learning for path planning and obstacle avoidance while achieving a similar smoothness performance of conventional methods? We propose an end-to-end approach that considers the motion constraints of differential drive robots, which can obtain a high velocity and smooth path while significantly reducing the processing time. 
Please see the paper for more details:

Paper: [Mobile Robot Collision Avoidance Based on Deep Reinforcement Learning with Motion Constraints](https://ieeexplore.ieee.org/document/10638222)

Video: [DRL](https://www.youtube.com/watch?v=wJZwQEW1tZ4).

{% capture col1 %}
{%
  include figure.html
  image="images/news/2024-8-mobile_robot.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}


## 5.2024:

3D dense mapping in aggressive motions remains challenging. We have used event cameras to improve dense mapping under aggressive motions. The performance is even better than several NERF-based methods.
Please check our Advanced Intelligent Systems paper for more details:

Paper: [EVI-SAM: Robust, Real-Time, Tightly-Coupled Event–Visual–Inertial State Estimation and 3D Dense Mapping](https://onlinelibrary.wiley.com/doi/10.1002/aisy.202400243)

Video: [EVI-SAM](https://www.youtube.com/watch?v=Nn40U4e5Si8).

{% capture col1 %}
{%
  include figure.html
  image="images/news/2024-5-EVI-SAM.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}


## 4.2024:

How to search for unknown dynamic objects in unknown environments using multiple robots?
We provide a Multi-Agent Reinforcement Learning framework to solving this issue.
Check our RAL paper and video for more details:

Paper: [HMA-SAR: Multi-Agent Search and Rescue for Unknown Located Dynamic Targets in Completely Unknown Environments](https://ieeexplore.ieee.org/document/10517396)

Video: [HMA-SAR](https://www.youtube.com/watch?v=0yFJ-mrWTvc).

{% capture col1 %}
{%
  include figure.html
  image="images/news/2024-4-HMA-SAR.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}


## 3.2024:

How to control quadruped robots with various configurations (structures, size, weights, etc.) and allow them to walk stably in various terrains?
We provide one solution to that with our MorAL framework. See our RAL paper:

Paper: [MorAL: Learning Morphologically Adaptive Locomotion Controller for Quadrupedal Robots on Challenging Terrains](https://ieeexplore.ieee.org/document/10463132)

Video: [MorAL](https://www.youtube.com/watch?v=EjR2OkiLzTA).

{% capture col1 %}
{%
  include figure.html
  image="images/news/2024-3-MORAL.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}


We have just opensourced the software for our event-based visual odometry algorithm: ESVIO.

Code: [Github Link](https://github.com/arclab-hku/ESVIO)

Paper: [P. Chen, W. Guan and P. Lu, "ESVIO: Event-Based Stereo Visual Inertial Odometry," in IEEE Robotics and Automation Letters, vol. 8, no. 6, pp. 3661-3668, June 2023.](https://ieeexplore.ieee.org/document/10107754).

 

## 2.2024:

Our paper on continuum robotic arm has been accepted by IEEE Robotics and Automation Letters.

Paper: [A Tendon-Driven Continuum Manipulator With Robust Shape Estimation by Multiple IMUs](https://ieeexplore.ieee.org/document/10427985)

Video: [Origami](https://www.bilibili.com/video/BV1yp421d7J2).

{% capture col1 %}
{%
  include figure.html
  image="images/news/2024-2-origami.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}


## 11.2023:

Our paper on SLAM has been accepted by IEEE Transactions on Intelligent Vehicles.
[ECMD: An Event-Centric Multisensory Driving Dataset for SLAM](https://ieeexplore.ieee.org/document/10342726)



## 10.2023:

Our paper on quadruped robot has been accepted by IEEE Robotics and Automation Letters:
[FT-Net: Learning Failure Recovery and Fault-tolerant Locomotion For Quadruped Robots](https://ieeexplore.ieee.org/document/10305254)

{% capture col1 %}
{%
  include figure.html
  image="images/news/2023-10-ft-net.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}

Our FT-net can enable quadruped robots to work even in the presence of partial and total rotor failures.



## 9.2023:

Our paper on event-based visual odometry has been accepted by IEEE Transactions on Automation Science and Engineering:
[PL-EVIO: Robust monocular event-based visual inertial odometry with point and line features](https://ieeexplore.ieee.org/document/10287884)

{% capture col1 %}
{%
  include figure.html
  image="images/news/2023-9-pl-evio.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}

Our event-based VO can enable quadrotors to perform aggressive maneuvers by using the onboard estimation without replying on motion capture systems.


## 7.2023:

Our paper on deep reinforcement learning has been accepted by IEEE Robotics and Automation Letters:
[Learning Agile Flights through Narrow Gaps with Varying Angles using Onboard Sensing](https://ieeexplore.ieee.org/document/10184073)

{% capture col1 %}
{%
  include figure.html
  image="images/news/2023-7-LAF.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}

 
## 6.2023:

Our paper on dynamic obstacle avoidance has been accepted by IEEE/ASME Transactions on Mechatronics.
Title: [Flying in Dynamic Scenes With Multitarget Velocimetry and Perception-Enhanced Planning](https://ieeexplore.ieee.org/document/10179014)

{% capture col1 %}
{%
  include figure.html
  image="images/news/2023-6-FDS.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}


## 5.2023:

Our paper on visual odometry has been accepted by IEEE Transactions on Instrumentation and Measurement.
Title: [Filtering 2D-3D Outliers by Camera Adjustment for Visual Odometry](https://ieeexplore.ieee.org/document/10138109)

{% capture col1 %}
{%
  include figure.html
  image="images/news/2023-5-2d-3d.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}


## 4.2023:

Our event-based VIO has been accepted by IEEE Robotics and Automation Letters:

Title: [ESVIO: Event-based Stereo Visual Inertial Odometry](https://ieeexplore.ieee.org/document/10107754)

The ESVIO can provide a stable and accurate state estimation in the presence of aggressive motions (aggressive rotational rates) and dark environments.

{% capture col1 %}
{%
  include figure.html
  image="images/news/2023-4-ESVIO.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}


## 3.2023:

We are excited to share our aerial continuum arm AeCoM, which is accepted by IEEE Transactions on Systems, Man, and Cybernetics: Systems.
Title: [AeCoM: An Aerial Continuum Manipulator with IMU-based Kinematic Modeling and Tendon-slacking Prevention](https://ieeexplore.ieee.org/document/10081306)

{% capture col1 %}
{%
  include figure.html
  image="images/news/2023-3-AECOM.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}


## 7.2022:

Our paper  has been accepted by IEEE Robotics and Automation Letters.
Our quadrotor can avoid multiple fast-moving tennis balls which are thrown simultaneously or continuously with only a RGBD camera.
Title: [Perception and Avoidance of Multiple Small Fast Moving Objects for Quadrotors with Only Low-cost RGBD Camera](https://ieeexplore.ieee.org/document/9881875)

{% capture col1 %}
{%
  include figure.html
  image="images/news/2022-7-PAMSF.png"
%}
{% endcapture %}

{% include cols.html col1=col1 %}
