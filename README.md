# 3D 视觉论文解读清单（B 站 HyperHorizon）

> Source: Bilibili UP **HyperHorizon**
> Snapshot: **2026-10-12**, **229** episodes. Data: [`papers_enriched.json`](papers_enriched.json)

## Data source / method / limits

**Data source**: collection episode list via `seasons_archives_list`; per-video metadata
via `x/web-interface/view` -- the **`desc` (description)** field carries the FULL paper
title, venue, arXiv link and a Chinese summary.

**Method**: descriptions follow `[paper share] <full title> (<venue>) - <cn summary>`;
venue parsing is nesting-aware (handles `SE(3)` and nested conference parentheses).

**Limits**: the `paper` column comes from the **description**, because Bilibili
truncates video **titles** at 80 chars; missing venue/arXiv stays empty; index only.

- 209 of 229 entries carry an arXiv id.

## All 229 episodes

| # | paper | venue | category | arXiv | length | B station |
|---:|---|---|---|---|---:|---|
| 1 | SPVC: Structured and Panoptic Video Fixing for Cross-Dataset Driving Scene Rendering | arXiv 2026 | paper | [2608.17420](https://arxiv.org/abs/2608.17420) | 15:52 | [link](https://www.bilibili.com/video/BV11cbf6mE1e) |
| 2 | OmniAct3D: Leveraging Foundation Geometry and Evidence-Grounded Reasoning for Panoramic 3D Detection | arXiv 2026 | paper | [2610.03015](https://arxiv.org/abs/2610.03015) | 16:05 | [link](https://www.bilibili.com/video/BV1vUp36UE5m) |
| 3 | Manifold4D: Denoising on Point Cloud Rendered Manifolds for Video Re-shooting | arXiv 2026 | paper | [2608.28174](https://arxiv.org/abs/2608.28174) | 15:07 | [link](https://www.bilibili.com/video/BV1yrtT6vEVJ) |
| 4 | Tele360: Real-Time Feed-Forward Human Reconstruction from Sparse Unposed Cameras | arXiv 2026 | paper | [2609.15032](https://arxiv.org/abs/2609.15032) | 15:21 | [link](https://www.bilibili.com/video/BV17Lec6DEnf) |
| 5 | VS-Splat: Voxel-Selective feed-forward Gaussian Splatting for end-to-end 3D object reconstruction from sparse-views | arXiv 2026 | paper | [2609.12343](https://arxiv.org/abs/2609.12343) | 16:20 | [link](https://www.bilibili.com/video/BV15GeJ6iELz) |
| 6 | Habitat-GS: A High-Fidelity Navigation Simulator with Dynamic Gaussian Splatting | arXiv 2026 | paper | [2604.12626](https://arxiv.org/abs/2604.12626) | 16:17 | [link](https://www.bilibili.com/video/BV1Fr8B69End) |
| 7 | UniDynamics: Event-RGB Fusion for Unified Future 4D Dynamic Scene Generation | arXiv 2026 | paper | [2610.03473](https://arxiv.org/abs/2610.03473) | 16:43 | [link](https://www.bilibili.com/video/BV1Rmp36JEA6) |
| 8 | GeoFF3D: Coordinate-Anchored Feed-Forward Reconstruction for Large-Scale UAV Mapping | arXiv 2026 | paper | [2608.28288](https://arxiv.org/abs/2608.28288) | 15:08 | [link](https://www.bilibili.com/video/BV1Untg62E3M) |
| 9 | CrossDepth: Geometry-Constrained Attention for Generalizable Multi-View Surround Depth Estimation | arXiv 2026 | paper | - | 15:34 | [link](https://www.bilibili.com/video/BV1WAbV6SEou) |
| 10 | Zero-Shot Novel Depth Synthesis Using 3D Foundation Models Scene Representations | arXiv 2026 | paper | [2609.04174](https://arxiv.org/abs/2609.04174) | 15:24 | [link](https://www.bilibili.com/video/BV1uubW6xEtX) |
| 11 | AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction | arXiv 2026 | paper | - | 18:53 | [link](https://www.bilibili.com/video/BV1iD8S6jExT) |
| 12 | OmniPoint: Universal Monocular Metric Pointcloud from Any Camera | arXiv 2026 | paper | [2609.09394](https://arxiv.org/abs/2609.09394) | 15:14 | [link](https://www.bilibili.com/video/BV1fUYV6XEv5) |
| 13 | OpenOcc: Open Vocabulary 3D Scene Reconstruction via Occupancy Representation | IROS 2024 | paper | [2403.11796](https://arxiv.org/abs/2403.11796) | 16:05 | [link](https://www.bilibili.com/video/BV1DKg76tECf) |
| 14 | LT-Mem: Volatility-Aware Spatio-Temporal Memory for Lifelong Scene Understanding | arXiv 2026 | paper | [2608.19059](https://arxiv.org/abs/2608.19059) | 15:02 | [link](https://www.bilibili.com/video/BV1hq8q6qEDv) |
| 15 | Info3R: Information-Adaptive Test-Time Training for 3D Reconstruction | arXiv 2026 | paper | [2609.21938](https://arxiv.org/abs/2609.21938) | 14:59 | [link](https://www.bilibili.com/video/BV1M1hp6fEiS) |
| 16 | RoboOcc: Enhancing the Geometric and Semantic Scene Understanding for Robots | arXiv 2025 | paper | [2504.14604](https://arxiv.org/abs/2504.14604) | 17:09 | [link](https://www.bilibili.com/video/BV1yJg76UEM4) |
| 17 | Scene Retargeting: Learning Object Placement with Analogical Transfer | arXiv 2026 | paper | [2609.36801](https://arxiv.org/abs/2609.36801) | 15:52 | [link](https://www.bilibili.com/video/BV1m1pG6zEiP) |
| 18 | TAPVid-MV: A Benchmark for Tracking Any Point in 3D Across Multiple Views | arXiv 2026 | paper | [2609.01899](https://arxiv.org/abs/2609.01899) | 15:10 | [link](https://www.bilibili.com/video/BV1nZte6zEJD) |
| 19 | Query Rewriting for Complex Object Segmentation in 4D Gaussian Representations | arXiv 2026 | paper | [2609.02664](https://arxiv.org/abs/2609.02664) | 13:23 | [link](https://www.bilibili.com/video/BV1note6gE91) |
| 20 | PanSplat: 4K Panorama Synthesis with Feed-Forward Gaussian Splatting | CVPR 2025 | paper | [2412.12096](https://arxiv.org/abs/2412.12096) | 18:13 | [link](https://www.bilibili.com/video/BV1oXgj6TEr3) |
| 21 | LumiTokens: 3D Relighting via Token-Space Lighting Transformation | arXiv 2026 | paper | [2608.18215](https://arxiv.org/abs/2608.18215) | 17:24 | [link](https://www.bilibili.com/video/BV1oR8M6aEYm) |
| 22 | OmniCam: Omni-Camera Trajectory Generation via Geometry-Grounded Pose Token Learning | arXiv 2026 | paper | [2610.09513](https://arxiv.org/abs/2610.09513) | 15:57 | [link](https://www.bilibili.com/video/BV1NVpt6mEDp) |
| 23 | NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction | arXiv 2026 | paper | [2608.22888](https://arxiv.org/abs/2608.22888) | 16:16 | [link](https://www.bilibili.com/video/BV14G8D6wECK) |
| 24 | InceptionGS: Generative Bootstrapping for Large-Scale Gaussian Splatting under Unstructured View Sampling | arXiv 2026 | paper | [2609.02747](https://arxiv.org/abs/2609.02747) | 15:41 | [link](https://www.bilibili.com/video/BV1fktv6BEcD) |
| 25 | Building Rome from a Single Image | arXiv 2026 | paper | [2610.08790](https://arxiv.org/abs/2610.08790) | 16:04 | [link](https://www.bilibili.com/video/BV11sp36NEhJ) |
| 26 | Joint-Embedding Prediction of Masked Point Tubes for Self-Supervised Learning on 4D Point Cloud Videos | arXiv 2026 | paper | [2608.24093](https://arxiv.org/abs/2608.24093) | 18:43 | [link](https://www.bilibili.com/video/BV12Rhw6wEoM) |
| 27 | Self-Geometry: GT-Free and Plug-and-Play Test-Time Adaptation for Geometrically Consistent 3D Vision Foundation Models | arXiv 2026 | paper | - | 17:16 | [link](https://www.bilibili.com/video/BV1VL8P6CEkD) |
| 28 | DecomVoxel: Harnessing 3D-Native Priors with Guided In-situ Denoising Optimization for Decompositional Scene Reconstruction | arXiv 2026 | paper | [2610.01914](https://arxiv.org/abs/2610.01914) | 16:12 | [link](https://www.bilibili.com/video/BV1nip36oEk6) |
| 29 | FIRE3D: Feed-forward Interactive 3D Scene Reconstruction Within A Minute | arXiv 2026 | paper | [2609.08848](https://arxiv.org/abs/2609.08848) | 15:18 | [link](https://www.bilibili.com/video/BV1dEYK6FEAx) |
| 30 | IRIS: Implicit Rendering Matters for Pose-Free Novel View Synthesis | arXiv 2026 | paper | [2609.18034](https://arxiv.org/abs/2609.18034) | 16:11 | [link](https://www.bilibili.com/video/BV1r2ey6EEqq) |
| 31 | CGGT: Curve-Grounded Geometry Transformer for 3D Parametric Curve Reconstruction | arXiv 2026 | paper | [2609.14521](https://arxiv.org/abs/2609.14521) | 15:06 | [link](https://www.bilibili.com/video/BV1B3ec6WEMj) |
| 32 | SGFormer: Satellite-Ground Fusion for 3D Semantic Scene Completion | CVPR 2025 | paper | [2503.16825](https://arxiv.org/abs/2503.16825) | 16:42 | [link](https://www.bilibili.com/video/BV1tDg76tEUc) |
| 33 | Adaptive World Memory 3D Foundation Model for Scalable 3D Mapping, Localization, and Rendering | arXiv 2026 | paper | [2609.21502](https://arxiv.org/abs/2609.21502) | 14:53 | [link](https://www.bilibili.com/video/BV1txhk65E72) |
| 34 | Scaling 3D Generative Priors to Large-Scale Scene Meshes from Multi-View Images | arXiv 2026 | paper | [2609.06385](https://arxiv.org/abs/2609.06385) | 16:27 | [link](https://www.bilibili.com/video/BV1EhYN6AEbf) |
| 35 | 学习用于 4D 重建的结构化运动几何 | arXiv:2607.22534 2026 | paper | - | 13:12 | [link](https://www.bilibili.com/video/BV1TsGP6dETR) |
| 36 | OpenSplatGraph: From Dense Semantic Maps to Structured Scene Graphs for Open-Vocabulary Robot Perception | arXiv 2026 | paper | [2610.07569](https://arxiv.org/abs/2610.07569) | 14:52 | [link](https://www.bilibili.com/video/BV1nYp36fEaQ) |
| 37 | HARMONY: Hierarchical Agentic Reasoning for MONocular Image-to-Scene Synthesis | arXiv 2026 | paper | [2609.26793](https://arxiv.org/abs/2609.26793) | 15:51 | [link](https://www.bilibili.com/video/BV1Aqps6eEG8) |
| 38 | Memory Tree Guided Key Frame Querying for Efficient 3D Question Answering | arXiv 2026 | paper | [2608.18009](https://arxiv.org/abs/2608.18009) | 16:44 | [link](https://www.bilibili.com/video/BV1GKbZ6xEp8) |
| 39 | GaussVid: Sparse-View Gaussian Splatting with 3D-Aware Video Diffusion Priors | arXiv 2026 | paper | - | 16:21 | [link](https://www.bilibili.com/video/BV12V8D6hE8r) |
| 40 | Guiding Image-to-3D Generation with Test-Time Partial Observations | arXiv 2026 | paper | [2609.10531](https://arxiv.org/abs/2609.10531) | 14:30 | [link](https://www.bilibili.com/video/BV1tTY566EvD) |
| 41 | LVSPM: Long Sequence View Synthesis and Pose Estimation Model | arXiv 2026 | paper | [2610.10960](https://arxiv.org/abs/2610.10960) | 15:44 | [link](https://www.bilibili.com/video/BV1cBpi6YEUM) |
| 42 | SAMV-DUSt3R: Instance-Centric 3D Scene Decoupling from Sparse Multi-Views | arXiv 2026 | paper | [2609.11279](https://arxiv.org/abs/2609.11279) | 15:49 | [link](https://www.bilibili.com/video/BV1UXYD6yECx) |
| 43 | Puffin-World: Scaling a Unified Multimodal Model with Native 3D World States | arXiv 2026 | paper | [2609.04196](https://arxiv.org/abs/2609.04196) | 14:54 | [link](https://www.bilibili.com/video/BV1GKbW6tEFM) |
| 44 | MegaParts: Scaling Part-Aware 3D Object Generation to 300 Parts via Token-Efficient Autoregressive Modeling | arXiv 2026 | paper | [2608.14783](https://arxiv.org/abs/2608.14783) | 16:00 | [link](https://www.bilibili.com/video/BV1yv876TE2h) |
| 45 | PlenoCI: Plenoptic CharacterIstics for View Dependence Aware Change Classification | arXiv 2026 | paper | [2609.28930](https://arxiv.org/abs/2609.28930) | 14:54 | [link](https://www.bilibili.com/video/BV18sp46nEPo) |
| 46 | TrackEverything: Long Horizon Dense Tracking via De-Duplicating 3D Scene Representations | arXiv 2026 | paper | [2609.30222](https://arxiv.org/abs/2609.30222) | 15:36 | [link](https://www.bilibili.com/video/BV1A8pa6pEvS) |
| 47 | Luce: Relightable Gaussians for 3D Asset Generation | arXiv 2026 | paper | [2608.23943](https://arxiv.org/abs/2608.23943) | 16:16 | [link](https://www.bilibili.com/video/BV1rwhA64ECf) |
| 48 | DynStream: Online Streaming 4D Gaussian Reconstruction of Dynamic Worlds from Unposed Video | arXiv 2026 | paper | [2610.09720](https://arxiv.org/abs/2610.09720) | 14:01 | [link](https://www.bilibili.com/video/BV1F2p46KEnd) |
| 49 | Think Locally, Refine Globally for Memory-Efficient 3D Reconstruction | arXiv 2026 | paper | [2609.21437](https://arxiv.org/abs/2609.21437) | 15:17 | [link](https://www.bilibili.com/video/BV1H5hn6GE1Z) |
| 50 | TopoSurfel: Closing the Loop between Gaussian Surfels and Meshes for Surface Reconstruction | arXiv 2026 | paper | [2608.20687](https://arxiv.org/abs/2608.20687) | 21:18 | [link](https://www.bilibili.com/video/BV1kHhV6WEc4) |
| 51 | AVSplat: Dense-View Feed-Forward 3D Gaussian Splatting with Assist-View Preconditioning | arXiv 2026 | paper | [2609.05925](https://arxiv.org/abs/2609.05925) | 14:34 | [link](https://www.bilibili.com/video/BV1T9YN67ESr) |
| 52 | 4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors | arXiv 2026 | paper | [2609.21176](https://arxiv.org/abs/2609.21176) | 16:44 | [link](https://www.bilibili.com/video/BV1pGhn6yEUK) |
| 53 | Beyond the Image Plane: World-Grounded Queries for Multi-Object Tracking | arXiv 2026 | paper | [2609.00924](https://arxiv.org/abs/2609.00924) | 14:04 | [link](https://www.bilibili.com/video/BV1x2tR6qEvZ) |
| 54 | Fysiverse-3D-SimReady Technical Report: Agentic Physical Simulation for Pragmatic 3D World Reconstruction | arXiv 2026 | paper | [2609.31715](https://arxiv.org/abs/2609.31715) | 16:17 | [link](https://www.bilibili.com/video/BV1Kwpg6wE14) |
| 55 | InfiniDepth: Arbitrary-Resolution and Fine-Grained Depth Estimation with Neural Implicit Fields | arXiv 2026 | paper | [2601.03252](https://arxiv.org/abs/2601.03252) | 16:20 | [link](https://www.bilibili.com/video/BV1L58B6GE3T) |
| 56 | Revisiting Local Context for Long-Horizon Streaming 3D Reconstruction | arXiv 2026 | paper | [2608.27529](https://arxiv.org/abs/2608.27529) | 16:06 | [link](https://www.bilibili.com/video/BV1eTtg64Epo) |
| 57 | Sparse auto-regressive modeling for scene generation from multi-view images | arXiv 2026 | paper | [2609.03931](https://arxiv.org/abs/2609.03931) | 15:12 | [link](https://www.bilibili.com/video/BV15QbE6HEYG) |
| 58 | PASTEL: Panoramic Alignment for Monocular 4D Scene Reconstruction | arXiv 2026 | paper | [2609.06099](https://arxiv.org/abs/2609.06099) | 16:05 | [link](https://www.bilibili.com/video/BV1TZYN6yEwV) |
| 59 | The Neverwhere Visual Parkour Benchmark Suite | arXiv 2026 | paper | [2609.16443](https://arxiv.org/abs/2609.16443) | 15:14 | [link](https://www.bilibili.com/video/BV1KheM69EaE) |
| 60 | StereoGaussians: Feed-Forward 3D Gaussian Splatting from Stereo Images | arXiv 2026 | paper | [2609.38592](https://arxiv.org/abs/2609.38592) | 15:00 | [link](https://www.bilibili.com/video/BV1uCp56SEss) |
| 61 | UniQuery4R: Unified 4D Scene Reconstruction from a Single Query | arXiv 2026 | paper | [2608.17283](https://arxiv.org/abs/2608.17283) | 15:17 | [link](https://www.bilibili.com/video/BV1QTbZ6RESt) |
| 62 | OmniIndoor3D: Comprehensive Indoor 3D Reconstruction | arXiv 2025 | paper | [2505.20610](https://arxiv.org/abs/2505.20610) | 15:25 | [link](https://www.bilibili.com/video/BV1DUgJ6qEZs) |
| 63 | On-the-Fly3R: Towards Robust Online 3D Reconstruction with Feed-Forward 3R Models for Large-Scale UAV Scenarios | arXiv 2026 | paper | [2609.00923](https://arxiv.org/abs/2609.00923) | 13:53 | [link](https://www.bilibili.com/video/BV1vttR6SEV9) |
| 64 | Generative Semantic Scene Completion | arXiv 2026 | paper | [2608.26737](https://arxiv.org/abs/2608.26737) | 21:36 | [link](https://www.bilibili.com/video/BV1HQtn6KEQD) |
| 65 | GraphWrit3R: End-to-End 3D Scene Graph Writing | arXiv 2026 | paper | [2609.31595](https://arxiv.org/abs/2609.31595) | 14:59 | [link](https://www.bilibili.com/video/BV1yvp46CER7) |
| 66 | Generation of High-Level Concepts in 3D Scene Graphs via Autoregressive Diffusion | arXiv 2026 | paper | [2608.28733](https://arxiv.org/abs/2608.28733) | 14:26 | [link](https://www.bilibili.com/video/BV1izt76mEsF) |
| 67 | DistScene: Object-to-Scene Distillation for 3D Scene Generation | arXiv 2026 | paper | [2610.06960](https://arxiv.org/abs/2610.06960) | 17:14 | [link](https://www.bilibili.com/video/BV1hVp36kEfW) |
| 68 | GrapeSplat: Geometry-Grounded Reconstruction via Amalgamated Pose-Free Encoding for Feed-Forward 3D Gaussian Splatting | arXiv 2026 | paper | [2609.23182](https://arxiv.org/abs/2609.23182) | 15:20 | [link](https://www.bilibili.com/video/BV1CZhC63Eny) |
| 69 | Representing Long Volumetric Video with Temporal Gaussian Hierarchy | - | paper | - | 16:58 | [link](https://www.bilibili.com/video/BV1mVg76XEuC) |
| 70 | SPOON: Towards Coherent Compositional 3D Scene Generation from Uncalibrated Multi-view Images | arXiv 2026 | paper | [2609.39590](https://arxiv.org/abs/2609.39590) | 15:03 | [link](https://www.bilibili.com/video/BV1DipG61EeK) |
| 71 | PIVOT: A Multi-Trajectory Dataset and Testbed for Pose, Intrinsics, and Novel Viewpoint Evaluation in Real-World 3D Reconstruction | arXiv 2026 | paper | [2608.25401](https://arxiv.org/abs/2608.25401) | 14:49 | [link](https://www.bilibili.com/video/BV1E64f6NE8H) |
| 72 | S2Tok: Streaming 3D Gaussian Reconstruction with Persistent Spatial Tokens | arXiv 2026 | paper | [2610.08978](https://arxiv.org/abs/2610.08978) | 15:16 | [link](https://www.bilibili.com/video/BV1PJpt6CEzY) |
| 73 | DDMS: Discriminative Distillation of Multi-view Foundational Features into Single-view Models | arXiv 2026 | paper | [2608.23850](https://arxiv.org/abs/2608.23850) | 16:28 | [link](https://www.bilibili.com/video/BV1fGhA6SE7N) |
| 74 | RouteBridge: Reliability-Routed Bidirectional Distillation Between Neural Radiance Fields and 3D Gaussian Splatting | arXiv 2026 | paper | [2609.09606](https://arxiv.org/abs/2609.09606) | 15:32 | [link](https://www.bilibili.com/video/BV1PBYV6hEbR) |
| 75 | AgentSTAR: Agentic Shape Tracking and Reconstruction from Monocular Videos | arXiv 2026 | paper | [2609.24487](https://arxiv.org/abs/2609.24487) | 15:58 | [link](https://www.bilibili.com/video/BV1Vdps6HEFr) |
| 76 | GaussianGPT: Towards Autoregressive 3D Gaussian Scene Generation | arXiv 2026 | paper | [2603.26661](https://arxiv.org/abs/2603.26661) | 15:38 | [link](https://www.bilibili.com/video/BV1nC8B6pEdm) |
| 77 | DiGS-Avatar: Single-Image Animatable 3D Human Reconstruction via UV-Space Diffusion | arXiv 2026 | paper | [2608.20759](https://arxiv.org/abs/2608.20759) | 17:16 | [link](https://www.bilibili.com/video/BV1hHhG6vE7d) |
| 78 | Rethinking 3D Noise: Learning 3D-Aware Video Priors via Optimization-Free Morphological Perturbations | arXiv 2026 | paper | [2609.03657](https://arxiv.org/abs/2609.03657) | 16:00 | [link](https://www.bilibili.com/video/BV1ajbE6LERG) |
| 79 | Beyond Placement and Articulation: Usage-Driven Code Scenes for Embodied Interaction | arXiv 2026 | paper | [2608.18840](https://arxiv.org/abs/2608.18840) | 15:00 | [link](https://www.bilibili.com/video/BV1818T6SEpE) |
| 80 | GroupForward: Building Referable 3D Scenes via Instance-Grouped Feed-Forward Gaussian Splatting | arXiv 2026 | paper | [2608.17535](https://arxiv.org/abs/2608.17535) | 19:47 | [link](https://www.bilibili.com/video/BV1vpbf6YEDs) |
| 81 | FLARE: Feed-Forward Geometry, Appearance and Camera Estimation from Uncalibrated Sparse Views | CVPR 2025 | paper | [2502.12138](https://arxiv.org/abs/2502.12138) | 18:57 | [link](https://www.bilibili.com/video/BV197tN6VEkV) |
| 82 | Sparse-View 4D Gaussian Splatting via Spatiotemporal Priors and Generative Assistance | arXiv 2026 | paper | [2610.04606](https://arxiv.org/abs/2610.04606) | 15:59 | [link](https://www.bilibili.com/video/BV18jp366ERv) |
| 83 | Reliability-Regulated Trajectory Optimization for Progressive COLMAP-Free 3D Gaussian Splatting | arXiv 2026 | paper | [2609.30865](https://arxiv.org/abs/2609.30865) | 15:35 | [link](https://www.bilibili.com/video/BV1crp46zE2C) |
| 84 | VideoScene: Distilling Video Diffusion Model to Generate 3D Scenes in One Step | arXiv 2025 | paper | [2504.01956](https://arxiv.org/abs/2504.01956) | 21:24 | [link](https://www.bilibili.com/video/BV1WfgL65EJa) |
| 85 | GATOR: Generative and Agentic 3D Object Reconstruction From Casual Images | arXiv 2026 | paper | [2610.11215](https://arxiv.org/abs/2610.11215) | 15:42 | [link](https://www.bilibili.com/video/BV13vpv61ED8) |
| 86 | Learning 3D Editing without Paired Supervision via Generative Prior Distillation | arXiv 2026 | paper | [2609.04942](https://arxiv.org/abs/2609.04942) | 14:59 | [link](https://www.bilibili.com/video/BV1ecbG6wEfu) |
| 87 | Cyc3D: Evaluating Cyclic Structural Stability and Asset Usability in Image-to-3D Generation | arXiv 2026 | paper | [2608.28080](https://arxiv.org/abs/2608.28080) | 16:14 | [link](https://www.bilibili.com/video/BV1Bctg68EYU) |
| 88 | GRF-Recon: Global Ray-Field Optimization for Long-Sequence Feed-forward Reconstruction | arXiv 2026 | paper | [2609.20012](https://arxiv.org/abs/2609.20012) | 17:20 | [link](https://www.bilibili.com/video/BV1znet6wEZD) |
| 89 | GAPS: Generative Active Pseudo-view Selection for Sparse-View 3D Gaussian Splatting | arXiv 2026 | paper | [2609.23436](https://arxiv.org/abs/2609.23436) | 15:14 | [link](https://www.bilibili.com/video/BV19Xps6pEmT) |
| 90 | MINT: A Unified Model for World-Space Camera and Hand Motion Estimation from Scalable Egocentric Pipeline Supervision | arXiv 2026 | paper | [2609.04958](https://arxiv.org/abs/2609.04958) | 15:49 | [link](https://www.bilibili.com/video/BV1cKbV6mEB7) |
| 91 | Matisse: Evidence-Space Reasoning for Active 3D Reconstruction | arXiv 2026 | paper | [2609.38746](https://arxiv.org/abs/2609.38746) | 15:08 | [link](https://www.bilibili.com/video/BV18BpG6VEgt) |
| 92 | Bi-FlowGS: Bridging Generative View Completion and Gaussian Geometry through Bidirectional Flow Co-Refinement | arXiv 2026 | paper | [2609.17039](https://arxiv.org/abs/2609.17039) | 14:33 | [link](https://www.bilibili.com/video/BV1ckeM6jEDJ) |
| 93 | Monocular Depth Estimation from a Single Image: Progress and Opportunities | arXiv 2026 | paper | [2609.01172](https://arxiv.org/abs/2609.01172) | 15:12 | [link](https://www.bilibili.com/video/BV1bxtZ6UEe9) |
| 94 | NavArena: Automated Construction of Goal-Oriented Navigation Benchmarks from 3D Gaussian Splatting Reconstructions | arXiv 2026 | paper | [2609.04602](https://arxiv.org/abs/2609.04602) | 17:41 | [link](https://www.bilibili.com/video/BV1Wzb367EwJ) |
| 95 | SceneScaffold: Active Scene-State Construction for Unified 3D Scene Understanding | arXiv 2026 | paper | [2609.33518](https://arxiv.org/abs/2609.33518) | 14:23 | [link](https://www.bilibili.com/video/BV1tzph64ET2) |
| 96 | TransHands: Repurposing Human Pose Encoders as Hand Pose Encoders | arXiv 2026 | paper | [2608.22341](https://arxiv.org/abs/2608.22341) | 15:46 | [link](https://www.bilibili.com/video/BV1cU896NErE) |
| 97 | RelationField: Relate Anything in Radiance Fields | CVPR 2025 | paper | - | 17:59 | [link](https://www.bilibili.com/video/BV1wxg761EjA) |
| 98 | UniDepthV2: Universal Monocular Metric Depth Estimation Made Simpler | IEEE TPAMI 2026 | paper | - | 17:11 | [link](https://www.bilibili.com/video/BV1nTgE62Eco) |
| 99 | Uni-3DAR: Unified 3D Generation and Understanding via Autoregression on Compressed Spatial Tokens | arXiv 2025 | paper | [2503.16278](https://arxiv.org/abs/2503.16278) | 16:28 | [link](https://www.bilibili.com/video/BV1GpgE6iERZ) |
| 100 | FounRef: Robust, Structure-Preserving, and Fast Metric Refinement of Frozen Monocular Foundation Priors with Sparse Anchors | arXiv 2026 | paper | [2609.29224](https://arxiv.org/abs/2609.29224) | 15:38 | [link](https://www.bilibili.com/video/BV186pv6GE8c) |
| 101 | LVS: Local View Synthesis from Relative Camera Pose by Reusing Previous Views | arXiv 2026 | paper | [2610.12127](https://arxiv.org/abs/2610.12127) | 16:18 | [link](https://www.bilibili.com/video/BV1fApi6xEKh) |
| 102 | OREN-X: Octree Residual Network for Real-Time Multi-Modal Mapping | arXiv 2026 | paper | [2609.29157](https://arxiv.org/abs/2609.29157) | 14:42 | [link](https://www.bilibili.com/video/BV13Hhy6RE3z) |
| 103 | ScenePilot: Grow-and-Repair Policy for Text-Driven 3D Indoor Scene Generation | arXiv 2026 | paper | [2608.30307](https://arxiv.org/abs/2608.30307) | 15:49 | [link](https://www.bilibili.com/video/BV1Zat76HE6N) |
| 104 | Reconstructing the Dynamic World: A Representation-Centric View of 4D Scene Reconstruction | arXiv 2026 | paper | [2609.39960](https://arxiv.org/abs/2609.39960) | 15:43 | [link](https://www.bilibili.com/video/BV1UrpG6GEEw) |
| 105 | DyGT: Modeling Object Dynamics with 3D Gaussian Temporal-Spatial Particle Graph Transformer | arXiv 2026 | paper | - | 15:55 | [link](https://www.bilibili.com/video/BV15n8M6dEQj) |
| 106 | R3DS: Reality-linked 3D Scenes for Panoramic Scene Understanding | ECCV 2024 | paper | [2403.12301](https://arxiv.org/abs/2403.12301) | 17:07 | [link](https://www.bilibili.com/video/BV1zhg763EM4) |
| 107 | Less Decoder is More Encoder: Geometric Representation Learning from Novel View Synthesis | arXiv 2026 | paper | [2610.03717](https://arxiv.org/abs/2610.03717) | 14:53 | [link](https://www.bilibili.com/video/BV1GDp367E2E) |
| 108 | StudioRecon：低重叠相机下的4D人体-场景重建 | - | paper | [2607.09125](https://arxiv.org/abs/2607.09125) | 14:45 | [link](https://www.bilibili.com/video/BV1Aogw6uEW6) |
| 109 | T3lescope: Arbitrary-Resolution High-Fidelity Generative Surface Reconstruction from Images | arXiv 2026 | paper | [2610.03308](https://arxiv.org/abs/2610.03308) | 14:53 | [link](https://www.bilibili.com/video/BV15mp36JErr) |
| 110 | ViPE: Video Pose Engine for 3D Geometric Perception | arXiv 2025 | paper | [2508.10934](https://arxiv.org/abs/2508.10934) | 16:04 | [link](https://www.bilibili.com/video/BV1Myb66iECg) |
| 111 | OccAnyScene: Towards Unified Indoor-Outdoor 3D Occupancy Prediction | arXiv 2026 | paper | [2608.08696](https://arxiv.org/abs/2608.08696) | 10:30 | [link](https://www.bilibili.com/video/BV1EkgG6bELt) |
| 112 | ParticleSplat: Self-supervised Object-centric Latent Particle Splatting | arXiv 2026 | paper | [2609.19463](https://arxiv.org/abs/2609.19463) | 15:13 | [link](https://www.bilibili.com/video/BV1MAet6yEE5) |
| 113 | Geometric Context Transformer for Streaming 3D Reconstruction | arXiv 2026 | paper | [2604.14141](https://arxiv.org/abs/2604.14141) | 14:35 | [link](https://www.bilibili.com/video/BV1GntN6GEnX) |
| 114 | Scal3R: Learning Efficient Multi-Relative Pose Query for Scalable Online 3D Reconstruction | arXiv 2026 | paper | [2609.04201](https://arxiv.org/abs/2609.04201) | 16:03 | [link](https://www.bilibili.com/video/BV1hJbE6VE4g) |
| 115 | NeoWorld-Pro: Programming Interactive Scenes from Monocular Images for Embodied Simulation | arXiv 2026 | paper | [2608.24212](https://arxiv.org/abs/2608.24212) | 15:51 | [link](https://www.bilibili.com/video/BV1DzhF6eExB) |
| 116 | PanoDreamer: Consistent Text to 360-Degree Scene Generation | - | paper | - | 17:48 | [link](https://www.bilibili.com/video/BV12Gg76WEy7) |
| 117 | GeoWeaver: Accurate Long-Sequence 3D Reconstruction via Hierarchical Geometric Assembly | arXiv 2026 | paper | [2608.17389](https://arxiv.org/abs/2608.17389) | 18:17 | [link](https://www.bilibili.com/video/BV1Fsbd6vEWU) |
| 118 | StreetCrafter: Street View Synthesis with Controllable Video Diffusion Models | CVPR 2025 | paper | [2412.13188](https://arxiv.org/abs/2412.13188) | 18:09 | [link](https://www.bilibili.com/video/BV1Yyg76aEK5) |
| 119 | VistaDream: Sampling multiview consistent images for single-view scene reconstruction | ICCV 2025 | paper | - | 16:15 | [link](https://www.bilibili.com/video/BV1zsgL6qE3G) |
| 120 | VoxelTTO: Voxel-Aligned Feed-Forward 3D Gaussian Splatting with Test-Time Optimization | arXiv 2026 | paper | [2609.21498](https://arxiv.org/abs/2609.21498) | 14:42 | [link](https://www.bilibili.com/video/BV1tZh76LEDm) |
| 121 | TRACKGRAPH: Online Open-Vocabulary 3D Scene Graphs via Image-Space Tracking | arXiv 2026 | paper | [2609.31005](https://arxiv.org/abs/2609.31005) | 14:58 | [link](https://www.bilibili.com/video/BV1ABp46rELF) |
| 122 | RichDreamer: A Generalizable Normal-Depth Diffusion Model for Detail Richness in Text-to-3D | arXiv 2023 | paper | [2311.16918](https://arxiv.org/abs/2311.16918) | 16:34 | [link](https://www.bilibili.com/video/BV1mDgL6SExs) |
| 123 | OTT3R: Multi-View 3D Reconstruction and Fast Dataset Generation at 1\% Compute | arXiv 2026 | paper | [2609.36374](https://arxiv.org/abs/2609.36374) | 16:39 | [link](https://www.bilibili.com/video/BV1wupg64EAy) |
| 124 | Geometry Without Coordinates: LiDAR Diffusion as a 3D Feature Bridge | arXiv 2026 | paper | [2609.10322](https://arxiv.org/abs/2609.10322) | 14:28 | [link](https://www.bilibili.com/video/BV1LcYE6cEpr) |
| 125 | Prometheus: 3D-Aware Latent Diffusion Models for Feed-Forward Text-to-3D Scene Generation | CVPR 2025 | paper | [2412.21117](https://arxiv.org/abs/2412.21117) | 15:19 | [link](https://www.bilibili.com/video/BV1Rdgj6NEjC) |
| 126 | Pixel-Perfect Depth with Semantics-Prompted Diffusion Transformers | NeurIPS 2025 | paper | [2510.07316](https://arxiv.org/abs/2510.07316) | 17:05 | [link](https://www.bilibili.com/video/BV1C7gL6GEpj) |
| 127 | ArtiMo: Agent-Driven Articulated Mesh Animation | arXiv 2026 | paper | [2608.20699](https://arxiv.org/abs/2608.20699) | 15:42 | [link](https://www.bilibili.com/video/BV1A6hG6pEki) |
| 128 | Stream3Dv2: Geometric-Semantic Fusion Enhanced Streaming Zero-Shot 3D Scene Understanding | arXiv 2026 | paper | [2608.21136](https://arxiv.org/abs/2608.21136) | 15:52 | [link](https://www.bilibili.com/video/BV14Xh36sEWs) |
| 129 | Dynamic-Robust Photometric-Semantic Reconstruction for Open-Vocabulary 3D Scene Understanding | arXiv 2026 | paper | [2608.29177](https://arxiv.org/abs/2608.29177) | 15:56 | [link](https://www.bilibili.com/video/BV12RtL6ZEN8) |
| 130 | ElasticFit: Fit-Aware 3D Object Insertion via VLM Reasoning and Generative Adaptation | arXiv 2026 | paper | [2610.07460](https://arxiv.org/abs/2610.07460) | 14:35 | [link](https://www.bilibili.com/video/BV1sbp36aExS) |
| 131 | \phi-RIE: From Photorealistic Reconstruction to Interactive Environments | arXiv 2026 | paper | [2609.26795](https://arxiv.org/abs/2609.26795) | 16:43 | [link](https://www.bilibili.com/video/BV1odh26uEJq) |
| 132 | VGGT-Bridge: Beyond Sequential Pose Graphs via Coarse-Stride Skip Edges | arXiv 2026 | paper | [2610.06594](https://arxiv.org/abs/2610.06594) | 15:30 | [link](https://www.bilibili.com/video/BV1YGp36VELS) |
| 133 | ReconSplat: Generalizable 3D Scene Reconstruction Beyond Observed Views | arXiv 2026 | paper | [2608.28895](https://arxiv.org/abs/2608.28895) | 15:20 | [link](https://www.bilibili.com/video/BV1LBt76EEk4) |
| 134 | TextSplat: Text-Guided Semantic Fusion for Generalizable Gaussian Splatting | ACM Multimedia 2025 | paper | [2504.09588](https://arxiv.org/abs/2504.09588) | 18:28 | [link](https://www.bilibili.com/video/BV1LjgE66EEK) |
| 135 | Masked Depth Modeling for Spatial Perception | arXiv 2026 | paper | [2601.17895](https://arxiv.org/abs/2601.17895) | 14:43 | [link](https://www.bilibili.com/video/BV1mhtN6eEYG) |
| 136 | Prim2Room: Layout-Controllable Room Mesh Generation from Primitives | arXiv 2024 | paper | [2409.05380](https://arxiv.org/abs/2409.05380) | 17:37 | [link](https://www.bilibili.com/video/BV19fgj6AEbd) |
| 137 | Photorealistic Novel View Synthesis of Human Faces using Next-Scale Transformers | arXiv 2026 | paper | [2608.23410](https://arxiv.org/abs/2608.23410) | 14:29 | [link](https://www.bilibili.com/video/BV1iQ8S61EA6) |
| 138 | SAR3D: Autoregressive 3D Object Generation and Understanding via Multi-scale 3D VQVAE | CVPR 2025 | paper | [2411.16856](https://arxiv.org/abs/2411.16856) | 15:12 | [link](https://www.bilibili.com/video/BV1xRg76REQk) |
| 139 | VoxelSplat: Dynamic Gaussian Splatting as an Effective Loss for Occupancy and Flow Prediction | arXiv 2025 | paper | [2506.05563](https://arxiv.org/abs/2506.05563) | 19:05 | [link](https://www.bilibili.com/video/BV1PdgL67Ek2) |
| 140 | HiCo-GS: Hierarchical Context Aggregation and Geometric Consistency for Octree Gaussian Splatting | ACM Multimedia (MM '26) 2026 | paper | [2608.14136](https://arxiv.org/abs/2608.14136) | 15:31 | [link](https://www.bilibili.com/video/BV1pN8g6yEDo) |
| 141 | Mira-Scene: Pixel-Aligned Layouts for Generative 3D Scene Reconstruction | arXiv 2026 | paper | [2609.23796](https://arxiv.org/abs/2609.23796) | 15:01 | [link](https://www.bilibili.com/video/BV159ps6XEru) |
| 142 | SplatLabel: Pseudo-Labelling through 4D Gaussian Splatting | arXiv 2026 | paper | [2609.29836](https://arxiv.org/abs/2609.29836) | 14:16 | [link](https://www.bilibili.com/video/BV1G7hy6bELh) |
| 143 | CapFrame: Text-Instructed Viewpoint Grounding in 3D Gaussian Scenes via Geometric Pseudo Labels | arXiv 2026 | paper | [2608.30342](https://arxiv.org/abs/2608.30342) | 15:51 | [link](https://www.bilibili.com/video/BV16jtn6FEcv) |
| 144 | RenderBench: Benchmarking Render-to-Real Video Transfer with Reconstructed Digital Twins | arXiv 2026 | paper | [2610.08684](https://arxiv.org/abs/2610.08684) | 15:24 | [link](https://www.bilibili.com/video/BV1Cap368Eb9) |
| 145 | Fysiverse-3D-Vision Technical Report: Generating Executable 3D Worlds from Images through Unified Spatial Reasoning | arXiv 2026 | paper | [2609.25741](https://arxiv.org/abs/2609.25741) | 16:09 | [link](https://www.bilibili.com/video/BV1bsps6kELP) |
| 146 | GenRec: Knowing Where to Reconstruct and Where to Generate | arXiv 2026 | paper | [2608.17832](https://arxiv.org/abs/2608.17832) | 15:43 | [link](https://www.bilibili.com/video/BV1R6bZ6wE9i) |
| 147 | SceneReGen: Generative Reconstruction of 3D Scenes from a Single Image | arXiv 2026 | paper | [2608.23930](https://arxiv.org/abs/2608.23930) | 16:22 | [link](https://www.bilibili.com/video/BV1HJhF6EEf7) |
| 148 | DSSR-3D: Decoupled Reasoning for View-Dependent Referring in 3D Gaussians | arXiv 2026 | paper | [2610.00040](https://arxiv.org/abs/2610.00040) | 15:39 | [link](https://www.bilibili.com/video/BV17rp36WEFs) |
| 149 | Physical AI Smart Spaces: A Large-Scale Benchmark for Multi-Camera 3D Perception in Smart Spaces | arXiv 2026 | paper | [2610.02580](https://arxiv.org/abs/2610.02580) | 15:59 | [link](https://www.bilibili.com/video/BV139p36LEoA) |
| 150 | WorldScore: A Unified Evaluation Benchmark for World Generation | arXiv 2025 | paper | [2504.00983](https://arxiv.org/abs/2504.00983) | 20:42 | [link](https://www.bilibili.com/video/BV1yogL61EXT) |
| 151 | SCION: Scene Composition with Instanced Neural Primitives | arXiv 2026 | paper | [2610.02322](https://arxiv.org/abs/2610.02322) | 15:39 | [link](https://www.bilibili.com/video/BV1G9p36LEzH) |
| 152 | SLAM-Former: Putting SLAM into One Transformer | ECCV 2026 | paper | [2509.16909](https://arxiv.org/abs/2509.16909) | 13:42 | [link](https://www.bilibili.com/video/BV1Peg56kEE6) |
| 153 | RoboGSim: A Real2Sim2Real Robotic Gaussian Splatting Simulator | arXiv 2024 | paper | [2411.11839](https://arxiv.org/abs/2411.11839) | 16:55 | [link](https://www.bilibili.com/video/BV1rpg762EQE) |
| 154 | Less Context, Better Geometry: Masked Geometric Encoder for Robust 3D Foundation Models | arXiv 2026 | paper | [2610.06813](https://arxiv.org/abs/2610.06813) | 13:59 | [link](https://www.bilibili.com/video/BV1hLp363Eja) |
| 155 | VGGT-CAD: Reconstructing Parametric CAD 3D Model with Geometric Grounding | arXiv 2026 | paper | [2609.21225](https://arxiv.org/abs/2609.21225) | 15:45 | [link](https://www.bilibili.com/video/BV1umhp6tEco) |
| 156 | Generating Multi-view Adversarial Examples for Visual Geometry Grounded Transformer | arXiv 2026 | paper | [2608.20748](https://arxiv.org/abs/2608.20748) | 18:50 | [link](https://www.bilibili.com/video/BV1EShG6jEej) |
| 157 | PRG-Fusion: Orchestrating Generative Priors with Reconstruction Evidence for Driving View Synthesis | arXiv 2026 | paper | [2609.06948](https://arxiv.org/abs/2609.06948) | 15:29 | [link](https://www.bilibili.com/video/BV1xRYN62EDC) |
| 158 | ReViV: Reconstructing the Viewer and the View in 4D from Monocular Egocentric Video | arXiv 2026 | paper | - | 14:43 | [link](https://www.bilibili.com/video/BV1jugj6qESP) |
| 159 | VGGT-Diff: Visual Geometry Meets Diffusion for Sparse-View Novel View Synthesis | arXiv 2026 | paper | [2609.33253](https://arxiv.org/abs/2609.33253) | 15:39 | [link](https://www.bilibili.com/video/BV1bopu6vE6e) |
| 160 | VDGS: Visibility-Driven Large-Scale 3D Gaussian Splatting for Aerial Scene Reconstruction | arXiv 2026 | paper | [2609.23049](https://arxiv.org/abs/2609.23049) | 13:32 | [link](https://www.bilibili.com/video/BV1xXhC6yEFH) |
| 161 | SceneEval: Evaluating Semantic Coherence in Text-Conditioned 3D Indoor Scene Synthesis | WACV 2026 Oral | paper | - | 15:42 | [link](https://www.bilibili.com/video/BV1Yrg76eEM2) |
| 162 | CODA: Depth-Aligned Scene Completion and Object Decomposition from a Single RGB-D Image | arXiv 2026 | paper | [2609.25654](https://arxiv.org/abs/2609.25654) | 15:38 | [link](https://www.bilibili.com/video/BV1Rdh26uECW) |
| 163 | DepthLab: From Partial to Complete | arXiv 2024 | paper | [2412.18153](https://arxiv.org/abs/2412.18153) | 14:38 | [link](https://www.bilibili.com/video/BV1QHtN66Er6) |
| 164 | Chat-Edit-3D++: Interactive 3D and 4D Scene Editing via Large Language Models | arXiv 2026 | paper | [2608.29137](https://arxiv.org/abs/2608.29137) | 15:41 | [link](https://www.bilibili.com/video/BV1J8t769EGt) |
| 165 | Open-Vocabulary Functional 3D Scene Graphs for Real-World Indoor Spaces | CVPR 2025 | paper | - | 15:28 | [link](https://www.bilibili.com/video/BV1B8gL6PEcc) |
| 166 | Structured 3D Latents for Scalable and Versatile 3D Generation | CVPR Spotlight 2025 | paper | - | 16:29 | [link](https://www.bilibili.com/video/BV1GxgE6eEwe) |
| 167 | Universal Scene Graph Generation | CVPR 2025 | paper | - | 18:32 | [link](https://www.bilibili.com/video/BV1ohgL6YE5Y) |
| 168 | G3AR: Graph-Guided Neural Visual Geometry for Scalable Multi-Sequence Aerial Registration | arXiv 2026 | paper | [2609.16603](https://arxiv.org/abs/2609.16603) | 15:25 | [link](https://www.bilibili.com/video/BV1YfeM6vEZK) |
| 169 | HIGS: Hierarchical Implicit Grids for Joint Geometric and Semantic Scene Understanding | arXiv 2026 | paper | [2609.38620](https://arxiv.org/abs/2609.38620) | 15:40 | [link](https://www.bilibili.com/video/BV1NTpG6iEtX) |
| 170 | Beyond Relative Geometry: Metric-Aware Geometry Perception for Robotics | arXiv 2026 | paper | [2608.27497](https://arxiv.org/abs/2608.27497) | 15:23 | [link](https://www.bilibili.com/video/BV1Eitg6iEQ1) |
| 171 | SceneHI: High-Resolution 3D-Consistent Scene Texturing with Controllable Illumination | arXiv 2026 | paper | [2609.10363](https://arxiv.org/abs/2609.10363) | 15:15 | [link](https://www.bilibili.com/video/BV1WPeG6ZEgE) |
| 172 | NAMVIS: Next-Scale Autoregressive Multi-View Image Synthesis | arXiv 2026 | paper | [2610.04722](https://arxiv.org/abs/2610.04722) | 15:44 | [link](https://www.bilibili.com/video/BV1nSph6SEXn) |
| 173 | M2Depth: Unifying Monocular Depth Foundation Priors with Multi-View Stereo | arXiv 2026 | paper | [2608.20788](https://arxiv.org/abs/2608.20788) | 15:35 | [link](https://www.bilibili.com/video/BV1j5hG6gEPy) |
| 174 | ARROW: Arbitrary Reconstruction and Tracking of 4D Observations in the Wild | arXiv 2026 | paper | [2610.01314](https://arxiv.org/abs/2610.01314) | 17:13 | [link](https://www.bilibili.com/video/BV1v1p36DEio) |
| 175 | ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes | CVPR 2017 | paper | [1702.04405](https://arxiv.org/abs/1702.04405) | 15:44 | [link](https://www.bilibili.com/video/BV1sog76WEaK) |
| 176 | RayZer: A Self-supervised Large View Synthesis Model | ICCV 2025 | paper | [2505.00702](https://arxiv.org/abs/2505.00702) | 16:12 | [link](https://www.bilibili.com/video/BV1ivg76BEyo) |
| 177 | RIGOR: Rig-Informed Geometry for Omnidirectional Reconstruction | arXiv 2026 | paper | [2609.13504](https://arxiv.org/abs/2609.13504) | 14:55 | [link](https://www.bilibili.com/video/BV1Vnec67EzF) |
| 178 | Scalix: Uncertainty-Aware Scale-Consistent Monocular SLAM | arXiv 2026 | paper | [2608.17553](https://arxiv.org/abs/2608.17553) | 15:01 | [link](https://www.bilibili.com/video/BV13KbZ6xETb) |
| 179 | LEGO-Anything: Coding Agents for 3D Scene Reconstruction | arXiv 2026 | paper | [2609.36380](https://arxiv.org/abs/2609.36380) | 15:06 | [link](https://www.bilibili.com/video/BV17Jpg6SER3) |
| 180 | Reconstructing Humans and Objects in Interaction using Large Reconstruction Models | arXiv 2026 | paper | [2608.27407](https://arxiv.org/abs/2608.27407) | 15:18 | [link](https://www.bilibili.com/video/BV1cqtW6VEZE) |
| 181 | LangStreet: Persistent Language Fields for Anchor-Decoded Street Gaussians | arXiv 2026 | paper | [2609.11616](https://arxiv.org/abs/2609.11616) | 14:51 | [link](https://www.bilibili.com/video/BV1e4Y96FEkk) |
| 182 | GaussianFlowOcc: Sparse and Weakly Supervised Occupancy Estimation using Gaussian Splatting and Temporal Flow | ICCV 2025 | paper | [2502.17288](https://arxiv.org/abs/2502.17288) | 14:42 | [link](https://www.bilibili.com/video/BV1N5gL6LE5z) |
| 183 | OccScene: Semantic Occupancy-based Cross-task Mutual Learning for 3D Scene Generation | IEEE TPAMI 2025 | paper | [2412.11183](https://arxiv.org/abs/2412.11183) | 15:58 | [link](https://www.bilibili.com/video/BV1WbgH6FE81) |
| 184 | WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild | arXiv 2026 | paper | [2608.28240](https://arxiv.org/abs/2608.28240) | 17:07 | [link](https://www.bilibili.com/video/BV1A2tT6AEt2) |
| 185 | DepthEvidence: Unifying Metric Depth Prediction and Geometric Reasoning in Multimodal Language Models | arXiv 2026 | paper | [2609.31103](https://arxiv.org/abs/2609.31103) | 14:31 | [link](https://www.bilibili.com/video/BV11Dpv6vEbX) |
| 186 | PePESeg3D: Perception Prior Enhances Multi-Scale Segmentation for 3D Gaussian Splatting | arXiv 2026 | paper | [2609.28645](https://arxiv.org/abs/2609.28645) | 16:06 | [link](https://www.bilibili.com/video/BV13wpx67ET2) |
| 187 | RoGe: Novel View Synthesis via End-to-End Implicit Reconstruction and Generation | arXiv 2026 | paper | [2609.02847](https://arxiv.org/abs/2609.02847) | 13:10 | [link](https://www.bilibili.com/video/BV1E8tB65EdW) |
| 188 | Learning Global Camera Poses from Noisy View-Graphs for Structure from Motion | arXiv 2026 | paper | [2609.09491](https://arxiv.org/abs/2609.09491) | 15:45 | [link](https://www.bilibili.com/video/BV13AY56VEyD) |
| 189 | PanoGS: Gaussian-based Panoptic Segmentation for 3D Open Vocabulary Scene Understanding | CVPR 2025 | paper | - | 16:18 | [link](https://www.bilibili.com/video/BV123gL6jEtC) |
| 190 | Emergent Multi-View Geometry Through Self-Distillation | arXiv 2026 | paper | [2609.39227](https://arxiv.org/abs/2609.39227) | 14:26 | [link](https://www.bilibili.com/video/BV1yTpG6iEQw) |
| 191 | Per-View Gaussian Predictions Enable Training-Free Distractor Filtering in Feed-Forward 3DGS | arXiv 2026 | paper | [2608.26951](https://arxiv.org/abs/2608.26951) | 15:28 | [link](https://www.bilibili.com/video/BV1rQtn6KEWR) |
| 192 | ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis | IEEE TPAMI 2025 | paper | - | 19:10 | [link](https://www.bilibili.com/video/BV1zggE6yEzt) |
| 193 | OpenGraph: Open-Vocabulary Hierarchical 3D Graph Representation in Large-Scale Outdoor Environments | IEEE RA-L 2024 | paper | [2403.09412](https://arxiv.org/abs/2403.09412) | 18:07 | [link](https://www.bilibili.com/video/BV1hQgJ6vEaT) |
| 194 | MV2GF: Multi-view Pedestrian Detection with a Visual Geometric Foundation Model | arXiv 2026 | paper | [2608.20639](https://arxiv.org/abs/2608.20639) | 14:54 | [link](https://www.bilibili.com/video/BV1BkhM6vEBD) |
| 195 | 4DStreamCtrl: Interactive Video Generation with Online 4D Control | arXiv 2026 | paper | [2608.25479](https://arxiv.org/abs/2608.25479) | 16:08 | [link](https://www.bilibili.com/video/BV1Pt4f6VELm) |
| 196 | Spackle: Completing Large View Single Image NVS with Adaptive Gaussians | arXiv 2026 | paper | [2609.30941](https://arxiv.org/abs/2609.30941) | 15:55 | [link](https://www.bilibili.com/video/BV1Nap461Emi) |
| 197 | SLAMFormer-∞: Infinite SLAM Transformer for Unbounded Frontend and Backend Processing | arXiv 2026 | paper | - | 13:42 | [link](https://www.bilibili.com/video/BV1iMg568EzA) |
| 198 | WildHSR: Metric Feed-Forward 4D People-Scene Reconstruction from a 3D Foundation Model | arXiv 2026 | paper | [2609.29106](https://arxiv.org/abs/2609.29106) | 14:54 | [link](https://www.bilibili.com/video/BV1Vepv6jEvF) |
| 199 | RIDE: Relocalization-Informed Depth Estimation with 3D Gaussian Splatting | arXiv 2026 | paper | [2609.11079](https://arxiv.org/abs/2609.11079) | 16:20 | [link](https://www.bilibili.com/video/BV1ZiYD6xEZC) |
| 200 | Track, Articulate, Act: Generating Articulation from Casual Human Videos | arXiv 2026 | paper | [2609.19119](https://arxiv.org/abs/2609.19119) | 14:14 | [link](https://www.bilibili.com/video/BV1tSeC6tEbD) |
| 201 | ActiveLang: Active Open-Vocabulary 3D Mapping with Semantic-Uncertainty-Guided Exploration | arXiv 2026 | paper | [2610.09518](https://arxiv.org/abs/2610.09518) | 13:58 | [link](https://www.bilibili.com/video/BV1nCp46ME7o) |
| 202 | Can Video Diffusion Model Reconstruct 4D Geometry? | arXiv 2025 | paper | [2503.21082](https://arxiv.org/abs/2503.21082) | 17:03 | [link](https://www.bilibili.com/video/BV12XgL6EEEm) |
| 203 | Lucida: Parse, Generate, and Place for Composable Real-to-Sim Scene Modeling | arXiv 2026 | paper | [2608.30821](https://arxiv.org/abs/2608.30821) | 14:58 | [link](https://www.bilibili.com/video/BV1vHtn6dEmq) |
| 204 | FunArt: Decoding Functional Structure and Articulation from Generative 3D Latents | arXiv 2026 | paper | [2609.20673](https://arxiv.org/abs/2609.20673) | 15:27 | [link](https://www.bilibili.com/video/BV1P8e46TEMT) |
| 205 | CADSplat: Sparse-View 3D Gaussian Splatting Aided by CAD Models for Robust, Photorealistic Digital-Twin Reconstruction | arXiv 2026 | paper | [2609.18473](https://arxiv.org/abs/2609.18473) | 17:06 | [link](https://www.bilibili.com/video/BV1K9eC6REWx) |
| 206 | AMB3R-SLAM: Kilometer-scale SLAM with Hierarchical Backend | arXiv 2026 | paper | [2609.19518](https://arxiv.org/abs/2609.19518) | 15:18 | [link](https://www.bilibili.com/video/BV1fze46FEjf) |
| 207 | Scenethesis: A Language and Vision Agentic Framework for 3D Scene Generation | arXiv 2025 | paper | [2505.02836](https://arxiv.org/abs/2505.02836) | 17:24 | [link](https://www.bilibili.com/video/BV1Y6g76NEkF) |
| 208 | Lens3D: Target-Conditioned Visual Foveation for Fine-Grained 3D Understanding | arXiv 2026 | paper | [2610.06611](https://arxiv.org/abs/2610.06611) | 15:26 | [link](https://www.bilibili.com/video/BV19gp36yEVx) |
| 209 | OREO: Fidelity Alignment in 3D Generation via On-the-fly Rendering-Editing Optimization | arXiv 2026 | paper | [2609.29788](https://arxiv.org/abs/2609.29788) | 15:13 | [link](https://www.bilibili.com/video/BV16Sh265EAU) |
| 210 | NeRFifyMesh: Optimizing Neural Radiance Fields from Textured Meshes for Robotics Scene Building | arXiv 2026 | paper | [2610.10387](https://arxiv.org/abs/2610.10387) | 15:28 | [link](https://www.bilibili.com/video/BV1QApt6WE18) |
| 211 | Argos: Adapt Rich Geometric Priors for Generalizable Online Scene-Change-Detection | arXiv 2026 | paper | [2610.10181](https://arxiv.org/abs/2610.10181) | 15:15 | [link](https://www.bilibili.com/video/BV1cspt6gEbH) |
| 212 | WeaveRL: Weaving Reconstruction into Scene-Aware Fabrics for Perceptive Reinforcement Learning | arXiv 2026 | paper | [2609.18685](https://arxiv.org/abs/2609.18685) | 15:02 | [link](https://www.bilibili.com/video/BV1Wpe169E4L) |
| 213 | Lyra 2.0: Explorable Generative 3D Worlds | arXiv 2026 | paper | [2604.13036](https://arxiv.org/abs/2604.13036) | 17:04 | [link](https://www.bilibili.com/video/BV1w68B6sES3) |
| 214 | CoANeRV: Coordinate-Aware Token-Space Neural Video Representation | arXiv 2026 | paper | - | 22:20 | [link](https://www.bilibili.com/video/BV1B1br69Eou) |
| 215 | UVGS: Reimagining Unstructured 3D Gaussian Splatting using UV Mapping | CVPR 2025 | paper | [2502.01846](https://arxiv.org/abs/2502.01846) | 18:35 | [link](https://www.bilibili.com/video/BV1regH6REwW) |
| 216 | CoMVS-GS: Collaborative Multi-View Stereo and 3D Gaussian Splatting for Surface Reconstruction | arXiv 2026 | paper | [2608.18413](https://arxiv.org/abs/2608.18413) | 15:26 | [link](https://www.bilibili.com/video/BV1YY8q6gEf3) |
| 217 | Seeing the World and the Self from Egocentric Video | arXiv 2026 | paper | [2609.01276](https://arxiv.org/abs/2609.01276) | 15:26 | [link](https://www.bilibili.com/video/BV1zFtd6ZES1) |
| 218 | GenIA: Generative Reconstruction with Test-Time Input Alignment | arXiv 2026 | paper | [2610.12388](https://arxiv.org/abs/2610.12388) | 15:40 | [link](https://www.bilibili.com/video/BV1k9pv6YEXg) |
| 219 | DecoGS: Adaptive Static-Dynamic Decoupling of 3D Gaussians for Free-Viewpoint Video Streaming | arXiv 2026 | paper | [2609.17230](https://arxiv.org/abs/2609.17230) | 15:59 | [link](https://www.bilibili.com/video/BV11YeM6HEnU) |
| 220 | OuroWorld: Bringing Any 3D World Alive as Diverse, Endlessly Looping 3D Cinemagraphs | arXiv 2026 | paper | [2610.12461](https://arxiv.org/abs/2610.12461) | 14:55 | [link](https://www.bilibili.com/video/BV1Rupe6CEg3) |
| 221 | Tetris3D: 3D Scene Generation With Objects That Fit Together | arXiv 2026 | paper | [2610.10539](https://arxiv.org/abs/2610.10539) | 15:26 | [link](https://www.bilibili.com/video/BV16Cp46MED4) |
| 222 | Pyramid Diffusion for Fine 3D Large Scene Generation | ECCV 2024 | paper | [2311.12085](https://arxiv.org/abs/2311.12085) | 16:33 | [link](https://www.bilibili.com/video/BV1dogj6eEA7) |
| 223 | M3GD: Multi-Modal Multi-View Geometric Diffusion for Camera--LiDAR Novel View Synthesis | arXiv 2026 | paper | [2609.30056](https://arxiv.org/abs/2609.30056) | 15:24 | [link](https://www.bilibili.com/video/BV1oDh26kEzU) |
| 224 | Dyna3: VLM-Guided Training-Free 4D Reconstruction via Depth Foundation Models | arXiv 2026 | paper | [2610.01286](https://arxiv.org/abs/2610.01286) | 17:08 | [link](https://www.bilibili.com/video/BV1j1p36DEh9) |
| 225 | GenNVS: Geometry-enhanced Novel View Synthesis via Disentangled 3D Prior | arXiv 2026 | paper | [2609.34579](https://arxiv.org/abs/2609.34579) | 15:33 | [link](https://www.bilibili.com/video/BV1ofph6kEJP) |
| 226 | Concept-Guided Exploration: Building Persistent, Actionable Scene Graphs | arXiv 2026 | paper | [2608.23650](https://arxiv.org/abs/2608.23650) | 16:14 | [link](https://www.bilibili.com/video/BV184hA6gEGs) |
| 227 | DensiTok: Making Feed-Forward 3D Gaussian Splatting See More Views Than It Is Given | arXiv 2026 | paper | [2610.07958](https://arxiv.org/abs/2610.07958) | 14:02 | [link](https://www.bilibili.com/video/BV1pYp36fEHT) |
| 228 | AdaOcc: Adaptive 3D Occupancy Prediction for Embodied Tasks | arXiv 2026 | paper | [2609.38864](https://arxiv.org/abs/2609.38864) | 15:44 | [link](https://www.bilibili.com/video/BV1SrpG6GEBr) |
| 229 | Stabilizing Camera-Controlled Novel View Synthesis at Inference Time | arXiv 2026 | paper | [2609.03639](https://arxiv.org/abs/2609.03639) | 15:42 | [link](https://www.bilibili.com/video/BV1h5bE62E6D) |

## Per entry (with Chinese summary)

- **SPVC: Structured and Panoptic Video Fixing for Cross-Dataset Driving Scene Rendering** - arXiv 2026 | [arXiv:2608.17420](https://arxiv.org/abs/2608.17420) | [project](https://li00147.github.io/SPVC-Project-Page/) | [B station](https://www.bilibili.com/video/BV11cbf6mE1e)
  - SPVC 用跨数据集伪影感知配对数据训练两阶段可控视频扩散模型，同时修复背景新视角渲染和前景车辆插入伪影。
- **OmniAct3D: Leveraging Foundation Geometry and Evidence-Grounded Reasoning for Panoramic 3D Detection** - arXiv 2026 | [arXiv:2610.03015](https://arxiv.org/abs/2610.03015) | [B station](https://www.bilibili.com/video/BV1vUp36UE5m)
  - 用全景几何适配、证据扎根推理和局部朝向专家，把透视训练的视觉基础模型迁移到单幅等距柱状图三维检测。
- **Manifold4D: Denoising on Point Cloud Rendered Manifolds for Video Re-shooting** - arXiv 2026 | [arXiv:2608.28174](https://arxiv.org/abs/2608.28174) | [B station](https://www.bilibili.com/video/BV1yrtT6vEVJ)
  - 把目标视角的点云渲染注入 flow matching 初始噪声，让几何只被信任一次；去噪阶段只保留源视频作为视觉条件。
- **Tele360: Real-Time Feed-Forward Human Reconstruction from Sparse Unposed Cameras** - arXiv 2026 | [arXiv:2609.15032](https://arxiv.org/abs/2609.15032) | [B station](https://www.bilibili.com/video/BV17Lec6DEnf)
  - 用 4--6 路无姿态 RGB 视频，前馈预测相机和像素对齐的 3D Gaussian maps，再以视频编解码支持远端自由视点渲染。
- **VS-Splat: Voxel-Selective feed-forward Gaussian Splatting for end-to-end 3D object reconstruction from sparse-views** - arXiv 2026 | [arXiv:2609.12343](https://arxiv.org/abs/2609.12343) | [B station](https://www.bilibili.com/video/BV15GeJ6iELz)
  - 从四张稀疏视图出发，学习选择物体体素，并只在选中体素内生成密集的细粒度高斯基元。
- **Habitat-GS: A High-Fidelity Navigation Simulator with Dynamic Gaussian Splatting** - arXiv 2026 | [arXiv:2604.12626](https://arxiv.org/abs/2604.12626) | [B station](https://www.bilibili.com/video/BV1Fr8B69End)
  - 用 3DGS 提升仿真视觉，用可驱动的高斯头像表达动态人类，再用代理胶囊把视觉实体接入导航碰撞。
- **UniDynamics: Event-RGB Fusion for Unified Future 4D Dynamic Scene Generation** - arXiv 2026 | [arXiv:2610.03473](https://arxiv.org/abs/2610.03473) | [B station](https://www.bilibili.com/video/BV1Rmp36JEA6)
  - 以事件流提供初始运动先验，以 RGB 提供外观参照，再用深度与光流约束扩散式未来场景生成。
- **GeoFF3D: Coordinate-Anchored Feed-Forward Reconstruction for Large-Scale UAV Mapping** - arXiv 2026 | [arXiv:2608.28288](https://arxiv.org/abs/2608.28288) | [B station](https://www.bilibili.com/video/BV1Untg62E3M)
  - 用近似地理位置直接定义预测坐标系，再用空间分块、先中心后外围的推理顺序和保持重力方向的层次聚合，完成大规模 UAV 三维重建。
- **CrossDepth: Geometry-Constrained Attention for Generalizable Multi-View Surround Depth Estimation** - arXiv 2026 | [B station](https://www.bilibili.com/video/BV1WAbV6SEou)
  - 用逐像素相机射线嵌入处理内参差异，用共享柱面上的几何约束跨图注意力扩展上下文，并用多种光度一致性实现无深度标签训练。
- **Zero-Shot Novel Depth Synthesis Using 3D Foundation Models Scene Representations** - arXiv 2026 | [arXiv:2609.04174](https://arxiv.org/abs/2609.04174) | [project](https://akola-mbey-denis.github.io/Z3D-page) | [B station](https://www.bilibili.com/video/BV1uubW6xEtX)
  - 用冻结的三维基础模型表征作为几何潜空间，通过姿态条件扩散生成未观测视角的深度。
- **AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction** - arXiv 2026 | [B station](https://www.bilibili.com/video/BV1iD8S6jExT)
  - 用水下适配的三维几何先验稳住跟踪，用介质感知初始化和混合场景表示提升流式重建。
- **OmniPoint: Universal Monocular Metric Pointcloud from Any Camera** - arXiv 2026 | [arXiv:2609.09394](https://arxiv.org/abs/2609.09394) | [project](https://botaoye.github.io/omnipoint/) | [B station](https://www.bilibili.com/video/BV1fUYV6XEv5)
  - 用 camera-agnostic 的 Ray+D 表示，把相机投影几何与场景结构分开学习。
- **OpenOcc: Open Vocabulary 3D Scene Reconstruction via Occupancy Representation** - IROS 2024 | [arXiv:2403.11796](https://arxiv.org/abs/2403.11796) | [project](https://doi.org/10.1109/IROS58592.2024.10801860) | [B station](https://www.bilibili.com/video/BV1DKg76tECf)
  - 用同一套 occupancy neural field 同时承载几何表面与开放词汇语言特征，并用 SCP 抑制跨视角语义噪声。
- **LT-Mem: Volatility-Aware Spatio-Temporal Memory for Lifelong Scene Understanding** - arXiv 2026 | [arXiv:2608.19059](https://arxiv.org/abs/2608.19059) | [B station](https://www.bilibili.com/video/BV1hq8q6qEDv)
  - 用波动性感知的三重记忆，跨会话保存物体身份、状态变化与长期统计，从而回答纵向时空问题。
- **Info3R: Information-Adaptive Test-Time Training for 3D Reconstruction** - arXiv 2026 | [arXiv:2609.21938](https://arxiv.org/abs/2609.21938) | [B station](https://www.bilibili.com/video/BV1M1hp6fEiS)
  - 用逐帧重要性控制状态写入，用信息驱动的重置恢复状态可塑性，并以坐标链保持长序列全局几何。
- **RoboOcc: Enhancing the Geometric and Semantic Scene Understanding for Robots** - arXiv 2025 | [arXiv:2504.14604](https://arxiv.org/abs/2504.14604) | [B station](https://www.bilibili.com/video/BV1yJg76UEM4)
  - 将 opacity 与椭球 geometry 前移到 Gaussian query 更新过程，缓解重叠语义歧义并细化室内几何建模。
- **Scene Retargeting: Learning Object Placement with Analogical Transfer** - arXiv 2026 | [arXiv:2609.36801](https://arxiv.org/abs/2609.36801) | [B station](https://www.bilibili.com/video/BV1m1pG6zEiP)
  - 用功能簇、三维基础特征和类比优化，把一个参考房间的空间组织迁移到不同目标房间。
- **TAPVid-MV: A Benchmark for Tracking Any Point in 3D Across Multiple Views** - arXiv 2026 | [arXiv:2609.01899](https://arxiv.org/abs/2609.01899) | [project](https://tapvidmv.github.io) | [B station](https://www.bilibili.com/video/BV1nZte6zEJD)
  - 用同步多视角、运动相机和共享三维世界坐标，系统评估任意物理点的长期跟踪，并把跟踪误差与几何重建误差拆开分析。
- **Query Rewriting for Complex Object Segmentation in 4D Gaussian Representations** - arXiv 2026 | [arXiv:2609.02664](https://arxiv.org/abs/2609.02664) | [B station](https://www.bilibili.com/video/BV1note6gE91)
  - 通过 training-free 的多级 query rewriting，去除叙事查询中的语言噪声，让文本 embedding 更贴合 object-centric 4D Gaussian 表示。
- **PanSplat: 4K Panorama Synthesis with Feed-Forward Gaussian Splatting** - CVPR 2025 | [arXiv:2412.12096](https://arxiv.org/abs/2412.12096) | [project](https://openaccess.thecvf.com/content/CVPR2025/html/Zhang_PanSplat_4K_P) | [B station](https://www.bilibili.com/video/BV1oXgj6TEr3)
  - 从两张宽基线全景图直接预测球面 3D Gaussian 金字塔，在单张 A100 上训练到 4K。
- **LumiTokens: 3D Relighting via Token-Space Lighting Transformation** - arXiv 2026 | [arXiv:2608.18215](https://arxiv.org/abs/2608.18215) | [project](https://neu-vi.github.io/LumiTokens/) | [B station](https://www.bilibili.com/video/BV1oR8M6aEYm)
  - LumiTokens 将 3D 重光照改写为潜在场景 token 的直接变换，用统一的光线 token 接入多种光源，并支持逐步、可组合的光照编辑。
- **OmniCam: Omni-Camera Trajectory Generation via Geometry-Grounded Pose Token Learning** - arXiv 2026 | [arXiv:2610.09513](https://arxiv.org/abs/2610.09513) | [project](https://zhenyangliu.github.io/OmniCam-Website/) | [B station](https://www.bilibili.com/video/BV1NVpt6mEDp)
  - 从单张全景图和文字轨迹描述生成具有空间感知能力的 相机位姿序列。
- **NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction** - arXiv 2026 | [arXiv:2608.22888](https://arxiv.org/abs/2608.22888) | [B station](https://www.bilibili.com/video/BV14G8D6wECK)
  - 用几何估计、动态语义分离和物理介质建模，把退化且充满运动目标的水下视频直接变成可渲染的四维高斯场景。
- **InceptionGS: Generative Bootstrapping for Large-Scale Gaussian Splatting under Unstructured View Sampling** - arXiv 2026 | [arXiv:2609.02747](https://arxiv.org/abs/2609.02747) | [B station](https://www.bilibili.com/video/BV1fktv6BEcD)
  - 用场景几何适应生成先验，再以光度融合和视角自适应采样软性更新 3DGS。
- **Building Rome from a Single Image** - arXiv 2026 | [arXiv:2610.08790](https://arxiv.org/abs/2610.08790) | [B station](https://www.bilibili.com/video/BV11sp36NEhJ)
  - 用自适应场景分块、显式二维到三维条件和室外合成数据，把物体级三维生成先验扩展到完整场景网格。
- **Joint-Embedding Prediction of Masked Point Tubes for Self-Supervised Learning on 4D Point Cloud Videos** - arXiv 2026 | [arXiv:2608.24093](https://arxiv.org/abs/2608.24093) | [B station](https://www.bilibili.com/video/BV12Rhw6wEoM)
  - 在 4D 点云视频中，用可见点管上下文预测被遮挡点管的潜在表示，并用 SIGReg 稳定训练。
- **Self-Geometry: GT-Free and Plug-and-Play Test-Time Adaptation for Geometrically Consistent 3D Vision Foundation Models** - arXiv 2026 | [B station](https://www.bilibili.com/video/BV1VL8P6CEkD)
  - 用测试时提取的 2D 像素对应作为 pseudo-GT，配合显式多视图几何约束与轻量 LoRA 适配，让冻结 VFM 在目标场景中恢复更一致的姿态与几何。
- **DecomVoxel: Harnessing 3D-Native Priors with Guided In-situ Denoising Optimization for Decompositional Scene Reconstruction** - arXiv 2026 | [arXiv:2610.01914](https://arxiv.org/abs/2610.01914) | [B station](https://www.bilibili.com/video/BV1nip36oEk6)
  - 在场景坐标中优化三维原生先验，并以占据与空闲空间锚点抑制漂移和幻觉，得到结构完整、纹理一致的分解式重建。
- **FIRE3D: Feed-forward Interactive 3D Scene Reconstruction Within A Minute** - arXiv 2026 | [arXiv:2609.08848](https://arxiv.org/abs/2609.08848) | [project](https://xiahongchi.github.io/Fire3D) | [B station](https://www.bilibili.com/video/BV1dEYK6FEAx)
  - 从未分割的 RGB 捕获出发，前馈地预测对象级位姿、完整几何和纹理，并在一分钟内组装成可交互场景。
- **IRIS: Implicit Rendering Matters for Pose-Free Novel View Synthesis** - arXiv 2026 | [arXiv:2609.18034](https://arxiv.org/abs/2609.18034) | [project](https://leo-frank.github.io/IRIS/) | [B station](https://www.bilibili.com/video/BV1r2ey6EEqq)
  - 用自预测相机约束潜在神经场的查询与光线渲染，在无姿态监督下兼顾新视角质量与相机几何。
- **CGGT: Curve-Grounded Geometry Transformer for 3D Parametric Curve Reconstruction** - arXiv 2026 | [arXiv:2609.14521](https://arxiv.org/abs/2609.14521) | [project](https://zhirui-gao.github.io/cggt/) | [B station](https://www.bilibili.com/video/BV1B3ec6WEMj)
  - 用几何感知的曲线 grounding 连接稀疏多视角图像与紧凑、可编辑的三维 CAD wireframe。
- **SGFormer: Satellite-Ground Fusion for 3D Semantic Scene Completion** - CVPR 2025 | [arXiv:2503.16825](https://arxiv.org/abs/2503.16825) | [project](https://github.com/gxytcrc/SGFormer) | [B station](https://www.bilibili.com/video/BV1tDg76tEUc)
  - 以卫星俯视的全局布局补足地面相机遮挡，再用地面特征校正与自适应融合守住局部几何和动态细节。
- **Adaptive World Memory 3D Foundation Model for Scalable 3D Mapping, Localization, and Rendering** - arXiv 2026 | [arXiv:2609.21502](https://arxiv.org/abs/2609.21502) | [B station](https://www.bilibili.com/video/BV1txhk65E72)
  - 用双阶段自适应世界记忆连接三维几何、可渲染高斯地图和大尺度 SLAM。
- **Scaling 3D Generative Priors to Large-Scale Scene Meshes from Multi-View Images** - arXiv 2026 | [arXiv:2609.06385](https://arxiv.org/abs/2609.06385) | [B station](https://www.bilibili.com/video/BV1EhYN6AEbf)
  - 以 TRELLIS2 为三维先验，通过自适应分块、局部上下文生成和全局外观对齐，从多视图图像生成连贯的大规模纹理场景网格。
- **学习用于 4D 重建的结构化运动几何** - arXiv:2607.22534 2026 | [B station](https://www.bilibili.com/video/BV1TsGP6dETR)
  - SM4RT 不再逐点预测无约束位移，而是用共享的 SE(3) motion bases 与时序不变的 assignment map 表示“哪些点一起动、它们如何动”。
- **OpenSplatGraph: From Dense Semantic Maps to Structured Scene Graphs for Open-Vocabulary Robot Perception** - arXiv 2026 | [arXiv:2610.07569](https://arxiv.org/abs/2610.07569) | [B station](https://www.bilibili.com/video/BV1nYp36fEaQ)
  - 用 reliability-aware semantic field 从稠密地图按查询提取物体，再以持久身份累积为可推理的三维场景图。
- **HARMONY: Hierarchical Agentic Reasoning for MONocular Image-to-Scene Synthesis** - arXiv 2026 | [arXiv:2609.26793](https://arxiv.org/abs/2609.26793) | [project](https://cwchenwang.github.io/harmony) | [B station](https://www.bilibili.com/video/BV1Aqps6eEG8)
  - 以空房间和校准相机为骨架，用 VLM 规划对象关系，再用图像空间与点云几何证据逐对象修正，生成可渲染、可交互的室内三维场景。
- **Memory Tree Guided Key Frame Querying for Efficient 3D Question Answering** - arXiv 2026 | [arXiv:2608.18009](https://arxiv.org/abs/2608.18009) | [project](https://github.com/hsiangwei0903/MemTree3D) | [B station](https://www.bilibili.com/video/BV1GKbZ6xEp8)
  - 用一次构建的 MemTree3D 让 LLM 先做空间—时间检索，再把少量关键帧交给 VLM，从而减少逐查询的全视频视觉搜索。
- **GaussVid: Sparse-View Gaussian Splatting with 3D-Aware Video Diffusion Priors** - arXiv 2026 | [B station](https://www.bilibili.com/video/BV12V8D6hE8r)
- **Guiding Image-to-3D Generation with Test-Time Partial Observations** - arXiv 2026 | [arXiv:2609.10531](https://arxiv.org/abs/2609.10531) | [B station](https://www.bilibili.com/video/BV1tTY566EvD)
  - 不改动预训练图像到三维模型，在采样过程中用部分几何观测的射线一致性似然修正速度场。
- **LVSPM: Long Sequence View Synthesis and Pose Estimation Model** - arXiv 2026 | [arXiv:2610.10960](https://arxiv.org/abs/2610.10960) | [B station](https://www.bilibili.com/video/BV1cBpi6YEUM)
  - 从无标定的长序列图像中，联合预测世界对齐的相机参数与新视角 RGB 图像，并在 16--256 个输入视图上保持可扩展性能。
- **SAMV-DUSt3R: Instance-Centric 3D Scene Decoupling from Sparse Multi-Views** - arXiv 2026 | [arXiv:2609.11279](https://arxiv.org/abs/2609.11279) | [B station](https://www.bilibili.com/video/BV1UXYD6yECx)
  - 用 prompt 指定目标实例，把 2D 掩码直接注入 MV-DUSt3R，并用空间排序选择更可靠的参考视图，从稀疏 RGB 视图得到目标对象的 3D 点图与置信度。
- **Puffin-World: Scaling a Unified Multimodal Model with Native 3D World States** - arXiv 2026 | [arXiv:2609.04196](https://arxiv.org/abs/2609.04196) | [project](https://kangliao929.github.io/projects/puffin-world/) | [B station](https://www.bilibili.com/video/BV1GKbW6tEFM)
  - 用物理锚定的相机条件，把相机理解、自由视点生成、三维世界生成与重建统一到同一个多模态模型中。
- **MegaParts: Scaling Part-Aware 3D Object Generation to 300 Parts via Token-Efficient Autoregressive Modeling** - arXiv 2026 | [arXiv:2608.14783](https://arxiv.org/abs/2608.14783) | [project](https://expmaster.github.io/megapar) | [B station](https://www.bilibili.com/video/BV1yv876TE2h)
  - 用自适应长度的离散部件表示压缩几何，再以长上下文自回归模型统一生成布局、部件框与局部形状。
- **PlenoCI: Plenoptic CharacterIstics for View Dependence Aware Change Classification** - arXiv 2026 | [arXiv:2609.28930](https://arxiv.org/abs/2609.28930) | [B station](https://www.bilibili.com/video/BV18sp46nEPo)
  - 用五维 plenoptic field 的解析结构，识别变化并区分 geometric change 与 appearance change，同时降低独立 3DGS 重建带来的误报。
- **TrackEverything: Long Horizon Dense Tracking via De-Duplicating 3D Scene Representations** - arXiv 2026 | [arXiv:2609.30222](https://arxiv.org/abs/2609.30222) | [project](https://trackeverything.github.io/) | [B station](https://www.bilibili.com/video/BV1A8pa6pEvS)
  - 在世界坐标中维护会跨窗口延续、并在空间上去重的三维点轨迹，使所有可见点的长视频跟踪不再随帧数线性膨胀。
- **Luce: Relightable Gaussians for 3D Asset Generation** - arXiv 2026 | [arXiv:2608.23943](https://arxiv.org/abs/2608.23943) | [B station](https://www.bilibili.com/video/BV1rwhA64ECf)
  - 用多模态 PBR 高斯云和统一潜变量，从单张图像生成可重光照、可导出网格的三维资产。
- **DynStream: Online Streaming 4D Gaussian Reconstruction of Dynamic Worlds from Unposed Video** - arXiv 2026 | [arXiv:2610.09720](https://arxiv.org/abs/2610.09720) | [B station](https://www.bilibili.com/video/BV1F2p46KEnd)
  - 从连续、无位姿、包含动态内容的视频流中，增量构建可渲染且全局一致的 4D Gaussian 场景。
- **Think Locally, Refine Globally for Memory-Efficient 3D Reconstruction** - arXiv 2026 | [arXiv:2609.21437](https://arxiv.org/abs/2609.21437) | [B station](https://www.bilibili.com/video/BV1H5hn6GE1Z)
  - LoG-VGGT 用有界记忆的局部窗口传播时间信息，再用紧凑 register token 做全局相机一致性修正。
- **TopoSurfel: Closing the Loop between Gaussian Surfels and Meshes for Surface Reconstruction** - arXiv 2026 | [arXiv:2608.20687](https://arxiv.org/abs/2608.20687) | [B station](https://www.bilibili.com/video/BV1kHhV6WEc4)
  - 以参数无关的可微代理网格把高斯表面元与连续表面连接起来，并用网格几何持续指导表面元演化。
- **AVSplat: Dense-View Feed-Forward 3D Gaussian Splatting with Assist-View Preconditioning** - arXiv 2026 | [arXiv:2609.05925](https://arxiv.org/abs/2609.05925) | [B station](https://www.bilibili.com/video/BV1T9YN67ESr)
  - 在全局聚合前注入相关且互补的辅助视图上下文，并在高占用体素中自适应锐化融合权重，从而恢复密集视角下的正向视角扩展。
- **4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors** - arXiv 2026 | [arXiv:2609.21176](https://arxiv.org/abs/2609.21176) | [B station](https://www.bilibili.com/video/BV1pGhn6yEUK)
  - 用多视角深度融合解决初始化缺失，再用参考引导的视频扩散恢复结果作为伪监督，迭代改进四维高斯表示。
- **Beyond the Image Plane: World-Grounded Queries for Multi-Object Tracking** - arXiv 2026 | [arXiv:2609.00924](https://arxiv.org/abs/2609.00924) | [B station](https://www.bilibili.com/video/BV1x2tR6qEvZ)
  - PLANET 将重建的三维场景几何注入 query 形成，并用长短期双分辨率记忆保留身份线索。
- **Fysiverse-3D-SimReady Technical Report: Agentic Physical Simulation for Pragmatic 3D World Reconstruction** - arXiv 2026 | [arXiv:2609.31715](https://arxiv.org/abs/2609.31715) | [B station](https://www.bilibili.com/video/BV1Kwpg6wE14)
  - 以实例与地面提示为锚点，把独立生成的物体资产校正为共享重力和相机的仿真就绪场景，并由智能体驱动目标条件物理 rollout。
- **InfiniDepth: Arbitrary-Resolution and Fine-Grained Depth Estimation with Neural Implicit Fields** - arXiv 2026 | [arXiv:2601.03252](https://arxiv.org/abs/2601.03252) | [project](https://zju3dv.github.io/InfiniDepth) | [B station](https://www.bilibili.com/video/BV1L58B6GE3T)
  - 用神经隐式场表示深度，在连续二维坐标上进行局部查询，从而兼顾任意分辨率、细粒度几何与大视角新视图合成。
- **Revisiting Local Context for Long-Horizon Streaming 3D Reconstruction** - arXiv 2026 | [arXiv:2608.27529](https://arxiv.org/abs/2608.27529) | [B station](https://www.bilibili.com/video/BV1eTtg64Epo)
  - 用当前帧和前 11 帧的 KV 特征做局部几何估计，再组合相邻位姿恢复超长视频的全局轨迹与点云。
- **Sparse auto-regressive modeling for scene generation from multi-view images** - arXiv 2026 | [arXiv:2609.03931](https://arxiv.org/abs/2609.03931) | [B station](https://www.bilibili.com/video/BV15QbE6HEYG)
  - 在稀疏、无约束的多视图输入下，于稀疏三维潜空间中联合生成未观测区域的几何与外观，并解码为 3D Gaussian Splatting 场景。
- **PASTEL: Panoramic Alignment for Monocular 4D Scene Reconstruction** - arXiv 2026 | [arXiv:2609.06099](https://arxiv.org/abs/2609.06099) | [B station](https://www.bilibili.com/video/BV1TZYN6yEwV)
  - 在全景空间中规划连续扩展轨迹，用受控的生成式先验补齐不可见区域，再以策略监督回写四维场景。
- **The Neverwhere Visual Parkour Benchmark Suite** - arXiv 2026 | [arXiv:2609.16443](https://arxiv.org/abs/2609.16443) | [B station](https://www.bilibili.com/video/BV1KheM69EaE)
  - 用 3D Gaussian Splatting 与高质量碰撞几何，把真实场景转成可重复的闭环视觉跑酷评测环境。
- **StereoGaussians: Feed-Forward 3D Gaussian Splatting from Stereo Images** - arXiv 2026 | [arXiv:2609.38592](https://arxiv.org/abs/2609.38592) | [B station](https://www.bilibili.com/video/BV1uCp56SEss)
  - 用冻结的立体表示锚定度量几何，再用双层高斯和扩展画布学习附近视角中的新内容。
- **UniQuery4R: Unified 4D Scene Reconstruction from a Single Query** - arXiv 2026 | [arXiv:2608.17283](https://arxiv.org/abs/2608.17283) | [project](https://kosmoresearch.github.io/UniQuery4R/) | [B station](https://www.bilibili.com/video/BV1QTbZ6RESt)
  - 对视频片段先统一编码，再用一个连续源像素查询选择源帧与目标帧；同一查询表示同时解码对应关系、目标时刻三维位置和场景流，并额外预测源深度与相机参数。
- **OmniIndoor3D: Comprehensive Indoor 3D Reconstruction** - arXiv 2025 | [arXiv:2505.20610](https://arxiv.org/abs/2505.20610) | [project](https://ucwxb.github.io/OmniIndoor3D/) | [B station](https://www.bilibili.com/video/BV1DUgJ6qEZs)
  - 用统一的 3D Gaussian 表示联合重建室内场景的外观、几何与全景语义。
- **On-the-Fly3R: Towards Robust Online 3D Reconstruction with Feed-Forward 3R Models for Large-Scale UAV Scenarios** - arXiv 2026 | [arXiv:2609.00923](https://arxiv.org/abs/2609.00923) | [B station](https://www.bilibili.com/video/BV1vttR6SEV9)
  - 用检索构造几何相关的局部上下文，用验证、拒绝、重试阻断错误传播，并以位姿图优化恢复全局一致性。
- **Generative Semantic Scene Completion** - arXiv 2026 | [arXiv:2608.26737](https://arxiv.org/abs/2608.26737) | [B station](https://www.bilibili.com/video/BV1HQtn6KEQD)
  - GSSC 用一个离散扩散框架覆盖数据合成、从噪声补全和冻结基线修正；其中 S2D2 以一步修正在 SemanticKITTI hidden test 上达到 38.8\% mIoU。
- **GraphWrit3R: End-to-End 3D Scene Graph Writing** - arXiv 2026 | [arXiv:2609.31595](https://arxiv.org/abs/2609.31595) | [project](https://graphwrit3r.insait.ai) | [B station](https://www.bilibili.com/video/BV1yvp46CER7)
  - 从点云、3D Gaussian Splat 或二者组合出发，在潜空间中联合预测物体与关系，并以结构化 JSON 直接输出完整三维场景图。
- **Generation of High-Level Concepts in 3D Scene Graphs via Autoregressive Diffusion** - arXiv 2026 | [arXiv:2608.28733](https://arxiv.org/abs/2608.28733) | [B station](https://www.bilibili.com/video/BV1izt76mEsF)
  - 从机器人观测的 plane graph 出发，以自回归扩散联合生成结构、语义与三维几何，完成任意深度的层级 3DSG。
- **DistScene: Object-to-Scene Distillation for 3D Scene Generation** - arXiv 2026 | [arXiv:2610.06960](https://arxiv.org/abs/2610.06960) | [project](https://coolbeam.github.io/DistScene/) | [B station](https://www.bilibili.com/video/BV1hVp36kEfW)
  - 将环境作为显式场景组件，与多个对象在共享坐标系中联合生成，再以场景上下文驱动局部对象细化。
- **GrapeSplat: Geometry-Grounded Reconstruction via Amalgamated Pose-Free Encoding for Feed-Forward 3D Gaussian Splatting** - arXiv 2026 | [arXiv:2609.23182](https://arxiv.org/abs/2609.23182) | [B station](https://www.bilibili.com/video/BV1CZhC63Eny)
  - 将多视图几何线索融合到稀疏体素场景中，再从占据体素直接解码全局一致的三维高斯。
- **Representing Long Volumetric Video with Temporal Gaussian Hierarchy** - [B station](https://www.bilibili.com/video/BV1mVg76XEuC)
- **SPOON: Towards Coherent Compositional 3D Scene Generation from Uncalibrated Multi-view Images** - arXiv 2026 | [arXiv:2609.39590](https://arxiv.org/abs/2609.39590) | [B station](https://www.bilibili.com/video/BV1DipG61EeK)
  - 用场景级重建几何协调逐视图姿态，把物体生成、布局选择和相机优化统一到一个连贯的三维场景中。
- **PIVOT: A Multi-Trajectory Dataset and Testbed for Pose, Intrinsics, and Novel Viewpoint Evaluation in Real-World 3D Reconstruction** - arXiv 2026 | [arXiv:2608.25401](https://arxiv.org/abs/2608.25401) | [B station](https://www.bilibili.com/video/BV1E64f6NE8H)
  - 用显式轨迹身份、双重姿态与双重内参，测量三维重建在更接近部署条件时的表现。
- **S2Tok: Streaming 3D Gaussian Reconstruction with Persistent Spatial Tokens** - arXiv 2026 | [arXiv:2610.08978](https://arxiv.org/abs/2610.08978) | [B station](https://www.bilibili.com/video/BV1PJpt6CEzY)
  - 用自适应的持久空间 Token 分离“更新已有场景”和“接纳新区域”，并从当前状态重新解码可渲染的 3D Gaussians。
- **DDMS: Discriminative Distillation of Multi-view Foundational Features into Single-view Models** - arXiv 2026 | [arXiv:2608.23850](https://arxiv.org/abs/2608.23850) | [B station](https://www.bilibili.com/video/BV1fGhA6SE7N)
  - 用多视角几何教师监督单视图学生，在增强三维一致性与局部可区分性的同时保留语义迁移能力。
- **RouteBridge: Reliability-Routed Bidirectional Distillation Between Neural Radiance Fields and 3D Gaussian Splatting** - arXiv 2026 | [arXiv:2609.09606](https://arxiv.org/abs/2609.09606) | [B station](https://www.bilibili.com/video/BV1PBYV6hEbR)
  - 以光线为单位估计两种表示的可靠性，选择 NeRF 教 3DGS、3DGS 教 NeRF，或对不可靠样本 abstain。
- **AgentSTAR: Agentic Shape Tracking and Reconstruction from Monocular Videos** - arXiv 2026 | [arXiv:2609.24487](https://arxiv.org/abs/2609.24487) | [B station](https://www.bilibili.com/video/BV1Vdps6HEFr)
  - 用 VLM 的结构推理寻找优化盆地，再用数值工具精确拟合形状、关节和跨帧姿态。
- **GaussianGPT: Towards Autoregressive 3D Gaussian Scene Generation** - arXiv 2026 | [arXiv:2603.26661](https://arxiv.org/abs/2603.26661) | [B station](https://www.bilibili.com/video/BV1nC8B6pEdm)
  - 将三维高斯场景压缩为离散空间 token，并用带三维空间先验的因果 Transformer 逐步生成、补全和外推场景。
- **DiGS-Avatar: Single-Image Animatable 3D Human Reconstruction via UV-Space Diffusion** - arXiv 2026 | [arXiv:2608.20759](https://arxiv.org/abs/2608.20759) | [project](https://github.com/KLMAV-CUC/DiG) | [B station](https://www.bilibili.com/video/BV1hHhG6vE7d)
  - 在 canonical UV latent 中完成单图人体的几何与外观，再解码为高保真、可直接动画的 3D Gaussian avatar。
- **Rethinking 3D Noise: Learning 3D-Aware Video Priors via Optimization-Free Morphological Perturbations** - arXiv 2026 | [arXiv:2609.03657](https://arxiv.org/abs/2609.03657) | [B station](https://www.bilibili.com/video/BV1ajbE6LERG)
  - 在三维高斯空间中施加形态扰动，免去逐场景优化，生成多视角一致的训练对，并提升视频扩散模型的几何恢复能力。
- **Beyond Placement and Articulation: Usage-Driven Code Scenes for Embodied Interaction** - arXiv 2026 | [arXiv:2608.18840](https://arxiv.org/abs/2608.18840) | [B station](https://www.bilibili.com/video/BV1818T6SEpE)
  - RoomWright 将房间描述转化为可执行的代码场景：场景内容由活动需求决定，交互由结构化规则驱动，布局由几何与物理校验落地。
- **GroupForward: Building Referable 3D Scenes via Instance-Grouped Feed-Forward Gaussian Splatting** - arXiv 2026 | [arXiv:2608.17535](https://arxiv.org/abs/2608.17535) | [B station](https://www.bilibili.com/video/BV1vpbf6YEDs)
  - 用低维实例嵌入把高斯基元组织成跨视角一致的三维实例，再让场景图与视觉语言模型完成复杂指代表达式的三维定位。
- **FLARE: Feed-Forward Geometry, Appearance and Camera Estimation from Uncalibrated Sparse Views** - CVPR 2025 | [arXiv:2502.12138](https://arxiv.org/abs/2502.12138) | [project](https://github.com/robbyant-research/FLARE) | [B station](https://www.bilibili.com/video/BV197tN6VEkV)
  - 以相机位姿为中间几何代理，把稀疏视图中的位姿、局部点图、全局场景和三维高斯外观串成一个可微的前馈系统。
- **Sparse-View 4D Gaussian Splatting via Spatiotemporal Priors and Generative Assistance** - arXiv 2026 | [arXiv:2610.04606](https://arxiv.org/abs/2610.04606) | [B station](https://www.bilibili.com/video/BV18jp366ERv)
  - 以空间、时间和生成式伪监督共同弥补稀疏相机造成的容量、运动与覆盖不足。
- **Reliability-Regulated Trajectory Optimization for Progressive COLMAP-Free 3D Gaussian Splatting** - arXiv 2026 | [arXiv:2609.30865](https://arxiv.org/abs/2609.30865) | [B station](https://www.bilibili.com/video/BV1crp46zE2C)
  - 用前后向循环一致性产生在线可靠性，以门控运动外推并加权固定几何的局部窗口位姿优化。
- **VideoScene: Distilling Video Diffusion Model to Generate 3D Scenes in One Step** - arXiv 2025 | [arXiv:2504.01956](https://arxiv.org/abs/2504.01956) | [project](https://hanyang-21.github.io/VideoScene) | [B station](https://www.bilibili.com/video/BV1WfgL65EJa)
  - 从两个稀疏视图构造三维先验，再蒸馏 CogVideoX，使三维一致的视频在单次去噪中生成。
- **GATOR: Generative and Agentic 3D Object Reconstruction From Casual Images** - arXiv 2026 | [arXiv:2610.11215](https://arxiv.org/abs/2610.11215) | [B station](https://www.bilibili.com/video/BV13vpv61ED8)
  - 用局部跨模态融合和文本条件生成完整资产，再用观测驱动的 edit--render--review 循环修复细节与拓扑。
- **Learning 3D Editing without Paired Supervision via Generative Prior Distillation** - arXiv 2026 | [arXiv:2609.04942](https://arxiv.org/abs/2609.04942) | [project](https://github.com/thiamine128/PriorEdit3D) | [B station](https://www.bilibili.com/video/BV1ecbG6wEfu)
  - 用无配对三维监督蒸馏强大的二维、语义与三维生成先验，学习快速、免反演、免三维掩码的三维编辑器。
- **Cyc3D: Evaluating Cyclic Structural Stability and Asset Usability in Image-to-3D Generation** - arXiv 2026 | [arXiv:2608.28080](https://arxiv.org/abs/2608.28080) | [B station](https://www.bilibili.com/video/BV1Bctg68EYU)
  - 用跨视角一致性、闭环循环稳定性、几何结构、网格和 UV 质量，联合评估图像到三维生成的可靠性。
- **GRF-Recon: Global Ray-Field Optimization for Long-Sequence Feed-forward Reconstruction** - arXiv 2026 | [arXiv:2609.20012](https://arxiv.org/abs/2609.20012) | [B station](https://www.bilibili.com/video/BV1znet6wEZD)
  - 用轻量几何适配增强局部感知，以混合权重稀疏光线场把跨帧几何约束送入全局优化，从而稳定扩展单目重建的序列长度。
- **GAPS: Generative Active Pseudo-view Selection for Sparse-View 3D Gaussian Splatting** - arXiv 2026 | [arXiv:2609.23436](https://arxiv.org/abs/2609.23436) | [B station](https://www.bilibili.com/video/BV19Xps6pEmT)
  - 用主动选择、受约束扩散生成和不确定性加权，把伪视角变成稀疏视角 3DGS 的可靠补充监督。
- **MINT: A Unified Model for World-Space Camera and Hand Motion Estimation from Scalable Egocentric Pipeline Supervision** - arXiv 2026 | [arXiv:2609.04958](https://arxiv.org/abs/2609.04958) | [B station](https://www.bilibili.com/video/BV1cKbV6mEB7)
  - 用大规模普通第一视角视频生成结构化运动监督，再以共享时空几何表示在一次前向中同时预测相机、双手和可见性。
- **Matisse: Evidence-Space Reasoning for Active 3D Reconstruction** - arXiv 2026 | [arXiv:2609.38746](https://arxiv.org/abs/2609.38746) | [B station](https://www.bilibili.com/video/BV18BpG6VEgt)
  - 在生成式三维证据空间中估计不确定性，用信息增益统一主动视图获取与长时序关键帧选择。
- **Bi-FlowGS: Bridging Generative View Completion and Gaussian Geometry through Bidirectional Flow Co-Refinement** - arXiv 2026 | [arXiv:2609.17039](https://arxiv.org/abs/2609.17039) | [B station](https://www.bilibili.com/video/BV1ckeM6jEDJ)
  - 用光流在生成式视角补全与 Gaussian geometry 之间建立可迭代的双向监督闭环。
- **Monocular Depth Estimation from a Single Image: Progress and Opportunities** - arXiv 2026 | [arXiv:2609.01172](https://arxiv.org/abs/2609.01172) | [B station](https://www.bilibili.com/video/BV1bxtZ6UEe9)
  - 从问题、数据、方法到应用，系统梳理单目深度估计迈向深度基础模型的演进。
- **NavArena: Automated Construction of Goal-Oriented Navigation Benchmarks from 3D Gaussian Splatting Reconstructions** - arXiv 2026 | [arXiv:2609.04602](https://arxiv.org/abs/2609.04602) | [B station](https://www.bilibili.com/video/BV1Wzb367EwJ)
  - 从固定 3DGS 重建中自动推导可行走空间、可达目标与统一闭环评测接口。
- **SceneScaffold: Active Scene-State Construction for Unified 3D Scene Understanding** - arXiv 2026 | [arXiv:2609.33518](https://arxiv.org/abs/2609.33518) | [B station](https://www.bilibili.com/video/BV1tzph64ET2)
  - 在固定视觉 token 预算下，把三维证据组织成实体、场景框架、关系和全局状态，再交给 LLM 统一处理 grounding、QA 与 dense captioning。
- **TransHands: Repurposing Human Pose Encoders as Hand Pose Encoders** - arXiv 2026 | [arXiv:2608.22341](https://arxiv.org/abs/2608.22341) | [B station](https://www.bilibili.com/video/BV1cU896NErE)
  - 用拓扑适配器把二维手部序列映射到人体运动编码器的表示空间，再以部分解冻完成三维手部姿态恢复。
- **RelationField: Relate Anything in Radiance Fields** - CVPR 2025 | [project](https://openaccess.thecvf.com/content/CVPR2025/html/Koch_RelationField_Relate_Anything_in_Radiance_Fie) | [B station](https://www.bilibili.com/video/BV1wxg761EjA)
  - 把对象间关系作为成对射线上的开放词汇特征蒸馏进辐射场，从 posed RGB 直接支持关系查询、3D scene graph 与关系引导实例分割。
- **UniDepthV2: Universal Monocular Metric Depth Estimation Made Simpler** - IEEE TPAMI 2026 | [project](https://doi.org/10.1109/TPAMI.2025.3628473) | [B station](https://www.bilibili.com/video/BV1nTgE62Eco)
  - 仅凭一张 RGB 图像，自举相机表征并直接恢复跨域 metric 3D，同时提升边缘、效率与置信度。
- **Uni-3DAR: Unified 3D Generation and Understanding via Autoregression on Compressed Spatial Tokens** - arXiv 2025 | [arXiv:2503.16278](https://arxiv.org/abs/2503.16278) | [project](https://g) | [B station](https://www.bilibili.com/video/BV1GpgE6iERZ)
  - 用八叉树压缩空间 Token 与 Masked Next-Token Prediction，把多类 3D 生成、Token 级理解和结构级理解纳入同一自回归接口。
- **FounRef: Robust, Structure-Preserving, and Fast Metric Refinement of Frozen Monocular Foundation Priors with Sparse Anchors** - arXiv 2026 | [arXiv:2609.29224](https://arxiv.org/abs/2609.29224) | [B station](https://www.bilibili.com/video/BV186pv6GE8c)
  - 冻结单目几何先验，结合稀疏度量锚点，以逐图像、无需训练的方式得到稠密度量深度，并尽量保留表面结构。
- **LVS: Local View Synthesis from Relative Camera Pose by Reusing Previous Views** - arXiv 2026 | [arXiv:2610.12127](https://arxiv.org/abs/2610.12127) | [B station](https://www.bilibili.com/video/BV1fApi6xEKh)
  - 用已渲染的 RGB-D 视图做相对位姿引导的几何复用，再以多尺度 RGB 残差恢复局部新视图。
- **OREN-X: Octree Residual Network for Real-Time Multi-Modal Mapping** - arXiv 2026 | [arXiv:2609.29157](https://arxiv.org/abs/2609.29157) | [B station](https://www.bilibili.com/video/BV13Hhy6RE3z)
  - 用一棵共享八叉树联合维护 SDF、occupancy、radiance 和 vision-language field，并通过跨模态监督与在线压缩同时提升精度、效率和可查询性。
- **ScenePilot: Grow-and-Repair Policy for Text-Driven 3D Indoor Scene Generation** - arXiv 2026 | [arXiv:2608.30307](https://arxiv.org/abs/2608.30307) | [project](https://zjw-louie.github.io/ScenePilot) | [B station](https://www.bilibili.com/video/BV1Zat76HE6N)
  - 以层次化空间先验规划功能组，以局部到全局的可执行修复稳定逐步生成的三维室内场景。
- **Reconstructing the Dynamic World: A Representation-Centric View of 4D Scene Reconstruction** - arXiv 2026 | [arXiv:2609.39960](https://arxiv.org/abs/2609.39960) | [B station](https://www.bilibili.com/video/BV1UrpG6GEEw)
  - 以场景表示为主线，统一梳理动态 NeRF 与动态 3D Gaussian Splatting 的方法、评测和开放问题。
- **DyGT: Modeling Object Dynamics with 3D Gaussian Temporal-Spatial Particle Graph Transformer** - arXiv 2026 | [B station](https://www.bilibili.com/video/BV15n8M6dEQj)
  - 从稀疏视角视频重建可追踪的 3D Gaussian 粒子，用空间补全、时间解耦和多尺度粒子图交互预测未来物体运动。
- **R3DS: Reality-linked 3D Scenes for Panoramic Scene Understanding** - ECCV 2024 | [arXiv:2403.12301](https://arxiv.org/abs/2403.12301) | [project](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/8056_ECCV_2024_paper.p) | [B station](https://www.bilibili.com/video/BV1zhg763EM4)
  - 用真实全景约束可编辑的合成三维代理，并把对象对应、支持层级与匹配集合一起交给全景场景理解模型。
- **Less Decoder is More Encoder: Geometric Representation Learning from Novel View Synthesis** - arXiv 2026 | [arXiv:2610.03717](https://arxiv.org/abs/2610.03717) | [B station](https://www.bilibili.com/video/BV1GDp367E2E)
  - SNAP 用局部位姿条件解码器和冻结视觉 teacher 的 latent reconstruction，把新视角合成的几何监督更直接地压回多视角编码器。
- **StudioRecon：低重叠相机下的4D人体-场景重建** - [arXiv:2607.09125](https://arxiv.org/abs/2607.09125) | [project](https://sisyphm.github.io/studiorecon-page/) | [B station](https://www.bilibili.com/video/BV1Aogw6uEW6)
- **T3lescope: Arbitrary-Resolution High-Fidelity Generative Surface Reconstruction from Images** - arXiv 2026 | [arXiv:2610.03308](https://arxiv.org/abs/2610.03308) | [B station](https://www.bilibili.com/video/BV15mp36JErr)
  - 单一固定分辨率的 3D 生成器，在推理时通过粗到细级联覆盖不同场景尺度，并用尺度匹配的图像特征恢复细节。
- **ViPE: Video Pose Engine for 3D Geometric Perception** - arXiv 2025 | [arXiv:2508.10934](https://arxiv.org/abs/2508.10934) | [project](https://research.nvidia.com/labs/toronto-ai/vipe/) | [B station](https://www.bilibili.com/video/BV1Myb66iECg)
  - ViPE 把关键帧 SLAM 的可扩展性、学习模型的鲁棒性和度量深度先验放进同一个 BA 框架，
- **OccAnyScene: Towards Unified Indoor-Outdoor 3D Occupancy Prediction** - arXiv 2026 | [arXiv:2608.08696](https://arxiv.org/abs/2608.08696) | [project](https://RoboPerception.github.io/OccAnyScene/) | [B station](https://www.bilibili.com/video/BV1EkgG6bELt)
  - 用像素视锥约束连续三维高斯，让同一个模型同时适配室内单目与室外环视占用协议。
- **ParticleSplat: Self-supervised Object-centric Latent Particle Splatting** - arXiv 2026 | [arXiv:2609.19463](https://arxiv.org/abs/2609.19463) | [B station](https://www.bilibili.com/video/BV1MAet6yEE5)
  - 用少量多视角或 RGB-D 观察推断对象中心粒子，再把粒子变成三维高斯，从而统一新视角合成、可控场景编辑与机器人操作表示。
- **Geometric Context Transformer for Streaming 3D Reconstruction** - arXiv 2026 | [arXiv:2604.14141](https://arxiv.org/abs/2604.14141) | [project](https://github.com/Robbyant/lingbot-map) | [B station](https://www.bilibili.com/video/BV1GntN6GEnX)
  - LingBot-Map 用学习到的三层几何上下文，在单次前向流式推理中抵抗长序列漂移。
- **Scal3R: Learning Efficient Multi-Relative Pose Query for Scalable Online 3D Reconstruction** - arXiv 2026 | [arXiv:2609.04201](https://arxiv.org/abs/2609.04201) | [project](https://linjohnss.github.io/scal3r/) | [B station](https://www.bilibili.com/video/BV1hJbE6VE4g)
  - 用多参考相对位姿查询替代脆弱的首帧全局回归，并用在线位姿图优化抑制长序列漂移。
- **NeoWorld-Pro: Programming Interactive Scenes from Monocular Images for Embodied Simulation** - arXiv 2026 | [arXiv:2608.24212](https://arxiv.org/abs/2608.24212) | [B station](https://www.bilibili.com/video/BV1DzhF6eExB)
  - 将单目场景重建改写为多模态大模型驱动的程序合成，并用对象级与场景级物理反馈，把外观、运动结构和空间关系一起优化到可仿真、可交互。
- **PanoDreamer: Consistent Text to 360-Degree Scene Generation** - [B station](https://www.bilibili.com/video/BV12Gg76WEy7)
- **GeoWeaver: Accurate Long-Sequence 3D Reconstruction via Hierarchical Geometric Assembly** - arXiv 2026 | [arXiv:2608.17389](https://arxiv.org/abs/2608.17389) | [project](http://kosmoresearch.github.io/GeoWeaver/) | [B station](https://www.bilibili.com/video/BV1Fsbd6vEWU)
  - 用可调的分块几何先验作为起点，再以三阶段测试时适配把局部预测组装成全局一致的长序列重建。
- **StreetCrafter: Street View Synthesis with Controllable Video Diffusion Models** - CVPR 2025 | [arXiv:2412.13188](https://arxiv.org/abs/2412.13188) | [project](https://zju3dv.github.io/street_crafter/) | [B station](https://www.bilibili.com/video/BV1Yyg76aEK5)
  - 用栅格化 LiDAR 作为像素级几何条件控制视频扩散，再将生成先验蒸馏进动态 3DGS，兼顾大视角外推质量、实时渲染与场景编辑。
- **VistaDream: Sampling multiview consistent images for single-view scene reconstruction** - ICCV 2025 | [project](https://vistadream-projectpage.github.io/) | [B station](https://www.bilibili.com/video/BV1zsgL6qE3G)
  - 以全局 3D 脚手架稳定场景扩展，再在扩散反演中注入多视图一致性约束，从单张图像重建可自由渲染的 3D Gaussian 场景。
- **VoxelTTO: Voxel-Aligned Feed-Forward 3D Gaussian Splatting with Test-Time Optimization** - arXiv 2026 | [arXiv:2609.21498](https://arxiv.org/abs/2609.21498) | [B station](https://www.bilibili.com/video/BV1tZh76LEDm)
  - 从任意数量的多视图图像和可选相机参数出发，构建体素对齐的 3DGS 场景，并通过 TTO 改善测试视角的位姿对齐与 RGB-D 渲染。
- **TRACKGRAPH: Online Open-Vocabulary 3D Scene Graphs via Image-Space Tracking** - arXiv 2026 | [arXiv:2609.31005](https://arxiv.org/abs/2609.31005) | [B station](https://www.bilibili.com/video/BV1ABp46rELF)
  - 在图像空间传播短期 mask 身份，再将 source tracks 在线融合为可用文本和图像查询的三维场景图。
- **RichDreamer: A Generalizable Normal-Depth Diffusion Model for Detail Richness in Text-to-3D** - arXiv 2023 | [arXiv:2311.16918](https://arxiv.org/abs/2311.16918) | [project](https://aigc3d.github.io/richdream) | [B station](https://www.bilibili.com/video/BV1mDgL6SExs)
  - 用联合 Normal-Depth 几何先验与深度条件 Albedo 先验，推动几何—外观解耦的高细节 Text-to-3D。
- **OTT3R: Multi-View 3D Reconstruction and Fast Dataset Generation at 1\% Compute** - arXiv 2026 | [arXiv:2609.36374](https://arxiv.org/abs/2609.36374) | [B station](https://www.bilibili.com/video/BV1wupg64EAy)
  - 用 生成离线三维监督，再以 102M 参数学生模型学习局部点图、置信度和相机姿态。
- **Geometry Without Coordinates: LiDAR Diffusion as a 3D Feature Bridge** - arXiv 2026 | [arXiv:2609.10322](https://arxiv.org/abs/2609.10322) | [B station](https://www.bilibili.com/video/BV1LcYE6cEpr)
  - 在二维伪标签监督下，把 LiDAR 条件扩散模型的中间 activation 回投到点云，并检验其中是否存在不依赖坐标的三维结构。
- **Prometheus: 3D-Aware Latent Diffusion Models for Feed-Forward Text-to-3D Scene Generation** - CVPR 2025 | [arXiv:2412.21117](https://arxiv.org/abs/2412.21117) | [project](https://openaccess.thecvf.com/content/CVPR2) | [B station](https://www.bilibili.com/video/BV1Rdgj6NEjC)
  - 复用二维生成先验，在 RGB-D 潜空间中联合生成多视图，再直接解码为像素对齐 3D Gaussian。
- **Pixel-Perfect Depth with Semantics-Prompted Diffusion Transformers** - NeurIPS 2025 | [arXiv:2510.07316](https://arxiv.org/abs/2510.07316) | [project](https://pixel-perfect-depth.github.io) | [B station](https://www.bilibili.com/video/BV1C7gL6GEpj)
  - 直接在像素空间生成深度，以语义提示和粗到细 DiT 同时守住全局结构、边缘细节与计算效率。
- **ArtiMo: Agent-Driven Articulated Mesh Animation** - arXiv 2026 | [arXiv:2608.20699](https://arxiv.org/abs/2608.20699) | [project](https://zou-2004.github.io/ArtiMo/) | [B station](https://www.bilibili.com/video/BV1A6hG6pEki)
  - 用 URDF 的低层运动约束承接 VLM/LLM 的语义与因果推理，并通过视觉 critic 迭代修正文本驱动的可动部件动画。
- **Stream3Dv2: Geometric-Semantic Fusion Enhanced Streaming Zero-Shot 3D Scene Understanding** - arXiv 2026 | [arXiv:2608.21136](https://arxiv.org/abs/2608.21136) | [B station](https://www.bilibili.com/video/BV14Xh36sEWs)
  - 以局部多视角和局部到历史的嵌套结构，实现训练免费的流式零样本三维分割，并扩展到检测与语言驱动的场景理解。
- **Dynamic-Robust Photometric-Semantic Reconstruction for Open-Vocabulary 3D Scene Understanding** - arXiv 2026 | [arXiv:2608.29177](https://arxiv.org/abs/2608.29177) | [B station](https://www.bilibili.com/video/BV12RtL6ZEN8)
  - SPAR 通过跨视角动态区域预测和动态区域感知优化，在无位姿、动态多视角输入下联合完成光度重建与开放词汇语义理解。
- **ElasticFit: Fit-Aware 3D Object Insertion via VLM Reasoning and Generative Adaptation** - arXiv 2026 | [arXiv:2610.07460](https://arxiv.org/abs/2610.07460) | [B station](https://www.bilibili.com/video/BV1sbp36aExS)
  - 让物体插入从“找到一个位置”升级为“理解局部空间、生成合适先验，并把物体拟合到可支撑的几何区域”。
- **\phi-RIE: From Photorealistic Reconstruction to Interactive Environments** - arXiv 2026 | [arXiv:2609.26795](https://arxiv.org/abs/2609.26795) | [B station](https://www.bilibili.com/video/BV1odh26uEJq)
  - 以共享对象证据耦合资产构造、源高斯移除和背景补全，使捕获的 Gaussian scene 具有可移动对象和可执行物理状态。
- **VGGT-Bridge: Beyond Sequential Pose Graphs via Coarse-Stride Skip Edges** - arXiv 2026 | [arXiv:2610.06594](https://arxiv.org/abs/2610.06594) | [B station](https://www.bilibili.com/video/BV1YGp36VELS)
  - 在不重新训练的前提下，用粗步长块产生的长程约束抑制 chunk-and-align 的累积漂移。
- **ReconSplat: Generalizable 3D Scene Reconstruction Beyond Observed Views** - arXiv 2026 | [arXiv:2608.28895](https://arxiv.org/abs/2608.28895) | [B station](https://www.bilibili.com/video/BV1LBt76EEk4)
  - 仅凭少量带相机位姿的 RGB 观察，同时完成未观测视角的外观补全与几何一致的深度预测。
- **TextSplat: Text-Guided Semantic Fusion for Generalizable Gaussian Splatting** - ACM Multimedia 2025 | [arXiv:2504.09588](https://arxiv.org/abs/2504.09588) | [B station](https://www.bilibili.com/video/BV1LjgE66EEK)
  - 用文本描述为深度、分割与跨视角三路特征动态分配权重，再解码为可泛化的 3D Gaussians。
- **Masked Depth Modeling for Spatial Perception** - arXiv 2026 | [arXiv:2601.17895](https://arxiv.org/abs/2601.17895) | [project](https://github.com/Robbyant/lingbot-depth) | [B station](https://www.bilibili.com/video/BV1mhtN6eEYG)
  - 用 RGB 上下文和有效深度 token 重建传感器缺失区域，学习可迁移的 metric-scale 空间表示。
- **Prim2Room: Layout-Controllable Room Mesh Generation from Primitives** - arXiv 2024 | [arXiv:2409.05380](https://arxiv.org/abs/2409.05380) | [B station](https://www.bilibili.com/video/BV19fgj6AEbd)
  - 以 2D 布局框 + 3D primitive 提供精确条件，再通过自适应视点、迭代生成与非刚性深度配准得到带纹理的房间网格。
- **Photorealistic Novel View Synthesis of Human Faces using Next-Scale Transformers** - arXiv 2026 | [arXiv:2608.23410](https://arxiv.org/abs/2608.23410) | [B station](https://www.bilibili.com/video/BV1iQ8S61EA6)
  - 用 next-scale autoregression 生成一致的人脸多视图，再交给 GS-LRM 类模型 lifting 为三维 Gaussian 表示。
- **SAR3D: Autoregressive 3D Object Generation and Understanding via Multi-scale 3D VQVAE** - CVPR 2025 | [arXiv:2411.16856](https://arxiv.org/abs/2411.16856) | [project](https://cyw-3d.github.io/projects/SAR3D/) | [B station](https://www.bilibili.com/video/BV1xRg76REQk)
  - 用同一套多尺度 3D 离散 token，把亚秒级条件生成与细粒度 3D 描述连接起来。
- **VoxelSplat: Dynamic Gaussian Splatting as an Effective Loss for Occupancy and Flow Prediction** - arXiv 2025 | [arXiv:2506.05563](https://arxiv.org/abs/2506.05563) | [project](https://doi.org/10.48550/arXiv.2506.05563) | [B station](https://www.bilibili.com/video/BV1PdgL67Ek2)
  - 把动态 3D Gaussians 变成仅训练期启用的渲染正则，同时提升 3D 占用语义与 scene flow，推理阶段零额外开销。
- **HiCo-GS: Hierarchical Context Aggregation and Geometric Consistency for Octree Gaussian Splatting** - ACM Multimedia (MM '26) 2026 | [arXiv:2608.14136](https://arxiv.org/abs/2608.14136) | [B station](https://www.bilibili.com/video/BV1pN8g6yEDo)
  - HiCo-GS 用 CLCA 补上八叉树层级间的上下文通信，再用 DNGC 约束深度与法向的一致性，以更干净的几何重建支撑大规模城市与复杂古塔场景。
- **Mira-Scene: Pixel-Aligned Layouts for Generative 3D Scene Reconstruction** - arXiv 2026 | [arXiv:2609.23796](https://arxiv.org/abs/2609.23796) | [project](https://sunyangtian.github.io/Mira-Scene-web/) | [B station](https://www.bilibili.com/video/BV159ps6XEru)
  - 用 bounded CCM 表示物体内部的像素到 canonical surface 对应，再与 scene-space PCM 对齐恢复物体变换。
- **SplatLabel: Pseudo-Labelling through 4D Gaussian Splatting** - arXiv 2026 | [arXiv:2609.29836](https://arxiv.org/abs/2609.29836) | [B station](https://www.bilibili.com/video/BV1G7hy6bELh)
  - 用带有显式时间流形的 4D Gaussian 表示，把二维语义和 360 度 LiDAR 几何蒸馏为可控、可评测的三维伪标签。
- **CapFrame: Text-Instructed Viewpoint Grounding in 3D Gaussian Scenes via Geometric Pseudo Labels** - arXiv 2026 | [arXiv:2608.30342](https://arxiv.org/abs/2608.30342) | [project](https://github.com/jirongli/CapFrame) | [B station](https://www.bilibili.com/video/BV16jtn6FEcv)
  - 用 MLLM 把组合式文本转换为方向与布局几何伪标签，再通过 3DGS 可微优化搜索符合描述的相机位姿。
- **RenderBench: Benchmarking Render-to-Real Video Transfer with Reconstructed Digital Twins** - arXiv 2026 | [arXiv:2610.08684](https://arxiv.org/abs/2610.08684) | [B station](https://www.bilibili.com/video/BV1Cap368Eb9)
  - 用经过几何和时间验收的真实场景数字孪生，把渲染到真实视频迁移放入可复现的成对真实目标评测中。
- **Fysiverse-3D-Vision Technical Report: Generating Executable 3D Worlds from Images through Unified Spatial Reasoning** - arXiv 2026 | [arXiv:2609.25741](https://arxiv.org/abs/2609.25741) | [B station](https://www.bilibili.com/video/BV1bsps6kELP)
  - 用统一的视觉—语言—几何表示，把单图三维重建中的资产生成与空间布局推理解耦，并连接到可执行属性。
- **GenRec: Knowing Where to Reconstruct and Where to Generate** - arXiv 2026 | [arXiv:2608.17832](https://arxiv.org/abs/2608.17832) | [project](https://atcelen.github.io/GenRec/) | [B station](https://www.bilibili.com/video/BV1R6bZ6wE9i)
  - 用 observation mask 把新视角合成拆成“观测区域重建”和“未观测区域生成”，让两类像素分别获得合适的结构、损失与梯度路径。
- **SceneReGen: Generative Reconstruction of 3D Scenes from a Single Image** - arXiv 2026 | [arXiv:2608.23930](https://arxiv.org/abs/2608.23930) | [B station](https://www.bilibili.com/video/BV1HJhF6EEf7)
  - 以带观察方向的完整物体网格为重建原语，显式估计平移与尺度，组装出共享观察坐标系中的三维场景。
- **DSSR-3D: Decoupled Reasoning for View-Dependent Referring in 3D Gaussians** - arXiv 2026 | [arXiv:2610.00040](https://arxiv.org/abs/2610.00040) | [B station](https://www.bilibili.com/video/BV17rp36WEFs)
  - 在连续三维高斯场上，把与视角无关的目标定位和与相机姿态相关的方向判断解耦，实现无需额外训练的视角依赖指代分割。
- **Physical AI Smart Spaces: A Large-Scale Benchmark for Multi-Camera 3D Perception in Smart Spaces** - arXiv 2026 | [arXiv:2610.02580](https://arxiv.org/abs/2610.02580) | [B station](https://www.bilibili.com/video/BV139p36LEoA)
  - PAISS 将可控的合成监督、外观迁移和隐藏真实目标统一到同一个多摄像头三维检测跟踪基准中。
- **WorldScore: A Unified Evaluation Benchmark for World Generation** - arXiv 2025 | [arXiv:2504.00983](https://arxiv.org/abs/2504.00983) | [project](https://haoyi-duan.github.io/WorldScore/) | [B station](https://www.bilibili.com/video/BV1yogL61EXT)
  - 把多场景世界生成拆成带相机布局的 next-scene 任务，并用统一的十维指标比较视频、3D 与 4D 生成模型。
- **SCION: Scene Composition with Instanced Neural Primitives** - arXiv 2026 | [arXiv:2610.02322](https://arxiv.org/abs/2610.02322) | [B station](https://www.bilibili.com/video/BV1G9p36LEzH)
  - 从多视角图像中学习可复用基元词典与轻量实例，让三维场景更紧凑、可控且可编辑。
- **SLAM-Former: Putting SLAM into One Transformer** - ECCV 2026 | [arXiv:2509.16909](https://arxiv.org/abs/2509.16909) | [project](https://tsinghua-mars-lab.github.io/SLAM-Former) | [B station](https://www.bilibili.com/video/BV1Peg56kEE6)
  - SLAM-Former 用共享权重的 Transformer 同时承担因果前端和全局后端，通过 map tokens 与 KV cache 的循环更新，在线跟踪并周期性修正全局几何。
- **RoboGSim: A Real2Sim2Real Robotic Gaussian Splatting Simulator** - arXiv 2024 | [arXiv:2411.11839](https://arxiv.org/abs/2411.11839) | [project](https://robogsim.github.io/) | [B station](https://www.bilibili.com/video/BV1rpg762EQE)
  - 以 3DGS 的真实感渲染连接 Isaac Sim 的物理交互，同时服务数据合成与闭环策略评测。
- **Less Context, Better Geometry: Masked Geometric Encoder for Robust 3D Foundation Models** - arXiv 2026 | [arXiv:2610.06813](https://arxiv.org/abs/2610.06813) | [B station](https://www.bilibili.com/video/BV1hLp363Eja)
  - 在训练时学习适应不完整的跨视角连接，在推理时按帧级冗余自适应压缩，从而提升三维重建的鲁棒性与可扩展性。
- **VGGT-CAD: Reconstructing Parametric CAD 3D Model with Geometric Grounding** - arXiv 2026 | [arXiv:2609.21225](https://arxiv.org/abs/2609.21225) | [B station](https://www.bilibili.com/video/BV1umhp6tEco)
  - 将预训练的三维几何先验与显式相机条件结合，在可变数量的视角下预测可执行 CAD 命令。
- **Generating Multi-view Adversarial Examples for Visual Geometry Grounded Transformer** - arXiv 2026 | [arXiv:2608.20748](https://arxiv.org/abs/2608.20748) | [B station](https://www.bilibili.com/video/BV1EShG6jEej)
  - MVAP-G 学习一个具备跨视角对齐能力的生成器，在单次前向过程中产生多视图一致的隐形扰动，从而显著破坏 VGGT 的三维重建。
- **PRG-Fusion: Orchestrating Generative Priors with Reconstruction Evidence for Driving View Synthesis** - arXiv 2026 | [arXiv:2609.06948](https://arxiv.org/abs/2609.06948) | [B station](https://www.bilibili.com/video/BV1xRYN62EDC)
  - 用重建可靠性与支持度生成 Preserve、Repair、Generate 标签，让 3DGS 外观、LiDAR 几何和视频先验在不同区域承担不同职责。
- **ReViV: Reconstructing the Viewer and the View in 4D from Monocular Egocentric Video** - arXiv 2026 | [project](https://reviv) | [B station](https://www.bilibili.com/video/BV1jugj6qESP)
  - ReViV 用一个 feed-forward 的 masked multimodal Transformer，从单目 RGB 同时重建观察者身体、手、凝视与相机、深度等视野状态。
- **VGGT-Diff: Visual Geometry Meets Diffusion for Sparse-View Novel View Synthesis** - arXiv 2026 | [arXiv:2609.33253](https://arxiv.org/abs/2609.33253) | [B station](https://www.bilibili.com/video/BV1bopu6vE6e)
  - 用 VGGT-Ω 的带置信度三维特征为视频扩散提供查询视角条件，再用点轨迹残差一致性稳定联合生成的多视图。
- **VDGS: Visibility-Driven Large-Scale 3D Gaussian Splatting for Aerial Scene Reconstruction** - arXiv 2026 | [arXiv:2609.23049](https://arxiv.org/abs/2609.23049) | [B station](https://www.bilibili.com/video/BV1xXhC6yEFH)
  - 用相机可见性统计同时指导场景分块和低可见性区域的梯度补偿，缓解大规模航拍场景中的监督失衡。
- **SceneEval: Evaluating Semantic Coherence in Text-Conditioned 3D Indoor Scene Synthesis** - WACV 2026 Oral | [B station](https://www.bilibili.com/video/BV1Yrg76eEM2)
- **CODA: Depth-Aligned Scene Completion and Object Decomposition from a Single RGB-D Image** - arXiv 2026 | [arXiv:2609.25654](https://arxiv.org/abs/2609.25654) | [B station](https://www.bilibili.com/video/BV1Rdh26uECW)
  - 先联合补全整个场景，再利用生成的属性编码把环境与对象分开，并用观测深度把生成几何锚定在真实表面。
- **DepthLab: From Partial to Complete** - arXiv 2024 | [arXiv:2412.18153](https://arxiv.org/abs/2412.18153) | [project](https://github.com/robbyant-research/DepthLab) | [B station](https://www.bilibili.com/video/BV1QHtN66Er6)
  - 用 RGB 图像和已知深度共同条件化扩散模型，在缺失区域预测与已有几何、尺度一致的绝对深度。
- **Chat-Edit-3D++: Interactive 3D and 4D Scene Editing via Large Language Models** - arXiv 2026 | [arXiv:2608.29137](https://arxiv.org/abs/2608.29137) | [project](https://github.com/Fangkang515/CE3D) | [B station](https://www.bilibili.com/video/BV1J8t769EGt)
  - 用二维 atlas 解耦编辑与重建，再由 LLM 调度视觉工具，实现支持多轮对话的 3D/4D 场景编辑。
- **Open-Vocabulary Functional 3D Scene Graphs for Real-World Indoor Spaces** - CVPR 2025 | [project](https://openfungraph.github.io) | [B station](https://www.bilibili.com/video/BV1B8gL6PEcc)
  - 从 posed RGB-D 序列构建开放词汇功能 3D 场景图，让对象、可交互部件与“如何作用”进入同一图表示。
- **Structured 3D Latents for Scalable and Versatile 3D Generation** - CVPR Spotlight 2025 | [B station](https://www.bilibili.com/video/BV1GxgE6eEwe)
  - TRELLIS 以稀疏体素承载局部视觉潜变量，在一个统一的 SLAT 空间中兼顾几何、外观、多格式解码与局部编辑。
- **Universal Scene Graph Generation** - CVPR 2025 | [project](https://sqwu.top/USG/) | [B station](https://www.bilibili.com/video/BV1ohgL6YE5Y)
  - 用一个端到端解析器把任意组合的文本、图像、视频与 3D 输入统一为兼顾共享语义和模态特性的场景图。
- **G3AR: Graph-Guided Neural Visual Geometry for Scalable Multi-Sequence Aerial Registration** - arXiv 2026 | [arXiv:2609.16603](https://arxiv.org/abs/2609.16603) | [B station](https://www.bilibili.com/video/BV1YfeM6vEZK)
  - 用几何验证的图结构指导分块和 Sim(3) 合并，让神经视觉几何扩展到多序列大规模航空影像。
- **HIGS: Hierarchical Implicit Grids for Joint Geometric and Semantic Scene Understanding** - arXiv 2026 | [arXiv:2609.38620](https://arxiv.org/abs/2609.38620) | [B station](https://www.bilibili.com/video/BV1NTpG6iEtX)
  - 用多分辨率隐式网格统一承载 SDF 与视觉语言特征，再以层级初始化和隐式空间对齐扩展到大规模场景。
- **Beyond Relative Geometry: Metric-Aware Geometry Perception for Robotics** - arXiv 2026 | [arXiv:2608.27497](https://arxiv.org/abs/2608.27497) | [B station](https://www.bilibili.com/video/BV1Eitg6iEQ1)
  - MAGP 将相机参数与深度观测中的物理尺度注入多视图几何，并通过残差 cross-attention 对接机器人策略。
- **SceneHI: High-Resolution 3D-Consistent Scene Texturing with Controllable Illumination** - arXiv 2026 | [arXiv:2609.10363](https://arxiv.org/abs/2609.10363) | [B station](https://www.bilibili.com/video/BV1WPeG6ZEgE)
  - 在共享 UV 潜空间中联合去噪多视角，再用几何感知的高分辨率细化与阴影生成得到可直接使用的场景纹理。
- **NAMVIS: Next-Scale Autoregressive Multi-View Image Synthesis** - arXiv 2026 | [arXiv:2610.04722](https://arxiv.org/abs/2610.04722) | [B station](https://www.bilibili.com/video/BV1nSph6SEXn)
  - 用多尺度投影位姿编码和双路径源图像条件，直接并行生成几何一致的新视图。
- **M2Depth: Unifying Monocular Depth Foundation Priors with Multi-View Stereo** - arXiv 2026 | [arXiv:2608.20788](https://arxiv.org/abs/2608.20788) | [B station](https://www.bilibili.com/video/BV1j5hG6gEPy)
  - 用 MVS 的度量几何约束校准单目深度，用单目结构先验补足多视图匹配缺失，并通过双向迭代实现统一细化。
- **ARROW: Arbitrary Reconstruction and Tracking of 4D Observations in the Wild** - arXiv 2026 | [arXiv:2610.01314](https://arxiv.org/abs/2610.01314) | [project](https://vision.rwth-aachen.de/arrow) | [B station](https://www.bilibili.com/video/BV1v1p36DEio)
  - 用输入依赖的观测身份替代固定顺序编码，在任意 RGB 观测集合上统一重建与跟踪。
- **ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes** - CVPR 2017 | [arXiv:1702.04405](https://arxiv.org/abs/1702.04405) | [project](https://www.scan-net.org/) | [B station](https://www.bilibili.com/video/BV1sog76WEaK)
  - 把易用 RGB-D 采集、自动三维重建与众包语义标注连成可扩展系统，并以大规模真实数据验证 3D 学习的价值。
- **RayZer: A Self-supervised Large View Synthesis Model** - ICCV 2025 | [arXiv:2505.00702](https://arxiv.org/abs/2505.00702) | [project](https://openaccess.thecvf.com/content/ICCV2025/html/Jiang_RayZer_A_Self-supervised_Large_V) | [B station](https://www.bilibili.com/video/BV1ivg76BEyo)
  - 从无位姿、未标定多视图中先预测相机，再重建潜在场景，仅凭 2D 光度监督学习前馈新视角合成。
- **RIGOR: Rig-Informed Geometry for Omnidirectional Reconstruction** - arXiv 2026 | [arXiv:2609.13504](https://arxiv.org/abs/2609.13504) | [project](https://github.com/TangentH/RIGOR) | [B station](https://www.bilibili.com/video/BV1Vnec67EzF)
  - 将每个全景拆成四个已知相对朝向的透视视图，用 rig 一致性修复局部预测，并用经过验证的回环约束校正长序列漂移。
- **Scalix: Uncertainty-Aware Scale-Consistent Monocular SLAM** - arXiv 2026 | [arXiv:2608.17553](https://arxiv.org/abs/2608.17553) | [B station](https://www.bilibili.com/video/BV13KbZ6xETb)
  - 将单目深度的 per-frame scale 与 per-pixel uncertainty 纳入可优化的 factor graph，使 SLAM 在室内外场景中恢复 metric-scale、尺度更一致的轨迹。
- **LEGO-Anything: Coding Agents for 3D Scene Reconstruction** - arXiv 2026 | [arXiv:2609.36380](https://arxiv.org/abs/2609.36380) | [B station](https://www.bilibili.com/video/BV17Jpg6SER3)
  - 将单张图像重建表述为可执行的 Image-to-Code 过程，用基准、轨迹诊断和插件控制迭代质量。
- **Reconstructing Humans and Objects in Interaction using Large Reconstruction Models** - arXiv 2026 | [arXiv:2608.27407](https://arxiv.org/abs/2608.27407) | [project](https://ac5113.github.io/MILO) | [B station](https://www.bilibili.com/video/BV1cqtW6VEZE)
  - 用 LRM 生成的联合人-物 mesh 作为几何支架，再解释出 SMPL-H 人体和可选物体模板。
- **LangStreet: Persistent Language Fields for Anchor-Decoded Street Gaussians** - arXiv 2026 | [arXiv:2609.11616](https://arxiv.org/abs/2609.11616) | [B station](https://www.bilibili.com/video/BV1e4Y96FEkk)
  - 让 view-conditioned children 负责路由观测，让 persistent slots 与 anchors 负责拥有语言；再用完成和 anchor-relative coding 兼顾稠密细节与低存储。
- **GaussianFlowOcc: Sparse and Weakly Supervised Occupancy Estimation using Gaussian Splatting and Temporal Flow** - ICCV 2025 | [arXiv:2502.17288](https://arxiv.org/abs/2502.17288) | [project](https://doi.org/10.48550/arXiv.2502.17288) | [B station](https://www.bilibili.com/video/BV1N5gL6LE5z)
  - 用稀疏 3D Gaussians、近线性注意力与显式 Gaussian Flow，同时解决弱监督占用估计的效率和动态场景一致性。
- **OccScene: Semantic Occupancy-based Cross-task Mutual Learning for 3D Scene Generation** - IEEE TPAMI 2025 | [arXiv:2412.11183](https://arxiv.org/abs/2412.11183) | [B station](https://www.bilibili.com/video/BV1WbgH6FE81)
  - OccScene 用语义占据提供细粒度几何与语义约束，同时让生成结果反过来扩充感知训练数据，形成生成与感知的跨任务互学习。
- **WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild** - arXiv 2026 | [arXiv:2608.28240](https://arxiv.org/abs/2608.28240) | [B station](https://www.bilibili.com/video/BV1A2tT6AEt2)
  - 用连续的生成式外观潜空间连接全局风格与局部光照，再用感知一致性掩码抑制瞬态物体。
- **DepthEvidence: Unifying Metric Depth Prediction and Geometric Reasoning in Multimodal Language Models** - arXiv 2026 | [arXiv:2609.31103](https://arxiv.org/abs/2609.31103) | [B station](https://www.bilibili.com/video/BV11Dpv6vEbX)
  - 将相机条件化的密集度量深度，转换为绑定对象标识的连续 geometry tokens，使同一个 VLM 同时支持深度预测、实例测量和几何推理。
- **PePESeg3D: Perception Prior Enhances Multi-Scale Segmentation for 3D Gaussian Splatting** - arXiv 2026 | [arXiv:2609.28645](https://arxiv.org/abs/2609.28645) | [B station](https://www.bilibili.com/video/BV13wpx67ET2)
  - 将感知先验同时用于几何重建和多尺度特征学习，得到更准确、更连贯的 3DGS 分割。
- **RoGe: Novel View Synthesis via End-to-End Implicit Reconstruction and Generation** - arXiv 2026 | [arXiv:2609.02847](https://arxiv.org/abs/2609.02847) | [project](https://roge.github.io) | [B station](https://www.bilibili.com/video/BV1E8tB65EdW)
  - 用相机射线查询隐式几何特征，并与视频 diffusion 端到端联合训练，实现稀疏输入下的可控新视角视频生成。
- **Learning Global Camera Poses from Noisy View-Graphs for Structure from Motion** - arXiv 2026 | [arXiv:2609.09491](https://arxiv.org/abs/2609.09491) | [B station](https://www.bilibili.com/video/BV13AY56VEyD)
  - 用边上带噪的相对位姿学习全局相机位姿，再通过三角化和鲁棒束调整恢复结构。
- **PanoGS: Gaussian-based Panoptic Segmentation for 3D Open Vocabulary Scene Understanding** - CVPR 2025 | [project](https://zju3dv.github.io/panogs) | [B station](https://www.bilibili.com/video/BV123gL6jEtC)
  - PanoGS 用连续三平面语言场与语言引导图聚类，让 3D Gaussian Splatting 同时回答“是什么”和“是哪一个实例”。
- **Emergent Multi-View Geometry Through Self-Distillation** - arXiv 2026 | [arXiv:2609.39227](https://arxiv.org/abs/2609.39227) | [B station](https://www.bilibili.com/video/BV1yTpG6iEQw)
  - 用教师额外看到的场景视角，约束学生在遮挡和增强条件下学习外观不变、几何一致的特征。
- **Per-View Gaussian Predictions Enable Training-Free Distractor Filtering in Feed-Forward 3DGS** - arXiv 2026 | [arXiv:2608.26951](https://arxiv.org/abs/2608.26951) | [B station](https://www.bilibili.com/video/BV1rQtn6KEWR)
  - 通过暂时排除某个输入视角关联的高斯、在其他输入视角上验证误差是否下降，实现无需训练的干扰物过滤。
- **ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis** - IEEE TPAMI 2025 | [project](https://doi.org/10.1109/TPAMI.2025.3613256) | [B station](https://www.bilibili.com/video/BV1zggE6yEzt)
  - 用点云提供可执行的六自由度相机约束，再让视频扩散模型修复粗糙几何，并通过迭代视角规划把单图拓展为长程一致的新视角序列。
- **OpenGraph: Open-Vocabulary Hierarchical 3D Graph Representation in Large-Scale Outdoor Environments** - IEEE RA-L 2024 | [arXiv:2403.09412](https://arxiv.org/abs/2403.09412) | [project](https://doi.org/10.1109/LRA.2024.3445607) | [B station](https://www.bilibili.com/video/BV1hQgJ6vEaT)
  - 用实例 caption 连接视觉与语言推理，再将对象、车道与区域组织成五层户外三维图。
- **MV2GF: Multi-view Pedestrian Detection with a Visual Geometric Foundation Model** - arXiv 2026 | [arXiv:2608.20639](https://arxiv.org/abs/2608.20639) | [B station](https://www.bilibili.com/video/BV1BkhM6vEBD)
  - 用冻结的视觉几何基础模型提供跨视角几何，用 TGF 与 FPA 把它转化为更稳健的鸟瞰图检测。
- **4DStreamCtrl: Interactive Video Generation with Online 4D Control** - arXiv 2026 | [arXiv:2608.25479](https://arxiv.org/abs/2608.25479) | [project](https://4dstreamctrl.github.io/) | [B station](https://www.bilibili.com/video/BV1Pt4f6VELm)
  - 用统一的三维点轨迹表达相机、物体和深度控制，并以四步因果蒸馏实现长视频在线生成。
- **Spackle: Completing Large View Single Image NVS with Adaptive Gaussians** - arXiv 2026 | [arXiv:2609.30941](https://arxiv.org/abs/2609.30941) | [B station](https://www.bilibili.com/video/BV1Nap461Emi)
  - 用冻结的基础 3DGS 保住可见区域，再用掩码约束的残差高斯只补足大视角下的缺失区域。
- **SLAMFormer-∞: Infinite SLAM Transformer for Unbounded Frontend and Backend Processing** - arXiv 2026 | [B station](https://www.bilibili.com/video/BV1iMg568EzA)
  - 用 memory condition 把同一个几何 Transformer 延伸到无界长序列，并用 PGGO 同时细化相机轨迹与稠密几何。
- **WildHSR: Metric Feed-Forward 4D People-Scene Reconstruction from a 3D Foundation Model** - arXiv 2026 | [arXiv:2609.29106](https://arxiv.org/abs/2609.29106) | [B station](https://www.bilibili.com/video/BV1Vepv6jEvF)
  - 用人体产生的尺度伪标签适配 up-to-scale 三维基础模型，再从其中读出跨帧身份对应，最终在一个度量世界中联合重建人体、相机和场景。
- **RIDE: Relocalization-Informed Depth Estimation with 3D Gaussian Splatting** - arXiv 2026 | [arXiv:2609.11079](https://arxiv.org/abs/2609.11079) | [B station](https://www.bilibili.com/video/BV1ZiYD6xEZC)
  - 从 PnP-RANSAC 内点提取稀疏度量锚点，校准冻结的 VDA-S 相对深度先验，输出带有全局、局部及时序一致性的稠密 metric depth。
- **Track, Articulate, Act: Generating Articulation from Casual Human Videos** - arXiv 2026 | [arXiv:2609.19119](https://arxiv.org/abs/2609.19119) | [project](https://track-articulate-act.github.io) | [B station](https://www.bilibili.com/video/BV1tSeC6tEbD)
  - 用密集 3D 点轨迹区分静止与运动部件，拟合转动或平移关节，再把重建的物体和手部动作放入 MuJoCo，通过接触复现操作。
- **ActiveLang: Active Open-Vocabulary 3D Mapping with Semantic-Uncertainty-Guided Exploration** - arXiv 2026 | [arXiv:2610.09518](https://arxiv.org/abs/2610.09518) | [B station](https://www.bilibili.com/video/BV1nCp46ME7o)
  - 用在线自适应的紧凑语言特征表示，联合几何覆盖与语义不确定性选择下一观察位置。
- **Can Video Diffusion Model Reconstruct 4D Geometry?** - arXiv 2025 | [arXiv:2503.21082](https://arxiv.org/abs/2503.21082) | [project](https://wayne-mai.github.io/publication/sora3r_arxiv_2025/) | [B station](https://www.bilibili.com/video/BV12XgL6EEEm)
  - Sora3R 将视频扩散先验迁移到 4D pointmap，证明单目视频可经统一潜空间直接恢复动态几何。
- **Lucida: Parse, Generate, and Place for Composable Real-to-Sim Scene Modeling** - arXiv 2026 | [arXiv:2608.30821](https://arxiv.org/abs/2608.30821) | [project](https://lucida-r2s.github.io/) | [B station](https://www.bilibili.com/video/BV1vHtn6dEmq)
  - 用多视角对象证据完成资产生成，再用闭环九自由度 GizmoAct 把资产精确放回真实场景。
- **FunArt: Decoding Functional Structure and Articulation from Generative 3D Latents** - arXiv 2026 | [arXiv:2609.20673](https://arxiv.org/abs/2609.20673) | [B station](https://www.bilibili.com/video/BV1P8e46TEMT)
  - 用冻结的生成式 3D 几何特征和轻量查询解码器，把静态 RGB-D 场景转成带功能元素与运动参数的层级场景图。
- **CADSplat: Sparse-View 3D Gaussian Splatting Aided by CAD Models for Robust, Photorealistic Digital-Twin Reconstruction** - arXiv 2026 | [arXiv:2609.18473](https://arxiv.org/abs/2609.18473) | [B station](https://www.bilibili.com/video/BV1K9eC6REWx)
  - 以 CAD 表面为几何锚点，把稀疏图像中的姿态、形状偏差与 3DGS 外观放进同一个可优化框架。
- **AMB3R-SLAM: Kilometer-scale SLAM with Hierarchical Backend** - arXiv 2026 | [arXiv:2609.19518](https://arxiv.org/abs/2609.19518) | [B station](https://www.bilibili.com/video/BV1fze46FEjf)
  - 用前端保证低延迟跟踪，用分层后端逐步约束局部、中程与全局漂移，从而支持千米级长轨迹重建。
- **Scenethesis: A Language and Vision Agentic Framework for 3D Scene Generation** - arXiv 2025 | [arXiv:2505.02836](https://arxiv.org/abs/2505.02836) | [B station](https://www.bilibili.com/video/BV1Y6g76NEkF)
- **Lens3D: Target-Conditioned Visual Foveation for Fine-Grained 3D Understanding** - arXiv 2026 | [arXiv:2610.06611](https://arxiv.org/abs/2610.06611) | [B station](https://www.bilibili.com/video/BV19gp36yEVx)
  - 用 3D 定位引导多视角取证，再以特权信息蒸馏提升三维模型的细粒度对象理解。
- **OREO: Fidelity Alignment in 3D Generation via On-the-fly Rendering-Editing Optimization** - arXiv 2026 | [arXiv:2609.29788](https://arxiv.org/abs/2609.29788) | [B station](https://www.bilibili.com/video/BV16Sh265EAU)
  - 用在线生成的、结构对齐的二维伪目标，把二维视觉细节持续迁移到三维生成器。
- **NeRFifyMesh: Optimizing Neural Radiance Fields from Textured Meshes for Robotics Scene Building** - arXiv 2026 | [arXiv:2610.10387](https://arxiv.org/abs/2610.10387) | [B station](https://www.bilibili.com/video/BV1QApt6WE18)
  - 从纹理网格采样几何、颜色、占据和法向，直接训练紧凑的 NeRF，并将其用于渲染、表面恢复、场景组合和机器人碰撞模拟。
- **Argos: Adapt Rich Geometric Priors for Generalizable Online Scene-Change-Detection** - arXiv 2026 | [arXiv:2610.10181](https://arxiv.org/abs/2610.10181) | [B station](https://www.bilibili.com/video/BV1cspt6gEbH)
  - 用冻结的几何基础模型特征结合跨访问共可见性比较，在检测变化的同时恢复相机、深度与变化感知的四维点云地图。
- **WeaveRL: Weaving Reconstruction into Scene-Aware Fabrics for Perceptive Reinforcement Learning** - arXiv 2026 | [arXiv:2609.18685](https://arxiv.org/abs/2609.18685) | [B station](https://www.bilibili.com/video/BV1Wpe169E4L)
  - 用可批量运行的 surfel 重建替换手工几何先验，让几何织物在训练和部署时都能查询实时、传感器导出的场景。
- **Lyra 2.0: Explorable Generative 3D Worlds** - arXiv 2026 | [arXiv:2604.13036](https://arxiv.org/abs/2604.13036) | [B station](https://www.bilibili.com/video/BV1w68B6sES3)
  - 用三维几何负责“找对历史”，用视频生成先验负责“生成外观”，再将长视频稳定地提升为可浏览的三维资产。
- **CoANeRV: Coordinate-Aware Token-Space Neural Video Representation** - arXiv 2026 | [B station](https://www.bilibili.com/video/BV1B1br69Eou)
- **UVGS: Reimagining Unstructured 3D Gaussian Splatting using UV Mapping** - CVPR 2025 | [arXiv:2502.01846](https://arxiv.org/abs/2502.01846) | [B station](https://www.bilibili.com/video/BV1regH6REwW)
  - UVGS 先把 3D Gaussian primitives 球面展开成有结构的 14 通道 UV map，再压成 3 通道 Super UVGS，从而直接复用成熟的 2D Autoencoder 与 diffusion model。
- **CoMVS-GS: Collaborative Multi-View Stereo and 3D Gaussian Splatting for Surface Reconstruction** - arXiv 2026 | [arXiv:2608.18413](https://arxiv.org/abs/2608.18413) | [B station](https://www.bilibili.com/video/BV1YY8q6gEf3)
  - MVS 提供几何证据，3DGS 提供可优化的显式表示，二者共同服务于更准确、更紧凑的表面重建。
- **Seeing the World and the Self from Egocentric Video** - arXiv 2026 | [arXiv:2609.01276](https://arxiv.org/abs/2609.01276) | [B station](https://www.bilibili.com/video/BV1zFtd6ZES1)
  - RESELF 用度量几何约束场景，用条件扩散补全自我，再用人体运动反馈修正相机。
- **GenIA: Generative Reconstruction with Test-Time Input Alignment** - arXiv 2026 | [arXiv:2610.12388](https://arxiv.org/abs/2610.12388) | [project](https://facebookresearch.github.io/GenIA) | [B station](https://www.bilibili.com/video/BV1k9pv6YEXg)
  - 在冻结生成先验上施加几何、可见性和渲染约束，让完整三维生成结果忠实对齐观测，并扩展到多视图与动态对象。
- **DecoGS: Adaptive Static-Dynamic Decoupling of 3D Gaussians for Free-Viewpoint Video Streaming** - arXiv 2026 | [arXiv:2609.17230](https://arxiv.org/abs/2609.17230) | [B station](https://www.bilibili.com/video/BV11YeM6HEnU)
  - 用自适应静动态解耦和选择性三维高斯优化，降低在线更新冗余并提升流式自由视点视频的质量与时间稳定性。
- **OuroWorld: Bringing Any 3D World Alive as Diverse, Endlessly Looping 3D Cinemagraphs** - arXiv 2026 | [arXiv:2610.12461](https://arxiv.org/abs/2610.12461) | [project](https://ouroworld.userwei.com) | [B station](https://www.bilibili.com/video/BV1Rupe6CEg3)
  - 从任意静态 3DGS 出发，以视频生成先验获得多样运动，再用周期四维表示输出可自由视角、无缝循环的三维动态照片。
- **Tetris3D: 3D Scene Generation With Objects That Fit Together** - arXiv 2026 | [arXiv:2610.10539](https://arxiv.org/abs/2610.10539) | [B station](https://www.bilibili.com/video/BV16Cp46MED4)
  - 通过邻域几何、物理关系和可见到不可见注意力，逐物体生成能够共同契合的三维场景。
- **Pyramid Diffusion for Fine 3D Large Scene Generation** - ECCV 2024 | [arXiv:2311.12085](https://arxiv.org/abs/2311.12085) | [project](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08675.pdf) | [B station](https://www.bilibili.com/video/BV1dogj6eEA7)
  - 用多个尺度专精的离散扩散模型，把高成本的大场景生成拆成“先定结构、再补细节”的连续过程。
- **M3GD: Multi-Modal Multi-View Geometric Diffusion for Camera--LiDAR Novel View Synthesis** - arXiv 2026 | [arXiv:2609.30056](https://arxiv.org/abs/2609.30056) | [B station](https://www.bilibili.com/video/BV1oDh26kEzU)
  - 将投影后的 LiDAR 几何统计和冻结点云特征作为目标视图的几何查询，接入已有的多视角图像潜空间生成器。
- **Dyna3: VLM-Guided Training-Free 4D Reconstruction via Depth Foundation Models** - arXiv 2026 | [arXiv:2610.01286](https://arxiv.org/abs/2610.01286) | [B station](https://www.bilibili.com/video/BV1j1p36DEh9)
  - 冻结 DA3，不做微调；用特征最佳匹配产生运动先验，用 VLM 引导 SAM 3 识别实例，再解耦重建静态背景和动态前景。
- **GenNVS: Geometry-enhanced Novel View Synthesis via Disentangled 3D Prior** - arXiv 2026 | [arXiv:2609.34579](https://arxiv.org/abs/2609.34579) | [B station](https://www.bilibili.com/video/BV1ofph6kEJP)
  - 将对象级几何、场景级布局和双流几何条件结合起来，生成结构更稳定的新视角视频。
- **Concept-Guided Exploration: Building Persistent, Actionable Scene Graphs** - arXiv 2026 | [arXiv:2608.23650](https://arxiv.org/abs/2608.23650) | [B station](https://www.bilibili.com/video/BV184hA6gEGs)
  - 从无先验全局地图开始，以异步房间与门概念代理增量构建可行动的持久场景图。
- **DensiTok: Making Feed-Forward 3D Gaussian Splatting See More Views Than It Is Given** - arXiv 2026 | [arXiv:2610.07958](https://arxiv.org/abs/2610.07958) | [B station](https://www.bilibili.com/video/BV1pYp36fEHT)
  - DensiTok 在预训练前馈式 3DGS 的 geometry encoder 与 reconstruction heads 之间，补全未观测视角的 geometry tokens。
- **AdaOcc: Adaptive 3D Occupancy Prediction for Embodied Tasks** - arXiv 2026 | [arXiv:2609.38864](https://arxiv.org/abs/2609.38864) | [project](https://wangjl-nb.github.io/AdaOcc_web/) | [B station](https://www.bilibili.com/video/BV1SrpG6GEBr)
  - 用统一的几何点接口、渐进式点查询和 containment loss，实现面向具身场景的传感器自适应、视角自适应与预算自适应占据预测。
- **Stabilizing Camera-Controlled Novel View Synthesis at Inference Time** - arXiv 2026 | [arXiv:2609.03639](https://arxiv.org/abs/2609.03639) | [B station](https://www.bilibili.com/video/BV1h5bE62E6D)
  - 以小步自回归相机轨迹为主线，在推理时稳定单图像新视角合成，并兼顾几何一致性、外观稳定性与生成效率。