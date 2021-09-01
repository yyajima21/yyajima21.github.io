---
permalink: /project.html
redirect_from:
  - /project/
title: "Projects"
author_profile: true
---
Over the past few years, I've worked on several projects related to computer vision, machine learning, and robotics. Beside my research work, I am currently a software member at RoboJackets working for perception and scene understanding projects using deep learning approach. In this project pages, I include some projects relevant to machine learning and robotics. 

## CS7641 Machine Learning Final Project
![CS7641](/images/cs7641/cs7641-final-project.png)
<br /><br />
In the [CS7641 course](https://mahdi-roozbahani.github.io/CS46417641-summer2021/), our team developed unsupervised and supervised point cloud clustering and segmentation models using [Stanford 3D Indoor Scene dataset (s3dis)](http://buildingparser.stanford.edu/dataset.html). As more 3D data is captured through 3D Lidar and depth camera sensors, our team focused on developing an efficient way to cluster objects in point cloud and to predict object labels using machine learning and deep learning models. My contribution is a development of deep learning model, named Dynamic Graph PointNet (DGPointNet), and this model combines the benefits of [Dynamic Graph CNN](https://arxiv.org/abs/1801.07829) and [PointNet](https://arxiv.org/abs/1612.00593). For further information, please visit the following [website](https://cs7641-pointcloudsegmentation.github.io/) and [video](https://gtvault-my.sharepoint.com/personal/yyajima3_gatech_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fyyajima3%5Fgatech%5Fedu%2FDocuments%2Fcs7641%5Fproject%2Fcs7641%5Ffinal%5Fproject%2Emp4&parent=%2Fpersonal%2Fyyajima3%5Fgatech%5Fedu%2FDocuments%2Fcs7641%5Fproject).

## CVPR Scan-to-BIM challenge 2021
![CVPR](/images/cvpr-scan2bim/gts2b.png)
<br /><br />
In [the Scan-to-BIM Challenge](https://cv4aec.github.io/), the goal is to reconstruct Building Information Models (BIM) from large scaled indoor and outdoor 3D point cloud data. My contribution includes modifying a 3D deep learning model and conducted a hyperparameter tuning to determine the best model to detects target objects (e.g. ceiling, walls, doors, etc.) Our method, named GTS2B, achieved [a second place](files/2D_SecondPlace_Certificate.pdf) in the 2D reconstruction task. Our recorded presentation can be found in [this link](https://www.youtube.com/watch?v=DR9ifKxutf8&list=TLGG8vy3pvaCCBQwMjA4MjAyMQ&t=1006s).

## RoboJackets
![RoboJackets](/images/robonav/robonav_team.jpg)
<br /><br />
[RoboJackets](https://robojackets.org/) is a competitive robotics team at Georgia Tech. Within this organization, I am a part of the [RoboNav Team](https://robojackets.org/teams/robonav/) working for computer vision projects such as object detection, classification, and point cloud processing using deep learning approach. For further information, please see details below (Photo Credit: RoboJackets).

### Relevant Projects
* [Real-Time Clustering for Lidar Point Cloud Data](https://github.com/RoboJackets/igvc-software/tree/master/igvc_perception/src/pointcloud_segmentation)

* [Multiclass Semantic Segmentation](https://github.com/RoboJackets/igvc-software/tree/master/igvc_perception/src/multiclass_segmentation)

## CS7648 Interactive Robot Learning Final Project
![CS7648](/images/cs7648/cs7648-method.png)
<br /><br />
In this class, we focused on studying how to retrain a reinforcement learning agent with sub-optimal demonstrations using a car racing game from [OpenAI](https://github.com/openai/gym/blob/master/gym/envs/box2d/car_racing.py). Due to increased number of available dataset, some dataset contain sub-optimal demonstrations that minimize the agent to reach to an optimal solution. Our team integrated the Convergent Actor-Critic by Humans (COACH) to retrain a behavior cloning agent trained with sub-optimal demonstrations. The proposed method shows strong performance of retrained models by improving the average of 8 % more efficient than the original models. Our final report is available in [this link](images/cs7648/CS7648_Project.pdf).

## Snowzer - An Automated Snowplow 
<img src="/images/robonav/snoozer.png" width="1000" height="60">
<br /><br />
This project is a part of ME6408 Advanced Mechatronics Group Project. The goal is to develop a low cost autonomous snowplow robot that can remove snow from designated area. I was in charge of software development especially computer vision and navigation tasks. For further information, please visit the following [website](https://bryancochrangt.wixsite.com/snowzer-the-machine) and [video](https://www.youtube.com/watch?v=2S0kVQGPxjE&feature=youtu.be) (Photo Credit: Bryan Cochran).