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

- [2026.09] Added 8 curated papers through 2026-09-04 covering streaming reconstruction, geometric pre-training, world-action models, generative reconstruction, and multi-view 3D tracking benchmarks.
- [2026.08] Added 43 curated papers through 2026-08-19 and expanded the taxonomy for 3D vision-language models, spatial intelligence, and standalone datasets/benchmarks.
- [2026.05] Added recent 3D/4D reconstruction, generation, perception, and world-model papers through 2026-05-03.
- [2026.01] Repo Launch — Learning-based-3D-Vision is now live! See [CONTRIBUTING.md](./CONTRIBUTING.md) for how to contribute.
- [Ongoing] Community Contributions Welcome — Submit papers via PR or open an issue.
- ⭐ [Ongoing] If you find this useful, please consider giving a star and sharing it with your research community!

---

## Categories


<ul style="list-style: none; padding: 0;">
<li style="margin-left: 0;"><a href="#surveys">Surveys</a></li>
<li style="margin-left: 0;">
<details>
<summary><a href="#end-to-end-3d-reconstruction">End to End 3D Reconstruction</a></summary>
<ul>
<li><a href="#non-pixel-aligned">non-pixel aligned</a></li>
<li><a href="#other-e2e-3d-reconstruction">other E2E 3D Reconstruction</a></li>
</ul>
</details>
</li>
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
<li style="margin-left: 0;"><a href="#4d-generation">4D Generation</a></li>
<li style="margin-left: 0;"><a href="#3d-editing">3D Editing</a></li>
<li style="margin-left: 0;">
<details>
<summary><a href="#3d-perception">3D Perception</a></summary>
<ul>
<li><a href="#depth--geometry-perception">Depth / Geometry Perception</a></li>
<li><a href="#3d-understanding">3D Understanding</a></li>
</ul>
</details>
</li>
<li style="margin-left: 0;">
<details>
<summary><a href="#3d-vision-language--spatial-intelligence">3D Vision-Language / Spatial Intelligence</a></summary>
<ul>
<li><a href="#3d-aware-vision-language-models">3D-Aware Vision-Language Models</a></li>
<li><a href="#spatial-reasoning--memory">Spatial Reasoning / Memory</a></li>
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
</ul>
</details>
</li>
<li style="margin-left: 0;"><a href="#datasets--benchmarks">Datasets / Benchmarks</a></li>
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
> **Last Updated:** 2026-09-04

