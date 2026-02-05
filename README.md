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

<style>
details summary {
  cursor: pointer;
  list-style: none;
  display: flex;
  align-items: center;
}
details summary::-webkit-details-marker {
  display: none;
}
details > summary::after {
  content: ' ▽';
  font-size: 0.65em;
  margin-left: 6px;
  line-height: 1;
}
details[open] > summary::after {
  content: ' ▼';
}
</style>

<ul style="list-style: none; padding: 0;">
<li style="margin-left: 0;"><a href="#surveys">Surveys</a></li>
<li style="margin-left: 0;"><a href="#end-to-end-3d-reconstruction">End to End 3D Reconstruction</a></li>
<li style="margin-left: 0;">
<details>
<summary><a href="#online-3rslam">Online 3R/SLAM</a></summary>
<ul>
<li><a href="#online-3r">Online 3R</a></li>
<li><a href="#slam">SLAM</a></li>
</ul>
</details>
</li>
<li style="margin-left: 0;"><a href="#3d-generation">3D Generation</a></li>
<li style="margin-left: 0;"><a href="#3d-perception">3D Perception</a></li>
<li style="margin-left: 0;">
<details>
<summary><a href="#4d-reconstruction">4D Reconstruction</a></summary>
<ul>
<li><a href="#e2e-4d-reconstruction">E2E 4D Reconstruction</a></li>
<li><a href="#non-e2e-4d-reconstruction">non-E2E 4D Reconstruction</a></li>
</ul>
</details>
</li>
<li style="margin-left: 0;"><a href="#4d-perception">4D Perception</a></li>
<li style="margin-left: 0;"><a href="#3d-free-method">3D Free Method</a></li>
<li style="margin-left: 0;"><a href="#related-analysis">Related Analysis</a></li>
<li style="margin-left: 0;">
<details>
<summary><a href="#foundation-models">Foundation Models</a></summary>
<ul>
<li><a href="#generationreconstruction-foundation-models">Generation/Reconstruction Foundation Models</a></li>
<li><a href="#physical-foundation-models">Physical Foundation Models</a></li>
</ul>
</details>
</li>
<li style="margin-left: 0;"><a href="#acknowledgements">Acknowledgements</a></li>
<li style="margin-left: 0;"><a href="#citation">Citation</a></li>
</ul>

> **Legend**
> ⭐️ Recommended / Must-read
> **Last Updated:** 2026-02-03  
## Categories

