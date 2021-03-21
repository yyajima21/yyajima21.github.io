---
permalink: /project.html
redirect_from:
  - /project/
title: "Projects"
author_profile: true
---
Over the past few years, I've worked on several personal & team projects related to computer vision, machine learning, and robotics. I am currently a software member at RoboJackets working for perception and scene understanding projects using deep learning approach. Beside RoboJackets, I also built an autonomous snowplow robot. During my undergraduate study, I was a mechanical and electrical team member in [GT Solar Racing Team](http://solarracing.gatech.edu/) at [Georgia Tech](https://www.gatech.edu/).

## RoboJackets
![RoboJackets](/images/robonav/robonav_team.jpg)
<br /><br />
[RoboJackets](https://robojackets.org/) is a competitive robotics team at Georgia Tech. Within this organization, I am a part of the [RoboNav Team](https://robojackets.org/teams/robonav/) working for computer vision projects such as object detection, classification, and point cloud processing using deep learning approach. For further information, please see details below (Photo Credit: RoboJackets).

### Relevant Projects
<!-- TODO: Need to learn how to resize images and add a border only top and bottom of table
<table style="border-collapse: collapse; border: none;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
</thead>
<tbody>

<tr style="border: none">
<td markdown="span" style="vertical-align: middle; padding-bottom: 3em; border: none;"><img src="/images/robonav/pointcloud-segmentation-1.png"></td>
<td markdown="span" style="font-size: 16px; vertical-align: middle; padding-bottom: 3em; border: none">
    [Real-Time Clustering for Lidar Point Cloud Data](../_robonav/2020-spring-robonav-1.md)<br>
    RoboNav Software<br>
    [code](https://github.com/RoboJackets/igvc-software/tree/master/igvc_perception/src/pointcloud_segmentation)<br>
    </td>
</tr>

<tr style="border: none">
<td markdown="span" style="vertical-align: middle; padding-bottom: 3em; border: none;"><img src="/images/robonav/semantic-segmentation-1.png"></td>
<td markdown="span" style="font-size: 16px; vertical-align: middle; padding-bottom: 3em; border: none">
    [Multiclass Semantic Segmentation using Pytorch](../_robonav/2020-spring-robonav-2.md)<br>
    RoboNav Software<br>
    [code](https://github.com/RoboJackets/igvc-software/tree/master/igvc_perception/src/multiclass_segmentation)<br>
    </td>
</tr>

</tbody>
</table>
-->
<ul>{% for post in site.robonav %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Snowzer - An Automated Snowplow 
<img src="/images/robonav/snoozer.png" width="1000" height="60">
<br /><br />
This project is a part of ME6408 Advanced Mechatronics Group Project. The goal is to develop a low cost autonomous snowplow robot that can remove snow from a designated area. I was in charge of software development especially computer vision and navigation tasks. For further information, please visit the following [website](https://bryancochrangt.wixsite.com/snowzer-the-machine) and [video](https://www.youtube.com/watch?v=2S0kVQGPxjE&feature=youtu.be) (Photo Credit: Bryan Cochran).

## DIY Self Driving Car
AutoRace is a fully electric 4WD RC vehicle that is capable of autonomous driving. I built this car to enhance my knowledge in robotics and software development of autonomous vehicle. For further information, please see details below.

## GT Solar Racing Team
<img src="images/robonav/gt_solar_racing.jpeg" width="1000" height="60">
Coming soon (Photo Credit: Georgia Tech Solar Racing Team).