# 3D Vision Methods
## Surveys
- "Advances in Neural 3D Mesh Texturing: A Survey". [![arXiv](https://img.shields.io/badge/arXiv-2606.00137-b31b1b.svg)](https://arxiv.org/abs/2606.00137) [![Project](https://img.shields.io/badge/Project-Page-green)](https://sairajk.github.io/neural-mesh-texturing/)
- "3D Generation for Embodied AI and Robotic Simulation: A Survey". [![arXiv](https://img.shields.io/badge/arXiv-2604.26509-b31b1b.svg)](https://arxiv.org/abs/2604.26509) [![Project](https://img.shields.io/badge/Project-Page-green)](https://3dgen4robot.github.io)
- "Advances in Global Solvers for 3D Vision". [![arXiv](https://img.shields.io/badge/arXiv-2602.14662-b31b1b.svg)](https://arxiv.org/abs/2602.14662) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/ericzzj1989/Awesome-Global-Solvers-for-3D-Vision)
- "Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey". [![arXiv](https://img.shields.io/badge/arXiv-2507.14501-b31b1b.svg)](https://arxiv.org/abs/2507.14501)
- "3D Scene Generation: A Survey". [![arXiv](https://img.shields.io/badge/arXiv-2505.05474-b31b1b.svg)](https://arxiv.org/abs/2505.05474v1)
- "Recent Advances in 3D Object and Scene Generation: A Survey". [![arXiv](https://img.shields.io/badge/arXiv-2504.11734-b31b1b.svg)](https://arxiv.org/abs/2504.11734)
- "Learning-based 3D Reconstruction in Autonomous Driving: A Comprehensive Survey". [![arXiv](https://img.shields.io/badge/arXiv-2503.14537-b31b1b.svg)](https://arxiv.org/abs/2503.14537)
- "A Review of 3D Reconstruction Techniques for Deformable Tissues in Robotic Surgery". [![arXiv](https://img.shields.io/badge/arXiv-2408.04426-b31b1b.svg)](https://arxiv.org/abs/2408.04426)


## End to End 3D Reconstruction
### non-pixel aligned
- **GlobalSplat**, "GlobalSplat: Efficient Feed-Forward 3D Gaussian Splatting via Global Scene Tokens". [![arXiv](https://img.shields.io/badge/arXiv-2604.15284-b31b1b.svg)](https://arxiv.org/abs/2604.15284) [![Project](https://img.shields.io/badge/Project-Page-green)](https://r-itk.github.io/globalsplat/)
- [⭐️] **NOVA3R**, "NOVA3R: Non-pixel-aligned Visual Transformer for Amodal 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2603.04179-b31b1b.svg)](https://arxiv.org/abs/2603.04179) [![Project](https://img.shields.io/badge/Project-Page-green)](https://wrchen530.github.io/nova3r/)

### other E2E 3D Reconstruction
- **Gekko**, "Revisiting Cross-View Completion: Self-Supervised Pre-Training via Reconstruction Error Comparison". [![arXiv](https://img.shields.io/badge/arXiv-2609.01530-b31b1b.svg)](https://arxiv.org/abs/2609.01530) [![Project](https://img.shields.io/badge/Project-Page-green)](https://thibautloiseau.github.io/projects/gekko/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/thibautloiseau/gekko)
- **ReconSplat**, "ReconSplat: Generalizable 3D Scene Reconstruction Beyond Observed Views". [![arXiv](https://img.shields.io/badge/arXiv-2608.28895-b31b1b.svg)](https://arxiv.org/abs/2608.28895) [![Project](https://img.shields.io/badge/Project-Page-green)](https://visinf.github.io/reconsplat/)
- **Argus**, "Argus: Metric Panoramic 3D Reconstruction for Indoor Scenes". [![arXiv](https://img.shields.io/badge/arXiv-2606.30047-b31b1b.svg)](https://arxiv.org/abs/2606.30047) [![Project](https://img.shields.io/badge/Project-Page-green)](https://argus-paper.realsee.ai/)
- [⭐️] **Déjà View**, "Déjà View: Looping Transformers for Multi-View 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2605.30215-b31b1b.svg)](https://arxiv.org/abs/2605.30215) [![Project](https://img.shields.io/badge/Project-Page-green)](https://research.nvidia.com/labs/dvl/projects/dvlt)
- **R³**, "R³: 3D Reconstruction via Relative Regression". [![arXiv](https://img.shields.io/badge/arXiv-2605.26519-b31b1b.svg)](https://arxiv.org/abs/2605.26519) [![Project](https://img.shields.io/badge/Project-Page-green)](https://kevinxu02.github.io/r3-site)
- **GenWildSplat**, "Generalizable Sparse-View 3D Reconstruction from Unconstrained Images". [![arXiv](https://img.shields.io/badge/arXiv-2604.28193-b31b1b.svg)](https://arxiv.org/abs/2604.28193) [![Project](https://img.shields.io/badge/Project-Page-green)](https://genwildsplat.github.io/)
- **RecGen**, "Reconstruction by Generation: 3D Multi-Object Scene Reconstruction from Sparse Observations". [![arXiv](https://img.shields.io/badge/arXiv-2604.27106-b31b1b.svg)](https://arxiv.org/abs/2604.27106) [![Project](https://img.shields.io/badge/Project-Page-green)](https://reconstruction-by-generation.github.io)
- **WildSplatter**, "WildSplatter: Feed-forward 3D Gaussian Splatting with Appearance Control from Unconstrained Images". [![arXiv](https://img.shields.io/badge/arXiv-2604.21182-b31b1b.svg)](https://arxiv.org/abs/2604.21182) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/yfujimura/WildSplatter)
- **AnyRecon**, "AnyRecon: Arbitrary-View 3D Reconstruction with Video Diffusion Model". [![arXiv](https://img.shields.io/badge/arXiv-2604.19747-b31b1b.svg)](https://arxiv.org/abs/2604.19747) [![Project](https://img.shields.io/badge/Project-Page-green)](https://yutian10.github.io/AnyRecon/)
- **VGG-T^3**, "VGG-T^3: Offline Feed-Forward 3D Reconstruction at Scale". [![arXiv](https://img.shields.io/badge/arXiv-2602.23361-b31b1b.svg)](https://arxiv.org/abs/2602.23361) [![Project](https://img.shields.io/badge/Project-Page-green)](https://research.nvidia.com/labs/dvl/projects/vgg-ttt/)
- [⭐️] **tttLRM**, "tttLRM: Test-Time Training for Long Context and Autoregressive 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2602.20160-b31b1b.svg)](https://arxiv.org/abs/2602.20160) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/cwchenwang/tttLRM)
- [⭐️] **E-RayZer**, "E-RayZer: Self-supervised 3D Reconstruction as Spatial Visual Pre-training". [![arXiv](https://img.shields.io/badge/arXiv-2512.10950-b31b1b.svg)](https://arxiv.org/abs/2512.10950) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/hwjiang1510/E-RayZer)
- [⭐️] **DA3**, "Depth Anything 3: Recovering the Visual Space from Any Views". [![arXiv](https://img.shields.io/badge/arXiv-2511.10647-b31b1b.svg)](https://arxiv.org/abs/2511.10647) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/ByteDance-Seed/Depth-Anything-3)
- **OmniVGGT**, "OmniVGGT: Omni-Modality Driven Visual Geometry Grounded Transformer". [![arXiv](https://img.shields.io/badge/arXiv-2511.10560-b31b1b.svg)](https://arxiv.org/abs/2511.10560v1) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Livioni/OmniVGGT-official)
- **MapAnything**, "MapAnything: Universal Feed-Forward Metric 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2509.13414-b31b1b.svg)](https://arxiv.org/abs/2509.13414v2) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/facebookresearch/map-anything)
- **VGGT-Long**, "VGGT-Long: Chunk It, Loop It, Align It — Pushing VGGT's Limits on Kilometer-Scale Long RGB Sequences". [![arXiv](https://img.shields.io/badge/arXiv-2507.16443-b31b1b.svg)](https://arxiv.org/abs/2507.16443)
- **Dens3R**, "Dens3R: A Foundation Model for 3D Geometry Prediction". [![arXiv](https://img.shields.io/badge/arXiv-2507.16290-b31b1b.svg)](https://arxiv.org/abs/2507.16290)
- [⭐️] **π^3**, "π^3: Permutation-Equivariant Visual Geometry Learning". [![arXiv](https://img.shields.io/badge/arXiv-2507.13347-b31b1b.svg)](https://arxiv.org/abs/2507.13347v2) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/yyfz/Pi3)
- **Test3R**, "Test3R: Learning to Reconstruct 3D at Test Time". [![arXiv](https://img.shields.io/badge/arXiv-2506.13750-b31b1b.svg)](https://arxiv.org/abs/2506.13750)
- **Mono3R**, "Mono3R: Exploiting Monocular Cues for Geometric 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2504.13419-b31b1b.svg)](https://arxiv.org/abs/2504.13419)
- **Pow3R**, "Pow3R: Empowering Unconstrained 3D Reconstruction with Camera and Scene Priors". [![arXiv](https://img.shields.io/badge/arXiv-2503.17316-b31b1b.svg)](https://arxiv.org/abs/2503.17316)
- [⭐️] **VGGT**, "VGGT: Visual Geometry Grounded Transformer". [![arXiv](https://img.shields.io/badge/arXiv-2503.11651-b31b1b.svg)](https://arxiv.org/abs/2503.11651) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/facebookresearch/vggt)
- **FLARE**, "FLARE: Feed-Forward Geometry, Appearance and Camera Estimation from Uncalibrated Sparse Views". [![arXiv](https://img.shields.io/badge/arXiv-2502.12138-b31b1b.svg)](https://arxiv.org/abs/2502.12138)
- **Fast3R**, "Fast3R: Towards 3D Reconstruction of 1000+ Images in One Forward Pass". [![arXiv](https://img.shields.io/badge/arXiv-2501.13928-b31b1b.svg)](https://arxiv.org/abs/2501.13928)
- **MV-DUSt3R+**, "MV-DUSt3R+: Single-Stage Scene Reconstruction from Sparse Views In 2 Seconds". [![arXiv](https://img.shields.io/badge/arXiv-2412.06974-b31b1b.svg)](https://arxiv.org/abs/2412.06974)
- [⭐️] **NopoSplat**, "No Pose, No Problem: Surprisingly Simple 3D Gaussian Splats from Sparse Unposed Images". [![arXiv](https://img.shields.io/badge/arXiv-2410.24207-b31b1b.svg)](https://arxiv.org/abs/2410.24207) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/cvg/NoPoSplat)
- **MASt3R**, "Grounding Image Matching in 3D with MASt3R". [![arXiv](https://img.shields.io/badge/arXiv-2406.09756-b31b1b.svg)](https://arxiv.org/abs/2406.09756) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/naver/mast3r)
- [⭐️] **MVSplat**, "MVSplat: Efficient 3D Gaussian Splatting from Sparse Multi-View Images". [![arXiv](https://img.shields.io/badge/arXiv-2403.14627-b31b1b.svg)](https://arxiv.org/abs/2403.14627) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/donydchen/mvsplat)
- [⭐️] **DUSt3R**, "DUSt3R: Geometric 3D Vision Made Easy". [![arXiv](https://img.shields.io/badge/arXiv-2312.14132-b31b1b.svg)](https://arxiv.org/abs/2312.14132) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/naver/dust3r)
- **VGGSfM**, "VGGSfM: Visual Geometry Grounded Deep Structure From Motion". [![arXiv](https://img.shields.io/badge/arXiv-2312.04563-b31b1b.svg)](https://arxiv.org/abs/2312.04563)
- [⭐️] **CroCo**, "CroCo: Self-Supervised Pre-training for 3D Vision Tasks by Cross-View Completion". [![arXiv](https://img.shields.io/badge/arXiv-2210.10716-b31b1b.svg)](https://arxiv.org/abs/2210.10716) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/naver/croco)


## Online 3R/SLAM
### Online 3R
- **Scal3R**, "Scal3R: Learning Efficient Multi-Relative Pose Query for Scalable Online 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2609.04201-b31b1b.svg)](https://arxiv.org/abs/2609.04201) [![Project](https://img.shields.io/badge/Project-Page-green)](https://linjohnss.github.io/scal3r/)
- [⭐️] **ABot-Recon**, "Revisiting Local Context for Long-Horizon Streaming 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2608.27529-b31b1b.svg)](https://arxiv.org/abs/2608.27529) [![Project](https://img.shields.io/badge/Project-Page-green)](https://amap-cvlab.github.io/ABot-Recon-html/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/amap-cvlab/ABot-Recon)
- [⭐️] **Anchor3R**, "Anchor3R: Streaming 3D Reconstruction with Transient Anchors for Long-Horizon Visual Mapping". [![arXiv](https://img.shields.io/badge/arXiv-2606.05035-b31b1b.svg)](https://arxiv.org/abs/2606.05035)
- [⭐️] **HorizonStream**, "HorizonStream: Long-Horizon Attention for Streaming 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2605.23889-b31b1b.svg)](https://arxiv.org/abs/2605.23889) [![Project](https://img.shields.io/badge/Project-Page-green)](https://3dagentworld.github.io/horizonstream/)
- **RetrieveVGGT**, "Attention Itself Could Retrieve. RetrieveVGGT: Training-Free Long Context Streaming 3D Reconstruction via Query-Key Similarity Retrieval". [![arXiv](https://img.shields.io/badge/arXiv-2605.09644-b31b1b.svg)](https://arxiv.org/abs/2605.09644) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/zzctmd/RetrieveVGGT)
- **StreamCacheVGGT**, "StreamCacheVGGT: Streaming visual geometry transformers with robust scoring and hybrid cache compression". [![arXiv](https://img.shields.io/badge/arXiv-2604.15237-b31b1b.svg)](https://arxiv.org/abs/2604.15237)
- [⭐️] **LingBot-Map**, "Geometric Context Transformer for Streaming 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2604.14141-b31b1b.svg)](https://arxiv.org/abs/2604.14141) [![Project](https://img.shields.io/badge/Project-Page-green)](https://technology.robbyant.com/lingbot-map) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/robbyant/lingbot-map)
- **Online3R**, "Online3R: Online Learning for Consistent Sequential Reconstruction Based on Geometry Foundation Model". [![arXiv](https://img.shields.io/badge/arXiv-2604.09480-b31b1b.svg)](https://arxiv.org/abs/2604.09480)
- [⭐️] **MeMix**, "MeMix: Writing Less, Remembering More for Streaming 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2603.15330-b31b1b.svg)](https://arxiv.org/abs/2603.15330) [![Project](https://img.shields.io/badge/Project-Page-green)](https://dongjiacheng06.github.io/MeMix/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/dongjiacheng06/MeMix)
- [⭐️] **ZipMap**, "ZipMap: Linear-Time Stateful 3D Reconstruction via Test-Time Training". [![arXiv](https://img.shields.io/badge/arXiv-2603.04385-b31b1b.svg)](https://arxiv.org/abs/2603.04385) [![Project](https://img.shields.io/badge/Project-Page-green)](https://haian-jin.github.io/ZipMap/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Haian-Jin/ZipMap)
- **LoGeR**, "LoGeR: Long-Context Geometric Reconstruction with Hybrid Memory". [![arXiv](https://img.shields.io/badge/arXiv-2603.03269-b31b1b.svg)](https://arxiv.org/abs/2603.03269)
- **LongStream**, "LongStream: Long-Sequence Streaming Autoregressive Visual Geometry". [![arXiv](https://img.shields.io/badge/arXiv-2602.13172-b31b1b.svg)](https://arxiv.org/abs/2602.13172) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/3DAgentWorld/LongStream/tree/main)
- **TTSA3R**, "TTSA3R: Training-Free Temporal-Spatial Adaptive Persistent State for Streaming 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2601.22615-b31b1b.svg)](https://arxiv.org/abs/2601.22615) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/anonus2357/ttsa3r)
- **InfiniteVGGT**, "InfiniteVGGT: Visual Geometry Grounded Transformer for Endless Streams". [![arXiv](https://img.shields.io/badge/arXiv-2601.02281-b31b1b.svg)](https://arxiv.org/abs/2601.02281v1) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/AutoLab-SAI-SJTU/InfiniteVGGT)
- **XStreamVGGT**, "XStreamVGGT: Extremely Memory-Efficient Streaming Vision Geometry Grounded Transformer with KV Cache Compression". [![arXiv](https://img.shields.io/badge/arXiv-2601.01204-b31b1b.svg)](https://arxiv.org/abs/2601.01204v1)
- **MUT3R**, "MUT3R: Motion-aware Updating Transformer for Dynamic 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2512.03939-b31b1b.svg)](https://arxiv.org/abs/2512.03939)
- [⭐️] **4D-VGGT**, "4D-VGGT: A General Foundation Model with SpatioTemporal Awareness for Dynamic Scene Geometry Estimation". [![arXiv](https://img.shields.io/badge/arXiv-2511.18416-b31b1b.svg)](https://arxiv.org/abs/2511.18416)
- [⭐️] **TTT3R**, "TTT3R: 3D RECONSTRUCTION AS TEST-TIME TRAINING". [![arXiv](https://img.shields.io/badge/arXiv-2509.26645-b31b1b.svg)](https://arxiv.org/abs/2509.26645v3) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Inception3D/TTT3R)
- **G-CUT3R**, "G-CUT3R: Guided 3D Reconstruction with Camera and Depth Prior Integration". [![arXiv](https://img.shields.io/badge/arXiv-2508.11379-b31b1b.svg)](https://arxiv.org/abs/2508.11379v2)
- [⭐️] **StreamVGGT**, "Streaming 4D Visual Geometry Transformer". [![arXiv](https://img.shields.io/badge/arXiv-2507.11539-b31b1b.svg)](https://arxiv.org/abs/2507.11539) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/wzzheng/StreamVGGT)
- [⭐️] **Point3R**, "Point3R: Streaming 3D Reconstruction with Explicit Spatial Pointer Memory". [![arXiv](https://img.shields.io/badge/arXiv-2507.02863-b31b1b.svg)](https://arxiv.org/abs/2507.02863) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/YkiWu/Point3R)
- [⭐️] **CUT3R**, "Continuous 3D Perception Model with Persistent State". [![arXiv](https://img.shields.io/badge/arXiv-2501.12387-b31b1b.svg)](https://arxiv.org/abs/2501.12387) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/CUT3R/CUT3R)
- [⭐️] **Spann3R**, "3D Reconstruction with Spatial Memory". [![arXiv](https://img.shields.io/badge/arXiv-2408.16061-b31b1b.svg)](https://arxiv.org/abs/2408.16061) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/HengyiWang/spann3r)


### SLAM
- **UniSim-SLAM**, "UniSim-SLAM: Feed-Forward SLAM with Unified Sim(3) Optimization". [![arXiv](https://img.shields.io/badge/arXiv-2608.01706-b31b1b.svg)](https://arxiv.org/abs/2608.01706) [![Project](https://img.shields.io/badge/Project-Page-green)](https://vision3d-lab.github.io/unisim-slam/)
- **RADIO-ViPE**, "RADIO-ViPE: Online Tightly Coupled Multi-Modal Fusion for Open-Vocabulary Semantic SLAM in Dynamic Environments". [![arXiv](https://img.shields.io/badge/arXiv-2604.26067-b31b1b.svg)](https://arxiv.org/abs/2604.26067)
- **Flow4DGS-SLAM**, "Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM". [![arXiv](https://img.shields.io/badge/arXiv-2604.22339-b31b1b.svg)](https://arxiv.org/abs/2604.22339)
- **GRS-SLAM3R**, "GRS-SLAM3R: Real-Time Dense SLAM with Gated Recurrent State". [![arXiv](https://img.shields.io/badge/arXiv-2509.23737-b31b1b.svg)](https://arxiv.org/abs/2509.23737v1)
- **SLAM-Former**, "SLAM-Former: Putting SLAM into One Transformer". [![arXiv](https://img.shields.io/badge/arXiv-2509.16909-b31b1b.svg)](https://arxiv.org/abs/2509.16909v1)
- **VGGT-SLAM**, "VGGT-SLAM: Dense RGB SLAM Optimized on the SL(4) Manifold". [![arXiv](https://img.shields.io/badge/arXiv-2505.12549-b31b1b.svg)](https://arxiv.org/abs/2505.12549) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/MIT-SPARK/VGGT-SLAM)
- **MASt3R-SLAM**, "MASt3R-SLAM: Real-Time Dense SLAM with 3D Reconstruction Priors". [![arXiv](https://img.shields.io/badge/arXiv-2412.12392-b31b1b.svg)](https://arxiv.org/abs/2412.12392v2) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/rmurai0610/MASt3R-SLAM)
- **SLAM3R**, "SLAM3R: Real-Time Dense Scene Reconstruction from Monocular RGB Videos". [![arXiv](https://img.shields.io/badge/arXiv-2412.09401-b31b1b.svg)](https://arxiv.org/abs/2412.09401) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/PKU-VCL-3DV/SLAM3R)

## 3D Generation
- [⭐️] **Hunyuan3D-Buffalo 1.0**, "Hunyuan3D-Buffalo 1.0: A Unified Multimodal Model for Scalable 3D Generation, Understanding, and Editing". [![arXiv](https://img.shields.io/badge/arXiv-2608.02711-b31b1b.svg)](https://arxiv.org/abs/2608.02711) [![Project](https://img.shields.io/badge/Project-Page-green)](https://tencent-hunyuan.github.io/Hunyuan3D-Buffalo1.0)
- **AssetGen**, "AssetGen: Deployable 3D Asset Generation at Interactive Speed". [![arXiv](https://img.shields.io/badge/arXiv-2605.26137-b31b1b.svg)](https://arxiv.org/abs/2605.26137)
- [⭐️] **PhysX-Omni**, "PhysX-Omni: Unified Simulation-Ready Physical 3D Generation for Rigid, Deformable, and Articulated Objects". [![arXiv](https://img.shields.io/badge/arXiv-2605.21572-b31b1b.svg)](https://arxiv.org/abs/2605.21572) [![Project](https://img.shields.io/badge/Project-Page-green)](https://physx-omni.github.io/)
- **Pixal3D**, "Pixal3D: Pixel-Aligned 3D Generation from Images". [![arXiv](https://img.shields.io/badge/arXiv-2605.10922-b31b1b.svg)](https://arxiv.org/abs/2605.10922) [![Project](https://img.shields.io/badge/Project-Page-green)](https://ldyang694.github.io/projects/pixal3d/)
- [⭐️] **PhysForge**, "PhysForge: Generating Physics-Grounded 3D Assets for Interactive Virtual World". [![arXiv](https://img.shields.io/badge/arXiv-2605.05163-b31b1b.svg)](https://arxiv.org/abs/2605.05163) [![Project](https://img.shields.io/badge/Project-Page-green)](https://hku-mmlab.github.io/PhysForge/)
- **CasLayout**, "CasLayout: Cascaded 3D Layout Diffusion for Indoor Scene Synthesis with Implicit Relation Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2604.27361-b31b1b.svg)](https://arxiv.org/abs/2604.27361) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/YingruiWoo/CasLayout)
- **CoMoVi**, "CoMoVi: Co-Generation of 3D Human Motions and Realistic Videos". [![arXiv](https://img.shields.io/badge/arXiv-2601.10632-b31b1b.svg)](https://arxiv.org/abs/2601.10632)
- [⭐️] **TRELLIS.2**, "Native and Compact Structured Latents for 3D Generation". [![arXiv](https://img.shields.io/badge/arXiv-2512.14692-b31b1b.svg)](https://arxiv.org/abs/2512.14692) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/microsoft/TRELLIS.2)
- **GeoWorld**, "GeoWorld: Unlocking the Potential of Geometry Models to Facilitate High-Fidelity 3D Scene Generation". [![arXiv](https://img.shields.io/badge/arXiv-2511.23191-b31b1b.svg)](https://arxiv.org/abs/2511.23191)
- **CUPID**, "CUPID: Generative 3D Reconstruction via Joint Object and Pose Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2510.20776-b31b1b.svg)](https://arxiv.org/abs/2510.20776) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/cupid3d/Cupid)
- [⭐️] **SAM 3D**, "SAM 3D: 3Dfy Anything in Images". [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://ai.meta.com/research/publications/sam-3d-3dfy-anything-in-images/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/facebookresearch/sam-3d-objects)
- [⭐️] **LYRA**, "LYRA: Generative 3D Scene Reconstruction via Video Diffusion Model Self-Distillation". [![arXiv](https://img.shields.io/badge/arXiv-2509.19296-b31b1b.svg)](https://arxiv.org/abs/2509.19296v1) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nv-tlabs/lyra)
- [⭐️] **Hunyuan3D 2.5**, "Hunyuan3D 2.5: Towards High-Fidelity 3D Assets Generation with Ultimate Details". [![arXiv](https://img.shields.io/badge/arXiv-2506.16504-b31b1b.svg)](https://arxiv.org/abs/2506.16504) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Tencent-Hunyuan/Hunyuan3D-2)
- **Hunyuan3D 2.1**, "Hunyuan3D 2.1: From Images to High-Fidelity 3D Assets with Production-Ready PBR Material". [![arXiv](https://img.shields.io/badge/arXiv-2506.15442-b31b1b.svg)](https://arxiv.org/abs/2506.15442)
- [⭐️] **TRELLIS**, "Structured 3D Latents for Scalable and Versatile 3D Generation". [![arXiv](https://img.shields.io/badge/arXiv-2412.01506-b31b1b.svg)](https://arxiv.org/abs/2412.01506) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/microsoft/TRELLIS)
- **Edify 3D**, "Edify 3D: Scalable High-Quality 3D Asset Generation". [![arXiv](https://img.shields.io/badge/arXiv-2411.07135-b31b1b.svg)](https://arxiv.org/abs/2411.07135)
- **Hunyuan3D 1.0**, "Hunyuan3D 1.0: A Unified Framework for Text-to-3D and Image-to-3D Generation". [![arXiv](https://img.shields.io/badge/arXiv-2411.02293-b31b1b.svg)](https://arxiv.org/abs/2411.02293) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Tencent/Hunyuan3D-1)
- **CAT3D**, "CAT3D: Create Anything in 3D with Multi-View Diffusion Models". [![arXiv](https://img.shields.io/badge/arXiv-2405.10314-b31b1b.svg)](https://arxiv.org/abs/2405.10314)
- **InstantMesh**, "InstantMesh: Efficient 3D Mesh Generation from a Single Image with Sparse-View Large Reconstruction Models". [![arXiv](https://img.shields.io/badge/arXiv-2404.07191-b31b1b.svg)](https://arxiv.org/abs/2404.07191)
- **GRM**, "GRM: Large Gaussian Reconstruction Model for Efficient 3D Reconstruction and Generation". [![arXiv](https://img.shields.io/badge/arXiv-2403.14621-b31b1b.svg)](https://arxiv.org/abs/2403.14621)
- **TripoSR**, "TripoSR: Fast 3D Object Reconstruction from a Single Image". [![arXiv](https://img.shields.io/badge/arXiv-2403.02151-b31b1b.svg)](https://arxiv.org/abs/2403.02151)
- [⭐️] **LGM**, "LGM: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation". [![arXiv](https://img.shields.io/badge/arXiv-2402.05054-b31b1b.svg)](https://arxiv.org/abs/2402.05054) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/3DTopia/LGM)
- **PF-LRM**, "PF-LRM: Pose-Free Large Reconstruction Model for Joint Pose and Shape Prediction". [![arXiv](https://img.shields.io/badge/arXiv-2311.12024-b31b1b.svg)](https://arxiv.org/abs/2311.12024)
- **Instant3D**, "Instant3D: Fast Text-to-3D with Sparse-View Generation and Large Reconstruction Model". [![arXiv](https://img.shields.io/badge/arXiv-2311.06214-b31b1b.svg)](https://arxiv.org/abs/2311.06214)
- [⭐️] **LRM**, "LRM: Large Reconstruction Model for Single Image to 3D". [![arXiv](https://img.shields.io/badge/arXiv-2311.04400-b31b1b.svg)](https://arxiv.org/abs/2311.04400) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/3DTopia/OpenLRM)
- [⭐️] **Zero123++**, "Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model". [![arXiv](https://img.shields.io/badge/arXiv-2310.15110-b31b1b.svg)](https://arxiv.org/abs/2310.15110) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/SUDO-AI-3D/zero123plus)
- **Wonder3D**, "Wonder3D: Single Image to 3D Using Cross-Domain Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2310.15008-b31b1b.svg)](https://arxiv.org/abs/2310.15008)
- **DreamGaussian**, "DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation". [![arXiv](https://img.shields.io/badge/arXiv-2309.16653-b31b1b.svg)](https://arxiv.org/abs/2309.16653)
- **SyncDreamer**, "SyncDreamer: Generating Multiview-Consistent Images from a Single-View Image". [![arXiv](https://img.shields.io/badge/arXiv-2309.03453-b31b1b.svg)](https://arxiv.org/abs/2309.03453)
- **MVDream**, "MVDream: Multi-View Diffusion for 3D Generation". [![arXiv](https://img.shields.io/badge/arXiv-2308.16512-b31b1b.svg)](https://arxiv.org/abs/2308.16512)
- **MVDiffusion**, "MVDiffusion: Enabling Holistic Multi-View Image Generation with Correspondence-Aware Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2307.01097-b31b1b.svg)](https://arxiv.org/abs/2307.01097)
- **Michelangelo**, "Michelangelo: Conditional 3D Shape Generation based on Shape-Image-Text Aligned Latent Representation". [![arXiv](https://img.shields.io/badge/arXiv-2306.17115-b31b1b.svg)](https://arxiv.org/abs/2306.17115) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/NeuralCarver/Michelangelo)
- **Shap-E**, "Shap-E: Generating Conditional 3D Implicit Functions". [![arXiv](https://img.shields.io/badge/arXiv-2305.02463-b31b1b.svg)](https://arxiv.org/abs/2305.02463)
- **Zero-1-to-3**, "Zero-1-to-3: Zero-Shot One Image to 3D Object". [![arXiv](https://img.shields.io/badge/arXiv-2303.11328-b31b1b.svg)](https://arxiv.org/abs/2303.11328)
- **Point-E**, "Point-E: A System for Generating 3D Point Clouds from Complex Prompts". [![arXiv](https://img.shields.io/badge/arXiv-2212.08751-b31b1b.svg)](https://arxiv.org/abs/2212.08751)
- **Magic3D**, "Magic3D: High-Resolution Text-to-3D Content Creation". [![arXiv](https://img.shields.io/badge/arXiv-2211.10440-b31b1b.svg)](https://arxiv.org/abs/2211.10440)
- **DreamFusion**, "DreamFusion: Text-to-3D Using 2D Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2209.14988-b31b1b.svg)](https://arxiv.org/abs/2209.14988)


## 4D Generation
- **MORPHOS**, "MORPHOS: Autoregressive 4D Generation with Temporal Structured Latents". [![arXiv](https://img.shields.io/badge/arXiv-2606.02491-b31b1b.svg)](https://arxiv.org/abs/2606.02491) [![Project](https://img.shields.io/badge/Project-Page-green)](https://cvlab-kaist.github.io/MORPHOS/)
- **AnimateAnyMesh++**, "AnimateAnyMesh++: A Flexible 4D Foundation Model for High-Fidelity Text-Driven Mesh Animation". [![arXiv](https://img.shields.io/badge/arXiv-2604.26917-b31b1b.svg)](https://arxiv.org/abs/2604.26917) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/JarrentWu1031/AnimateAnyMesh-pp)
- **Sculpt4D**, "Sculpt4D: Generating 4D Shapes via Sparse-Attention Diffusion Transformers". [![arXiv](https://img.shields.io/badge/arXiv-2604.21592-b31b1b.svg)](https://arxiv.org/abs/2604.21592)
- **One4D**, "One4D: Unified 4D Generation and Reconstruction via Decoupled LoRA Control". [![arXiv](https://img.shields.io/badge/arXiv-2511.18922-b31b1b.svg)](https://arxiv.org/abs/2511.18922)
- **CAT4D**, "CAT4D: Create Anything in 4D with Multi-View Video Diffusion Models". [![arXiv](https://img.shields.io/badge/arXiv-2411.18613-b31b1b.svg)](https://arxiv.org/abs/2411.18613)
- **SV4D**, "SV4D: Dynamic 3D Content Generation with Multi-Frame and Multi-View Consistency". [![arXiv](https://img.shields.io/badge/arXiv-2407.17470-b31b1b.svg)](https://arxiv.org/abs/2407.17470)
- **Diffusion4D**, "Diffusion4D: Fast Spatial-Temporal Consistent 4D Generation via Video Diffusion Models". [![arXiv](https://img.shields.io/badge/arXiv-2405.16645-b31b1b.svg)](https://arxiv.org/abs/2405.16645)
- **SC4D**, "SC4D: Sparse-Controlled Video-to-4D Generation and Motion Transfer". [![arXiv](https://img.shields.io/badge/arXiv-2404.03736-b31b1b.svg)](https://arxiv.org/abs/2404.03736)
- **STAG4D**, "STAG4D: Spatial-Temporal Anchored Generative 4D Gaussians". [![arXiv](https://img.shields.io/badge/arXiv-2403.14939-b31b1b.svg)](https://arxiv.org/abs/2403.14939)
- **4DGen**, "4DGen: Grounded 4D Content Generation with Spatial-Temporal Consistency". [![arXiv](https://img.shields.io/badge/arXiv-2312.17225-b31b1b.svg)](https://arxiv.org/abs/2312.17225)
- **DreamGaussian4D**, "DreamGaussian4D: Generative 4D Gaussian Splatting". [![arXiv](https://img.shields.io/badge/arXiv-2312.17142-b31b1b.svg)](https://arxiv.org/abs/2312.17142)
- **4D-fy**, "4D-fy: Text-to-4D Generation Using Hybrid Score Distillation Sampling". [![arXiv](https://img.shields.io/badge/arXiv-2311.17984-b31b1b.svg)](https://arxiv.org/abs/2311.17984)
- **Animate124**, "Animate124: Animating One Image to 4D Dynamic Scene". [![arXiv](https://img.shields.io/badge/arXiv-2311.14603-b31b1b.svg)](https://arxiv.org/abs/2311.14603)
- **Consistent4D**, "Consistent4D: Consistent 360° Dynamic Object Generation from Monocular Video". [![arXiv](https://img.shields.io/badge/arXiv-2311.02848-b31b1b.svg)](https://arxiv.org/abs/2311.02848)
- **Text-to-4D Dynamic Scene Generation**, "Text-to-4D Dynamic Scene Generation". [![arXiv](https://img.shields.io/badge/arXiv-2301.11280-b31b1b.svg)](https://arxiv.org/abs/2301.11280)


## 3D Editing
- **TanGO**, "TanGO: Training-Free 3D Editing via Tangent-Space Guidance and Optimization". [![arXiv](https://img.shields.io/badge/arXiv-2607.14927-b31b1b.svg)](https://arxiv.org/abs/2607.14927)
- **Pxform**, "Feedforward 3D Editing Learns from Semantic-Part Transformation". [![arXiv](https://img.shields.io/badge/arXiv-2605.27351-b31b1b.svg)](https://arxiv.org/abs/2605.27351) [![Project](https://img.shields.io/badge/Project-Page-green)](https://dennis-jwweng.github.io/pxform/)
- **FluSplat**, "FluSplat: Sparse-View 3D Editing without Test-Time Optimization". [![arXiv](https://img.shields.io/badge/arXiv-2604.20038-b31b1b.svg)](https://arxiv.org/abs/2604.20038)
- **TransSplat**, "TransSplat: Unbalanced Semantic Transport for Language-Driven 3DGS Editing". [![arXiv](https://img.shields.io/badge/arXiv-2604.19571-b31b1b.svg)](https://arxiv.org/abs/2604.19571)
- **VecSet-Edit**, "VecSet-Edit: Unleashing Pre-Trained LRM for Mesh Editing from Single Image". [![arXiv](https://img.shields.io/badge/arXiv-2602.04349-b31b1b.svg)](https://arxiv.org/abs/2602.04349)
- **CoreEditor**, "CoreEditor: Consistent 3D Editing via Correspondence-Constrained Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2508.11603-b31b1b.svg)](https://arxiv.org/abs/2508.11603)
- **DreamCatalyst**, "DreamCatalyst: Fast and High-Quality 3D Editing via Controlling Editability and Identity". [![arXiv](https://img.shields.io/badge/arXiv-2407.11394-b31b1b.svg)](https://arxiv.org/abs/2407.11394)
- **GaussCtrl**, "GaussCtrl: Multi-View Consistent Text-Driven 3D Gaussian Splatting Editing". [![arXiv](https://img.shields.io/badge/arXiv-2403.08733-b31b1b.svg)](https://arxiv.org/abs/2403.08733)
- **Instruct-GS2GS**, "Instruct-GS2GS: Editing 3D Gaussian Splats with Instructions". [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://instruct-gs2gs.github.io/data/Instruct-GS2GS_2024.pdf)
- **GSEdit**, "GSEdit: Efficient Text-Guided Editing of 3D Objects via Gaussian Splatting". [![arXiv](https://img.shields.io/badge/arXiv-2403.05154-b31b1b.svg)](https://arxiv.org/abs/2403.05154)
- **TIP-Editor**, "TIP-Editor: An Accurate 3D Editor Following Both Text-Prompts and Image-Prompts". [![arXiv](https://img.shields.io/badge/arXiv-2401.14828-b31b1b.svg)](https://arxiv.org/abs/2401.14828)
- **GaussianEditor**, "GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting". [![arXiv](https://img.shields.io/badge/arXiv-2311.14521-b31b1b.svg)](https://arxiv.org/abs/2311.14521)
- **DreamEditor**, "DreamEditor: Text-Driven 3D Scene Editing with Neural Fields". [![arXiv](https://img.shields.io/badge/arXiv-2306.13455-b31b1b.svg)](https://arxiv.org/abs/2306.13455)
- **Instruct-NeRF2NeRF**, "Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions". [![arXiv](https://img.shields.io/badge/arXiv-2303.12789-b31b1b.svg)](https://arxiv.org/abs/2303.12789)
- **Vox-E**, "Vox-E: Text-Guided Voxel Editing of 3D Objects". [![arXiv](https://img.shields.io/badge/arXiv-2303.12048-b31b1b.svg)](https://arxiv.org/abs/2303.12048)


## 3D Perception
### Depth / Geometry Perception
- [⭐️] **LingBot-Depth**, "LingBot-Depth: Masked Depth Modeling for Spatial Perception". [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Robbyant/lingbot-depth)
- "Last-Layer-Centric Feature Recombination: Unleashing 3D Geometric Knowledge in DINOv3 for Monocular Depth Estimation". [![arXiv](https://img.shields.io/badge/arXiv-2604.26454-b31b1b.svg)](https://arxiv.org/abs/2604.26454)
- **CARVE**, "Unlocking the Power of Critical Factors for 3D Visual Geometry Estimation". [![arXiv](https://img.shields.io/badge/arXiv-2604.21713-b31b1b.svg)](https://arxiv.org/abs/2604.21713) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/aim-uofa/CARVE)
- **AnyDepth**, "AnyDepth: Depth Estimation Made Easy". [![arXiv](https://img.shields.io/badge/arXiv-2601.02760-b31b1b.svg)](https://arxiv.org/abs/2601.02760)
- **DA^2**, "DA^2: Depth Anything in Any Direction". [![arXiv](https://img.shields.io/badge/arXiv-2509.26618-b31b1b.svg)](https://arxiv.org/abs/2509.26618)
- "Depth Anything at Any Condition". [![arXiv](https://img.shields.io/badge/arXiv-2507.01634-b31b1b.svg)](https://arxiv.org/abs/2507.01634)
- [⭐️] "**Depth Anything v2**". [![arXiv](https://img.shields.io/badge/arXiv-2406.09414-b31b1b.svg)](https://arxiv.org/abs/2406.09414) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/DepthAnything/Depth-Anything-V2)
- [⭐️] **Depth Anything**, "Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data". [![arXiv](https://img.shields.io/badge/arXiv-2401.10891-b31b1b.svg)](https://arxiv.org/abs/2401.10891) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/LiheYoung/Depth-Anything)

### 3D Understanding
- **EPS3D**, "EPS3D: End-to-End Feed-Forward 3D Panoptic Segmentation". [![arXiv](https://img.shields.io/badge/arXiv-2606.08980-b31b1b.svg)](https://arxiv.org/abs/2606.08980) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Runsong123/EPS3D)
- **Semantic Foam**, "Semantic Foam: Unifying Spatial and Semantic Scene Decomposition". [![arXiv](https://img.shields.io/badge/arXiv-2604.26262-b31b1b.svg)](https://arxiv.org/abs/2604.26262) [![Project](https://img.shields.io/badge/Project-Page-green)](http://semanticfoam.github.io/)
- "Multiple Consistent 2D-3D Mappings for Robust Zero-Shot 3D Visual Grounding". [![arXiv](https://img.shields.io/badge/arXiv-2604.26261-b31b1b.svg)](https://arxiv.org/abs/2604.26261)
- **Utonia**, "Utonia: Toward One Encoder for All Point Clouds". [![arXiv](https://img.shields.io/badge/arXiv-2603.03283-b31b1b.svg)](https://arxiv.org/abs/2603.03283) [![Project](https://img.shields.io/badge/Project-Page-green)](https://pointcept.github.io/Utonia/)
- **OpenVoxel**, "OpenVoxel: Training-Free Grouping and Captioning Voxels for Open-Vocabulary 3D Scene Understanding". [![arXiv](https://img.shields.io/badge/arXiv-2601.09575-b31b1b.svg)](https://arxiv.org/abs/2601.09575)
- **MVGGT**, "MVGGT: Multimodal Visual Geometry Grounded Transformer for Multiview 3D Referring Expression Segmentation". [![arXiv](https://img.shields.io/badge/arXiv-2601.06874-b31b1b.svg)](https://arxiv.org/abs/2601.06874) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/sosppxo/mvggt)
- [⭐️] **SAM3D**, "SAM3D: Zero-Shot 3D Object Detection via Segment Anything Model". [![arXiv](https://img.shields.io/badge/arXiv-2306.02245-b31b1b.svg)](https://arxiv.org/abs/2306.02245)

## 3D Vision-Language / Spatial Intelligence
### 3D-Aware Vision-Language Models
- [⭐️] **Qwen-3D**, "Qwen-3D: A Generalist 3D Vision-Language Model for Spatial Understanding". [![arXiv](https://img.shields.io/badge/arXiv-2608.02980-b31b1b.svg)](https://arxiv.org/abs/2608.02980) [![Project](https://img.shields.io/badge/Project-Page-green)](https://qwen-3d.github.io/)
- **Ground3D-LMM**, "Ground3D-LMM: Fine-Grained 3D Point Grounding and Spatial Reasoning with LMM". [![arXiv](https://img.shields.io/badge/arXiv-2607.05493-b31b1b.svg)](https://arxiv.org/abs/2607.05493)
- **GR3D**, "Grounded 3D-Aware Spatial Vision-Language Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2605.30307-b31b1b.svg)](https://arxiv.org/abs/2605.30307) [![Project](https://img.shields.io/badge/Project-Page-green)](https://www.anjiecheng.me/gr3d)
- **DepthVLM**, "Unlocking Dense Metric Depth Estimation in VLMs". [![arXiv](https://img.shields.io/badge/arXiv-2605.15876-b31b1b.svg)](https://arxiv.org/abs/2605.15876) [![Project](https://img.shields.io/badge/Project-Page-green)](https://depthvlm.github.io/)

### Spatial Reasoning / Memory
- **Reasmory**, "Reasmory: 3D Reconstruction as Explicit Memory for VLMs Spatial Reasoning". [![arXiv](https://img.shields.io/badge/arXiv-2606.00963-b31b1b.svg)](https://arxiv.org/abs/2606.00963)
- **SpatialForge**, "SpatialForge: Bootstrapping 3D-Aware Spatial Reasoning from Open-World 2D Images". [![arXiv](https://img.shields.io/badge/arXiv-2605.11462-b31b1b.svg)](https://arxiv.org/abs/2605.11462)
- **World2VLM**, "World2VLM: Distilling World Model Imagination into VLMs for Dynamic Spatial Reasoning". [![arXiv](https://img.shields.io/badge/arXiv-2604.26934-b31b1b.svg)](https://arxiv.org/abs/2604.26934) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/WanyueZhang-ai/World2VLM)
- **Think3D**, "Think3D: Thinking with Space for Spatial Reasoning". [![arXiv](https://img.shields.io/badge/arXiv-2601.13029-b31b1b.svg)](https://arxiv.org/abs/2601.13029)
- **Map2Thought**, "Map2Thought: Explicit 3D Spatial Reasoning via Metric Cognitive Maps". [![arXiv](https://img.shields.io/badge/arXiv-2601.11442-b31b1b.svg)](https://arxiv.org/abs/2601.11442)

## 4D Reconstruction
### E2E 4D Reconstruction
- **SM4RT**, "SM4RT: Learning Structured Motion Geometry for 4D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2607.22534-b31b1b.svg)](https://arxiv.org/abs/2607.22534) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/wzzheng/SM4RT)
- [⭐️] **OmniX**, "OmniX: Any-view and Any-time 4D Reconstruction via Feed-forward Trajectory Fields". [![arXiv](https://img.shields.io/badge/arXiv-2607.10840-b31b1b.svg)](https://arxiv.org/abs/2607.10840) [![Project](https://img.shields.io/badge/Project-Page-green)](https://omnix4d.github.io/)
- **C4G**, "Learning Global Motion with Compact Gaussians for Feed-Forward 4D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2605.31595-b31b1b.svg)](https://arxiv.org/abs/2605.31595) [![Project](https://img.shields.io/badge/Project-Page-green)](https://cvlab-kaist.github.io/C4G)
- **NoPo4D**, "No Pose, No Problem in 4D: Feed-Forward Dynamic Gaussians from Unposed Multi-View Videos". [![arXiv](https://img.shields.io/badge/arXiv-2605.22190-b31b1b.svg)](https://arxiv.org/abs/2605.22190) [![Project](https://img.shields.io/badge/Project-Page-green)](https://bralani.github.io/nopo4d_html/)
- **Flow4R**, "Flow4R: Unifying 4D Reconstruction and Tracking with Scene Flow". [![arXiv](https://img.shields.io/badge/arXiv-2602.14021-b31b1b.svg)](https://arxiv.org/abs/2602.14021)
- **Motion 3-to-4**, "Motion 3-to-4: 3D Motion Reconstruction for 4D Synthesis". [![arXiv](https://img.shields.io/badge/arXiv-2601.14253-b31b1b.svg)](https://arxiv.org/abs/2601.14253)
- **V-DPM**, "V-DPM: 4D Video Reconstruction with Dynamic Point Maps". [![arXiv](https://img.shields.io/badge/arXiv-2601.09499-b31b1b.svg)](https://arxiv.org/abs/2601.09499)
- [⭐️] **D4RT**, "Efficiently Reconstructing Dynamic Scenes One D4RT at a Time". [![arXiv](https://img.shields.io/badge/arXiv-2512.08924-b31b1b.svg)](https://arxiv.org/abs/2512.08924) [![GitHub](https://img.shields.io/badge/GitHub-Page-blue)](https://d4rt-paper.github.io/) [![Blog](https://img.shields.io/badge/DeepMind-Blog-yellow)](https://deepmind.google/blog/d4rt-teaching-ai-to-see-the-world-in-four-dimensions/)
- [⭐️] **VGGT4D**, "VGGT4D: Mining Motion Cues in Visual Geometry Transformers for 4D Scene Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2511.19971-b31b1b.svg)](https://arxiv.org/abs/2511.19971) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/3DAgentWorld/VGGT4D)
- **C4D**, "C4D: 4D Made from 3D through Dual Correspondences". [![arXiv](https://img.shields.io/badge/arXiv-2510.14960-b31b1b.svg)](https://arxiv.org/abs/2510.14960)
- **St4RTrack**, "St4RTrack: Simultaneous 4D Reconstruction and Tracking in the World". [![arXiv](https://img.shields.io/badge/arXiv-2504.13152-b31b1b.svg)](https://arxiv.org/abs/2504.13152) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nhan-nguyen-trong/St4RTrack)
- **D²USt3R**, "D²USt3R: Enhancing 3D Reconstruction with 4D Pointmaps for Dynamic Scenes". [![arXiv](https://img.shields.io/badge/arXiv-2504.06264-b31b1b.svg)](https://arxiv.org/abs/2504.06264)
- **MonST3R**, "MonST3R: A Simple Approach for Estimating Geometry in the Presence of Motion". [![arXiv](https://img.shields.io/badge/arXiv-2410.03825-b31b1b.svg)](https://arxiv.org/abs/2410.03825)
- **Shape of Motion**, "Shape of Motion: 4D Reconstruction from a Single Video". [![arXiv](https://img.shields.io/badge/arXiv-2407.13764-b31b1b.svg)](https://arxiv.org/abs/2407.13764) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/vye16/shape-of-motion)


### non-E2E 4D Reconstruction
- **GeoRect4D**, "GeoRect4D: Geometry-Compatible Generative Rectification for Dynamic Sparse-View 3D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2604.20784-b31b1b.svg)](https://arxiv.org/abs/2604.20784)
- [⭐️] "Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2511.14540-b31b1b.svg)](https://arxiv.org/abs/2511.14540)
- **Sparse4DGS**, "Sparse4DGS: 4D Gaussian Splatting for Sparse-Frame Dynamic Scene Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2511.07122-b31b1b.svg)](https://arxiv.org/abs/2511.07122)
- **MegaSaM**, "MegaSaM: Accurate, Fast, and Robust Structure and Motion from Casual Dynamic Videos". [![arXiv](https://img.shields.io/badge/arXiv-2412.04463-b31b1b.svg)](https://arxiv.org/abs/2412.04463)
- **SplatFields**, "Neural Gaussian Splats for Sparse 3D and 4D Reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2409.11211-b31b1b.svg)](https://arxiv.org/abs/2409.11211) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/markomih/SplatFields)
- **L4GM**, "L4GM: Large 4D Gaussian Reconstruction Model". [![arXiv](https://img.shields.io/badge/arXiv-2406.10324-b31b1b.svg)](https://arxiv.org/abs/2406.10324) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nv-tlabs/L4GM-official)
- **Gaussian-Flow**, "Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle". [![arXiv](https://img.shields.io/badge/arXiv-2312.03431-b31b1b.svg)](https://arxiv.org/abs/2312.03431) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/NJU-3DV/Gaussian-Flow)
- [⭐️] "4D Gaussian Splatting for Real-Time Dynamic Scene Rendering". [![arXiv](https://img.shields.io/badge/arXiv-2310.08528-b31b1b.svg)](https://arxiv.org/abs/2310.08528) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/hustvl/4DGaussians)


## 4D Editing
- **Vista4D**, "Vista4D: Video Reshooting with 4D Point Clouds". [![arXiv](https://img.shields.io/badge/arXiv-2604.21915-b31b1b.svg)](https://arxiv.org/abs/2604.21915) [![Project](https://img.shields.io/badge/Project-Page-green)](https://eyeline-labs.github.io/Vista4D)
- **Catalyst4D**, "Catalyst4D: High-Fidelity 3D-to-4D Scene Editing via Dynamic Propagation". [![arXiv](https://img.shields.io/badge/arXiv-2603.12766-b31b1b.svg)](https://arxiv.org/abs/2603.12766)
- **Instruct-4DGS**, "Instruct-4DGS: Efficient Dynamic Scene Editing via 4D Gaussian-Based Static-Dynamic Separation". [![arXiv](https://img.shields.io/badge/arXiv-2502.02091-b31b1b.svg)](https://arxiv.org/abs/2502.02091)
- **Instruct 4D-to-4D**, "Instruct 4D-to-4D: Editing 4D Scenes as Pseudo-3D Scenes Using 2D Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2406.09402-b31b1b.svg)](https://arxiv.org/abs/2406.09402)
- **Control4D**, "Control4D: Efficient 4D Portrait Editing with Text". [![arXiv](https://img.shields.io/badge/arXiv-2305.20082-b31b1b.svg)](https://arxiv.org/abs/2305.20082)


## 4D Perception
### 4D Geometry / Motion Perception
- **Velox**, "Velox: Learning Representations of 4D Geometry and Appearance". [![arXiv](https://img.shields.io/badge/arXiv-2605.04527-b31b1b.svg)](https://arxiv.org/abs/2605.04527) [![Project](https://img.shields.io/badge/Project-Page-green)](https://apple.github.io/ml-velox)
- [⭐️] **SelfEvo**, "Self-Improving 4D Perception via Self-Distillation". [![arXiv](https://img.shields.io/badge/arXiv-2604.08532-b31b1b.svg)](https://arxiv.org/abs/2604.08532) [![Project](https://img.shields.io/badge/Project-Page-green)](https://self-evo.github.io/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Self-Evo/SelfEvo)
- **PAGE-4D**, "PAGE-4D: Disentangled Pose and Geometry Estimation for VGGT-4D Perception". [![arXiv](https://img.shields.io/badge/arXiv-2510.17568-b31b1b.svg)](https://arxiv.org/abs/2510.17568)
- [⭐️] **ViPE**, "ViPE: Video Pose Engine for 3D Geometric Perception". [![arXiv](https://img.shields.io/badge/arXiv-2508.10934-b31b1b.svg)](https://arxiv.org/abs/2508.10934) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nv-tlabs/vipe)
- **Uni4D**, "Uni4D: Unifying Visual Foundation Models for 4D Modeling from a Single Video". [![arXiv](https://img.shields.io/badge/arXiv-2503.21761-b31b1b.svg)](https://arxiv.org/abs/2503.21761) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Davidyao99/uni4d)
- **Stereo4D**, "Stereo4D: Learning How Things Move in 3D from Internet Stereo Videos". [![arXiv](https://img.shields.io/badge/arXiv-2412.09621-b31b1b.svg)](https://arxiv.org/abs/2412.09621) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/mli0603/stereo4d)

### 4D Understanding / Tracking
- **TrackCraft3R**, "TrackCraft3R: Repurposing Video Diffusion Transformers for Dense 3D Tracking". [![arXiv](https://img.shields.io/badge/arXiv-2605.12587-b31b1b.svg)](https://arxiv.org/abs/2605.12587) [![Project](https://img.shields.io/badge/Project-Page-green)](https://cvlab-kaist.github.io/TrackCraft3r/)
- **ReScene4D**, "ReScene4D: Temporally Consistent Semantic Instance Segmentation of Evolving Indoor 3D Scenes". [![arXiv](https://img.shields.io/badge/arXiv-2601.11508-b31b1b.svg)](https://arxiv.org/abs/2601.11508)
- **3AM**, "3AM: Segment Anything with Geometric Consistency in Videos". [![arXiv](https://img.shields.io/badge/arXiv-2601.08831-b31b1b.svg)](https://arxiv.org/abs/2601.08831)
- **Trace Anything**, "Trace Anything: Representing Any Video in 4D via Trajectory Fields". [![arXiv](https://img.shields.io/badge/arXiv-2510.13802-b31b1b.svg)](https://arxiv.org/abs/2510.13802) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/ByteDance-Seed/TraceAnything)

## Explicit 3D-Free Methods
- [⭐️] **LagerNVS**, "LagerNVS: Latent Geometry for Fully Neural Real-time Novel View Synthesis". [![arXiv](https://img.shields.io/badge/arXiv-2603.20176-b31b1b.svg)](https://arxiv.org/abs/2603.20176) [![Project](https://img.shields.io/badge/Project-Page-green)](http://szymanowiczs.github.io/lagernvs)
- [⭐️] **SVSM**, "Scaling View Synthesis Transformers".  [![arXiv](https://img.shields.io/badge/arXiv-2602.21341-b31b1b.svg)](https://arxiv.org/abs/2602.21341) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/evnkim/SVSM)
- [⭐️] **XFactor**, "True Self-Supervised Novel View Synthesis is Transferable". [![arXiv](https://img.shields.io/badge/arXiv-2510.13063-b31b1b.svg)](https://arxiv.org/abs/2510.13063) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/vsitzmann/xfactor-nvs)
- [⭐️] **RayZer**, "RayZer: A Self-supervised Large View Synthesis Model". [![arXiv](https://img.shields.io/badge/arXiv-2505.00702-b31b1b.svg)](https://arxiv.org/abs/2505.00702) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/hwjiang1510/RayZer)
- [⭐️] **LVSM**, "LVSM: A Large View Synthesis Model with Minimal 3D Inductive Bias". [![arXiv](https://img.shields.io/badge/arXiv-2410.17242-b31b1b.svg)](https://arxiv.org/abs/2410.17242) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/haian-jin/LVSM)


## Related Analysis
- **Co-VGGT**, "What VGGT Knows About Overlap: Probing Geometric Foundation Models for Co-Visibility". [![arXiv](https://img.shields.io/badge/arXiv-2607.09503-b31b1b.svg)](https://arxiv.org/abs/2607.09503)
- "One Scene, Two Depths: Probing Geometric Ambiguity in Monocular Foundation Models". [![arXiv](https://img.shields.io/badge/arXiv-2606.29600-b31b1b.svg)](https://arxiv.org/abs/2606.29600)
- "Can These Views Be One Scene? Evaluating Multiview 3D Consistency when 3D Foundation Models Hallucinate". [![arXiv](https://img.shields.io/badge/arXiv-2605.18754-b31b1b.svg)](https://arxiv.org/abs/2605.18754) [![Project](https://img.shields.io/badge/Project-Page-green)](https://mvp18.github.io/3d-consistency-metrics/)
- **PDI-Bench**, "Quantitative Video World Model Evaluation for Geometric-Consistency". [![arXiv](https://img.shields.io/badge/arXiv-2605.15185-b31b1b.svg)](https://arxiv.org/abs/2605.15185) [![Project](https://img.shields.io/badge/Project-Page-green)](https://pdi-bench.github.io/)
- "How Much 3D Do Video Foundation Models Encode?". [![arXiv](https://img.shields.io/badge/arXiv-2512.19949-b31b1b.svg)](https://arxiv.org/abs/2512.19949)
- [⭐️] "On Geometric Understanding and Learned Priors in Feed-forward 3D Reconstruction Models". [![arXiv](https://img.shields.io/badge/arXiv-2512.11508-b31b1b.svg)](https://arxiv.org/abs/2512.11508)
- "What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models". [![arXiv](https://img.shields.io/badge/arXiv-2512.03422-b31b1b.svg)](https://arxiv.org/abs/2512.03422v1)
- "Feat2GS: Probing Visual Foundation Models with Gaussian Splatting". [![arXiv](https://img.shields.io/badge/arXiv-2412.09606-b31b1b.svg)](https://arxiv.org/abs/2412.09606)


## Foundation Models with 3D Awareness
### Generative Models
- **SpatialFusion**, "SpatialFusion: Endowing Unified Image Generation with Intrinsic 3D Geometric Awareness". [![arXiv](https://img.shields.io/badge/arXiv-2604.26341-b31b1b.svg)](https://arxiv.org/abs/2604.26341)
- [⭐️] **GLD**, "Repurposing Geometric Foundation Models for Multi-view Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2603.22275-b31b1b.svg)](https://arxiv.org/abs/2603.22275) [![Project](https://img.shields.io/badge/Project-Page-green)](https://cvlab-kaist.github.io/GLD/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/cvlab-kaist/GLD/tree/main)
- **Helios**, "Helios: Real Real-Time Long Video Generation Model". [![arXiv](https://img.shields.io/badge/arXiv-2603.04379-b31b1b.svg)](https://arxiv.org/abs/2603.04379) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/PKU-YuanGroup/Helios)
- [⭐️] **VerseCrafter**, "VerseCrafter: Dynamic Realistic Video World Model with 4D Geometric Control". [![arXiv](https://img.shields.io/badge/arXiv-2601.05138-b31b1b.svg)](https://arxiv.org/abs/2601.05138) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/TencentARC/VerseCrafter)
- "Choreographing a World of Dynamic Objects". [![arXiv](https://img.shields.io/badge/arXiv-2601.04194-b31b1b.svg)](https://arxiv.org/abs/2601.04194)
- **OmniView**, "OmniView: An All-Seeing Diffusion Model for 3D and 4D View Synthesis". [![arXiv](https://img.shields.io/badge/arXiv-2512.10940-b31b1b.svg)](https://arxiv.org/abs/2512.10940) [![Project](https://img.shields.io/badge/Project-Page-green)](https://snap-research.github.io/OmniView/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/omniview-video/omniview)
- **SeeU**, "SeeU: Seeing the Unseen World via 4D Dynamics-aware Generation". [![arXiv](https://img.shields.io/badge/arXiv-2512.03350-b31b1b.svg)](https://arxiv.org/abs/2512.03350) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/YuYuan-Yolanda/SeeU)
- [⭐️] "Video World Models with Long-term Spatial Memory". [![arXiv](https://img.shields.io/badge/arXiv-2506.05284-b31b1b.svg)](https://arxiv.org/abs/2506.05284)
- **Wan**, "Wan: Open and Advanced Large-Scale Video Generative Models". [![arXiv](https://img.shields.io/badge/arXiv-2503.20314-b31b1b.svg)](https://arxiv.org/abs/2503.20314v2) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Wan-Video/Wan2.1)

### World Models / Action Models
> **Scope:** Models in this section must use explicit 3D/4D geometry, geometric supervision, spatial action/state representations, or direct action modeling for Physical AI. Generic video-only world models are out of scope.

- **Puffin-World**, "Puffin-World: Scaling a Unified Multimodal Model with Native 3D World States". [![arXiv](https://img.shields.io/badge/arXiv-2609.04196-b31b1b.svg)](https://arxiv.org/abs/2609.04196) [![Project](https://img.shields.io/badge/Project-Page-green)](https://kangliao929.github.io/projects/puffin-world/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/KangLiao929/Puffin)
- **SA-WAM**, "Spatially Aware World Action Model via Geometric Latent Diffusion". [![arXiv](https://img.shields.io/badge/arXiv-2609.02531-b31b1b.svg)](https://arxiv.org/abs/2609.02531)
- **GaussianWAM**, "GaussianWAM: Distilling Geometry and Semantics from 3D Gaussian Fields into World-Action Models". [![arXiv](https://img.shields.io/badge/arXiv-2608.24714-b31b1b.svg)](https://arxiv.org/abs/2608.24714)
- **LAWM-3D**, "LAWM-3D: Learning 3D-Aware Latent Actions from Human Videos for Generalizable Robot World Models". [![arXiv](https://img.shields.io/badge/arXiv-2608.05706-b31b1b.svg)](https://arxiv.org/abs/2608.05706)
- **3DPWM**, "3D Point World Models: Point Completion Enables More Accurate Dynamics Learning". [![arXiv](https://img.shields.io/badge/arXiv-2607.00148-b31b1b.svg)](https://arxiv.org/abs/2607.00148)
- [⭐️] **WAM4D**, "WAM4D: Fast 4D World Action Model via Spatial Register Tokens". [![arXiv](https://img.shields.io/badge/arXiv-2606.14048-b31b1b.svg)](https://arxiv.org/abs/2606.14048)
- **μ₀**, "μ₀: A Scalable 3D Interaction-Trace World Model". [![arXiv](https://img.shields.io/badge/arXiv-2606.13769-b31b1b.svg)](https://arxiv.org/abs/2606.13769)
- [⭐️] **3DThinkVLA**, "3DThinkVLA: Endowing Vision-Language-Action Models with Latent 3D Priors via 3D-Thinking-Guided Co-training". [![arXiv](https://img.shields.io/badge/arXiv-2606.04436-b31b1b.svg)](https://arxiv.org/abs/2606.04436)
- [⭐️] **Cosmos 3**, "Cosmos 3: Omnimodal World Models for Physical AI". [![arXiv](https://img.shields.io/badge/arXiv-2606.02800-b31b1b.svg)](https://arxiv.org/abs/2606.02800) [![Project](https://img.shields.io/badge/Project-Page-green)](https://research.nvidia.com/labs/cosmos-lab/cosmos3) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/nvidia/cosmos)
- **GEM-4D**, "GEM-4D: Geometry-Enhanced Video World Models for Robot Manipulation". [![arXiv](https://img.shields.io/badge/arXiv-2605.22882-b31b1b.svg)](https://arxiv.org/abs/2605.22882) [![Project](https://img.shields.io/badge/Project-Page-green)](https://gem-4d.github.io/)
- **X-WAM**, "Unified 4D World Action Modeling from Video Priors with Asynchronous Denoising". [![arXiv](https://img.shields.io/badge/arXiv-2604.26694-b31b1b.svg)](https://arxiv.org/abs/2604.26694) [![Project](https://img.shields.io/badge/Project-Page-green)](https://sharinka0715.github.io/X-WAM/)
- **GeoPT**, "GeoPT: Scaling Physics Simulation via Lifted Geometric Pre-Training". [![arXiv](https://img.shields.io/badge/arXiv-2602.20399-b31b1b.svg)](https://arxiv.org/abs/2602.20399) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Physics-Scaling/GeoPT)
- [⭐️] **LingBot-VA**, "Causal World Modeling for Robot Control". [![arXiv](https://img.shields.io/badge/arXiv-2601.21998-b31b1b.svg)](https://arxiv.org/abs/2601.21998) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Robbyant/lingbot-va)
- **RoboBrain 2.5**, "RoboBrain 2.5: Depth in Sight, Time in Mind". [![arXiv](https://img.shields.io/badge/arXiv-2601.14352-b31b1b.svg)](https://arxiv.org/abs/2601.14352)
- [⭐️] **NeoVerse**, "NeoVerse: Enhancing 4D World Model with in-the-wild Monocular Videos". [![arXiv](https://img.shields.io/badge/arXiv-2601.00393-b31b1b.svg)](https://arxiv.org/abs/2601.00393) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/IamCreateAI/NeoVerse)
- **DynamicVerse**, "DynamicVerse: A Physically-Aware Multimodal Framework for 4D World Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2512.03000-b31b1b.svg)](https://arxiv.org/abs/2512.03000) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Dynamics-X/DynamicVerse)
- **HunyuanWorld 1.0**, "HunyuanWorld 1.0: Generating Immersive, Explorable, and Interactive 3D Worlds from Words or Pixels". [![arXiv](https://img.shields.io/badge/arXiv-2507.21809-b31b1b.svg)](https://arxiv.org/abs/2507.21809) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/Tencent-Hunyuan/HunyuanWorld-1.0)

## Datasets / Benchmarks
- **TAPVid-MV**, "TAPVid-MV: A Benchmark for Tracking Any Point in 3D Across Multiple Views". [![arXiv](https://img.shields.io/badge/arXiv-2609.01899-b31b1b.svg)](https://arxiv.org/abs/2609.01899)
- **GST-Bench**, "GST-Bench: Can VLMs Develop Global Spatial Awareness from Video?". [![arXiv](https://img.shields.io/badge/arXiv-2608.05747-b31b1b.svg)](https://arxiv.org/abs/2608.05747)
- **Embodied3DBench**, "Embodied3DBench: Benchmarking Low-Level Embodied Spatial Intelligence of Vision Language Models". [![arXiv](https://img.shields.io/badge/arXiv-2605.29074-b31b1b.svg)](https://arxiv.org/abs/2605.29074)
- [⭐️] **3DReflecNet**, "3DReflecNet: A Large-Scale Dataset for 3D Reconstruction of Reflective, Transparent, and Low-Texture Objects". [![arXiv](https://img.shields.io/badge/arXiv-2605.10204-b31b1b.svg)](https://arxiv.org/abs/2605.10204)
- **AirZoo**, "AirZoo: A Unified Large-Scale Dataset for Grounding Aerial Geometric 3D Vision". [![arXiv](https://img.shields.io/badge/arXiv-2604.26567-b31b1b.svg)](https://arxiv.org/abs/2604.26567)
- **MegaDepth-X**, "Long-tail Internet photo reconstruction". [![arXiv](https://img.shields.io/badge/arXiv-2604.22714-b31b1b.svg)](https://arxiv.org/abs/2604.22714) [![Project](https://img.shields.io/badge/Project-Page-green)](https://megadepth-x.github.io/)
- **Holo360D**, "Holo360D: A Large-Scale Real-World Dataset with Continuous Trajectories for Advancing Panoramic 3D Reconstruction and Beyond". [![arXiv](https://img.shields.io/badge/arXiv-2604.22482-b31b1b.svg)](https://arxiv.org/abs/2604.22482)
- [⭐️] **OmniWorld**, "OmniWorld: A Multi-Domain and Multi-Modal Dataset for 4D World Modeling". [![arXiv](https://img.shields.io/badge/arXiv-2509.12201-b31b1b.svg)](https://arxiv.org/abs/2509.12201v1) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/yangzhou24/OmniWorld)


## 3D Vision Applications
### Autonomous Driving
- **HERMES++**, "HERMES++: Toward a Unified Driving World Model for 3D Scene Understanding and Generation". [![arXiv](https://img.shields.io/badge/arXiv-2604.28196-b31b1b.svg)](https://arxiv.org/abs/2604.28196) [![Project](https://img.shields.io/badge/Project-Page-green)](https://h-embodvis.github.io/HERMESV2/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/H-EmbodVis/HERMESV2)
- **Unposed-to-3D**, "Unposed-to-3D: Learning Simulation-Ready Vehicles from Real-World Images". [![arXiv](https://img.shields.io/badge/arXiv-2604.19257-b31b1b.svg)](https://arxiv.org/abs/2604.19257)
- **UniUGP**, "Unifying Understanding, Generation, and Planning For End-to-end Autonomous Driving". [![arXiv](https://img.shields.io/badge/arXiv-2512.09864-b31b1b.svg)](https://arxiv.org/abs/2512.09864) [![Project](https://img.shields.io/badge/Project-Page-green)](https://seed-uniugp.github.io/)
- **DGGT**, "DGGT: Feedforward 4D Reconstruction of Dynamic Driving Scenes using Unposed Images". [![arXiv](https://img.shields.io/badge/arXiv-2512.03004-b31b1b.svg)](https://arxiv.org/abs/2512.03004) [![Project](https://img.shields.io/badge/Project-Page-green)](https://xiaomi-research.github.io/dggt/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/xiaomi-research/dggt)
- **EOT-WM**, "Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies Ego-Other Vehicle Trajectories in Video Latent Space". [![arXiv](https://img.shields.io/badge/arXiv-2503.09215-b31b1b.svg)](https://arxiv.org/abs/2503.09215)
- **OccLLaMA**, "An Occupancy-Language-Action Generative World Model for Autonomous Driving". [![arXiv](https://img.shields.io/badge/arXiv-2409.03272-b31b1b.svg)](https://arxiv.org/abs/2409.03272) [![Project](https://img.shields.io/badge/Project-Page-green)](https://vilonge.github.io/OccLLaMA_Page/)
- **OccWorld**, "Learning a 3D Occupancy World Model for Autonomous Driving". [![arXiv](https://img.shields.io/badge/arXiv-2311.16038-b31b1b.svg)](https://arxiv.org/abs/2311.16038) [![Project](https://img.shields.io/badge/Project-Page-green)](https://wzzheng.net/OccWorld/) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/wzzheng/OccWorld)
- **UniAD** (Planning-oriented Autonomous Driving), "Planning-oriented Autonomous Driving". [![arXiv](https://img.shields.io/badge/arXiv-2212.10156-b31b1b.svg)](https://arxiv.org/abs/2212.10156) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/opendrivelab/uniad)


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
```
## Star History

<a href="https://www.star-history.com/?repos=dongjiacheng06%2FLearning-based-3D-Vision&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=dongjiacheng06/Learning-based-3D-Vision&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=dongjiacheng06/Learning-based-3D-Vision&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=dongjiacheng06/Learning-based-3D-Vision&type=date&legend=top-left" />
 </picture>
</a>