- [Surveys](#surveys)
- [End to End 3D Reconstruction](#end-to-end-3d-reconstruction)
- [Online 3R/SLAM](#online-3rslam) ▸
  - [Online 3R](#online-3r)
  - [SLAM](#slam)
- [3D Generation](#3d-generation)
- [3D Perception](#3d-perception)
- [4D Reconstruction](#4d-reconstruction) ▸
  - [E2E 4D Reconstruction](#e2e-4d-reconstruction)
  - [non-E2E 4D Reconstruction](#non-e2e-4d-reconstruction)
- [4D Perception](#4d-perception)
- [3D Free Method](#3d-free-method)
- [Related Analysis](#related-analysis)
- [Foundation Models](#foundation-models) ▸
  - [Generation/Reconstruction Foundation Models](#generationreconstruction-foundation-models)
  - [Physical Foundation Models](#physical-foundation-models)
- [Acknowledgements](#acknowledgements)
- [Citation](#citation)

> **Legend**
> ⭐️ Recommended / Must-read
> **Last Updated:** 2026-02-03  
---



## 4D Reconstruction
### E2E 4D Reconstruction
- **Motion 3-to-4**, "Motion 3-to-4: 3D Motion Reconstruction for 4D Synthesis". [![arXiv](https://img.shields.io/badge/arXiv-2601.14253-b31b1b.svg)](https://arxiv.org/abs/2601.14253)
- **V-DPM**, "V-DPM: 4D Video Reconstruction with Dynamic Point Maps". [![arXiv](https://img.shields.io/badge/arXiv-2601.09499-b31b1b.svg)](https://arxiv.org/abs/2601.09499)
- [⭐️] **D4RT**, "Efficiently Reconstructing Dynamic Scenes One D4RT at a Time". [![arXiv](https://img.shields.io/badge/arXiv-2512.08924-b31b1b.svg)](https://arxiv.org/abs/2512.08924) [![GitHub](https://img.shields.io/badge/GitHub-Page-blue)](https://d4rt-paper.github.io/) [![Blog](https://img.shields.io/badge/DeepMind-Blog-yellow)](https://deepmind.google/blog/d4rt-teaching-ai-to-see-the-world-in-four-dimensions/)
- [⭐️] **VGGT4D**, "VGGT4D: Mining Motion Cues in Visual Geometry Transformers for 4D Scene Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2511.19971-b31b1b.svg)](https://arxiv.org/abs/2511.19971) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/3DAgentWorld/VGGT4D)
- [⭐️] **4D-VGGT**, "4D-VGGT: A General Foundation Model with SpatioTemporal Awareness for Dynamic Scene Geometry Estimation". [![arXiv](https://img.shields.io/badge/arXiv-2511.18416-b31b1b.svg)](https://arxiv.org/abs/2511.18416)
- **One4D**, "One4D: Unified 4D Generation and Reconstruction via Decoupled LoRA Control". [![arXiv](https://img.shields.io/badge/arXiv-2511.18922-b31b1b.svg)](https://arxiv.org/abs/2511.18922)
- **C4D**, "C4D: 4D Made from 3D through Dual Correspondences". [![arXiv](https://img.shields.io/badge/arXiv-2510.14960-b31b1b.svg)](https://arxiv.org/abs/2510.14960)
- **St4RTrack**, "St4RTrack: Simultaneous 4D Reconstruction and Tracking in the World". [![arXiv](https://img.shields.io/badge/arXiv-2504.13152-b31b1b.svg)](https://arxiv.org/abs/2504.13152) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nhan-nguyen-trong/St4RTrack)
- **CAT4D**, "CAT4D: Create Anything in 4D with Multi-View Video Diffusion Models". [![arXiv](https://img.shields.io/badge/arXiv-2411.18613-b31b1b.svg)](https://arxiv.org/abs/2411.18613)
- **Shape of Motion**, "Shape of Motion: 4D Reconstruction from a Single Video". [![arXiv](https://img.shields.io/badge/arXiv-2407.13764-b31b1b.svg)](https://arxiv.org/abs/2407.13764) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/vye16/shape-of-motion)


### non-E2E 4D Reconstruction
- **Sparse4DGS**, "Sparse4DGS: 4D Gaussian Splatting for Sparse-Frame Dynamic Scene Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2511.07122-b31b1b.svg)](https://arxiv.org/abs/2511.07122)
- [⭐️] "Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2511.14540-b31b1b.svg)](https://arxiv.org/abs/2511.14540)
- **SplatFields**, "Neural Gaussian Splats for Sparse 3D and 4D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2409.11211-b31b1b.svg)](https://arxiv.org/abs/2409.11211) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/markomih/SplatFields)
- **L4GM**, "L4GM: Large 4D Gaussian Reconstruction Model". [![arXiv](https://img.shields.io/badge/arXiv-2406.10324-b31b1b.svg)](https://arxiv.org/abs/2406.10324) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nv-tlabs/L4GM-official)
- **Gaussian-Flow**, "Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle". [![arXiv](https://img.shields.io/badge/arXiv-2312.03431-b31b1b.svg)](https://arxiv.org/abs/2312.03431) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/NJU-3DV/Gaussian-Flow)
- [⭐️] "4D Gaussian Splatting for Real-Time Dynamic Scene Rendering". [![arXiv](https://img.shields.io/badge/arXiv-2310.08528-b31b1b.svg)](https://arxiv.org/abs/2310.08528) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/hustvl/4DGaussians)


## 4D Perception
- **ReScene4D**, "ReScene4D: Temporally Consistent Semantic Instance Segmentation of Evolving Indoor 3D Scenes". [![arXiv](https://img.shields.io/badge/arXiv-2601.11508-b31b1b.svg)](https://arxiv.org/abs/2601.11508)
- [⭐️] **VerseCrafter**, "VerseCrafter: Dynamic Realistic Video World Model with 4D Geometric Control". [![arXiv](https://img.shields.io/badge/arXiv-2601.05138-b31b1b.svg)](https://arxiv.org/abs/2601.05138) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/TencentARC/VerseCrafter)
- [⭐️] **NeoVerse**, "NeoVerse: Enhancing 4D World Model with in-the-wild Monocular Videos". [![arXiv](https://img.shields.io/badge/arXiv-2601.00393-b31b1b.svg)](https://arxiv.org/abs/2601.00393) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/IamCreateAI/NeoVerse)
- "Choreographing a World of Dynamic Objects". [![arXiv](https://img.shields.io/badge/arXiv-2601.04194-b31b1b.svg)](https://arxiv.org/abs/2601.04194)
- **3AM**, "3AM: Segment Anything with Geometric Consistency in Videos". [![arXiv](https://img.shields.io/badge/arXiv-2601.08831-b31b1b.svg)](https://arxiv.org/abs/2601.08831)
- **SeeU**, "SeeU: Seeing the Unseen World via 4D Dynamics-aware Generation". [![arXiv](https://img.shields.io/badge/arXiv-2512.03350-b31b1b.svg)](https://arxiv.org/abs/2512.03350) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/YuYuan-Yolanda/SeeU)
- **DynamicVerse**, "DynamicVerse: A Physically-Aware Multimodal Framework for 4D World Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2512.03000-b31b1b.svg)](https://arxiv.org/abs/2512.03000) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Dynamics-X/DynamicVerse)
- **PAGE-4D**, "PAGE-4D: Disentangled Pose and Geometry Estimation for VGGT-4D Perception". [![arXiv](https://img.shields.io/badge/arXiv-2510.17568-b31b1b.svg)](https://arxiv.org/abs/2510.17568)
- **Trace Anything**, "Trace Anything: Representing Any Video in 4D via Trajectory Fields". [![arXiv](https://img.shields.io/badge/arXiv-2510.13802-b31b1b.svg)](https://arxiv.org/abs/2510.13802) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/ByteDance-Seed/TraceAnything)
- [⭐️] **OmniWorld**, "OmniWorld: A Multi-Domain and Multi-Modal Dataset for 4D World Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2509.12201-b31b1b.svg)](https://arxiv.org/abs/2509.12201v1) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/yangzhou24/OmniWorld)
- [⭐️] **ViPE**, "ViPE: Video Pose Engine for 3D Geometric Perception". [![arXiv](https://img.shields.io/badge/arXiv-2508.10934-b31b1b.svg)](https://arxiv.org/abs/2508.10934) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nv-tlabs/vipe)
- **Uni4D**, "Uni4D: Unifying Visual Foundation Models for 4D Modeling from a Single Video". [![arXiv](https://img.shields.io/badge/arXiv-2503.21761-b31b1b.svg)](https://arxiv.org/abs/2503.21761) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Davidyao99/uni4d)
- **Stereo4D**, "Stereo4D: Learning How Things Move in 3D from Internet Stereo Videos". [![arXiv](https://img.shields.io/badge/arXiv-2412.09621-b31b1b.svg)](https://arxiv.org/abs/2412.09621) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/mli0603/stereo4d)



## 3D Free Method
- [⭐️] **XFactor**, "True Self-Supervised Novel View Synthesis is Transferable". [![arXiv](https://img.shields.io/badge/arXiv-2510.13063-b31b1b.svg)](https://arxiv.org/abs/2510.13063) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/vsitzmann/xfactor-nvs)
- [⭐️] **RayZer**, "RayZer: A Self-supervised Large View Synthesis Model". [![arXiv](https://img.shields.io/badge/arXiv-2505.00702-b31b1b.svg)](https://arxiv.org/abs/2505.00702) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/hwjiang1510/RayZer)
- [⭐️] **LVSM**, "LVSM: A Large View Synthesis Model with Minimal 3D Inductive Bias". [![arXiv](https://img.shields.io/badge/arXiv-2410.17242-b31b1b.svg)](https://arxiv.org/abs/2410.17242) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/haian-jin/LVSM)



## Related Analysis
- "On Geometric Understanding and Learned Data Priors in VGGT". [![arXiv](https://img.shields.io/badge/arXiv-2512.11508-b31b1b.svg)](https://arxiv.org/abs/2512.11508)
- "What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models". [![arXiv](https://img.shields.io/badge/arXiv-2512.03422-b31b1b.svg)](https://arxiv.org/abs/2512.03422v1)
- "How Much 3D Do Video Foundation Models Encode?". [![arXiv](https://img.shields.io/badge/arXiv-2512.19949-b31b1b.svg)](https://arxiv.org/abs/2512.19949)
- "Feat2GS: Probing Visual Foundation Models with Gaussian Splatting". [![arXiv](https://img.shields.io/badge/arXiv-2412.09606-b31b1b.svg)](https://arxiv.org/abs/2412.09606)


## Foundation Models
### Generation/Reconstruction Foundation Models
- **HunyuanWorld 1.0**, "HunyuanWorld 1.0: Generating Immersive, Explorable, and Interactive 3D Worlds from Words or Pixels". [![arXiv](https://img.shields.io/badge/arXiv-2507.21809-b31b1b.svg)](https://arxiv.org/abs/2507.21809) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Tencent-Hunyuan/HunyuanWorld-1.0)
- **Hunyuan3D 2.5**, "Hunyuan3D 2.5: Towards High-Fidelity 3D Assets Generation with Ultimate Details". [![arXiv](https://img.shields.io/badge/arXiv-2506.1650-b31b1b.svg)](https://arxiv.org/abs/2506.1650) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Tencent-Hunyuan/Hunyuan3D-2)
- [⭐️] "Video World Models with Long-term Spatial Memory". [![arXiv](https://img.shields.io/badge/arXiv-2506.05284-b31b1b.svg)](https://arxiv.org/abs/2506.05284)
- **Wan**, "Wan: Open and Advanced Large-Scale Video Generative Models". [![arXiv](https://img.shields.io/badge/arXiv-2503.20314-b31b1b.svg)](https://arxiv.org/abs/2503.20314v2) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Wan-Video/Wan2.1)
- **Hunyuan3D 1.0**, "Hunyuan3D 1.0: A Unified Framework for Text-to-3D and Image-to-3D Generation". [![arXiv](https://img.shields.io/badge/arXiv-2411.02293-b31b1b.svg)](https://arxiv.org/abs/2411.02293) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Tencent/Hunyuan3D-1)


### Physical Foundation Models
- [⭐️] **Cosmos2.5**, "World Simulation with Video Foundation Models for
Physical AI". [![arXiv](https://img.shields.io/badge/arXiv-2511.00062-b31b1b.svg)](https://arxiv.org/abs/2511.00062v1) [![GitHub](https://img.shields.io/badge/GitHub-predict2.5-blue)](https://github.com/nvidia-cosmos/cosmos-predict2.5) [![GitHub](https://img.shields.io/badge/GitHub-transfer2.5-blue)](https://github.com/nvidia-cosmos/cosmos-transfer2.5) [![GitHub](https://img.shields.io/badge/GitHub-reason1-blue)](https://github.com/nvidia-cosmos/cosmos-reason1)
- [⭐️] **Cosmos**, "Cosmos World Foundation Model Platform for Physical AI". [![arXiv](https://img.shields.io/badge/arXiv-2501.03575-b31b1b.svg)](https://arxiv.org/abs/2501.03575v3) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/NVIDIA/Cosmos)




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
