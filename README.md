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
<li style="margin-left: 0;"><a href="#3d-editing">3D Editing</a></li>
<li style="margin-left: 0;">
<details>
<summary><a href="#3d-perception">3D Perception</a></summary>
<ul>
<li><a href="#depth--geometry-perception">Depth / Geometry Perception</a></li>
<li><a href="#3d-understanding">3D Understanding</a></li>
<li><a href="#spatial-reasoning">Spatial Reasoning</a></li>
</ul>
</details>
</li>
<li style="margin-left: 0;">
<details>
<summary><a href="#4d-reconstruction">4D Reconstruction</a></summary>
<ul>
<li><a href="#e2e-4d-reconstruction">E2E 4D Reconstruction</a></li>
<li><a href="#non-e2e-4d-reconstruction">non-E2E 4D Reconstruction</a></li>
</ul>
</details>
</li>
<li style="margin-left: 0;"><a href="#4d-editing">4D Editing</a></li>
<li style="margin-left: 0;">
<details>
<summary><a href="#4d-perception">4D Perception</a></summary>
<ul>
<li><a href="#4d-geometry--motion-perception">4D Geometry / Motion Perception</a></li>
<li><a href="#4d-understanding--tracking">4D Understanding / Tracking</a></li>
</ul>
</details>
</li>
<li style="margin-left: 0;"><a href="#explicit-3d-free-methods">Explicit 3D-Free Methods</a></li>
<li style="margin-left: 0;"><a href="#related-analysis">Related Analysis</a></li>
<li style="margin-left: 0;">
<details>
<summary><a href="#foundation-models-with-3d-awareness">Foundation Models with 3D Awareness</a></summary>
<ul>
<li><a href="#generative-models">Generative Models</a></li>
<li><a href="#world-models--action-models">World Models / Action Models</a></li>
<li><a href="#datasets--benchmarks">Datasets / Benchmarks</a></li>
</ul>
</details>
</li>
<li style="margin-left: 0;">
<details>
<summary><a href="#3d-vision-applications">3D Vision Applications</a></summary>
<ul>
<li><a href="#autonomous-driving">Autonomous Driving</a></li>
</ul>
</details>
</li>
<li style="margin-left: 0;"><a href="#acknowledgements">Acknowledgements</a></li>
<li style="margin-left: 0;"><a href="#citation">Citation</a></li>
</ul>

> **Legend**<br>
> ⭐️ Recommended<br>
> **Last Updated:** 2026-04-15

