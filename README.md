# Awesome Video Stabilization ( in progress )
A curated list of awesome video stabilization resources.

## Non-DL based Video Stabilization

| Year | Published | Title | Paper | Code / Project Page | Tags | 
| -------- | -------- | -------- | -------- | -------- | -------- | 
| 2021 | WACV | Cinematic-L1 Video Stabilization with a Log-Homography Model | [arXiv](https://arxiv.org/pdf/2011.08144.pdf) <br> [CVPR](https://openaccess.thecvf.com/content/WACV2021/papers/Bradley_Cinematic-L1_Video_Stabilization_With_a_Log-Homography_Model_WACV_2021_paper.pdf) | - | offline |
| 2020 | arXiv | Adaptively Meshed Video Stabilization | [arXiv](https://arxiv.org/pdf/2006.07820.pdf) | - | offline |
| 2019 | TCVG | Effective Video Stabilization via Joint Trajectory Smoothing and Frame Warping | [TCVG](https://ieeexplore.ieee.org/document/8737754)| [Matlab](https://github.com/705062791/TVCG-Video-Stabilization-via-joint-Trajectory-Smoothing-and-frame-warping) | offline |
| 2018 | ECCV | Selfie Video Stabilization | [ECCV](https://cseweb.ucsd.edu/~ravir/selfievideo.pdf) | - | selfie video |
| 2017 | CVPR | Direct Photometric Alignment by Mesh Deformation | [CVPR](http://www.liushuaicheng.org/CVPR2017/DirectPhotometric.pdf)| - | offline |
| 2017 | TIP | CodingFlow:Enable Video Coding for Video Stabilization | [TIP](http://www.liushuaicheng.org/TIP/CodingFlow/CodingFlow.pdf) | - | offline |
| 2016 | ECCV | MeshFlow: Minimum Latency Online Video Stabilization | [ECCV](http://www.liushuaicheng.org/eccv2016/meshflow.pdf) | [project page](http://www.liushuaicheng.org/eccv2016/index.html) | online |
| 2014 | CVPR | SteadyFlow: Spatially Smooth Optical Flow for Video Stabilization | [CVPR](http://www.liushuaicheng.org/CVPR2014/SteadyFlow.pdf) | [project page](http://www.liushuaicheng.org/CVPR2014/) | offline |
| 2013 | SIGGRAPH | Bundled Camera Paths for Video Stabilization | [SIGGRAPH](http://www.liushuaicheng.org/SIGGRAPH2013/BundledPaths.pdf) | [project page](http://www.liushuaicheng.org/SIGGRAPH2013/) | offline |
| 2013 | TVCG | Spatially and Temporally Optimized Video Stabilization | [TVCG](http://graphics.csie.ncku.edu.tw/Tony/papers/video_stablization.pdf) | [project page](https://people.cs.nctu.edu.tw/~yushuen/VideoStabilization/) | offline |
|  2012 | CVPR | Video Stabilization with a depth camera | [CVPR](http://www.liushuaicheng.org/CVPR2012/cvpr12_stabilization.pdf) | [project page](http://www.liushuaicheng.org/CVPR2012/index.html) | offline |
| 2012 | SIGGRAPH | Video Stabilization using Epipolar Geometry | [SIGGRAPH](https://www.cs.huji.ac.il/w~raananf/projects/stab/paper.pdf) | [project page](https://www.cs.huji.ac.il/w~raananf/projects/stab/) | offline |
| 2011 | SIGGRAPH | Subspace Video Stabilization | [SIGGRAPH](http://web.cecs.pdx.edu/~fliu/papers/tog2010.pdf) | [project page](http://web.cecs.pdx.edu/~fliu/project/subspace_stabilization/) | offline |
| 2011 | CVPR | Auto-Directed Video Stabilization with Robust L1 Optimal Camera Paths | [CVPR](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/37041.pdf) | [project page](https://www.cc.gatech.edu/cpl/projects/videostabilization/) | offline |
| 2009 | SIGGRAPH | Content-Preserving Warps for 3D Video Stabilization | [SIGGRAPH](https://vcai.mpi-inf.mpg.de/teaching/gvv_seminar_2012/papers/Content-Preserving%20Warps%20for%203D%20Video%20Stabilization.pdf) | [project page](http://web.cecs.pdx.edu/~fliu/project/3dstab.htm) | offline <br> 3D |




## DL-based Video Stabilization


| Year | Published | Title | Paper | Code / Project Page | Tags | 
| -------- | -------- | -------- | -------- | -------- | -------- | 
| 2022 | WACV | Deep Online Fused Video Stabilization | [arXiv](https://arxiv.org/pdf/2102.01279.pdf) <br> [wacv](https://openaccess.thecvf.com/content/WACV2022/papers/Shi_Deep_Online_Fused_Video_Stabilization_WACV_2022_paper.pdf) | [PyTorch](https://github.com/googleinterns/deep-stabilization) (official)<br> [project page](https://zhmeishi.github.io/dvs/) | online |
| 2022 | arXiv | DUT: Learning Video Stabilization By Simply Watching Unstable Videos | [arXiv](https://arxiv.org/pdf/2011.14574.pdf) | [PyTorch](https://github.com/Annbless/DUTCode) | offline |
| 2021 | BMVC | Self-Supervised Real-time Video Stabilization | [arXiv](https://arxiv.org/pdf/2111.05980.pdf) | - | self-supervised <br> online |
| 2021 | ICCV | Out-of-boundary View Synthesis Towards Full-Frame Video Stabilization | [arXiv](https://arxiv.org/pdf/2108.09041.pdf) | [Code](https://github.com/Annbless/OVS_Stabilization) <br> (no code provided) | offline <br> full-frame <br> two-stage |
| 2021 | ICCV | Hybrid Neural Fusion for Full-frame Video Stabilization | [arXiv](https://arxiv.org/pdf/2102.06205.pdf) <br> [ICCV](https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Hybrid_Neural_Fusion_for_Full-Frame_Video_Stabilization_ICCV_2021_paper.pdf) | [PyTorch](https://github.com/alex04072000/FuSta) <br> [project page](https://alex04072000.github.io/FuSta/) | offline <br> full-frame |
| 2021 | CVPR | 3D Video Stabilization with Depth Estimation by CNN-based Optimization | [CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Lee_3D_Video_Stabilization_With_Depth_Estimation_by_CNN-Based_Optimization_CVPR_2021_paper.pdf) | [project page](https://yaochih.github.io/deep3d-stabilizer.io/) | 3D <br> offline |
| 2021 | CVPR | Real-Time Selfie Video Stabilization | [arXiv](https://arxiv.org/pdf/2009.02007.pdf)| [Code](https://github.com/jiy173/selfievideostabilization) <br> (no training code) | online <br> selfie video |
| 2021 | ICIP | PixStabNet: Fast Multi-Scale Deep Online Video Stabilization with Pixel-Based Warping | [ICIP](https://ieeexplore.ieee.org/document/9506801) | - | online |
| 2020 | CVPR | Learning Video Stabilization Using Optical Flow | [CVPR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yu_Learning_Video_Stabilization_Using_Optical_Flow_CVPR_2020_paper.pdf) | [Code](https://drive.google.com/file/d/1wQJYFd8TMbCRzhmFfDyBj7oHAGfyr1j6/view) | offline |
| 2020 | TOG | Deep Iterative Frame Interpolation for Full-frame Video Stabilization | [arXiv](https://arxiv.org/pdf/1909.02641.pdf) | [PyTorch](https://github.com/jinsc37/DIFRINT) | offline <br> full-frame |
| 2020 | TIP | PWStableNet: Learning Pixel-wise Warping Maps for Video Stabilization | [TIP](https://ieeexplore.ieee.org/document/8951447) | [PyTorch](https://github.com/mindazhao/PWStableNet) | offline |
| 2020 | arXiv | Deep Motion Blind Video Stabilization | [arXiv](https://arxiv.org/pdf/2011.09697.pdf) | - | offline |
| 2019 | CVPR | Robust Video Stabilization by Optimization in CNN Weight Space | [CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yu_Robust_Video_Stabilization_by_Optimization_in_CNN_Weight_Space_CVPR_2019_paper.pdf) | [Code](https://drive.google.com/file/d/16e7RcF5duczK-OtSVxJoEuixQem1SsLF/view) | offline |
| 2019 | TIP | Deep Online Video Stabilization With Multi-Grid Warping Transformation Learning | [TIP](https://ieeexplore.ieee.org/document/8554287) | [Tensorflow](https://github.com/cxjyxxme/deep-online-video-stabilization-deploy)| online|
| 2018 | CGF | Deep Video Stabilization Using Adversarial Networks | [CGF](https://cg.cs.tsinghua.edu.cn/papers/CGF-2018-video-stab.pdf) | [PyTorch](https://github.com/mindazhao/Deep-Video-Stabilization-Using-Adversarial-Networks)| offline |





