<p align="center">
  <h1 align="center">
  Awesome 3DGS SLAM
  </h1>
</p>

This repository contains a curated list of resources addressing the 3DGS (3D Gaussian Splatting) SLAM, includinig image sensor, event camera, and LiDAR, etc.

If you find some ignored papers, **feel free to [*create pull requests*](https://github.com/KwanWaiPang/Awesome-Transformer-based-SLAM/blob/pdf/How-to-PR.md), or [*open issues*](https://github.com/KwanWaiPang/Awesome-3DGS-SLAM/issues/new)**. 

Contributions in any form to make this list more comprehensive are welcome.

If you find this repository useful, a simple star should be the best affirmation. 😊

Feel free to share this list with others!

# Overview
- [Image-based 3DGS](#Image-based-3DGS)
- [LiDAR-based 3DGS](#LiDAR-based-3DGS)
- [Event-based 3DGS](#Event-based-3DGS)



<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->
## Image-based 3DGS

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`ICRA`|[RGB-Only Gaussian Splatting SLAM for Unbounded Outdoor Scenes](https://arxiv.org/pdf/2502.15633?)|[![Github stars](https://img.shields.io/github/stars/3DAgentWorld/OpenGS-SLAM.svg)](https://github.com/3DAgentWorld/OpenGS-SLAM)|[website](https://3dagentworld.github.io/opengs-slam/)| 
|2025|`ICCV`|[Outdoor Monocular SLAM with Global Scale-Consistent 3D Gaussian Pointmaps](https://arxiv.org/pdf/2507.03737)|[![Github stars](https://img.shields.io/github/stars/3DAgentWorld/S3PO-GS.svg)](https://github.com/3DAgentWorld/S3PO-GS)|[website](https://3dagentworld.github.io/S3PO-GS/)|
|2025|`IEEE Transactions on Artificial Intelligence`|[Constrained Gaussian Splatting via Implicit TSDF Hash Grid for Dense RGB-D SLAM](https://ieeexplore.ieee.org/abstract/document/11060934)|---|---|
|2025|`Joint International Conference on Automation-Intelligence-Safety`|[Mono-SLAM: Monocular 3D Gaussian Splatting SLAM with Geometric Loss and Multi-view Consistency](https://ieeexplore.ieee.org/abstract/document/11051648)|---|---|
|2025|`RAL`|[FusionGS-SLAM: Multiple Sensors Fusion for Localization and Real-Time Photorealistic Mapping](https://ieeexplore.ieee.org/abstract/document/11066268/)|---|---|
|2025|`RAL`|[SAGA-SLAM: Scale-Adaptive 3D Gaussian Splatting for Visual SLAM](https://ieeexplore.ieee.org/abstract/document/11067946/)|---|---|
|2025|`arXiv`|[GRAND-SLAM: Local Optimization for Globally Consistent Large-Scale Multi-Agent Gaussian SLAM](https://arxiv.org/pdf/2506.18885)|---|---|
|2025|`RAL`|[Dense Monocular SLAM in Real-time with Structured Gaussian Representation](https://ieeexplore.ieee.org/abstract/document/11052667/)|---|---|
|2025|`arXiv`|[TVG-SLAM: Robust Gaussian Splatting SLAM with Tri-view Geometric Constraints](https://arxiv.org/pdf/2506.23207)|---|---| 
|2025|`arXiv`|[GRAND-SLAM: Local Optimization for Globally Consistent Large-Scale Multi-Agent Gaussian SLAM](https://arxiv.org/pdf/2506.18885)|---|---|
|2025|`IROS`|[SplatPose: Geometry-Aware 6-DoF Pose Estimation from Single RGB Image via 3D Gaussian Splatting](https://arxiv.org/pdf/2503.05174?)|---|---|
|2025|`TASE`|[MG-SLAM: Structure Gaussian Splatting SLAM with Manhattan World Hypothesis](https://ieeexplore.ieee.org/abstract/document/11029049)|---|---|
|2025|`arXiv`|[Dy3DGS-SLAM: Monocular 3D Gaussian Splatting SLAM for Dynamic Environments](https://arxiv.org/pdf/2506.05965)|---|---|
|2025|`arXiv`|[GS4: Generalizable Sparse Splatting Semantic SLAM](https://arxiv.org/pdf/2506.06517)|---|[website](https://mingqij.github.io/projects/gs4/)|
|2025|`International Conference on Autonomous Agents and Multiagent Systems`|[OGS-SLAM: Hybrid ORB-Gaussian Splatting SLAM](https://dl.acm.org/doi/abs/10.5555/3709347.3743762)|[![Github stars](https://img.shields.io/github/stars/realXiaohan/OGS-SLAM.svg)](https://github.com/realXiaohan/OGS-SLAM)|---|
|2025|`arXiv`|[Globally Consistent RGB-D SLAM with 2D Gaussian Splatting](https://arxiv.org/pdf/2506.00970)|[![Github stars](https://img.shields.io/github/stars/PRBonn/2DGS-SLAM.svg)](https://github.com/PRBonn/2DGS-SLAM)|MASt3R for Loop Closure|
|2025|`arXiv`|[VTGaussian-SLAM: RGBD SLAM for Large Scale Scenes with Splatting View-Tied 3D Gaussians](https://arxiv.org/pdf/2506.02741)|---|[website](https://machineperceptionlab.github.io/VTGaussian-SLAM-Project/)|
|2025|`arXiv`|[VPGS-SLAM: Voxel-based Progressive 3D Gaussian SLAM in Large-Scale Scenes](https://arxiv.org/pdf/2505.18992)|[![Github stars](https://img.shields.io/github/stars/dtc111111/vpgs-slam.svg)](https://github.com/dtc111111/vpgs-slam)|---| 
|2025|`arXiv`|[ADD-SLAM: Adaptive Dynamic Dense SLAM with Gaussian Splatting](https://arxiv.org/pdf/2505.19420)|---|---|
|2025|`arXiv`|[LGSBA: Local Gaussian Splatting Bundle Adjustment for Optimizing 3DGS Rendering Quality](https://www.preprints.org/frontend/manuscript/ddecffbfbb0306ab43042be32552275f/download_pub)|[![Github stars](https://img.shields.io/github/stars/wla-98/worse-pose-but-better-3DGS.svg)](https://github.com/wla-98/worse-pose-but-better-3DGS)|---| 
|2025|`CVPR`|[4DTAM: Non-Rigid Tracking and Mapping via Dynamic Surface Gaussians](https://muskie82.github.io/4dtam/paper/4dtam_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/muskie82/4dtam.svg)](https://github.com/muskie82/4dtam)|[website](https://muskie82.github.io/4dtam/)| 
|2025|`arXiv`|[UP-SLAM: Adaptively Structured Gaussian SLAM with Uncertainty Prediction in Dynamic Environments](https://arxiv.org/pdf/2505.22335)|---|[website](https://aczheng-cai.github.io/up_slam.github.io/)|
|2025|`arXiv`|[DynaGSLAM: Real-Time Gaussian-Splatting SLAM for Online Rendering, Tracking, Motion Predictions of Moving Objects in Dynamic Scenes](https://arxiv.org/pdf/2503.11979)|[![Github stars](https://img.shields.io/github/stars/BlarkLee/DynaGSLAM_official.svg)](https://github.com/BlarkLee/DynaGSLAM_official)|[website](https://blarklee.github.io/dynagslam/)| 
|2025|`arXiv`|[Large-Scale Gaussian Splatting SLAM](https://arxiv.org/pdf/2505.09915)|---|[website](https://lsgsslam.github.io/)| 
|2025|`IEEE-SJ`|[DSOSplat: Monocular 3D Gaussian SLAM with Direct Tracking](https://ieeexplore.ieee.org/abstract/document/10994228/)|---|---|
|2025|`arXiv`|[GauS-SLAM: Dense RGB-D SLAM with Gaussian Surfels](https://arxiv.org/pdf/2505.01934)|[![Github stars](https://img.shields.io/github/stars/gaus-slam/gaus-slam.svg)](https://github.com/gaus-slam/gaus-slam)|[website](https://gaus-slam.github.io/)| 
|2025|`RSS`|[GauSS-MI: Gaussian Splatting Shannon Mutual Information for Active 3D Reconstruction](https://arxiv.org/pdf/2504.21067)|[![Github stars](https://img.shields.io/github/stars/JohannaXie/GauSS-MI.svg)](https://github.com/JohannaXie/GauSS-MI)|---|
|2025|`arXiv`|[GSFF-SLAM: 3D Semantic Gaussian Splatting SLAM via Feature Field](https://arxiv.org/pdf/2504.19409)|---|---|
|2025|`arXiv`|[GSFeatLoc: Visual Localization Using Feature Correspondence on 3D Gaussian Splatting](https://arxiv.org/pdf/2504.20379)|---|---|
|2025|`CVPR`|[SmallGS: Gaussian Splatting Based Camera Pose Estimation for Small-Baseline Videos](https://arxiv.org/pdf/2504.17810)|---|[website](https://yuxinyao620.github.io/SmallGS/)<br>MonST3R+3DGS| 
|2025|`arXiv`|[Enhancing Gaussian Splatting SLAM with Feature-based Tracking](https://lamor.fer.hr/images/50050805/gsslam.pdf)|---|---| 
|2025|`arXiv`|[ToF-Splatting: Dense SLAM using Sparse Time-of-Flight Depth and Multi-Frame Integration](https://arxiv.org/pdf/2504.16545)|---|---|
|2025|`RAL`|[SDD-SLAM: Semantic-Driven Dynamic SLAM with Gaussian Splatting](https://ieeexplore.ieee.org/abstract/document/10966164)|---|---| 
|2025|`IEEE Sensors Journal`|[Dynamic SLAM with 3D Gaussian Splatting Supporting Monocular Sensing](https://ieeexplore.ieee.org/abstract/document/10970383/)|---|---|
|2025|`arXiv`|[SLAM&Render: A Benchmark for the Intersection Between Neural Rendering, Gaussian Splatting and SLAM](https://arxiv.org/pdf/2504.13713)|[![Github stars](https://img.shields.io/github/stars/samuel-cerezo/SLAM-Render.svg)](https://github.com/samuel-cerezo/SLAM-Render)|[website](https://samuel-cerezo.github.io/SLAM&Render)<br>dataset|
|2025|`arXiv`|[Direct Sparse Odometry with Continuous 3D Gaussian Maps for Indoor Environments](https://arxiv.org/pdf/2503.03373)|[![Github stars](https://img.shields.io/github/stars/JD-hust/gs-dso.svg)](https://github.com/JD-hust/gs-dso)|---|
|2025|`CVPR`|[MAGiC-SLAM: Multi-Agent Gaussian Globally Consistent SLAM](https://arxiv.org/pdf/2411.16785)|[![Github stars](https://img.shields.io/github/stars/VladimirYugay/MAGiC-SLAM.svg)](https://github.com/VladimirYugay/MAGiC-SLAM)|[website](https://vladimiryugay.github.io/magic_slam/)|
|2025|`arXiv`|[4D Gaussian Splatting SLAM](https://arxiv.org/pdf/2503.16710)|[![Github stars](https://img.shields.io/github/stars/yanyan-li/4DGS-SLAM.svg)](https://github.com/yanyan-li/4DGS-SLAM)|[website](https://yanyan-li.github.io/project/gs/4dgsslam.html)| 
|2025|`arXiv`|[GI-SLAM: Gaussian-Inertial SLAM](https://arxiv.org/pdf/2503.18275)|---|---| 
|2025|`arXiv`|[FGS-SLAM: Fourier-based Gaussian Splatting for Real-time SLAM with Sparse and Dense Map Fusion](https://arxiv.org/pdf/2503.01109)|---|---|
|2025|`ICRA`|[OpenGS-SLAM: Open-Set Dense Semantic SLAM with 3D Gaussian Splatting for Object-Level Scene Understanding](https://arxiv.org/pdf/2503.01646?)|[![Github stars](https://img.shields.io/github/stars/YOUNG-bit/open_semantic_slam.svg)](https://github.com/YOUNG-bit/open_semantic_slam)|[website](https://young-bit.github.io/opengs-github.github.io/)|
|2025|`arXiv`|[VIGS SLAM: IMU-based Large-Scale 3D Gaussian Splatting SLAM](https://arxiv.org/pdf/2501.13402)|---|---|
|2025|`arXiv`|[Embracing Dynamics: Dynamics-aware 4D Gaussian Splatting SLAM](https://arxiv.org/pdf/2504.04844)|---|---|
|2025|`arXiv`|[Monogs++: Fast and accurate monocular rgb gaussian slam](https://arxiv.org/pdf/2504.02437)|---|---|
|2025|`RAL`|[RGBDS-SLAM: A RGB-D Semantic Dense SLAM Based on 3D Multi Level Pyramid Gaussian Splatting](https://arxiv.org/pdf/2412.01217)|[![Github stars](https://img.shields.io/github/stars/zhenzhongcao/RGBDS-SLAM.svg)](https://github.com/zhenzhongcao/RGBDS-SLAM)|---|
|2025|`arXiv`|[VINGS-Mono: Visual-Inertial Gaussian Splatting Monocular SLAM in Large Scenes](https://arxiv.org/pdf/2501.08286)|---|[website](https://vings-mono.github.io/)|
|2025|`CVPR`|[WildGS-SLAM: Monocular Gaussian Splatting SLAM in Dynamic Environments](https://arxiv.org/pdf/2504.03886)|[![Github stars](https://img.shields.io/github/stars/GradientSpaces/WildGS-SLAM.svg)](https://github.com/GradientSpaces/WildGS-SLAM)|[website](https://wildgs-slam.github.io/)|
|2025|`arXiv`|[GARAD-SLAM: 3D GAussian splatting for Real-time Anti Dynamic SLAM](https://arxiv.org/pdf/2502.03228)|---|---|
|2025|`arXiv`|[GS-GVINS: A Tightly-integrated GNSS-Visual-Inertial Navigation System Augmented by 3D Gaussian Splatting](https://arxiv.org/pdf/2502.10975)|---|---|
|2024|`arXiv`|[FlashSLAM: Accelerated RGB-D SLAM for Real-Time 3D Scene Reconstruction with Gaussian Splatting](https://arxiv.org/pdf/2412.00682)|[![Github stars](https://img.shields.io/github/stars/flashslam/FlashSLAM.svg)](https://github.com/flashslam/FlashSLAM)|[website](https://flashslam.github.io/)|
|2024|`arXiv`|[PG-SLAM: Photo-realistic and Geometry-aware RGB-D SLAM in Dynamic Environments](https://arxiv.org/pdf/2411.15800)|---|---|
|2024|`ECCV`|[6dgs: 6d pose estimation from a single image and a 3d gaussian splatting model](https://arxiv.org/pdf/2407.15484)|[![Github stars](https://img.shields.io/github/stars/mbortolon97/6dgs.svg)](https://github.com/mbortolon97/6dgs)|[website](https://mbortolon97.github.io/6dgs/)|
|2024|`arXiv`|[Splat-slam: Globally optimized rgb-only slam with 3d gaussians](https://arxiv.org/pdf/2405.16544)|[![Github stars](https://img.shields.io/github/stars/eriksandstroem/Splat-SLAM.svg)](https://github.com/eriksandstroem/Splat-SLAM)|---|
|2024|`arXiv`|[TAMBRIDGE: Bridging Frame-Centered Tracking and 3D Gaussian Splatting for Enhanced SLAM](https://arxiv.org/pdf/2405.19614)|[![Github stars](https://img.shields.io/github/stars/ZeldaFromHeaven/TAMBRIDGE-DAVID.svg)](https://github.com/ZeldaFromHeaven/TAMBRIDGE-DAVID)|[website](https://zeldafromheaven.github.io/TAMBRIDGE/)|
|2024|`arXiv`|[HI-SLAM2: Geometry-Aware Gaussian SLAM for Fast Monocular Scene Reconstruction](https://arxiv.org/pdf/2411.17982)|[![Github stars](https://img.shields.io/github/stars/Willyzw/HI-SLAM2.svg)](https://github.com/Willyzw/HI-SLAM2)|[website](https://hi-slam2.github.io/)|
|2024|`NIPS`|[DG-SLAM: Robust Dynamic Gaussian Splatting SLAM with Hybrid Pose Optimization](https://arxiv.org/pdf/2411.08373)|[![Github stars](https://img.shields.io/github/stars/fudan-zvg/DG-SLAM.svg)](https://github.com/fudan-zvg/DG-SLAM)|---|
|2025|`ICRA`|[Gassidy: Gaussian Splatting SLAM in Dynamic Environments](https://arxiv.org/pdf/2411.15476)|---|[website](https://wen950223.wixsite.com/gassidy-slam-1)|
|2024|`arXiv`|[DGS-SLAM: Gaussian Splatting SLAM in Dynamic Environment](https://arxiv.org/pdf/2411.10722)|[![Github stars](https://img.shields.io/github/stars/kmk97/DGS-SLAM.svg)](https://github.com/kmk97/DGS-SLAM)|---|
|2024|`International Conference on Robotics, Control and Automation Engineering`|[Motiongs: Compact gaussian splatting slam by motion filter](https://arxiv.org/pdf/2405.11129)|---|---|
|2024|`arXiv`|[Ngm-slam: Gaussian splatting slam with radiance field submap](https://arxiv.org/pdf/2405.05702)|---|---|
|2024|`arXiv`|[Monocular gaussian slam with language extended loop closure](https://arxiv.org/pdf/2405.13748)|---|---|
|2024|`RAL`|[Mgs-slam: Monocular sparse tracking and gaussian mapping with depth smooth regularization](https://arxiv.org/pdf/2405.06241)|---|---|
|2024|`ACM SIGGRAPH`|[Rtg-slam: Real-time 3d reconstruction at scale using gaussian splatting](https://arxiv.org/pdf/2404.19706?)|[![Github stars](https://img.shields.io/github/stars/MisEty/RTG-SLAM.svg)](https://github.com/MisEty/RTG-SLAM)|[website](https://gapszju.github.io/RTG-SLAM/)|
|2024|`arXiv`|[3dgs-reloc: 3d gaussian splatting for map representation and visual relocalization](https://arxiv.org/pdf/2403.11367)|---|---|
|2024|`ECCV`|[Rgbd gs-icp slam](https://arxiv.org/pdf/2403.12550)|[![Github stars](https://img.shields.io/github/stars/Lab-of-AI-and-Robotics/GS_ICP_SLAM.svg)](https://github.com/Lab-of-AI-and-Robotics/GS_ICP_SLAM)|---|
|2024|`ECCV`|[Cg-slam: Efficient dense rgb-d slam in a consistent uncertainty-aware 3d gaussian field](https://arxiv.org/pdf/2403.16095)|[![Github stars](https://img.shields.io/github/stars/hjr37/CG-SLAM.svg)](https://github.com/hjr37/CG-SLAM)|[website](https://zju3dv.github.io/cg-slam/)| 
|2024|`IROS`|[Mm3dgs slam: Multi-modal 3d gaussian splatting for slam using vision, depth, and inertial measurements](https://arxiv.org/pdf/2404.00923)|[![Github stars](https://img.shields.io/github/stars/VITA-Group/MM3DGS-SLAM.svg)](https://github.com/VITA-Group/MM3DGS-SLAM)|[website](https://vita-group.github.io/MM3DGS-SLAM/)| 
|2024|`RAL`|[Neds-slam: A neural explicit dense semantic slam framework using 3d gaussian splatting](https://arxiv.org/pdf/2403.11679)|---|---|
|2024|`IROS`|[High-fidelity slam using gaussian splatting with rendering-guided densification and regularized optimization](https://arxiv.org/pdf/2403.12535)|[![Github stars](https://img.shields.io/github/stars/ljjTYJR/HF-SLAM.svg)](https://github.com/ljjTYJR/HF-SLAM)|---|
|2024|`arXiv`|[Semgauss-slam: Dense semantic gaussian splatting slam](https://arxiv.org/pdf/2403.07494)|---|---|
|2024|`ECCV`|[Sgs-slam: Semantic gaussian splatting for neural dense slam](https://arxiv.org/pdf/2402.03246)|[![Github stars](https://img.shields.io/github/stars/ShuhongLL/SGS-SLAM.svg)](https://github.com/ShuhongLL/SGS-SLAM)|---|
|2024|`CVPR`|[Photo-slam: Real-time simultaneous localization and photorealistic mapping for monocular stereo and rgb-d cameras](https://openaccess.thecvf.com/content/CVPR2024/papers/Huang_Photo-SLAM_Real-time_Simultaneous_Localization_and_Photorealistic_Mapping_for_Monocular_Stereo_CVPR_2024_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/HuajianUP/Photo-SLAM.svg)](https://github.com/HuajianUP/Photo-SLAM)|[website](https://huajianup.github.io/research/Photo-SLAM/)|
|2024|`CVPR`|[Gaussian splatting slam](https://openaccess.thecvf.com/content/CVPR2024/papers/Matsuki_Gaussian_Splatting_SLAM_CVPR_2024_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/muskie82/MonoGS.svg)](https://github.com/muskie82/MonoGS)|[website](https://rmurai.co.uk/projects/GaussianSplattingSLAM/)<br>MonoGS|
|2024|`CVPR`|[Splatam: Splat track & map 3d gaussians for dense rgb-d slam](https://openaccess.thecvf.com/content/CVPR2024/papers/Keetha_SplaTAM_Splat_Track__Map_3D_Gaussians_for_Dense_RGB-D_CVPR_2024_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/spla-tam/SplaTAM.svg)](https://github.com/spla-tam/SplaTAM)|[website](https://spla-tam.github.io/)|
|2024|`CVPR`|[Gs-slam: Dense visual slam with 3d gaussian splatting](https://openaccess.thecvf.com/content/CVPR2024/papers/Yan_GS-SLAM_Dense_Visual_SLAM_with_3D_Gaussian_Splatting_CVPR_2024_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/yanchi-3dv/diff-gaussian-rasterization-for-gsslam.svg)](https://github.com/yanchi-3dv/diff-gaussian-rasterization-for-gsslam)|[website](https://gs-slam.github.io/)|
|2023|`arXiv`|[Gaussian-slam: Photo-realistic dense slam with gaussian splatting](https://arxiv.org/pdf/2312.10070)|[![Github stars](https://img.shields.io/github/stars/VladimirYugay/Gaussian-SLAM.svg)](https://github.com/VladimirYugay/Gaussian-SLAM)|[website](https://vladimiryugay.github.io/gaussian_slam/)|

## LiDAR-based 3DGS
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`ICCV`|[GS-LIVM: Real-Time Photo-Realistic LiDAR-Inertial-Visual Mapping with Gaussian Splatting](https://arxiv.org/pdf/2410.17084)|[![Github stars](https://img.shields.io/github/stars/xieyuser/GS-LIVM.svg)](https://github.com/xieyuser/GS-LIVM)|---|
|2025|`arXiv`|[Gaussian-LIC2: LiDAR-Inertial-Camera Gaussian Splatting SLAM](https://arxiv.org/pdf/2507.04004)|[![Github stars](https://img.shields.io/github/stars/APRIL-ZJU/Gaussian-LIC.svg)](https://github.com/APRIL-ZJU/Gaussian-LIC)|[website](https://xingxingzuo.github.io/gaussian_lic/)|[website](https://xingxingzuo.github.io/gaussian_lic2/)|
|2025|`arXiv`|[Splat-LOAM: Gaussian Splatting LiDAR Odometry and Mapping](https://arxiv.org/pdf/2503.17491)|[![Github stars](https://img.shields.io/github/stars/rvp-group/Splat-LOAM.svg)](https://github.com/rvp-group/Splat-LOAM)|[Test](https://kwanwaipang.github.io/Splat-LOAM/)|
|2025|`arXiv`|[GS-LIVO: Real-Time LiDAR, Inertial, and Visual Multi-sensor Fused Odometry with Gaussian Mapping](https://arxiv.org/pdf/2501.08672)|[![Github stars](https://img.shields.io/github/stars/HKUST-Aerial-Robotics/GS-LIVO.svg)](https://github.com/HKUST-Aerial-Robotics/GS-LIVO) |---|
|2025|`TIM`|[LVI-GS: Tightly-coupled LiDAR-Visual-Inertial SLAM using 3D Gaussian Splatting](https://ieeexplore.ieee.org/abstract/document/10926911)|---|[website](https://kwanwaipang.github.io/LVI-GS/)|
|2024|`RAL`|[LiV-GS: LiDAR-Vision Integration for 3D Gaussian Splatting SLAM in Outdoor Environments](https://arxiv.org/pdf/2411.12185)|---|---|
|2025|`ICRA`|[Gaussian-lic: Photo-realistic lidar-inertial-camera slam with 3d gaussian splatting](https://arxiv.org/pdf/2404.06926)|[![Github stars](https://img.shields.io/github/stars/APRIL-ZJU/Gaussian-LIC.svg)](https://github.com/APRIL-ZJU/Gaussian-LIC)|[website](https://xingxingzuo.github.io/gaussian_lic/)|
|2024|`ECCV`|[TCLC-GS: Tightly Coupled LiDAR-Camera Gaussian Splatting for Autonomous Driving: Supplementary Materials](https://arxiv.org/pdf/2404.02410)|---|---|
|2024|`IROS`|[MM-Gaussian: 3D Gaussian-based multi-modal fusion for localization and reconstruction in unbounded scenes](https://arxiv.org/pdf/2404.04026)|---|---|
|2024|`RAL`|[LIV-GaussMap: LiDAR-inertial-visual fusion for real-time 3D radiance field map rendering](https://arxiv.org/pdf/2401.14857)|[![Github stars](https://img.shields.io/github/stars/sheng00125/LIV-GaussMap.svg)](https://github.com/sheng00125/LIV-GaussMap)|---| 
|2024|`CVPR`|[Drivinggaussian: Composite gaussian splatting for surrounding dynamic autonomous driving scenes](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhou_DrivingGaussian_Composite_Gaussian_Splatting_for_Surrounding_Dynamic_Autonomous_Driving_Scenes_CVPR_2024_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/VDIGPKU/DrivingGaussian.svg)](https://github.com/VDIGPKU/DrivingGaussian)|---|

## Event-based 3DGS
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`CVPR`|[DiET-GS: Diffusion Prior and Event Stream-Assisted Motion Deblurring 3D Gaussian Splatting Supplementary Material](https://openaccess.thecvf.com/content/CVPR2025/papers/Lee_DiET-GS_Diffusion_Prior_and_Event_Stream-Assisted_Motion_Deblurring_3D_Gaussian_CVPR_2025_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/DiET-GS/DiET-GS.svg)](https://github.com/DiET-GS/DiET-GS)|[website](https://diet-gs.github.io/)|
|2025|`arXiv`|[GS2E: Gaussian Splatting is an Effective Data Generator for Event Stream Generation](https://arxiv.org/pdf/2505.15287)|[![Github stars](https://img.shields.io/github/stars/PKU-YuanGroup/GS2E.svg)](https://github.com/PKU-YuanGroup/GS2E) |[website](https://intothemild.github.io/GS2E.github.io/)|
|2025|`arXiv`|[EBAD-Gaussian: Event-driven Bundle Adjusted Deblur Gaussian Splatting](https://arxiv.org/pdf/2504.10012)|---|---|
|2025|`AAAI`|[SpikeGS: Reconstruct 3D Scene Captured by a Fast-Moving Bio-Inspired Camera](https://ojs.aaai.org/index.php/AAAI/article/view/32340/34495)|[![Github stars](https://img.shields.io/github/stars/yijiaguo02/SpikeGS.svg)](https://github.com/yijiaguo02/SpikeGS)|[website](https://spikegs.github.io/)|
|2025|`AAAI`|[EvHDR-GS: Event-guided HDR Video Reconstruction with 3D Gaussian Splatting](https://ojs.aaai.org/index.php/AAAI/article/view/32237/34392)|---|---|
|2025|`3DV`|[E-3DGS: Event-based Novel View Rendering of Large-scale Scenes Using 3D Gaussian Splatting](https://arxiv.org/pdf/2502.10827)|[![Github stars](https://img.shields.io/github/stars/sohaib023/E-3DGS.svg)](https://github.com/sohaib023/E-3DGS)|[website](https://4dqv.mpi-inf.mpg.de/E3DGS/)<br>[test](https://kwanwaipang.github.io/E-3DGS/)|
|2024|`arXiv`|[IncEventGS: Pose-Free Gaussian Splatting from a Single Event Camera](https://arxiv.org/pdf/2410.08107)|[![Github stars](https://img.shields.io/github/stars/WU-CVGL/IncEventGS.svg)](https://github.com/WU-CVGL/IncEventGS)|---|
|2024|`arXiv`|[EventSplat: 3D Gaussian Splatting from Moving Event Cameras for Real-time Rendering](https://arxiv.org/pdf/2412.07293)|---|---|
|2024|`Asia Pacific Signal and Information Processing Association Annual Summit and Conference`|[Ev3DGS: Event Enhanced 3D Gaussian Splatting from Blurry Images](http://www.apsipa2024.org/files/papers/253.pdf)|[![Github stars](https://img.shields.io/github/stars/npucvr/Ev3DGS.svg)](https://github.com/npucvr/Ev3DGS)|---|
|2024|`IEEE International Conference on Image Processing`|[E2gs: Event enhanced gaussian splatting](https://arxiv.org/pdf/2406.14978)|[![Github stars](https://img.shields.io/github/stars/deguchihiroyuki/E2GS.svg)](https://github.com/deguchihiroyuki/E2GS)|---|
|2024|`arXiv`|[Evagaussians: Event stream assisted gaussian splatting from blurry images](https://arxiv.org/pdf/2405.20224)|[![Github stars](https://img.shields.io/github/stars/PKU-YuanGroup/EvaGaussians.svg)](https://github.com/PKU-YuanGroup/EvaGaussians)|[website](https://www.falcary.com/EvaGaussians/)| 
|2024|`CoRL`|[Event3dgs: Event-based 3d gaussian splatting for fast egomotion](https://arxiv.org/pdf/2406.02972)|---|[website](https://tyxiong23.github.io/event3dgs)|
|2024|`ICML`|[Evggs: A collaborative learning framework for event-based generalizable gaussian splatting](https://arxiv.org/pdf/2405.14959)|[![Github stars](https://img.shields.io/github/stars/Mercerai/EvGGS.svg)](https://github.com/Mercerai/EvGGS)|---| 




## Other Resources
* [MrNeRF's Awesome 3DGS](https://github.com/MrNeRF/awesome-3D-gaussian-splatting)
* [convert 3D meshes into 3DGS](https://github.com/electronicarts/mesh2splat)
* Survey for SLAM in Legged Robot：[Paper List](https://github.com/KwanWaiPang/Awesome-Legged-Robot-Localization-and-Mapping) 
* Survey for Learning-based VO,VIO,IO：[Paper List](https://github.com/KwanWaiPang/Awesome-Learning-based-VO-VIO) 
* Survey for Transformer-based SLAM：[Paper List](https://github.com/KwanWaiPang/Awesome-Transformer-based-SLAM) 
* Survey for Diffusion-based SLAM：[Paper List](https://github.com/KwanWaiPang/Awesome-Diffusion-based-SLAM) 
* Survey for NeRF-based SLAM：[Blog](https://blog.csdn.net/gwplovekimi/article/details/135083274)
* Survey for Deep IMU-Bias Inference [Blog](https://kwanwaipang.github.io/Deep-IMU-Bias/)
* Paper Survey for Degeneracy of LiDAR-SLAM [Blog](https://kwanwaipang.github.io/Lidar_Degeneracy/)
* Paper Survey for dynamic SLAM [Blog](https://kwanwaipang.github.io/Dynamic-SLAM/)
* Reproduction and Learning for LOAM Series [Blog](https://blog.csdn.net/gwplovekimi/article/details/119711762?spm=1001.2014.3001.5502)
* A geometry-shader-based, global CUDA sorted high-performance 3D Gaussian Splatting rasterizer. Can achieve a 5-10x speedup in rendering compared to the vanialla diff-gaussian-rasterization.[fast-gaussian-rasterization](https://github.com/dendenxu/fast-gaussian-rasterization)
* Other related papers:
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`arXiv`|[Revisiting Depth Representations for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/pdf/2506.05327)|[![Github stars](https://img.shields.io/github/stars/aim-uofa/PM-Loss.svg)](https://github.com/aim-uofa/PM-Loss)|[website](https://aim-uofa.github.io/PMLoss/)|
|2025|`arXiv`|[Voyager: Real-Time Splatting City-Scale 3D Gaussians on Your Phone](https://arxiv.org/pdf/2506.02774)|---|[website](https://voyager-web.netlify.app/)|
|2025|`arXiv`|[R3GS: Gaussian Splatting for Robust Reconstruction and Relocalization in Unconstrained Image Collections](https://arxiv.org/pdf/2505.15294)|---|---|
|2025|`arXiv`|[Recollection from Pensieve: Novel View Synthesis via Learning from Uncalibrated Videos](https://arxiv.org/pdf/2505.13440)|[![Github stars](https://img.shields.io/github/stars/Dwawayu/Pensieve.svg)](https://github.com/Dwawayu/Pensieve)|---|
|2025|`arXiv`|[STORM: Spatio-Temporal Reconstruction Model for Large-Scale Outdoor Scenes](https://arxiv.org/pdf/2501.00602)| [![Github stars](https://img.shields.io/github/stars/NVlabs/GaussianSTORM.svg)](https://github.com/NVlabs/GaussianSTORM)|[website](https://jiawei-yang.github.io/STORM/)|
|2025|`SIGGRAPH `|[Monocular Online Reconstruction with Enhanced Detail Preservation](https://arxiv.org/pdf/2505.07887)|---|[website](https://poiw.github.io/MODP/)| 
|2025|`arXiv`|[Sparse2DGS: Geometry-Prioritized Gaussian Splatting for Surface Reconstruction from Sparse Views](https://arxiv.org/pdf/2504.20378)|[![Github stars](https://img.shields.io/github/stars/Wuuu3511/Sparse2DGS.svg)](https://github.com/Wuuu3511/Sparse2DGS)|---| 
|2025|`CVPR`|[ODHSR: Online Dense 3D Reconstruction of Humans and Scenes from Monocular Videos](https://arxiv.org/pdf/2504.13167)|[![Github stars](https://img.shields.io/github/stars/eth-ait/ODHSR.svg)](https://github.com/eth-ait/ODHSR)|[website](https://eth-ait.github.io/ODHSR/)|
|2025|`arXiv`|[You Need a Transition Plane: Bridging Continuous Panoramic 3D Reconstruction with Perspective Gaussian Splatting](https://arxiv.org/pdf/2504.09062)|[![Github stars](https://img.shields.io/github/stars/zhijieshen-bjtu/TPGS.svg)](https://github.com/zhijieshen-bjtu/TPGS)|---|
|2024|`arXiv`|[GaussianSpa: An" Optimizing-Sparsifying" Simplification Framework for Compact and High-Quality 3D Gaussian Splatting](https://arxiv.org/pdf/2411.06019)|[![Github stars](https://img.shields.io/github/stars/noodle-lab/GaussianSpa.svg)](https://github.com/noodle-lab/GaussianSpa)|[website](https://noodle-lab.github.io/gaussianspa/)|
|2024|`ACM International Conference on Multimedia`|[Spikegs: 3d gaussian splatting from spike streams with high-speed camera motion](https://arxiv.org/pdf/2407.10062)|---|---|
|2024|`ICLR`|[Real-time photorealistic dynamic scene representation and rendering with 4d gaussian splatting](https://arxiv.org/pdf/2310.10642)|[![Github stars](https://img.shields.io/github/stars/fudan-zvg/4d-gaussian-splatting.svg)](https://github.com/fudan-zvg/4d-gaussian-splatting)|4DGS|
|2024|`ACM SIGGRAPH`|[2d gaussian splatting for geometrically accurate radiance fields](https://dl.acm.org/doi/pdf/10.1145/3641519.3657428)|[![Github stars](https://img.shields.io/github/stars/hbb1/2d-gaussian-splatting.svg)](https://github.com/hbb1/2d-gaussian-splatting)|[website](https://surfsplatting.github.io/)<br>2DGS|
|2024|`CVPR`|[Dngaussian: Optimizing sparse-view 3d gaussian radiance fields with global-local depth normalization](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_DNGaussian_Optimizing_Sparse-View_3D_Gaussian_Radiance_Fields_with_Global-Local_Depth_CVPR_2024_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/Fictionarry/DNGaussian.svg)](https://github.com/Fictionarry/DNGaussian)|---| 
|2024|`RAL`|[HGS-mapping: Online dense mapping using hybrid Gaussian representation in urban scenes](https://arxiv.org/pdf/2403.20159)|---|---|
|2024|`arXiv`|[Compact 3d gaussian splatting for dense visual slam](https://arxiv.org/pdf/2403.11247)|[![Github stars](https://img.shields.io/github/stars/dtc111111/Compact_GSSLAM.svg)](https://github.com/dtc111111/Compact_GSSLAM)|---|
|2024|`CVPR`|[4d gaussian splatting for real-time dynamic scene rendering](https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_4D_Gaussian_Splatting_for_Real-Time_Dynamic_Scene_Rendering_CVPR_2024_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/hustvl/4DGaussians.svg)](https://github.com/hustvl/4DGaussians)|[website](https://guanjunwu.github.io/4dgs/)<br>4DGS|
|2023|`ACM Transactions on Graphics`|[3d gaussian splatting for real-time radiance field rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_low.pdf)|[![Github stars](https://img.shields.io/github/stars/graphdeco-inria/gaussian-splatting.svg)](https://github.com/graphdeco-inria/gaussian-splatting)|[website](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)|

<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->
  