# 3D Vision Methods
## Surveys
- "Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey". [![arXiv](https://img.shields.io/badge/arXiv-2507.14501-b31b1b.svg)](https://arxiv.org/abs/2507.14501)
- "3D Scene Generation: A Survey". [![arXiv](https://img.shields.io/badge/arXiv-2505.05474-b31b1b.svg)](https://arxiv.org/abs/2505.05474v1)
- "Learning-based 3D Reconstruction in Autonomous Driving: A Comprehensive Survey". [![arXiv](https://img.shields.io/badge/arXiv-2503.14537-b31b1b.svg)](https://arxiv.org/abs/2503.14537)
- "Recent Advances in 3D Object and Scene Generation: A Survey". [![arXiv](https://img.shields.io/badge/arXiv-2504.11734-b31b1b.svg)](https://arxiv.org/abs/2504.11734)
- "A Review of 3D Reconstruction Techniques for Deformable Tissues in Robotic Surgery". [![arXiv](https://img.shields.io/badge/arXiv-2408.04426-b31b1b.svg)](https://arxiv.org/abs/2408.04426)


## End to End 3D Reconstruction
- [⭐️] **NOVA3R**, "NOVA3R: Non-pixel-aligned Visual Transformer for Amodal 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2603.04179-b31b1b.svg)](https://arxiv.org/abs/2603.04179) [![Project](https://img.shields.io/badge/Project-Page-green)](https://wrchen530.github.io/nova3r/)
- [⭐️] **tttLRM**, "tttLRM: Test-Time Training for Long Context and Autoregressive 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2602.20160-b31b1b.svg)](https://arxiv.org/abs/2602.20160) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/cwchenwang/tttLRM)
- **VGG-T^3**, "VGG-T^3: Offline Feed-Forward 3D Reconstruction at Scale". [![arXiv](https://img.shields.io/badge/arXiv-2602.23361-b31b1b.svg)](https://arxiv.org/abs/2602.23361) [![Project](https://img.shields.io/badge/Project-Page-green)](https://research.nvidia.com/labs/dvl/projects/vgg-ttt/)
- [⭐️] **E-RayZer**, "E-RayZer: Self-supervised 3D Reconstruction as Spatial Visual Pre-training". [![arXiv](https://img.shields.io/badge/arXiv-2512.10950-b31b1b.svg)](https://arxiv.org/abs/2512.10950) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/hwjiang1510/E-RayZer)
- [⭐️] **DA3**, "Depth Anything 3: Recovering the Visual Space from Any Views". [![arXiv](https://img.shields.io/badge/arXiv-2511.10647-b31b1b.svg)](https://arxiv.org/abs/2511.10647) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/ByteDance-Seed/Depth-Anything-3)
- **OmniVGGT**, "OmniVGGT: Omni-Modality Driven Visual Geometry Grounded Transformer". [![arXiv](https://img.shields.io/badge/arXiv-2511.10560-b31b1b.svg)](https://arxiv.org/abs/2511.10560v1) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Livioni/OmniVGGT-official)
- **MapAnything**, "MapAnything: Universal Feed-Forward Metric 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2509.13414-b31b1b.svg)](https://arxiv.org/abs/2509.13414v2) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/facebookresearch/map-anything)
- **VGGT-Long**, "VGGT-Long: Chunk It, Loop It, Align It — Pushing VGGT's Limits on Kilometer-Scale Long RGB Sequences". [![arXiv](https://img.shields.io/badge/arXiv-2507.16443-b31b1b.svg)](https://arxiv.org/abs/2507.16443)
- **Dens3R**, "Dens3R: A Foundation Model for 3D Geometry Prediction". [![arXiv](https://img.shields.io/badge/arXiv-2507.16290-b31b1b.svg)](https://arxiv.org/abs/2507.16290)
- **Test3R**, "Test3R: Learning to Reconstruct 3D at Test Time". [![arXiv](https://img.shields.io/badge/arXiv-2506.13750-b31b1b.svg)](https://arxiv.org/abs/2506.13750)
- **Mono3R**, "Mono3R: Exploiting Monocular Cues for Geometric 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2504.13419-b31b1b.svg)](https://arxiv.org/abs/2504.13419)
- **Pow3R**, "Pow3R: Empowering Unconstrained 3D Reconstruction with Camera and Scene Priors". [![arXiv](https://img.shields.io/badge/arXiv-2503.17316-b31b1b.svg)](https://arxiv.org/abs/2503.17316)
- [⭐️] **π^3**, "π^3: Permutation-Equivariant Visual Geometry Learning". [![arXiv](https://img.shields.io/badge/arXiv-2507.13347-b31b1b.svg)](https://arxiv.org/abs/2507.13347v2) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/yyfz/Pi3)
- [⭐️] **VGGT**, "On Geometric Understanding and Learned Data Priors in VGGT". [![arXiv](https://img.shields.io/badge/arXiv-2503.11651-b31b1b.svg)](https://arxiv.org/abs/2503.11651) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/facebookresearch/vggt)
- **FLARE**, "FLARE: Feed-Forward Geometry, Appearance and Camera Estimation from Uncalibrated Sparse Views". [![arXiv](https://img.shields.io/badge/arXiv-2502.12138-b31b1b.svg)](https://arxiv.org/abs/2502.12138)
- **Fast3R**, "Fast3R: Towards 3D Reconstruction of 1000+ Images in One Forward Pass". [![arXiv](https://img.shields.io/badge/arXiv-2501.13928-b31b1b.svg)](https://arxiv.org/abs/2501.13928)
- [⭐️] **NopoSplat**, "No Pose, No Problem: Surprisingly Simple 3D Gaussian Splats from Sparse Unposed Images". [![arXiv](https://img.shields.io/badge/arXiv-2410.24207-b31b1b.svg)](https://arxiv.org/abs/2410.24207) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/cvg/NoPoSplat)
- **MV-DUSt3R+**, "MV-DUSt3R+: Single-Stage Scene Reconstruction from Sparse Views In 2 Seconds". [![arXiv](https://img.shields.io/badge/arXiv-2412.06974-b31b1b.svg)](https://arxiv.org/abs/2412.06974)
- **MASt3R**, "Grounding Image Matching in 3D with MASt3R". [![arXiv](https://img.shields.io/badge/arXiv-2406.09756-b31b1b.svg)](https://arxiv.org/abs/2406.09756) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/naver/mast3r)
- [⭐️] **MVSplat**, "MVSplat: Efficient 3D Gaussian Splatting from Sparse Multi-View Images". [![arXiv](https://img.shields.io/badge/arXiv-2403.14627-b31b1b.svg)](https://arxiv.org/abs/2403.14627) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/donydchen/mvsplat)
- [⭐️] **DUSt3R**, "DUSt3R: Geometric 3D Vision Made Easy". [![arXiv](https://img.shields.io/badge/arXiv-2312.14132-b31b1b.svg)](https://arxiv.org/abs/2312.14132) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/naver/dust3r)
- [⭐️] **CroCo**, "CroCo: Self-Supervised Pre-training for 3D Vision Tasks by Cross-View Completion". [![arXiv](https://img.shields.io/badge/arXiv-2210.10716-b31b1b.svg)](https://arxiv.org/abs/2210.10716) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/naver/croco)


## Online 3R/SLAM
### Online 3R
- **Online3R**, "Online3R: Online Learning for Consistent Sequential Reconstruction Based on Geometry Foundation Model". [![arXiv](https://img.shields.io/badge/arXiv-2604.09480-b31b1b.svg)](https://arxiv.org/abs/2604.09480)
- [⭐️] **MeMix**, "MeMix: Writing Less, Remembering More for Streaming 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2603.15330-b31b1b.svg)](https://arxiv.org/abs/2603.15330) [![Project](https://img.shields.io/badge/Project-Page-green)](https://dongjiacheng06.github.io/MeMix/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/dongjiacheng06/MeMix)
- [⭐️] **ZipMap**, "ZipMap: Linear-Time Stateful 3D Reconstruction via Test-Time Training". [![arXiv](https://img.shields.io/badge/arXiv-2603.04385-b31b1b.svg)](https://arxiv.org/abs/2603.04385) [![Project](https://img.shields.io/badge/Project-Page-green)](https://haian-jin.github.io/ZipMap/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Haian-Jin/ZipMap)
- **LongStream**, "LongStream: Long-Sequence Streaming Autoregressive Visual Geometry". [![arXiv](https://img.shields.io/badge/arXiv-2602.13172-b31b1b.svg)](https://arxiv.org/abs/2602.13172) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/3DAgentWorld/LongStream/tree/main)
- **TTSA3R**, "TTSA3R: Training-Free Temporal-Spatial Adaptive Persistent State for Streaming 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2601.22615-b31b1b.svg)](https://arxiv.org/abs/2601.22615) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/anonus2357/ttsa3r)
- **InfiniteVGGT**, "InfiniteVGGT: Visual Geometry Grounded Transformer for Endless Streams". [![arXiv](https://img.shields.io/badge/arXiv-2601.02281-b31b1b.svg)](https://arxiv.org/abs/2601.02281v1) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/AutoLab-SAI-SJTU/InfiniteVGGT)
- **XStreamVGGT**, "XStreamVGGT: Extremely Memory-Efficient Streaming Vision Geometry Grounded Transformer with KV Cache Compression". [![arXiv](https://img.shields.io/badge/arXiv-2601.01204-b31b1b.svg)](https://arxiv.org/abs/2601.01204v1)
- **MUT3R**, "MUT3R: Motion-aware Updating Transformer for Dynamic 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2512.03939-b31b1b.svg)](https://arxiv.org/abs/2512.03939)
- [⭐️] **TTT3R**, "TTT3R: 3D RECONSTRUCTION AS TEST-TIME TRAINING". [![arXiv](https://img.shields.io/badge/arXiv-2509.26645-b31b1b.svg)](https://arxiv.org/abs/2509.26645v3) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Inception3D/TTT3R)
- **G-CUT3R**, "G-CUT3R: Guided 3D Reconstruction with Camera and Depth Prior Integration". [![arXiv](https://img.shields.io/badge/arXiv-2508.11379-b31b1b.svg)](https://arxiv.org/abs/2508.11379v2)
- [⭐️] **StreamVGGT**, "Streaming 4D Visual Geometry Transformer". [![arXiv](https://img.shields.io/badge/arXiv-2507.11539-b31b1b.svg)](https://arxiv.org/abs/2507.11539) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/wzzheng/StreamVGGT)
- [⭐️] **Point3R**, "Point3R: Streaming 3D Reconstruction with Explicit Spatial Pointer Memory". [![arXiv](https://img.shields.io/badge/arXiv-2507.02863-b31b1b.svg)](https://arxiv.org/abs/2507.02863) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/YkiWu/Point3R)
- [⭐️] **CUT3R**, "Continuous 3D Perception Model with Persistent State". [![arXiv](https://img.shields.io/badge/arXiv-2501.12387-b31b1b.svg)](https://arxiv.org/abs/2501.12387) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/CUT3R/CUT3R)
- [⭐️] **Spann3R**, "3D Reconstruction with Spatial Memory". [![arXiv](https://img.shields.io/badge/arXiv-2408.16061-b31b1b.svg)](https://arxiv.org/abs/2408.16061) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/HengyiWang/spann3r)


### SLAM
- **SLAM-Former**, "SLAM-Former: Putting SLAM into One Transformer". [![arXiv](https://img.shields.io/badge/arXiv-2509.16909-b31b1b.svg)](https://arxiv.org/abs/2509.16909v1)
- **GRS-SLAM3R**, "GRS-SLAM3R: Real-Time Dense SLAM with Gated Recurrent State". [![arXiv](https://img.shields.io/badge/arXiv-2509.23737-b31b1b.svg)](https://arxiv.org/abs/2509.23737v1)
- **VGGT-SLAM**, "VGGT-SLAM: Dense RGB SLAM Optimized on the SL(4) Manifold". [![arXiv](https://img.shields.io/badge/arXiv-2505.12549-b31b1b.svg)](https://arxiv.org/abs/2505.12549) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/MIT-SPARK/VGGT-SLAM)
- **SLAM3R**, "SLAM3R: Real-Time Dense Scene Reconstruction from Monocular RGB Videos". [![arXiv](https://img.shields.io/badge/arXiv-2412.09401-b31b1b.svg)](https://arxiv.org/abs/2412.09401) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/PKU-VCL-3DV/SLAM3R)
- **MASt3R-SLAM**, "MASt3R-SLAM: Real-Time Dense SLAM with 3D Reconstruction Priors". [![arXiv](https://img.shields.io/badge/arXiv-2412.12392-b31b1b.svg)](https://arxiv.org/abs/2412.12392v2) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/rmurai0610/MASt3R-SLAM)

## 3D Generation
- **CoMoVi**, "CoMoVi: Co-Generation of 3D Human Motions and Realistic Videos". [![arXiv](https://img.shields.io/badge/arXiv-2601.10632-b31b1b.svg)](https://arxiv.org/abs/2601.10632)
- [⭐️] **TRELLIS.2**, "Native and Compact Structured Latents for 3D Generation". [![arXiv](https://img.shields.io/badge/arXiv-2512.14692-b31b1b.svg)](https://arxiv.org/abs/2512.14692) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/microsoft/TRELLIS.2)
- [⭐️] **SAM 3D**, "SAM 3D: 3Dfy Anything in Images". [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://ai.meta.com/research/publications/sam-3d-3dfy-anything-in-images/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/facebookresearch/sam-3d-objects)
- **GeoWorld**, "GeoWorld: Unlocking the Potential of Geometry Models to Facilitate High-Fidelity 3D Scene Generation". [![arXiv](https://img.shields.io/badge/arXiv-2511.23191-b31b1b.svg)](https://arxiv.org/abs/2511.23191)
- **CUPID**, "CUPID: Generative 3D Reconstruction via Joint Object and Pose Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2510.20776-b31b1b.svg)](https://arxiv.org/abs/2510.20776) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/cupid3d/Cupid)
- [⭐️] **LYRA**, "LYRA: Generative 3D Scene Reconstruction via Video Diffusion Model Self-Distillation". [![arXiv](https://img.shields.io/badge/arXiv-2509.19296-b31b1b.svg)](https://arxiv.org/abs/2509.19296v1) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nv-tlabs/lyra)
- **Hunyuan3D 2.5**, "Hunyuan3D 2.5: Towards High-Fidelity 3D Assets Generation with Ultimate Details". [![arXiv](https://img.shields.io/badge/arXiv-2506.16504-b31b1b.svg)](https://arxiv.org/abs/2506.16504) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Tencent-Hunyuan/Hunyuan3D-2)
- **Hunyuan3D 2.1**, "Hunyuan3D 2.1: From Images to High-Fidelity 3D Assets with Production-Ready PBR Material". [![arXiv](https://img.shields.io/badge/arXiv-2506.15442-b31b1b.svg)](https://arxiv.org/abs/2506.15442)
- [⭐️] **TRELLIS**, "Structured 3D Latents for Scalable and Versatile 3D Generation". [![arXiv](https://img.shields.io/badge/arXiv-2412.01506-b31b1b.svg)](https://arxiv.org/abs/2412.01506) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/microsoft/TRELLIS)
- **Hunyuan3D 1.0**, "Hunyuan3D 1.0: A Unified Framework for Text-to-3D and Image-to-3D Generation". [![arXiv](https://img.shields.io/badge/arXiv-2411.02293-b31b1b.svg)](https://arxiv.org/abs/2411.02293) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Tencent/Hunyuan3D-1)
- **Edify 3D**, "Edify 3D: Scalable High-Quality 3D Asset Generation". [![arXiv](https://img.shields.io/badge/arXiv-2411.07135-b31b1b.svg)](https://arxiv.org/abs/2411.07135)
- **InstantMesh**, "InstantMesh: Efficient 3D Mesh Generation from a Single Image with Sparse-View Large Reconstruction Models". [![arXiv](https://img.shields.io/badge/arXiv-2404.07191-b31b1b.svg)](https://arxiv.org/abs/2404.07191)
- **TripoSR**, "TripoSR: Fast 3D Object Reconstruction from a Single Image". [![arXiv](https://img.shields.io/badge/arXiv-2403.02151-b31b1b.svg)](https://arxiv.org/abs/2403.02151)
- [⭐️] **LGM**, "LGM: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation". [![arXiv](https://img.shields.io/badge/arXiv-2402.05054-b31b1b.svg)](https://arxiv.org/abs/2402.05054) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/3DTopia/LGM)
- **Instant3D**, "Instant3D: Fast Text-to-3D with Sparse-View Generation and Large Reconstruction Model". [![arXiv](https://img.shields.io/badge/arXiv-2311.06214-b31b1b.svg)](https://arxiv.org/abs/2311.06214)
- [⭐️] **LRM**, "LRM: Large Reconstruction Model for Single Image to 3D". [![arXiv](https://img.shields.io/badge/arXiv-2311.04400-b31b1b.svg)](https://arxiv.org/abs/2311.04400) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/3DTopia/OpenLRM)
- **DreamGaussian**, "DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation". [![arXiv](https://img.shields.io/badge/arXiv-2309.16653-b31b1b.svg)](https://arxiv.org/abs/2309.16653)
- [⭐️] **Zero123++**, "Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model". [![arXiv](https://img.shields.io/badge/arXiv-2310.15110-b31b1b.svg)](https://arxiv.org/abs/2310.15110) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/SUDO-AI-3D/zero123plus)
- **Wonder3D**, "Wonder3D: Single Image to 3D Using Cross-Domain Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2310.15008-b31b1b.svg)](https://arxiv.org/abs/2310.15008)
- **MVDream**, "MVDream: Multi-View Diffusion for 3D Generation". [![arXiv](https://img.shields.io/badge/arXiv-2308.16512-b31b1b.svg)](https://arxiv.org/abs/2308.16512)
- **Michelangelo**, "Michelangelo: Conditional 3D Shape Generation based on Shape-Image-Text Aligned Latent Representation". [![arXiv](https://img.shields.io/badge/arXiv-2306.17115-b31b1b.svg)](https://arxiv.org/abs/2306.17115) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/NeuralCarver/Michelangelo)
- **Magic3D**, "Magic3D: High-Resolution Text-to-3D Content Creation". [![arXiv](https://img.shields.io/badge/arXiv-2211.10440-b31b1b.svg)](https://arxiv.org/abs/2211.10440)
- **DreamFusion**, "DreamFusion: Text-to-3D Using 2D Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2209.14988-b31b1b.svg)](https://arxiv.org/abs/2209.14988)


## 3D Editing
- **Instruct-NeRF2NeRF**, "Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions". [![arXiv](https://img.shields.io/badge/arXiv-2303.12789-b31b1b.svg)](https://arxiv.org/abs/2303.12789)
- **DreamEditor**, "DreamEditor: Text-Driven 3D Scene Editing with Neural Fields". [![arXiv](https://img.shields.io/badge/arXiv-2306.13455-b31b1b.svg)](https://arxiv.org/abs/2306.13455)
- **GaussianEditor**, "GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting". [![arXiv](https://img.shields.io/badge/arXiv-2311.14521-b31b1b.svg)](https://arxiv.org/abs/2311.14521)
- **GSEdit**, "GSEdit: Efficient Text-Guided Editing of 3D Objects via Gaussian Splatting". [![arXiv](https://img.shields.io/badge/arXiv-2403.05154-b31b1b.svg)](https://arxiv.org/abs/2403.05154)
- **DreamCatalyst**, "DreamCatalyst: Fast and High-Quality 3D Editing via Controlling Editability and Identity". [![arXiv](https://img.shields.io/badge/arXiv-2407.11394-b31b1b.svg)](https://arxiv.org/abs/2407.11394)
- **CoreEditor**, "CoreEditor: Consistent 3D Editing via Correspondence-Constrained Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2508.11603-b31b1b.svg)](https://arxiv.org/abs/2508.11603)
- **Vox-E**, "Vox-E: Text-Guided Voxel Editing of 3D Objects". [![arXiv](https://img.shields.io/badge/arXiv-2303.12048-b31b1b.svg)](https://arxiv.org/abs/2303.12048)
- **VecSet-Edit**, "VecSet-Edit: Unleashing Pre-Trained LRM for Mesh Editing from Single Image". [![arXiv](https://img.shields.io/badge/arXiv-2602.04349-b31b1b.svg)](https://arxiv.org/abs/2602.04349)


## 3D Perception
### Depth / Geometry Perception
- **LingBot-Depth**, "LingBot-Depth: Masked Depth Modeling for Spatial Perception". [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Robbyant/lingbot-depth)
- **AnyDepth**, "AnyDepth: Depth Estimation Made Easy". [![arXiv](https://img.shields.io/badge/arXiv-2601.02760-b31b1b.svg)](https://arxiv.org/abs/2601.02760)
- **DA^2**, "DA^2: Depth Anything in Any Direction". [![arXiv](https://img.shields.io/badge/arXiv-2509.26618-b31b1b.svg)](https://arxiv.org/abs/2509.26618)
- "Depth Anything at Any Condition". [![arXiv](https://img.shields.io/badge/arXiv-2507.01634-b31b1b.svg)](https://arxiv.org/abs/2507.01634)
- [⭐️] "Depth Anything v2". [![arXiv](https://img.shields.io/badge/arXiv-2406.09414-b31b1b.svg)](https://arxiv.org/abs/2406.09414) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/DepthAnything/Depth-Anything-V2)
- [⭐️] **Depth Anything**, "Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data". [![arXiv](https://img.shields.io/badge/arXiv-2401.10891-b31b1b.svg)](https://arxiv.org/abs/2401.10891) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/LiheYoung/Depth-Anything)

### 3D Understanding
- **Utonia**, "Utonia: Toward One Encoder for All Point Clouds". [![arXiv](https://img.shields.io/badge/arXiv-2603.03283-b31b1b.svg)](https://arxiv.org/abs/2603.03283) [![Project](https://img.shields.io/badge/Project-Page-green)](https://pointcept.github.io/Utonia/)
- **MVGGT**, "MVGGT: Multimodal Visual Geometry Grounded Transformer for Multiview 3D Referring Expression Segmentation". [![arXiv](https://img.shields.io/badge/arXiv-2601.06874-b31b1b.svg)](https://arxiv.org/abs/2601.06874) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/sosppxo/mvggt)
- **OpenVoxel**, "OpenVoxel: Training-Free Grouping and Captioning Voxels for Open-Vocabulary 3D Scene Understanding". [![arXiv](https://img.shields.io/badge/arXiv-2601.09575-b31b1b.svg)](https://arxiv.org/abs/2601.09575)
- [⭐️] **SAM3D**, "SAM3D: Zero-Shot 3D Object Detection via Segment Anything Model". [![arXiv](https://img.shields.io/badge/arXiv-2306.02245-b31b1b.svg)](https://arxiv.org/abs/2306.02245)

### Spatial Reasoning
- **Map2Thought**, "Map2Thought: Explicit 3D Spatial Reasoning via Metric Cognitive Maps". [![arXiv](https://img.shields.io/badge/arXiv-2601.11442-b31b1b.svg)](https://arxiv.org/abs/2601.11442)
- **Think3D**, "Think3D: Thinking with Space for Spatial Reasoning". [![arXiv](https://img.shields.io/badge/arXiv-2601.13029-b31b1b.svg)](https://arxiv.org/abs/2601.13029)

## 4D Reconstruction
### E2E 4D Reconstruction
- **Flow4R**, "Flow4R: Unifying 4D Reconstruction and Tracking with Scene Flow". [![arXiv](https://img.shields.io/badge/arXiv-2602.14021-b31b1b.svg)](https://arxiv.org/abs/2602.14021)
- **Motion 3-to-4**, "Motion 3-to-4: 3D Motion Reconstruction for 4D Synthesis". [![arXiv](https://img.shields.io/badge/arXiv-2601.14253-b31b1b.svg)](https://arxiv.org/abs/2601.14253)
- **V-DPM**, "V-DPM: 4D Video Reconstruction with Dynamic Point Maps". [![arXiv](https://img.shields.io/badge/arXiv-2601.09499-b31b1b.svg)](https://arxiv.org/abs/2601.09499)
- [⭐️] **D4RT**, "Efficiently Reconstructing Dynamic Scenes One D4RT at a Time". [![arXiv](https://img.shields.io/badge/arXiv-2512.08924-b31b1b.svg)](https://arxiv.org/abs/2512.08924) [![GitHub](https://img.shields.io/badge/GitHub-Page-blue)](https://d4rt-paper.github.io/) [![Blog](https://img.shields.io/badge/DeepMind-Blog-yellow)](https://deepmind.google/blog/d4rt-teaching-ai-to-see-the-world-in-four-dimensions/)
- [⭐️] **VGGT4D**, "VGGT4D: Mining Motion Cues in Visual Geometry Transformers for 4D Scene Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2511.19971-b31b1b.svg)](https://arxiv.org/abs/2511.19971) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/3DAgentWorld/VGGT4D)
- [⭐️] **4D-VGGT**, "4D-VGGT: A General Foundation Model with SpatioTemporal Awareness for Dynamic Scene Geometry Estimation". [![arXiv](https://img.shields.io/badge/arXiv-2511.18416-b31b1b.svg)](https://arxiv.org/abs/2511.18416)
- **One4D**, "One4D: Unified 4D Generation and Reconstruction via Decoupled LoRA Control". [![arXiv](https://img.shields.io/badge/arXiv-2511.18922-b31b1b.svg)](https://arxiv.org/abs/2511.18922)
- **C4D**, "C4D: 4D Made from 3D through Dual Correspondences". [![arXiv](https://img.shields.io/badge/arXiv-2510.14960-b31b1b.svg)](https://arxiv.org/abs/2510.14960)
- **D²USt3R**, "D²USt3R: Enhancing 3D Reconstruction with 4D Pointmaps for Dynamic Scenes". [![arXiv](https://img.shields.io/badge/arXiv-2504.06264-b31b1b.svg)](https://arxiv.org/abs/2504.06264)
- **St4RTrack**, "St4RTrack: Simultaneous 4D Reconstruction and Tracking in the World". [![arXiv](https://img.shields.io/badge/arXiv-2504.13152-b31b1b.svg)](https://arxiv.org/abs/2504.13152) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nhan-nguyen-trong/St4RTrack)
- **CAT4D**, "CAT4D: Create Anything in 4D with Multi-View Video Diffusion Models". [![arXiv](https://img.shields.io/badge/arXiv-2411.18613-b31b1b.svg)](https://arxiv.org/abs/2411.18613)
- **MonST3R**, "MonST3R: A Simple Approach for Estimating Geometry in the Presence of Motion". [![arXiv](https://img.shields.io/badge/arXiv-2410.03825-b31b1b.svg)](https://arxiv.org/abs/2410.03825)
- **Shape of Motion**, "Shape of Motion: 4D Reconstruction from a Single Video". [![arXiv](https://img.shields.io/badge/arXiv-2407.13764-b31b1b.svg)](https://arxiv.org/abs/2407.13764) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/vye16/shape-of-motion)


### non-E2E 4D Reconstruction
- **MegaSaM**, "MegaSaM: Accurate, Fast, and Robust Structure and Motion from Casual Dynamic Videos". [![arXiv](https://img.shields.io/badge/arXiv-2412.04463-b31b1b.svg)](https://arxiv.org/abs/2412.04463)
- **Sparse4DGS**, "Sparse4DGS: 4D Gaussian Splatting for Sparse-Frame Dynamic Scene Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2511.07122-b31b1b.svg)](https://arxiv.org/abs/2511.07122)
- [⭐️] "Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2511.14540-b31b1b.svg)](https://arxiv.org/abs/2511.14540)
- **SplatFields**, "Neural Gaussian Splats for Sparse 3D and 4D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2409.11211-b31b1b.svg)](https://arxiv.org/abs/2409.11211) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/markomih/SplatFields)
- **L4GM**, "L4GM: Large 4D Gaussian Reconstruction Model". [![arXiv](https://img.shields.io/badge/arXiv-2406.10324-b31b1b.svg)](https://arxiv.org/abs/2406.10324) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nv-tlabs/L4GM-official)
- **Gaussian-Flow**, "Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle". [![arXiv](https://img.shields.io/badge/arXiv-2312.03431-b31b1b.svg)](https://arxiv.org/abs/2312.03431) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/NJU-3DV/Gaussian-Flow)
- [⭐️] "4D Gaussian Splatting for Real-Time Dynamic Scene Rendering". [![arXiv](https://img.shields.io/badge/arXiv-2310.08528-b31b1b.svg)](https://arxiv.org/abs/2310.08528) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/hustvl/4DGaussians)


## 4D Editing
- **Instruct 4D-to-4D**, "Instruct 4D-to-4D: Editing 4D Scenes as Pseudo-3D Scenes Using 2D Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2406.09402-b31b1b.svg)](https://arxiv.org/abs/2406.09402)
- **Instruct-4DGS**, "Instruct-4DGS: Efficient Dynamic Scene Editing via 4D Gaussian-Based Static-Dynamic Separation". [![arXiv](https://img.shields.io/badge/arXiv-2502.02091-b31b1b.svg)](https://arxiv.org/abs/2502.02091)
- **Catalyst4D**, "Catalyst4D: High-Fidelity 3D-to-4D Scene Editing via Dynamic Propagation". [![arXiv](https://img.shields.io/badge/arXiv-2603.12766-b31b1b.svg)](https://arxiv.org/abs/2603.12766)


## 4D Perception
### 4D Geometry / Motion Perception
- [⭐️] **ViPE**, "ViPE: Video Pose Engine for 3D Geometric Perception". [![arXiv](https://img.shields.io/badge/arXiv-2508.10934-b31b1b.svg)](https://arxiv.org/abs/2508.10934) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nv-tlabs/vipe)
- **PAGE-4D**, "PAGE-4D: Disentangled Pose and Geometry Estimation for VGGT-4D Perception". [![arXiv](https://img.shields.io/badge/arXiv-2510.17568-b31b1b.svg)](https://arxiv.org/abs/2510.17568)
- **Uni4D**, "Uni4D: Unifying Visual Foundation Models for 4D Modeling from a Single Video". [![arXiv](https://img.shields.io/badge/arXiv-2503.21761-b31b1b.svg)](https://arxiv.org/abs/2503.21761) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Davidyao99/uni4d)
- **Stereo4D**, "Stereo4D: Learning How Things Move in 3D from Internet Stereo Videos". [![arXiv](https://img.shields.io/badge/arXiv-2412.09621-b31b1b.svg)](https://arxiv.org/abs/2412.09621) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/mli0603/stereo4d)

### 4D Understanding / Tracking
- **ReScene4D**, "ReScene4D: Temporally Consistent Semantic Instance Segmentation of Evolving Indoor 3D Scenes". [![arXiv](https://img.shields.io/badge/arXiv-2601.11508-b31b1b.svg)](https://arxiv.org/abs/2601.11508)
- **3AM**, "3AM: Segment Anything with Geometric Consistency in Videos". [![arXiv](https://img.shields.io/badge/arXiv-2601.08831-b31b1b.svg)](https://arxiv.org/abs/2601.08831)
- **Trace Anything**, "Trace Anything: Representing Any Video in 4D via Trajectory Fields". [![arXiv](https://img.shields.io/badge/arXiv-2510.13802-b31b1b.svg)](https://arxiv.org/abs/2510.13802) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/ByteDance-Seed/TraceAnything)

## Explicit 3D-Free Methods
- **LagerNVS**, "LagerNVS: Latent Geometry for Fully Neural Real-time Novel View Synthesis". [![arXiv](https://img.shields.io/badge/arXiv-2603.20176-b31b1b.svg)](https://arxiv.org/abs/2603.20176) [![Project](https://img.shields.io/badge/Project-Page-green)](http://szymanowiczs.github.io/lagernvs)
- [⭐️] **SVSM**, "Scaling View Synthesis Transformers".  [![arXiv](https://img.shields.io/badge/arXiv-2602.21341-b31b1b.svg)](https://arxiv.org/abs/2602.21341) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/evnkim/SVSM)
- [⭐️] **XFactor**, "True Self-Supervised Novel View Synthesis is Transferable". [![arXiv](https://img.shields.io/badge/arXiv-2510.13063-b31b1b.svg)](https://arxiv.org/abs/2510.13063) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/vsitzmann/xfactor-nvs)
- [⭐️] **RayZer**, "RayZer: A Self-supervised Large View Synthesis Model". [![arXiv](https://img.shields.io/badge/arXiv-2505.00702-b31b1b.svg)](https://arxiv.org/abs/2505.00702) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/hwjiang1510/RayZer)
- [⭐️] **LVSM**, "LVSM: A Large View Synthesis Model with Minimal 3D Inductive Bias". [![arXiv](https://img.shields.io/badge/arXiv-2410.17242-b31b1b.svg)](https://arxiv.org/abs/2410.17242) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/haian-jin/LVSM)


## Related Analysis
- "On Geometric Understanding and Learned Data Priors in VGGT". [![arXiv](https://img.shields.io/badge/arXiv-2512.11508-b31b1b.svg)](https://arxiv.org/abs/2512.11508)
- "What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models". [![arXiv](https://img.shields.io/badge/arXiv-2512.03422-b31b1b.svg)](https://arxiv.org/abs/2512.03422v1)
- "How Much 3D Do Video Foundation Models Encode?". [![arXiv](https://img.shields.io/badge/arXiv-2512.19949-b31b1b.svg)](https://arxiv.org/abs/2512.19949)
- "Feat2GS: Probing Visual Foundation Models with Gaussian Splatting". [![arXiv](https://img.shields.io/badge/arXiv-2412.09606-b31b1b.svg)](https://arxiv.org/abs/2412.09606)


## Foundation Models with 3D Awareness
### Generative Models
- [⭐️] **GLD**, "Repurposing Geometric Foundation Models for Multi-view Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2603.22275-b31b1b.svg)](https://arxiv.org/abs/2603.22275) [![Project](https://img.shields.io/badge/Project-Page-green)](https://cvlab-kaist.github.io/GLD/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/cvlab-kaist/GLD/tree/main)
- **OmniView**, "OmniView: An All-Seeing Diffusion Model for 3D and 4D View Synthesis". [![arXiv](https://img.shields.io/badge/arXiv-2512.10940-b31b1b.svg)](https://arxiv.org/abs/2512.10940) [![Project](https://img.shields.io/badge/Project-Page-green)](https://snap-research.github.io/OmniView/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/omniview-video/omniview)
- [⭐️] **VerseCrafter**, "VerseCrafter: Dynamic Realistic Video World Model with 4D Geometric Control". [![arXiv](https://img.shields.io/badge/arXiv-2601.05138-b31b1b.svg)](https://arxiv.org/abs/2601.05138) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/TencentARC/VerseCrafter)
- **SeeU**, "SeeU: Seeing the Unseen World via 4D Dynamics-aware Generation". [![arXiv](https://img.shields.io/badge/arXiv-2512.03350-b31b1b.svg)](https://arxiv.org/abs/2512.03350) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/YuYuan-Yolanda/SeeU)
- "Choreographing a World of Dynamic Objects". [![arXiv](https://img.shields.io/badge/arXiv-2601.04194-b31b1b.svg)](https://arxiv.org/abs/2601.04194)
- [⭐️] "Video World Models with Long-term Spatial Memory". [![arXiv](https://img.shields.io/badge/arXiv-2506.05284-b31b1b.svg)](https://arxiv.org/abs/2506.05284)
- **Wan**, "Wan: Open and Advanced Large-Scale Video Generative Models". [![arXiv](https://img.shields.io/badge/arXiv-2503.20314-b31b1b.svg)](https://arxiv.org/abs/2503.20314v2) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Wan-Video/Wan2.1)

### World Models / Action Models
- **RoboBrain 2.5**, "RoboBrain 2.5: Depth in Sight, Time in Mind". [![arXiv](https://img.shields.io/badge/arXiv-2601.14352-b31b1b.svg)](https://arxiv.org/abs/2601.14352)
- [⭐️] **LingBot-World**, "Advancing Open-source World Models". [![arXiv](https://img.shields.io/badge/arXiv-2601.20540-b31b1b.svg)](https://arxiv.org/abs/2601.20540) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/robbyant/lingbot-world)
- **HunyuanWorld 1.0**, "HunyuanWorld 1.0: Generating Immersive, Explorable, and Interactive 3D Worlds from Words or Pixels". [![arXiv](https://img.shields.io/badge/arXiv-2507.21809-b31b1b.svg)](https://arxiv.org/abs/2507.21809) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Tencent-Hunyuan/HunyuanWorld-1.0)
- [⭐️] **NeoVerse**, "NeoVerse: Enhancing 4D World Model with in-the-wild Monocular Videos". [![arXiv](https://img.shields.io/badge/arXiv-2601.00393-b31b1b.svg)](https://arxiv.org/abs/2601.00393) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/IamCreateAI/NeoVerse)
- **DynamicVerse**, "DynamicVerse: A Physically-Aware Multimodal Framework for 4D World Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2512.03000-b31b1b.svg)](https://arxiv.org/abs/2512.03000) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Dynamics-X/DynamicVerse)
- **GeoPT**, "GeoPT: Scaling Physics Simulation via Lifted Geometric Pre-Training". [![arXiv](https://img.shields.io/badge/arXiv-2602.20399-b31b1b.svg)](https://arxiv.org/abs/2602.20399) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Physics-Scaling/GeoPT)
- [⭐️] **LingBot-VA**, "Causal World Modeling for Robot Control". [![arXiv](https://img.shields.io/badge/arXiv-2601.21998-b31b1b.svg)](https://arxiv.org/abs/2601.21998) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Robbyant/lingbot-va)
- [⭐️] **Cosmos2.5**, "World Simulation with Video Foundation Models for Physical AI". [![arXiv](https://img.shields.io/badge/arXiv-2511.00062-b31b1b.svg)](https://arxiv.org/abs/2511.00062v1) [![GitHub](https://img.shields.io/badge/GitHub-predict2.5-blue)](https://github.com/nvidia-cosmos/cosmos-predict2.5) [![GitHub](https://img.shields.io/badge/GitHub-transfer2.5-blue)](https://github.com/nvidia-cosmos/cosmos-transfer2.5) [![GitHub](https://img.shields.io/badge/GitHub-reason1-blue)](https://github.com/nvidia-cosmos/cosmos-reason1)
- [⭐️] **Cosmos**, "Cosmos World Foundation Model Platform for Physical AI". [![arXiv](https://img.shields.io/badge/arXiv-2501.03575-b31b1b.svg)](https://arxiv.org/abs/2501.03575v3) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/NVIDIA/Cosmos)

### Datasets / Benchmarks
- [⭐️] **OmniWorld**, "OmniWorld: A Multi-Domain and Multi-Modal Dataset for 4D World Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2509.12201-b31b1b.svg)](https://arxiv.org/abs/2509.12201v1) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/yangzhou24/OmniWorld)


## 3D Vision Applications
### Autonomous Driving
- **OccLLaMA**, "An Occupancy-Language-Action Generative World Model for Autonomous Driving". [![arXiv](https://img.shields.io/badge/arXiv-2409.03272-b31b1b.svg)](https://arxiv.org/abs/2409.03272) [![Project](https://img.shields.io/badge/Project-Page-green)](https://vilonge.github.io/OccLLaMA_Page/)
- **OccWorld**, "Learning a 3D Occupancy World Model for Autonomous Driving". [![arXiv](https://img.shields.io/badge/arXiv-2311.16038-b31b1b.svg)](https://arxiv.org/abs/2311.16038) [![Project](https://img.shields.io/badge/Project-Page-green)](https://wzzheng.net/OccWorld/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/wzzheng/OccWorld)
- **UniAD** (Planning-oriented Autonomous Driving), "Planning-oriented Autonomous Driving". [![arXiv](https://img.shields.io/badge/arXiv-2212.10156-b31b1b.svg)](https://arxiv.org/abs/2212.10156) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/opendrivelab/uniad)
- **UniUGP**, "Unifying Understanding, Generation, and Planning For End-to-end Autonomous Driving". [![arXiv](https://img.shields.io/badge/arXiv-2512.09864-b31b1b.svg)](https://arxiv.org/abs/2512.09864) [![Project](https://img.shields.io/badge/Project-Page-green)](https://seed-uniugp.github.io/)
- **EOT-WM**, "Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies Ego-Other Vehicle Trajectories in Video Latent Space". [![arXiv](https://img.shields.io/badge/arXiv-2503.09215-b31b1b.svg)](https://arxiv.org/abs/2503.09215)
- **DGGT**, "DGGT: Feedforward 4D Reconstruction of Dynamic Driving Scenes using Unposed Images". [![arXiv](https://img.shields.io/badge/arXiv-2512.03004-b31b1b.svg)](https://arxiv.org/abs/2512.03004) [![Project](https://img.shields.io/badge/Project-Page-green)](https://xiaomi-research.github.io/dggt/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/xiaomi-research/dggt)


## Acknowledgements
This project has largely drawn on the following projects:
-  [Awesome-World-Models](https://github.com/knightnemo/Awesome-World-Models)
-  [Awesome FeedForward 3D/4D Reconstruction](https://github.com/2hiTee/awesome-feedforward-3D-4D-Reconstruction)
-  [Awesome 3D Generation](https://github.com/2hiTee/awesome-3D-Generation)
-  [Awesome 3D/4D Editing](https://github.com/2hiTee/awesome-3D-4D-Editing)
  
Huge shoutout the the authors for their awesome work.

## Citation
If you find this repository useful, please consider citing it:

```bibtex
@misc{learningbased3dvision,
  title        = {Learning-based 3D Vision: A curated list of representative works in learning-based 3D vision},
  author       = {Dong, Jiacheng, Huan Li and Contributors},
  howpublished = {\url{https://github.com/dongjiacheng06/Learning-based-3D-Vision}},
  year         = {2026}
}
