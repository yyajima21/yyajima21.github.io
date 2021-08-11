---
permalink: /project.html
redirect_from:
  - /project/
title: "Projects"
author_profile: true
---
Over the past few years, I've worked on several personal & team projects related to computer vision, machine learning, and robotics. Beside my research work, I am currently a software member at RoboJackets working for perception and scene understanding projects using deep learning approach. In this project pages, I include some projects related to machine learning and robotics. 

## CS7641 Machine Learning Final Project
![RoboJackets](/images/cs7641/cs7641-final-project.png)
<br /><br />
In the [CS7641 course](https://mahdi-roozbahani.github.io/CS46417641-summer2021/), our team developed unsupervised and supervised point cloud clustering and segmentation methods. As more 3D data is captured through lidar and depth sensors, our team focuses on developing a efficient way to cluster objects in point cloud and predict object labels using machine learning and deep learning. My contribution is a development of deep learning model, named Dynamic Graph PointNet (DGPointNet), and this model combines the benefits of [Dynamic Graph CNN](https://arxiv.org/abs/1801.07829) and [PointNet](https://arxiv.org/abs/1612.00593). For further information, please visit the following [website](https://cs7641-pointcloudsegmentation.github.io/) and [video](https://gtvault-my.sharepoint.com/personal/yyajima3_gatech_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fyyajima3%5Fgatech%5Fedu%2FDocuments%2Fcs7641%5Fproject%2Fcs7641%5Ffinal%5Fproject%2Emp4&parent=%2Fpersonal%2Fyyajima3%5Fgatech%5Fedu%2FDocuments%2Fcs7641%5Fproject).

## CVPR Scan-to-BIM challenge 2021
<img src="/images/cvpr-scan2bim/gts2b.png" width="750" height="450">
<br /><br />
In [this competition](https://cv4aec.github.io/), the goal is to reconstruct Building Information Models (BUM) from 3D point cloud data acquired from lidar and depth map camera. My contribution includes a development of customizing a deep learning model and hyperparameter tuning to determine the best model to detects target objects (e.g. ceiling, walls, doors, etc.) Our method, named GTS2B, achieved [a second place](files/2D_SecondPlace_Certificate.pdf) in the 2D reconstruction task. Our recorded presentation can be found in [this link](https://www.youtube.com/watch?v=DR9ifKxutf8&list=TLGG8vy3pvaCCBQwMjA4MjAyMQ&t=1006s).

## RoboJackets
![RoboJackets](/images/robonav/robonav_team.jpg)
<br /><br />
[RoboJackets](https://robojackets.org/) is a competitive robotics team at Georgia Tech. Within this organization, I am a part of the [RoboNav Team](https://robojackets.org/teams/robonav/) working for computer vision projects such as object detection, classification, and point cloud processing using deep learning approach. For further information, please see details below (Photo Credit: RoboJackets).

### Relevant Projects
<ul>{% for post in site.robonav %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## CS7648 Interactive Robot Learning Final Project
![RoboJackets](/images/cs7648/cs7648-method.png)
<br /><br />
In this class, we focused on studying how to retrain reinforcement learning agent with sub-optimal demonstrations using a simulated racing game from [OpenAI](https://github.com/openai/gym/blob/master/gym/envs/box2d/car_racing.py). Due to increased number of available dataset, some dataset contains sub-optimal demonstration that minimizes the agent to learn an optimal solution. Our team integrates Convergent Actor-Critic by Humans (COACH) to retrain a behavior cloning agent trained with sub-optimal demonstration. The proposed method shows strong performance of retrained models by improving the average of 108 % more efficient than the original models. Our final report is available in [this link](images/cs7648/CS7648_Project.pdf).

## Snowzer - An Automated Snowplow 
<img src="/images/robonav/snoozer.png" width="1000" height="60">
<br /><br />
This project is a part of ME6408 Advanced Mechatronics Group Project. The goal is to develop a low cost autonomous snowplow robot that can remove snow from a designated area. I was in charge of software development especially computer vision and navigation tasks. For further information, please visit the following [website](https://bryancochrangt.wixsite.com/snowzer-the-machine) and [video](https://www.youtube.com/watch?v=2S0kVQGPxjE&feature=youtu.be) (Photo Credit: Bryan Cochran).