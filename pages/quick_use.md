---
layout: page-fullwidth
title: "Quick Use"
subheadline: "USTC FLICAR Dataset"
teaser: "We have experimented with some state-of-the-art methods on our dataset. And some convenient and useful tools and SDK are provided for using the dataset.</br> If you are seeking to do the same, please check out the following to get the work done quickly."
permalink: "/quick_use/"
header: no
---
<div class="panel radius" markdown="1">
{: #toc }
*  TOC
{:toc}
</div>

### FAST-LIO
**FAST-LIO for USTC FLICAR:**
<a href="https://github.com/ustc-flicar/ustcflicar-FAST-LIO">https://github.com/ustc-flicar/ustcflicar-FAST-LIO</a><br>
**Credit:** Forked from <a href="https://github.com/hku-mars/FAST_LIO">https://github.com/hku-mars/FAST_LIO</a><br>
<p align="center">
    <img src="../data_image/FAST-LIO.png" width="100%"/>
</p>
<p style="text-align: center;">Left:FAST-LIO with Velodyne HDL32E data and Xsens MTi-G-710 data from HF003 sequence<br>Right: FAST-LIO with LiVOX Avia(Lidar and imu) data from HF003 sequence </p>

### VINS-Mono / VINS-Fusion

<font color="red">Note:</font> When we collect data, we start the sensors in order. Before starting a sensor, program need to check whether the previous sensor is working properly. So at the beginning of the rosbag, not all sensors have finished starting. When using a sensor fusion algorithm (such as camera-IMU), you can play rosbag for a period of time (about 10s), and then start the algorithm after all the sensors are started to prevent initialization errors.

**VINS-Mono for USTC FLICAR:**
<a href="https://github.com/ustc-flicar/ustcflicar-VINS-Mono">https://github.com/ustc-flicar/ustcflicar-VINS-Mono</a><br>
**Credit:** Forked from <a href="https://github.com/HKUST-Aerial-Robotics/VINS-Mono">https://github.com/HKUST-Aerial-Robotics/VINS-Mono</a>

**VINS-Fusion for USTC FLICAR:**
<a href="https://github.com/ustc-flicar/ustcflicar-VINS-Fusion">https://github.com/ustc-flicar/ustcflicar-VINS-Fusion</a><br>
**Credit:** Forked from <a href="https://github.com/HKUST-Aerial-Robotics/VINS-Fusion">https://github.com/HKUST-Aerial-Robotics/VINS-Fusion</a>
<p align="center">
    <img src="../data_image/vins-mono-hf001.png" width="100%"/>
</p>
<p style="text-align: center;">Left:VINS-Mono with Hikvision1 data and Xsens MTi-G-710 data from HF003 sequence<br>Right: VINS-Fusion with Bumblebee-xb3-Left/Right data and Xsens MTi-G-710 data from HF003 sequence</p>

### ORB-SLAM3

<font color="red">Note:</font>We found that different versions of ORB SLAM3 codes have different configuration requirements and operating effects in different system environments. We provide two versions of ORB_SLAM3 codes that adapted to our experimental environment (Ubuntu 18.04, ROS melodic).

**ORB-SLAM3 for USTC FLICAR (IMU):**
<a href="https://github.com/ustc-flicar/ustcflicar-ORB-SLAM3-IMU">https://github.com/ustc-flicar/ustcflicar-ORB-SLAM3-IMU</a><br>
**ORB-SLAM3 for USTC FLICAR (no IMU):**
<a href="https://github.com/ustc-flicar/ustcflicar-ORB-SLAM3-no-IMU">https://github.com/ustc-flicar/ustcflicar-ORB-SLAM3-no-IMU</a><br>
**Credit:** Forked from <a href="https://github.com/UZ-SLAMLab/ORB_SLAM3">https://github.com/UZ-SLAMLab/ORB_SLAM3</a><br>

<p align="center">
    <img src="../data_image/orb_slam3.png" width="100%"/>
</p>
<p style="text-align: center;">ORB-SLAM3 with Hikvision1 data and Xsens MTi-G-710 data from HF003 sequence</p>

### A-LOAM
**A-LOAM for USTC FLICAR:**
<a href="https://github.com/ustc-flicar/ustcflicar-A-LOAM">https://github.com/ustc-flicar/ustcflicar-A-LOAM</a><br>
**Credit:** Forked from <a href="https://github.com/HKUST-Aerial-Robotics/A-LOAM">https://github.com/HKUST-Aerial-Robotics/A-LOAM</a><br>
<p align="center">
    <img src="../data_image/hdl-aloam-1-hf001.png" width="100%"/>
</p>
<p style="text-align: center;">A-LOAM with horizontal Velodyne HDL-32E data from HF003 sequence</p>

<p align="center">
    <img src="../data_image/hdl-aloam-2-hf001.png" width="100%"/>
</p>
<p style="text-align: center;">A-LOAM with vertical Velodyne VLP-32C data from HF003 sequence</p>

### LeGO-LOAM
**LeGO-LOAM for USTC FLICAR:**
<a href="https://github.com/ustc-flicar/ustcflicar-LeGO-LOAM">https://github.com/ustc-flicar/ustcflicar-LeGO-LOAM</a><br>
**Credit:** Forked from <a href="https://github.com/RobustFieldAutonomyLab/LeGO-LOAM">https://github.com/RobustFieldAutonomyLab/LeGO-LOAM</a><br>
<p align="center">
    <img src="../data_image/hdl-legoloam-1-hf001.png" width="100%"/>
</p>
<p style="text-align: center;">LeGO-LOAM with horizontal Velodyne HDL-32E data from HF003 sequence</p>
<p align="center">
    <img src="../data_image/hdl-legoloam-2-hf001.png" width="100%"/>
</p>
<p style="text-align: center;">LeGO-LOAM with vertical Velodyne VLP-32C data from HF003 sequence</p>

### LIO-SAM
**LIO-SAM for USTC FLICAR:**
<a href="https://github.com/ustc-flicar/ustcflicar-LIO-SAM">https://github.com/ustc-flicar/ustcflicar-LIO-SAM</a><br>
**Credit:** Forked from <a href="https://github.com/TixiaoShan/LIO-SAM">https://github.com/TixiaoShan/LIO-SAM</a><br>
<p align="center">
    <img src="../data_image/LIO_SAM.png" width="100%"/>
</p>




### Evaluation:EVO
EVO Tools:<a href="https://github.com/MichaelGrupp/evo">https://github.com/MichaelGrupp/evo</a><br>
<img src="../data_image/evo/evo1.png" width="100%"/>
<img src="../data_image/evo/evo3.png" width="100%"/>
<p style="text-align: center;">Overview</p>
