# [USTC FLICAR: A Sensors Fusion Dataset of Lidar-Inertial-Camera for Heavy-duty Autonomous Aerial Work Robots](https://ustc-flicar.github.io/)

This site presents the USTC FLICAR Dataset, collected from our research on heavy-duty autonomous aerial work robots, featuring a comprehensive set of [sensors](https://ustc-flicar.github.io/sensors/):

* Four 3D LiDARs (Velodyne HDL32/VLP32; LiVOX Avia; Ouster OS0-128)
* Two stereo cameras (Bumblebee XB3/XB2)
* Two monocular cameras (Hikvison; FILR IR)
* Multiple Inertial Measurement Units (IMUs) 
* GNSS/INS system (Xsens MTI-G-710)
* Laser tracker for millimeter-level ground truth positions (API T3 Laser Tracker)

The dataset extends the typical autonomous driving sensing suite to aerial scenes, utilizing the “Giraffe” mapping robot based on a bucket truck. This platform is designed to explore the potential of combining autonomous driving perception systems with aerial work robots. Additionally, we introduce the Semantic FLICAR dataset, which provides fine-grained semantic segmentation annotations for multimodal continuous data in both temporal and spatial dimensions. 

# Citation
If you use some resource from this data suite, please cite it as

```
@article{wang2023ustc,
  title={USTC FLICAR: A sensors fusion dataset of LiDAR-inertial-camera for heavy-duty autonomous aerial work robots},
  author={Wang, Ziming and Liu, Yujiang and Duan, Yifan and Li, Xingchen and Zhang, Xinran and Ji, Jianmin and Dong, Erbao and Zhang, Yanyong},
  journal={The International Journal of Robotics Research},
  volume={42},
  number={11},
  pages={1015--1047},
  year={2023},
  publisher={SAGE Publications Sage UK: London, England}
}
```
[[Journal](https://journals.sagepub.com/doi/abs/10.1177/02783649231195650)][[Preprint](https://arxiv.org/pdf/2304.01986)]

# Updates

**22/01/2025**: Support the SOTA LIVO System [Fast-LIVO2](https://github.com/hku-mars/FAST-LIVO2)!

**01/09/2024**: The [author](https://ustc-flicar.github.io/contact/) came to the [HKU MaRS Lab](https://mars.hku.hk/) for postgraduate study under supervised by [Prof. Fu Zhang](https://scholar.google.com/citations?user=V-eYCF8AAAAJ&hl=zh-CN&oi=ao) and continued his journey in robotics and SLAM