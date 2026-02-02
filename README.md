<div align="center">

# Learning-based 3D Vision

[![GitHub stars](https://img.shields.io/github/stars/dongjiacheng06/Learning-based-3D-Vision?style=social)](https://github.com/dongjiacheng06/Learning-based-3D-Vision/stargazers)
[![License](https://img.shields.io/github/license/dongjiacheng06/Learning-based-3D-Vision)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](./CONTRIBUTING.md)

A curated collection of works in **Learning-based 3D Vision**, systematically organizing nearly ten major branches of 3D/4D vision research, include but not limited to E2E 3D Reconstruction/4DV/Online Reconstruction and other several frontier fields. This repository was created to help researchers quickly locate papers relevant to their field and enable newcomers to build a clear understanding of the landscape. It aims to serve as a comprehensive resource for scholars, practitioners, and enthusiasts exploring 3D vision and its exciting applications in embodied intelligence, world perception, and beyond. 
<p align="center">
  <img src="assets/image.png" alt="Learning-based 3D Vision" width="100%" style="border-radius: 15px; box-shadow: 0 4px 24px rgba(0,0,0,.1); margin: 5px 0;">
</p>

*Photo Credit: [Gemini-Nano-Banana🍌](https://aistudio.google.com/models/gemini-2-5-flash-image)*.
</div>

---

## News & Updates
Major updates and announcements are shown below. Scroll for full taxonomy and paper lists.

- [2026.01] Repo Launch — Learning-based-3D-Vision is now live! See [CONTRIBUTING.md](./CONTRIBUTING.md) for how to contribute.
- [Ongoing] Community Contributions Welcome — Submit papers via PR or open an issue.
- ⭐ [Ongoing] If you find this useful, please consider giving a star and sharing it with your research community!

---

## Categories
- [Learning-based 3D Vision](#learning-based-3d-vision)
  - [News \& Updates](#news--updates)
  - [Categories](#categories)
  - [Surveys](#surveys)
  - [End to End 3D Reconstruction](#end-to-end-3d-reconstruction)
  - [Online 3R/SLAM](#online-3rslam)
    - [Online 3R](#online-3r)
    - [SLAM](#slam)
  - [3D Generation](#3d-generation)
  - [3D Perception](#3d-perception)
  - [4D Reconstruction](#4d-reconstruction)
    - [E2E 4D Reconstruction](#e2e-4d-reconstruction)
    - [non-E2E 4D Reconstruction](#non-e2e-4d-reconstruction)
  - [4D Perception](#4d-perception)
  - [3D Free Method](#3d-free-method)
  - [Related Analysis](#related-analysis)
  - [Foundation Models](#foundation-models)
    - [Generation/Reconstruction Foundation Models](#generationreconstruction-foundation-models)
    - [Physical Foundation Models](#physical-foundation-models)
  - [Acknowledgements](#acknowledgements)
  - [Citation](#citation)

> **Legend**
> ⭐️ Recommended / Must-read
> **Last Updated:** 2026-02-03  
---

## Surveys
- "Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey". [arXiv 2025.07](https://arxiv.org/abs/2507.14501)
- "3D Scene Generation: A Survey". [arXiv 2025.05](https://arxiv.org/abs/2505.05474v1)
- "Recent Advances in 3D Object and Scene Generation: A Survey". [arXiv 2025.04](https://arxiv.org/abs/2504.11734)


## End to End 3D Reconstruction
- [⭐️] **E-RayZer**, "E-RayZer: Self-supervised 3D Reconstruction as Spatial Visual Pre-training". [arXiv 2025.12](https://arxiv.org/abs/2512.10950)
- [⭐️] **DA3**, "Depth Anything 3: Recovering the Visual Space from Any Views". [arXiv 2025.11](https://arxiv.org/abs/2511.10647), [github](https://github.com/ByteDance-Seed/Depth-Anything-3)
- **OmniVGGT**, "OmniVGGT: Omni-Modality Driven Visual Geometry Grounded Transformer". [arXiv 2025.11](https://arxiv.org/abs/2511.10560v1)
- **MapAnything**, "MapAnything: Universal Feed-Forward Metric 3D Reconstruction". [arXiv 2025.09](https://arxiv.org/abs/2509.13414v2), [github](https://github.com/facebookresearch/map-anything)
- [⭐️] **π^3**, "π^3: Permutation-Equivariant Visual Geometry Learning". [arXiv 2025.07](https://arxiv.org/abs/2507.13347v2), [github](https://github.com/yyfz/Pi3)
- [⭐️] **VGGT**, "On Geometric Understanding and Learned Data Priors in VGGT". [arXiv 2025.03](https://arxiv.org/abs/2503.11651), [github](https://github.com/facebookresearch/vggt)
- [⭐️] **NopoSplat**, "No Pose, No Problem: Surprisingly Simple 3D Gaussian Splats from Sparse Unposed Images". [arXiv 2024.10](https://arxiv.org/abs/2410.24207), [github](https://github.com/cvg/NoPoSplat)
- [⭐️] **MVSplat**, "MVSplat: Efficient 3D Gaussian Splatting from Sparse Multi-View Images". [arXiv 2024.03](https://arxiv.org/abs/2403.14627), [github](https://github.com/donydchen/mvsplat)
- [⭐️] **DUSt3R**, "DUSt3R: Geometric 3D Vision Made Easy". [arXiv 2023.12](https://arxiv.org/abs/2312.14132), [github](https://github.com/naver/dust3r)
- [⭐️] **CroCo**, "CroCo: Self-Supervised Pre-training for 3D Vision Tasks by Cross-View Completion". [arXiv 2022.10](https://arxiv.org/abs/2210.10716), [github](https://github.com/naver/croco)


## Online 3R/SLAM
### Online 3R
-  **InfiniteVGGT**, "InfiniteVGGT: Visual Geometry Grounded Transformer for Endless Streams". [arXiv 2026.01](https://arxiv.org/abs/2601.02281v1)
-  **XStreamVGGT**, "XStreamVGGT: Extremely Memory-Efficient Streaming Vision Geometry Grounded Transformer with KV Cache Compression". [arXiv 2026.01](https://arxiv.org/abs/2601.01204v1)
-  **TTT3R**, "TTT3R: 3D RECONSTRUCTION AS TEST-TIME TRAINING". [arXiv 2025.10](https://arxiv.org/abs/2509.26645v3)
-  **G-CUT3R**, "G-CUT3R: Guided 3D Reconstruction with Camera and Depth Prior Integration". [arXiv 2025.09](https://arxiv.org/abs/2508.11379v2)
- [⭐️] **StreamVGGT**, "Streaming 4D Visual Geometry Transformer". [arXiv 2025.07](https://arxiv.org/abs/2507.11539), [github](https://github.com/wzzheng/StreamVGGT)
- [⭐️] **Point3R**, "Point3R: Streaming 3D Reconstruction with Explicit Spatial Pointer Memory". [arXiv 2025.07](https://arxiv.org/abs/2507.02863), [github](https://github.com/YkiWu/Point3R)
- [⭐️] **CUT3R**, "Continuous 3D Perception Model with Persistent State". [arXiv 2025.01](https://arxiv.org/abs/2501.12387), [github](https://github.com/CUT3R/CUT3R)
- [⭐️] **Spann3R**, "3D Reconstruction with Spatial Memory". [arXiv 2024.08](https://arxiv.org/abs/2408.16061), [github](https://github.com/HengyiWang/spann3r)



### SLAM
- **VGGT-SLAM**, "VGGT-SLAM: Dense RGB SLAM Optimized on the SL(4) Manifold". [arXiv 2025.09](https://arxiv.org/abs/2505.12549)
- **SLAM-Former**, "SLAM-Former: Putting SLAM into One Transformer". [arXiv 2025.09](https://arxiv.org/abs/2509.16909v1)
- **GRS-SLAM3R**, "GRS-SLAM3R: Real-Time Dense SLAM with Gated Recurrent State". [arXiv 2025.09](https://arxiv.org/abs/2509.23737v1)
- **SLAM3R**, "SLAM3R: Real-Time Dense Scene Reconstruction from Monocular RGB Videos". [arXiv 2024.12](https://arxiv.org/abs/2412.09401), [github](https://github.com/PKU-VCL-3DV/SLAM3R)
- **MASt3R-SLAM**, "MASt3R-SLAM: Real-Time Dense SLAM with 3D Reconstruction Priors". [arXiv 2024.12](https://arxiv.org/abs/2412.12392v2), [github](https://github.com/rmurai0610/MASt3R-SLAM)

## 3D Generation
- **CoMoVi**, "CoMoVi: Co-Generation of 3D Human Motions and Realistic Videos". [arXiv 2026.01](https://arxiv.org/abs/2601.10632)
- **GeoWorld**, "GeoWorld: Unlocking the Potential of Geometry Models to Facilitate High-Fidelity 3D Scene Generation". [arXiv 2025.11](https://arxiv.org/abs/2511.23191)
- [⭐️] **LYRA**, "LYRA: Generative 3D Scene Reconstruction via Video Diffusion Model Self-Distillation". [arXiv 2025.09](https://arxiv.org/abs/2509.19296v1), [github](https://github.com/nv-tlabs/lyra)
- [⭐️] **TRELLIS**, "Structured 3D Latents for Scalable and Versatile 3D Generation". [arXiv 2024.12](https://arxiv.org/abs/2412.01506), [github](https://github.com/microsoft/TRELLIS)
- [⭐️] **LGM**, "LGM: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation". [arXiv 2024.02](https://arxiv.org/abs/2402.05054), [github](https://github.com/3DTopia/LGM)
- [⭐️] **LRM**, "LRM: Large Reconstruction Model for Single Image to 3D". [arXiv 2023.11](https://arxiv.org/abs/2311.04400), [github](https://github.com/3DTopia/OpenLRM)
- [⭐️] **Zero123++**, "Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model". [arXiv 2023.10](https://arxiv.org/abs/2310.15110), [github](https://github.com/SUDO-AI-3D/zero123plus)
- **Michelangelo**, "Michelangelo: Conditional 3D Shape Generation based on Shape-Image-Text Aligned Latent Representation". [arXiv 2023.06](https://arxiv.org/abs/2306.17115), [github](https://github.com/NeuralCarver/Michelangelo)




## 3D Perception
- **MVGGT**, "MVGGT: Multimodal Visual Geometry Grounded Transformer for Multiview 3D Referring Expression Segmentation". [arXiv 2026.01](https://arxiv.org/abs/2601.06874)
- **Map2Thought**, "Map2Thought: Explicit 3D Spatial Reasoning via Metric Cognitive Maps". [arXiv 2026.01](https://arxiv.org/abs/2601.11442)
- **RoboBrain 2.5**, "RoboBrain 2.5: Depth in Sight, Time in Mind". [arXiv 2026.01](https://arxiv.org/abs/2601.14352)
- **Think3D**, "Think3D: Thinking with Space for Spatial Reasoning". [arXiv 2026.01](https://arxiv.org/abs/2601.13029)
- **OpenVoxel**, "OpenVoxel: Training-Free Grouping and Captioning Voxels for Open-Vocabulary 3D Scene Understanding". [arXiv 2026.01](https://arxiv.org/abs/2601.09575)
- **AnyDepth**, "AnyDepth: Depth Estimation Made Easy". [arXiv 2026.01](https://arxiv.org/abs/2601.02760)
- **DA^2**, "DA^2: Depth Anything in Any Direction". [arXiv 2025.09](https://arxiv.org/abs/2509.26618)
- "Depth Anything at Any Condition". [arXiv 2025.07](https://arxiv.org/abs/2507.01634)
- [⭐️] "Depth Anything v2". [arXiv 2024.06](https://arxiv.org/abs/2406.09414), [github](https://github.com/DepthAnything/Depth-Anything-V2)
- [⭐️] **Depth Anything**, "Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data". [arXiv 2024.01](https://arxiv.org/abs/2401.10891), [github](https://github.com/LiheYoung/Depth-Anything)
- [⭐️] **SAM3D**, "SAM3D: Zero-Shot 3D Object Detection via Segment Anything Model". [arXiv 2024.01](https://arxiv.org/abs/2306.02245)




## 4D Reconstruction
### E2E 4D Reconstruction
- **Motion 3-to-4**, "Motion 3-to-4: 3D Motion Reconstruction for 4D Synthesis". [arXiv 2026.01](https://arxiv.org/abs/2601.14253)
- **V-DPM**, "V-DPM: 4D Video Reconstruction with Dynamic Point Maps". [arXiv 2026.01](https://arxiv.org/abs/2601.09499)
- [⭐️] **D4RT**, "Efficiently Reconstructing Dynamic Scenes One D4RT at a Time". [arXiv 2025.12](https://arxiv.org/abs/2512.08924), [github](https://d4rt-paper.github.io/),[DeepMind Blog](https://deepmind.google/blog/d4rt-teaching-ai-to-see-the-world-in-four-dimensions/)
- [⭐️] **VGGT4D**, "VGGT4D: Mining Motion Cues in Visual Geometry Transformers for 4D Scene Reconstruction". [arXiv 2025.11](https://arxiv.org/abs/2511.19971)
- [⭐️] **4D-VGGT**, "4D-VGGT: A General Foundation Model with SpatioTemporal Awareness for Dynamic Scene Geometry Estimation". [arXiv 2025.11](https://arxiv.org/abs/2511.18416)
- **One4D**, "One4D: Unified 4D Generation and Reconstruction via Decoupled LoRA Control". [arXiv 2025.11](https://arxiv.org/abs/2511.18922)
- **C4D**, "C4D: 4D Made from 3D through Dual Correspondences". [arXiv 2025.10](https://arxiv.org/abs/2510.14960)
- **St4RTrack**, "St4RTrack: Simultaneous 4D Reconstruction and Tracking in the World". [arXiv 2025.04](https://arxiv.org/abs/2504.13152), [github](https://github.com/nhan-nguyen-trong/St4RTrack)
- **CAT4D**, "CAT4D: Create Anything in 4D with Multi-View Video Diffusion Models". [arXiv 2024.11](https://arxiv.org/abs/2411.18613)
- **Shape of Motion**, "Shape of Motion: 4D Reconstruction from a Single Video". [arXiv 2024.07](https://arxiv.org/abs/2407.13764), [github](https://github.com/vye16/shape-of-motion)


### non-E2E 4D Reconstruction
- **Sparse4DGS**, "Sparse4DGS: 4D Gaussian Splatting for Sparse-Frame Dynamic Scene Reconstruction". [arXiv 2025.11](https://arxiv.org/abs/2511.07122)
- [⭐️] "Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction". [arXiv 2025.11](https://arxiv.org/abs/2511.14540)
- **SplatFields**, "Neural Gaussian Splats for Sparse 3D and 4D Reconstruction". [arXiv 2024.9](https://arxiv.org/abs/2409.11211), [github](https://github.com/markomih/SplatFields)
- **L4GM**, "L4GM: Large 4D Gaussian Reconstruction Model". [arXiv 2024.7](https://arxiv.org/abs/2406.10324), [github](https://github.com/nv-tlabs/L4GM-official)
- **Gaussian-Flow**, "Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle". [arXiv 2023.12](https://arxiv.org/abs/2312.03431), [github](https://github.com/NJU-3DV/Gaussian-Flow)
- [⭐️] "4D Gaussian Splatting for Real-Time Dynamic Scene Rendering". [arXiv 2023.10](https://arxiv.org/abs/2310.08528), [github](https://github.com/hustvl/4DGaussians)


## 4D Perception
- **ReScene4D**, "ReScene4D: Temporally Consistent Semantic Instance Segmentation of Evolving Indoor 3D Scenes". [arXiv 2026.01](https://arxiv.org/abs/2601.11508)
- [⭐️] **VerseCrafter**, "VerseCrafter: Dynamic Realistic Video World Model with 4D Geometric Control". [arXiv 2026.01](https://arxiv.org/abs/2601.05138)
- [⭐️] **NeoVerse**, "NeoVerse: Enhancing 4D World Model with in-the-wild Monocular Videos". [arXiv 2026.01](https://arxiv.org/abs/2601.00393)
- "Choreographing a World of Dynamic Objects". [arXiv 2026.01](https://arxiv.org/abs/2601.04194)
- **3AM**, "3AM: Segment Anything with Geometric Consistency in Videos". [arXiv 2026.01](https://arxiv.org/abs/2601.08831)
- **SeeU**, "SeeU: Seeing the Unseen World via 4D Dynamics-aware Generation". [arXiv 2025.12](https://arxiv.org/abs/2512.03350)
- **DynamicVerse**, "DynamicVerse: A Physically-Aware Multimodal Framework for 4D World Modeling". [arXiv 2025.12](https://arxiv.org/abs/2512.03000)
- **PAGE-4D**, "PAGE-4D: Disentangled Pose and Geometry Estimation for VGGT-4D Perception". [arXiv 2025.10](https://arxiv.org/abs/2510.17568)
- **Trace Anything**, "Trace Anything: Representing Any Video in 4D via Trajectory Fields". [arXiv 2025.10](https://arxiv.org/abs/2510.13802)
- [⭐️] **OmniWorld**, "OmniWorld: A Multi-Domain and Multi-Modal Dataset for 4D World Modeling". [arXiv 2025.09](https://arxiv.org/abs/2509.12201v1)
- [⭐️] **ViPE**, "ViPE: Video Pose Engine for 3D Geometric Perception". [arXiv 2025.08](https://arxiv.org/abs/2508.10934)
- **Uni4D**, "Uni4D: Unifying Visual Foundation Models for 4D Modeling from a Single Video". [arXiv 2025.03](https://arxiv.org/abs/2503.21761), [github](https://github.com/Davidyao99/uni4d)
- **Stereo4D**, "Stereo4D: Learning How Things Move in 3D from Internet Stereo Videos". [arXiv 2025.03](https://arxiv.org/abs/2412.09621), [github](https://github.com/mli0603/stereo4d)



## 3D Free Method
- [⭐️] **XFactor**, "True Self-Supervised Novel View Synthesis is Transferable". [arXiv 2025.10](https://arxiv.org/abs/2510.13063)
- [⭐️] **RayZer**, "RayZer: A Self-supervised Large View Synthesis Model". [arXiv 2025.05](https://arxiv.org/abs/2505.00702), [github](https://github.com/hwjiang1510/RayZer)
- [⭐️] **LVSM**, "LVSM: A Large View Synthesis Model with Minimal 3D Inductive Bias". [arXiv 2024.10](https://arxiv.org/abs/2410.17242), [github](https://github.com/haian-jin/LVSM)



## Related Analysis
- "On Geometric Understanding and Learned Data Priors in VGGT". [arXiv 2025.12](https://arxiv.org/abs/2512.11508)
- "What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models". [arXiv 2025.12](https://arxiv.org/abs/2512.03422v1)
- "How Much 3D Do Video Foundation Models Encode?". [arXiv 2025.07](https://arxiv.org/abs/2512.19949)
- "Feat2GS: Probing Visual Foundation Models with Gaussian Splatting". [arXiv 2024.12](https://arxiv.org/abs/2412.09606)


## Foundation Models
### Generation/Reconstruction Foundation Models
- **HunyuanWorld 1.0**, "HunyuanWorld 1.0: Generating Immersive, Explorable, and Interactive 3D Worlds from Words or Pixels". [arXiv 2025.07](https://arxiv.org/abs/2507.21809)
- **Hunyuan3D 2.5**, "Hunyuan3D 2.5: Towards High-Fidelity 3D Assets Generation with Ultimate Details". [arXiv 2025.06](https://arxiv.org/abs/2506.1650), [github](https://github.com/Tencent-Hunyuan/Hunyuan3D-2)
- [⭐️] "Video World Models with Long-term Spatial Memory". [arXiv 2025.06](https://arxiv.org/abs/2506.05284)
- **Wan**, "Wan: Open and Advanced Large-Scale Video Generative Models". [arXiv 2025.03](https://arxiv.org/abs/2503.20314v2), [github](https://github.com/Wan-Video/Wan2.1)
- **Hunyuan3D 1.0**, "Hunyuan3D 1.0: A Unified Framework for Text-to-3D and Image-to-3D Generation". [arXiv 2024.11](https://arxiv.org/abs/2411.02293), [github](https://github.com/Tencent/Hunyuan3D-1)


### Physical Foundation Models
- [⭐️] **Cosmos2.5**, "World Simulation with Video Foundation Models for
Physical AI". [arXiv 2025.11](https://arxiv.org/abs/2511.00062v1)  [cosmos-predict2.5](https://github.com/nvidia-cosmos/cosmos-predict2.5)  [cosmos-transfer2.5](https://github.com/nvidia-cosmos/cosmos-transfer2.5)  [cosmos-reason1](https://github.com/nvidia-cosmos/cosmos-reason1)
- [⭐️] **Cosmos**, "Cosmos World Foundation Model Platform for Physical AI". [arXiv 2025.01](https://arxiv.org/abs/2501.03575v3), [github](https://github.com/NVIDIA/Cosmos)




## Acknowledgements
This project has largely drawn on the following projects:
-  [Awesome-World-Models](https://github.com/knightnemo/Awesome-World-Models)
  
Huge shoutout the the authors for their awesome work.

## Citation
If you find this repository useful, please consider citing it:

```bibtex
@misc{learningbased3dvision,
  title        = {Learning-based 3D Vision: A curated list of representative works in learning-based 3D vision},
  author       = {Dong, Jiacheng, Huan Li and Contributors},
  howpublished = {\url{https://github.com/dongjiacheng06/Awesome-3D-papers}},
  year         = {2026}
}

