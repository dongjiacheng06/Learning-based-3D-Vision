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
  - [Foundation Models](#3d-foundation-models-application)
  - [Acknowledgements](#acknowledgements)
  - [Citation](#citation)

> **Legend**  
> ⭐️ Recommended / Must-read  
---

## Surveys 
- "3D Scene Generation: A Survey". [arXiv 2025.05](https://arxiv.org/abs/2505.05474v1)
- "Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey". [arXiv 2025.07](https://arxiv.org/abs/2507.14501)



## End to End 3D Reconstruction 
- [⭐️] **CroCo**, "CroCo: Self-Supervised Pre-training for 3D Vision Tasks by Cross-View Completion". [arXiv 2022.10](https://arxiv.org/abs/2210.10716)
- [⭐️] **DUSt3R**, "DUSt3R: Geometric 3D Vision Made Easy". [arXiv 2023.12](https://arxiv.org/abs/2312.14132)
- [⭐️] **MVSplat**, "MVSplat: Efficient 3D Gaussian Splatting from Sparse Multi-View Images". [arXiv 2024.03](https://arxiv.org/abs/2403.14627)
- [⭐️] **NopoSplat**, "No Pose, No Problem: Surprisingly Simple 3D Gaussian Splats from Sparse Unposed Images". [arXiv 2024.10](https://arxiv.org/abs/2410.24207)
- [⭐️] **VGGT**, "On Geometric Understanding and Learned Data Priors in VGGT". [arXiv 2025.03](https://arxiv.org/abs/2503.11651)
- [⭐️] **π^3**, "π^3: Permutation-Equivariant Visual Geometry Learning". [arXiv 2025.07](https://arxiv.org/abs/2507.13347v2)
- **MapAnything**, "MapAnything: Universal Feed-Forward Metric 3D Reconstruction". [arXiv 2025.09](https://arxiv.org/abs/2509.13414v2)
- **OmniVGGT**, "OmniVGGT: Omni-Modality Driven Visual Geometry Grounded Transformer". [arXiv 2025.11](https://arxiv.org/abs/2511.10560v1)
- [⭐️] **DA3**, "Depth Anything 3: Recovering the Visual Space from Any Views". [arXiv 2025.11](https://arxiv.org/abs/2511.10647)
- [⭐️] **E-RayZer**, "E-RayZer: Self-supervised 3D Reconstruction as Spatial Visual Pre-training". [arXiv 2025.12](https://arxiv.org/abs/2512.10950)


## Online 3R/SLAM
### Online 3R
- [⭐️] **Spann3R**, "3D Reconstruction with Spatial Memory". [arXiv 2024.08](https://arxiv.org/abs/2408.16061)
- [⭐️] **CUT3R**, "Continuous 3D Perception Model with Persistent State". [arXiv 2025.01](https://arxiv.org/abs/2501.12387)
- [⭐️] **Point3R**, "Point3R: Streaming 3D Reconstruction with Explicit Spatial Pointer Memory". [arXiv 2025.07](https://arxiv.org/abs/2507.02863)
- [⭐️] **StreamVGGT**, "Streaming 4D Visual Geometry Transformer". [arXiv 2025.07](https://arxiv.org/abs/2507.11539)
-  **G-CUT3R**, "G-CUT3R: Guided 3D Reconstruction with Camera and Depth Prior Integration". [arXiv 2025.09](https://arxiv.org/abs/2508.11379v2)
-  **TTT3R**, "TTT3R: 3D RECONSTRUCTION AS TEST-TIME TRAINING". [arXiv 2025.10](https://arxiv.org/abs/2509.26645v3)
-  **XStreamVGGT**, "XStreamVGGT: Extremely Memory-Efficient Streaming Vision Geometry Grounded Transformer with KV Cache Compression". [arXiv 2026.01](https://arxiv.org/abs/2601.01204v1)
-  **InfiniteVGGT**, "InfiniteVGGT: Visual Geometry Grounded Transformer for Endless Streams". [arXiv 2026.01](https://arxiv.org/abs/2601.02281v1)



### SLAM
- **MASt3R-SLAM**, "MASt3R-SLAM: Real-Time Dense SLAM with 3D Reconstruction Priors". [arXiv 2024.12](https://arxiv.org/abs/2412.12392v2)
- **SLAM3R**, "SLAM3R: Real-Time Dense Scene Reconstruction from Monocular RGB Videos". [arXiv 2024.12](https://arxiv.org/abs/2412.09401)
- **GRS-SLAM3R**, "GRS-SLAM3R: Real-Time Dense SLAM with Gated Recurrent State". [arXiv 2025.09](https://arxiv.org/abs/2509.23737v1)
- **SLAM-Former**, "SLAM-Former: Putting SLAM into One Transformer". [arXiv 2025.09](https://arxiv.org/abs/2509.16909v1)
- **VGGT-SLAM**, "VGGT-SLAM: Dense RGB SLAM Optimized on the SL(4) Manifold". [arXiv 2025.09](https://arxiv.org/abs/2505.12549)

## 3D Generation
- **Michelangelo**, "Michelangelo: Conditional 3D Shape Generation based on Shape-Image-Text Aligned Latent Representation"[arXiv 2023.06](https://arxiv.org/abs/2306.17115)
- [⭐️] **Zero123++**, "Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model"[arXiv 2023.10](https://arxiv.org/abs/2310.15110)
- [⭐️] **LRM**, "LRM: Large Reconstruction Model for Single Image to 3D"[arXiv 2023.11](https://arxiv.org/abs/2311.04400)
- [⭐️] **LGM**, "LGM: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation". [arXiv 2024.02](https://arxiv.org/abs/2402.05054)
- [⭐️] **TRELLIS**, "Structured 3D Latents for Scalable and Versatile 3D Generation". [arXiv 2024.12](https://arxiv.org/pdf/2412.01506)
- [⭐️] **LYRA**, "LYRA: Generative 3D Scene Reconstruction via Video Diffusion Model Self-Distillation". [arXiv 2025.09](https://arxiv.org/pdf/2509.19296v1)
- **GeoWorld**, "GeoWorld: Unlocking the Potential of Geometry Models to Facilitate High-Fidelity 3D Scene Generation". [arXiv 2025.11](https://arxiv.org/pdf/2511.23191)

## 3D Perception
- [⭐️] **SAM3D**, "SAM3D: Zero-Shot 3D Object Detection via Segment Anything Model". [arXiv 2024.01](https://arxiv.org/abs/2306.02245)
- [⭐️] **Depth Anything**, "Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data". [arXiv 2024.01](https://arxiv.org/abs/2401.10891)
- [⭐️] "Depth Anything v2". [arXiv 2024.06](https://arxiv.org/abs/2406.09414)
- "Depth Anything at Any Condition". [arXiv 2025.07](https://arxiv.org/abs/2507.01634)
- **DA^2**, "DA^2: Depth Anything in Any Direction". [arXiv 2025.09](https://arxiv.org/abs/2509.26618)
- **AnyDepth**, "AnyDepth: Depth Estimation Made Easy". [arXiv 2026.01](https://arxiv.org/abs/2601.02760)
- **OpenVoxel**, "OpenVoxel: Training-Free Grouping and Captioning Voxels for Open-Vocabulary 3D Scene Understanding". [arXiv 2026.01](https://arxiv.org/abs/2601.09575)


## 4D Reconstruction
### E2E 4D Reconstruction
- **Shape of Motion**, "Shape of Motion: 4D Reconstruction from a Single Video". [arXiv 2024.07](https://arxiv.org/abs/2407.13764)
- **CAT4D**, "CAT4D: Create Anything in 4D with Multi-View Video Diffusion Models". [arXiv 2024.11](https://arxiv.org/abs/2411.18613)
- **St4RTrack**, "St4RTrack: Simultaneous 4D Reconstruction and Tracking in the World". [arXiv 2025.04](https://arxiv.org/abs/2504.13152)
- **C4D**, "C4D: 4D Made from 3D through Dual Correspondences". [arXiv 2025.10](https://arxiv.org/abs/2510.14960)
- **One4D**, "One4D: Unified 4D Generation and Reconstruction via Decoupled LoRA Control". [arXiv 2025.11](https://arxiv.org/abs/2511.18922)
- [⭐️] **4D-VGGT**, "4D-VGGT: A General Foundation Model with SpatioTemporal Awareness for Dynamic Scene Geometry Estimation". [arXiv 2025.11](https://arxiv.org/abs/2511.18416)
- [⭐️] **VGGT4D**, "VGGT4D: Mining Motion Cues in Visual Geometry Transformers for 4D Scene Reconstruction". [arXiv 2025.11](https://arxiv.org/abs/2511.19971)
- **D4RT**, "Efficiently Reconstructing Dynamic Scenes One D4RT at a Time". [arXiv 2025.12](https://arxiv.org/abs/2512.08924)
- **V-DPM**, "V-DPM: 4D Video Reconstruction with Dynamic Point Maps". [arXiv 2026.01](https://arxiv.org/abs/2601.09499)


### non-E2E 4D Reconstruction
- [⭐️] "4D Gaussian Splatting for Real-Time Dynamic Scene Rendering". [arXiv 2023.10](https://arxiv.org/abs/2310.08528)
- **Gaussian-Flow**, "Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle". [arXiv 2023.12](https://arxiv.org/abs/2312.03431)
- **L4GM**, "L4GM: Large 4D Gaussian Reconstruction Model". [arXiv 2024.7](https://arxiv.org/abs/2406.10324)
- **SplatFields**, "Neural Gaussian Splats for Sparse 3D and 4D Reconstruction". [arXiv 2024.9](https://arxiv.org/abs/2409.11211)
- [⭐️] "Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction". [arXiv 2025.11](https://arxiv.org/abs/2511.14540)
- **Sparse4DGS**"Sparse4DGS: 4D Gaussian Splatting for Sparse-Frame Dynamic Scene Reconstruction". [arXiv 2025.11](https://arxiv.org/abs/2511.07122)


## 4D Perception
- **Stereo4D**, "Stereo4D: Learning How Things Move in 3D from Internet Stereo Videos". [arXiv 2025.03](https://arxiv.org/abs/2412.09621)
- **Uni4D**, "Uni4D: Unifying Visual Foundation Models for 4D Modeling from a Single Video". [arXiv 2025.03](https://arxiv.org/abs/2503.21761)
- [⭐️] **ViPE**, "ViPE: Video Pose Engine for 3D Geometric Perception". [arXiv 2025.08](https://arxiv.org/abs/2508.10934)
- [⭐️] **OmniWorld**, "OmniWorld: A Multi-Domain and Multi-Modal Dataset for 4D World Modeling". [arXiv 2025.09](https://arxiv.org/abs/2509.12201v1)
- **Trace Anything**, "Trace Anything: Representing Any Video in 4D via Trajectory Fields". [arXiv 2025.10](https://arxiv.org/abs/2510.13802)
- **PAGE-4D**, "PAGE-4D: Disentangled Pose and Geometry Estimation for VGGT-4D Perception". [arXiv 2025.10](https://arxiv.org/abs/2510.17568)
- **DynamicVerse**, "DynamicVerse: A Physically-Aware Multimodal Framework for 4D World Modeling". [arXiv 2025.12](https://arxiv.org/abs/2512.03000)
- **SeeU**, "SeeU: Seeing the Unseen World via 4D Dynamics-aware Generation". [arXiv 2025.12](https://arxiv.org/abs/2512.03350)
- **3AM**, "3AM: Segment Anything with Geometric Consistency in Videos". [arXiv 2026.01](https://arxiv.org/abs/2601.08831)
- "Choreographing a World of Dynamic Objects". [arXiv 2026.01](https://arxiv.org/abs/2601.04194)
- [⭐️] **NeoVerse**, "NeoVerse: Enhancing 4D World Model with in-the-wild Monocular Videos". [arXiv 2026.01](https://arxiv.org/abs/2601.00393)



## 3D Free Method
- [⭐️] **LVSM**, "LVSM: A Large View Synthesis Model with Minimal 3D Inductive Bias". [arXiv 2024.10](https://arxiv.org/abs/2410.17242)
- [⭐️] **RayZer**, "RayZer: A Self-supervised Large View Synthesis Model". [arXiv 2025.05](https://arxiv.org/abs/2505.00702)
- [⭐️] **XFactor**, "True Self-Supervised Novel View Synthesis is Transferable". [arXiv 2025.10](https://arxiv.org/abs/2510.13063)



## Related Analysis
- "How Much 3D Do Video Foundation Models Encode?". [arXiv 2025.07](https://arxiv.org/abs/2512.19949)
- "What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models". [arXiv 2025.12](https://arxiv.org/abs/2512.03422v1)
- "On Geometric Understanding and Learned Data Priors in VGGT". [arXiv 2025.12](https://arxiv.org/abs/2512.11508)


## Foundation Models
### Generation/Reconstruction Foundation Models
- **Hunyuan3D 1.0**, "Hunyuan3D 1.0: A Unified Framework for Text-to-3D and Image-to-3D Generation". [arXiv 2024.11](https://arxiv.org/abs/2411.02293)
- **Wan**, "Wan: Open and Advanced Large-Scale Video Generative Models". [arXiv 2025.03](https://arxiv.org/abs/2503.20314v2)
Wan: Open and Advanced Large-Scale Video 
- [⭐️] "Video World Models with Long-term Spatial Memory". [arXiv 2025.06](https://arxiv.org/abs/2506.05284)
- **Hunyuan3D 2.5**, "Hunyuan3D 2.5: Towards High-Fidelity 3D Assets Generation with Ultimate Details". [arXiv 2025.06](https://arxiv.org/abs/2506.1650)
- **HunyuanWorld 1.0**, "HunyuanWorld 1.0: Generating Immersive, Explorable, and Interactive 3D Worlds from Words or Pixels". [arXiv 2025.07](https://arxiv.org/abs/2507.21809)
- **HunyuanWorld 1.0**, "HunyuanWorld 1.0: Generating Immersive, Explorable, and Interactive 3D Worlds from Words or Pixels". [arXiv 2025.07](https://arxiv.org/abs/2507.21809)


### Physical Foundation Models
- [⭐️] **Cosmos**, "Cosmos World Foundation Model Platform for Physical AI". [arXiv 2025.01](https://arxiv.org/abs/2501.03575v3)
- [⭐️] **Cosmos2.5**, "World Simulation with Video Foundation Models for
Physical AI". [arXiv 2025.11](https://arxiv.org/abs/2511.00062v1)(https://github.com/nvidia-cosmos/cosmos-predict2.5)(https://github.com/nvidia-cosmos/cosmos-transfer2.5)(https://github.com/nvidia-cosmos/cosmos-reason1)




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

