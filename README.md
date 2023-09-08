# <p align='center'>`SLAM Useful Papers`</p>

This is a list of papers I found useful and am collecting for my use as well as for others. This is not a complete list, this is just the papers I found, let me know if you think there are some others I should add. I'll try to keep organizing this into subcategories as the papers accumulate.

I might also make notes to make it easier for me to revisit them.
The initial list is credited to RPL. Follow them for interesting slam research.
Follow the numbers next to the list to get an order of reading these papers.



<summary>Table of Content</summary>

- [SLAM Basics](#slam-basics)
- [SLAM/Tracking and Mapping](#slam/tracking-and-mapping)
- [Visual Odometry](#visual-odometry)
- [Visual-Inertial](#visual-inertial)
- [Lidar Odometry](#lidar-odometry)
- [Lidar-Inertial](#lidar-inertial)
- [iSAM](#iSAM)



## SLAM Basics
1. Probabilistic Robotics
2. Factorgraphs for Robot Perception

## SLAM/Tracking and Mapping
1. PTAM: Parallel Tracking and Mapping for Small AR Workspaces (2)
2. ORB-SLAM: A Versatile and Accurate Monocular SLAM System (3)
3. DTAM: Dense Tracking and Mapping in Real-Time (4)
4. LSD-SLAM: Large-Scale Direct Monocular SLAM (6)
5. KinectFusion: Real-Time Dense Surface Mapping and Tracking (8)
6. Kintinuous: Spatially Extended KinectFusion (10)
7. ElasticFusion: Dense SLAM Without A Pose Graph (12)
8. REMODE: Probabilistic, Monocular Dense Reconstruction in Real Time
9. Probabilistic Semi-Dense Mapping from Highly Accurate Feature-Based Monocular SLAM
10. Deformation-based Loop Closure for Large Scale Dense RGB-D SLAM
11. BundleFusion: Real-time Globally Consistent 3D Reconstruction using On-the-fly Surface Re-integration

## Visual Odometry
1. Real-Time Visual Odometry from Dense RGB-D Images
2. Robust Odometry Estimation for RGB-D Cameras (9)
3. SVO: Fast Semi-Direct Monocular Visual Odometry (5)
4. DSO: Direct Sparse Odometry (7)
5. Robust Real-Time Visual Odometry for Dense RGB-D Mapping

## Visual-Inertial
1. Visual-Inertial Monocular SLAM with Map Reuse (13)
2. Keyframe-Based Visual-Inertial SLAM Using Nonlinear Optimization (14)
3. On-manifold preintegration for real-time visual–inertial odometry (15)

## Lidar Odometry
1. Low-drift and Real-time Lidar Odometry and Mapping
2. KISS-ICP: In Defense of Point-to-Point ICP – Simple, Accurate, and Robust Registration If Done the Right Way

## Lidar-Inertial
1. LIO-SAM: Tightly-coupled Lidar Inertial Odometry via
Smoothing and Mapping
2. LeGO-LOAM: Lightweight and Groundoptimized Lidar Odometry and Mapping on Variable Terrain

## iSAM
1. Square Root SAM: Simultaneous Localization and Mapping via Square Root Information Smoothing
2. iSAM: Incremental Smoothing and Mapping
3. iSAM2: Incremental Smoothing and Mapping Using the Bayes Tree
4. (iSAM3) A Nonparametric Belief Solution to the Bayes Tree


## Others
CPA-SLAM: Consistent Plane-Model Alignment for Direct RGB-D SLAM
Efficient Non-Consecutive Feature Tracking for Robust Structure-from-Motion


<!-- ### `New to NeRF`

#### **Begin of NeRF, Always Start Here**

:fire:**NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis**<br>
*Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, Ren Ng*<br>
ECCV 2020, 19 Mar 2020 <br>
[[arXiv](https://arxiv.org/abs/2003.08934)] [[Project](https://www.matthewtancik.com/nerf)] [[Code](https://github.com/bmild/nerf)] [[PyTorch Impl](https://github.com/yenchenlin/nerf-pytorch)] [[Notes](./paper_discussions/NeRF.md)]

#### **NeRF Related Surveys**

:fire:**State of the Art on Neural Rendering**<br>
*Ayush Tewari, Ohad Fried, Justus Thies, Vincent Sitzmann, Stephen Lombardi, Kalyan Sunkavalli, Ricardo Martin-Brualla, Tomas Simon, Jason Saragih, Matthias Nießner, Rohit Pandey, Sean Fanello, Gordon Wetzstein, Jun-Yan Zhu, Christian Theobalt, Maneesh Agrawala, Eli Shechtman, Dan B Goldman, Michael Zollhöfer*<br>
ECCV 2020,8 Apr 2020<br>
[[arXiv](https://arxiv.org/abs/2004.03805)]

:fire:**Advances in Neural Rendering**<br>
*Ayush Tewari, Justus Thies, Ben Mildenhall, Pratul Srinivasan, Edgar Tretschk, Yifan Wang, Christoph Lassner, Vincent Sitzmann, Ricardo Martin-Brualla, Stephen Lombardi, Tomas Simon, Christian Theobalt, Matthias Niessner, Jonathan T. Barron, Gordon Wetzstein, Michael Zollhoefer, Vladislav Golyanik*<br>
ECCV 2022, 10 Nov 2021<br>
[[arXiv](https://arxiv.org/abs/2111.05849)]

:fire:**NeRF: Neural Radiance Field in 3D Vision, A Comprehensive Review**<br>
*Kyle Gao, Yina Gao, Hongjie He, Dening Lu, Linlin Xu, Jonathan Li*<br>
TPAMI 2022, 1 Oct 2022<br>
[[arXiv](https://arxiv.org/abs/2210.00379)]

**Neural Radiance Fields: Past, Present, and Future**<br>
*Ansh Mittal*<br>
In Progress,20 Apr 2023<br>
[[arXiv](https://arxiv.org/abs/2304.10050)]

#### **NeRF Tutorials**

:fire:**Neural Rendering Course**<br>
SIGGRAPH 2021 [[BiliBili](https://www.bilibili.com/video/BV1B3411q7hy)]

:fire:**Neural Volumetric Rendering for Computer Vision**<br>
ECCV 2022 Tutorial [[Website](https://sites.google.com/berkeley.edu/nerf-tutorial/home)]

:fire:**Scaling NeRF Up and Down: Big Scenes and Real-Time View Synthesis**<br>
I3D 2023 Keynote [[Video](https://www.bilibili.com/video/BV1fh4y1t7rW/)]

#### **NeRF OpenSource Tools**

:fire:**Nerfstudio: A Modular Framework for Neural Radiance Field Development**<br>
*Matthew Tancik, Ethan Weber, Evonne Ng, Ruilong Li, Brent Yi, Justin Kerr, Terrance Wang, Alexander Kristoffersen, Jake Austin, Kamyar Salahi, Abhik Ahuja, David McAllister, Angjoo Kanazawa*<br>
arXiv preprint, 8 Feb 2023<br>
>Nerfstudio provides a simple API that allows for a simplified end-to-end process of creating, training, and visualizing NeRFs. The library supports an interpretable implementation of NeRFs by modularizing each component.<br>

[[arXiv](https://arxiv.org/abs/2302.04264)] [[Website](https://docs.nerf.studio/en/latest/#)] [[Github](https://github.com/nerfstudio-project/nerfstudio)]

:fire:**NerfAcc: Efficient Sampling Accelerates NeRFs**<br>
*Ruilong Li, Hang Gao, Matthew Tancik, Angjoo Kanazawa*<br>
arXiv preprint, 8 May 2023<br>
>NerfAcc is a PyTorch Nerf acceleration toolbox for both training and inference. It focus on efficient sampling in the volumetric rendering pipeline of radiance fields, which is universal and plug-and-play for most of the NeRFs. With minimal modifications to the existing codebases, Nerfacc provides significant speedups in training various recent NeRF papers. And it is pure Python interface with flexible APIs!<br>

[[arXiv](https://arxiv.org/abs/2305.04966)] [[Website](https://www.nerfacc.com/en/latest/index.html)]  [[Github](https://github.com/KAIR-BAIR/nerfacc)]

:fire:**threestudio: A unified framework for 3D content generation**<br>
*Yuan-Chen Guo and Ying-Tian Liu and Chen Wang and Zi-Xin Zou and Guan Luo and Chia-Hao Chen and Yan-Pei Cao and Song-Hai Zhang*<br>
Github repo,2023<br>
>threestudio is a unified framework for 3D content creation from text prompts, single images, and few-shot images, by lifting 2D text-to-image generation models.

[[Github](https://github.com/threestudio-project/threestudio)]

### `NeRF Fundamental Enhancements`

:fire:**NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections**<br>
*Ricardo Martin-Brualla, Noha Radwan, Mehdi S. M. Sajjadi, Jonathan T. Barron, Alexey Dosovitskiy, Daniel Duckworth*<br>
CVPR 2021, 5 Aug 2020 <br>
[[arXiv](https://arxiv.org/abs/2008.02268)] [[Project](https://nerf-w.github.io/)] -->
