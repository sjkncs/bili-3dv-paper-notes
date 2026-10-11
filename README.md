# 3D 视觉论文解读清单（B 站 HyperHorizon）

> 来源：B 站 UP 主 **HyperHorizon**（mid \11470647\）的合集「3D视觉论文解读」（season_id \8981267\）。
> 快照日期：**2026-10-11**，共 **229** 集，归入 **12** 个分类。
> 结构化数据：[papers.json](papers.json)

## 数据来源 · 计算方法 · 口径限制

**数据来源**：B 站公开接口 \x/polymer/web-space/seasons_archives_list\（mid 11470647、season 8981267，分 3 页各 100 条抓取）。

**计算方法**：标题按开头的 \【…】\ 拆出分类，括号内若含 \｜\ 则前半为会议、后半为分类；论文名取第一个 ASCII 冒号之前的部分；时长与播放量直接取接口字段。

**口径限制（重要，必读）**
- **B 站对视频标题有 80 字符硬上限**。本清单 **136 / 229** 条标题在词中间被切断，且合集接口与 \iew\ 接口返回的都是同一个 80 字符串——**论文完整标题无法从平台获得，我没有猜测补齐**。
- 另有 **4 条**论文名内部含冒号，其"论文名"切分点存在歧义。
- 这是**待看队列，不是质量榜单**。顺序即投稿顺序；\iews\ 只是弱热度信号，不能当作重要程度。
- 本仓库**只索引标题、时长、链接**，不含视频、字幕或笔记。

## 分类分布

| category | count |
|---|---:|
| 3D重建 | 75 |
| 3D生成 | 43 |
| 3D理解 | 40 |
| 3DGS | 23 |
| 深度估计 | 15 |
| SLAM | 12 |
| 神经渲染 | 11 |
| 3D理解·Benchmark | 3 |
| 3D重建·Benchmark | 3 |
| 3D重建·Dataset | 2 |
| 3D生成·Benchmark | 1 |
| 神经渲染·Dataset | 1 |


## 全部 229 集

| # | BVID | paper | category | venue | length | views |
|---:|---|---|---|---|---:|---:|
| 1 | [BV11cbf6mE1e](https://www.bilibili.com/video/BV11cbf6mE1e) | SPVC (title cut at 80 chars) | 神经渲染·Dataset | - | 15:52 | 120 |
| 2 | [BV123gL6jEtC](https://www.bilibili.com/video/BV123gL6jEtC) | PanoGS (title cut at 80 chars) | 3D理解 | CVPR 2025 | 16:18 | 299 |
| 3 | [BV12Gg76WEy7](https://www.bilibili.com/video/BV12Gg76WEy7) | PanoDreamer | 3D生成 | CVPRW 2025 | 17:48 | 43 |
| 4 | [BV12Rhw6wEoM](https://www.bilibili.com/video/BV12Rhw6wEoM) | Joint-Embedding Prediction of Masked Point Tubes for Self-Supervised Learn (title cut at 80 chars) | 3D理解 | - | 18:43 | 127 |
| 5 | [BV12V8D6hE8r](https://www.bilibili.com/video/BV12V8D6hE8r) | GaussVid (title cut at 80 chars) | 3DGS | - | 16:21 | 400 |
| 6 | [BV12XgL6EEEm](https://www.bilibili.com/video/BV12XgL6EEEm) | Sora3R | 3D重建 | - | 17:03 | 204 |
| 7 | [BV13KbZ6xETb](https://www.bilibili.com/video/BV13KbZ6xETb) | Scalix | SLAM | - | 15:01 | 347 |
| 8 | [BV14G8D6wECK](https://www.bilibili.com/video/BV14G8D6wECK) | NemoSplat (title cut at 80 chars) | 3D重建 | - | 16:16 | 331 |
| 9 | [BV14Xh36sEWs](https://www.bilibili.com/video/BV14Xh36sEWs) | Stream3Dv2 (title cut at 80 chars) | 3D理解 | - | 15:52 | 195 |
| 10 | [BV15n8M6dEQj](https://www.bilibili.com/video/BV15n8M6dEQj) | DyG²T | 3DGS | - | 15:55 | 311 |
| 11 | [BV1818T6SEpE](https://www.bilibili.com/video/BV1818T6SEpE) | Beyond Placement and Articulation (title cut at 80 chars) | 3D理解 | - | 15:00 | 102 |
| 12 | [BV184hA6gEGs](https://www.bilibili.com/video/BV184hA6gEGs) | Concept-Guided Exploration | 3D理解 | - | 16:14 | 72 |
| 13 | [BV197tN6VEkV](https://www.bilibili.com/video/BV197tN6VEkV) | FLARE (title cut at 80 chars) | 3D重建 | CVPR 2025 | 18:57 | 256 |
| 14 | [BV19fgj6AEbd](https://www.bilibili.com/video/BV19fgj6AEbd) | Prim2Room | 3D生成 | - | 17:37 | 42 |
| 15 | [BV1A6hG6pEki](https://www.bilibili.com/video/BV1A6hG6pEki) | ArtiMo | 3D理解 | - | 15:42 | 113 |
| 16 | [BV1Aogw6uEW6](https://www.bilibili.com/video/BV1Aogw6uEW6) | StudioRecon (title cut at 80 chars) | 3D重建 | SIGGRAPH 2026 | 14:45 | 104 |
| 17 | [BV1B1br69Eou](https://www.bilibili.com/video/BV1B1br69Eou) | CoANeRV | 神经渲染 | - | 22:20 | 102 |
| 18 | [BV1B8gL6PEcc](https://www.bilibili.com/video/BV1B8gL6PEcc) | OpenFunGraph (title cut at 80 chars) | 3D理解 | CVPR 2025 | 15:28 | 68 |
| 19 | [BV1BkhM6vEBD](https://www.bilibili.com/video/BV1BkhM6vEBD) | MV2GF (title cut at 80 chars) | 3D理解 | - | 14:54 | 282 |
| 20 | [BV1C7gL6GEpj](https://www.bilibili.com/video/BV1C7gL6GEpj) | Pixel-Perfect Depth with Semantics-Prompted Diffusion Transfo (title cut at 80 chars) | 深度估计 | NeurIPS 2025 | 17:05 | 63 |
| 21 | [BV1DKg76tECf](https://www.bilibili.com/video/BV1DKg76tECf) | OpenOcc (title cut at 80 chars) | 3D重建 | IROS 2024 | 16:05 | 116 |
| 22 | [BV1DUgJ6qEZs](https://www.bilibili.com/video/BV1DUgJ6qEZs) | OmniIndoor3D | 3D重建 | - | 15:25 | 138 |
| 23 | [BV1DzhF6eExB](https://www.bilibili.com/video/BV1DzhF6eExB) | NeoWorld-Pro (title cut at 80 chars) | 3D重建 | - | 15:51 | 180 |
| 24 | [BV1E64f6NE8H](https://www.bilibili.com/video/BV1E64f6NE8H) | PIVOT (title cut at 80 chars) | 3D重建·Benchmark | - | 14:49 | 140 |
| 25 | [BV1EShG6jEej](https://www.bilibili.com/video/BV1EShG6jEej) | Generating Multi-view Adversarial Examples for Visual Geometry Grounded Tr (title cut at 80 chars) | 3D理解 | - | 18:50 | 268 |
| 26 | [BV1EkgG6bELt](https://www.bilibili.com/video/BV1EkgG6bELt) | OccAnyScene | 3D理解 | - | 10:30 | 136 |
| 27 | [BV1Fr8B69End](https://www.bilibili.com/video/BV1Fr8B69End) | Habitat-GS (title cut at 80 chars) | 3DGS | - | 16:17 | 163 |
| 28 | [BV1Fsbd6vEWU](https://www.bilibili.com/video/BV1Fsbd6vEWU) | GeoWeaver (title cut at 80 chars) | 3D重建 | - | 18:17 | 244 |
| 29 | [BV1GKbZ6xEp8](https://www.bilibili.com/video/BV1GKbZ6xEp8) | MemTree3D (title cut at 80 chars) | 3D理解 | ECCV 2026 | 16:44 | 353 |
| 30 | [BV1GntN6GEnX](https://www.bilibili.com/video/BV1GntN6GEnX) | LingBot-Map | SLAM | - | 14:35 | 600 |
| 31 | [BV1GpgE6iERZ](https://www.bilibili.com/video/BV1GpgE6iERZ) | Uni-3DAR (title cut at 80 chars) | 3D生成 | - | 16:28 | 69 |
| 32 | [BV1GxgE6eEwe](https://www.bilibili.com/video/BV1GxgE6eEwe) | TRELLIS (title cut at 80 chars) | 3D生成 | CVPR 2025 | 16:29 | 76 |
| 33 | [BV1HJhF6EEf7](https://www.bilibili.com/video/BV1HJhF6EEf7) | SceneReGen | 3D生成 | - | 16:22 | 536 |
| 34 | [BV1HQtn6KEQD](https://www.bilibili.com/video/BV1HQtn6KEQD) | Generative Semantic Scene Completion | 3D理解 | - | 21:36 | 195 |
| 35 | [BV1L58B6GE3T](https://www.bilibili.com/video/BV1L58B6GE3T) | InfiniDepth (title cut at 80 chars) | 深度估计 | - | 16:20 | 151 |
| 36 | [BV1LjgE66EEK](https://www.bilibili.com/video/BV1LjgE66EEK) | TextSplat (title cut at 80 chars) | 3D重建 | ACM MM 2025 | 18:28 | 36 |
| 37 | [BV1Myb66iECg](https://www.bilibili.com/video/BV1Myb66iECg) | ViPE | SLAM | - | 16:04 | 544 |
| 38 | [BV1N5gL6LE5z](https://www.bilibili.com/video/BV1N5gL6LE5z) | GaussianFlowOcc (title cut at 80 chars) | 3DGS | ICCV 2025 | 14:42 | 62 |
| 39 | [BV1PdgL67Ek2](https://www.bilibili.com/video/BV1PdgL67Ek2) | VoxelSplat (title cut at 80 chars) | 3DGS | CVPR 2025 | 19:05 | 201 |
| 40 | [BV1Peg56kEE6](https://www.bilibili.com/video/BV1Peg56kEE6) | SLAM-Former | SLAM | ECCV 2026 | 13:42 | 1308 |
| 41 | [BV1Pt4f6VELm](https://www.bilibili.com/video/BV1Pt4f6VELm) | 4DStreamCtrl | 3D生成 | - | 16:08 | 282 |
| 42 | [BV1QHtN66Er6](https://www.bilibili.com/video/BV1QHtN66Er6) | DepthLab | 深度估计 | - | 14:38 | 192 |
| 43 | [BV1QTbZ6RESt](https://www.bilibili.com/video/BV1QTbZ6RESt) | UniQuery4R | 3D重建 | - | 15:17 | 156 |
| 44 | [BV1R6bZ6wE9i](https://www.bilibili.com/video/BV1R6bZ6wE9i) | GenRec | 神经渲染 | - | 15:43 | 984 |
| 45 | [BV1Rdgj6NEjC](https://www.bilibili.com/video/BV1Rdgj6NEjC) | Prometheus (title cut at 80 chars) | 3D生成 | CVPR 2025 | 15:19 | 229 |
| 46 | [BV1TsGP6dETR](https://www.bilibili.com/video/BV1TsGP6dETR) | SM4RT | 3D重建 | - | 13:12 | 268 |
| 47 | [BV1VL8P6CEkD](https://www.bilibili.com/video/BV1VL8P6CEkD) | Self-Geometry (title cut at 80 chars) | 3D理解 | - | 17:16 | 295 |
| 48 | [BV1WbgH6FE81](https://www.bilibili.com/video/BV1WbgH6FE81) | OccScene (title cut at 80 chars) | 3D生成 | TPAMI 2025 | 15:58 | 157 |
| 49 | [BV1WfgL65EJa](https://www.bilibili.com/video/BV1WfgL65EJa) | VideoScene (title cut at 80 chars) | 3D生成 | CVPR 2025 | 21:24 | 71 |
| 50 | [BV1Y6g76NEkF](https://www.bilibili.com/video/BV1Y6g76NEkF) | Scenethesis (title cut at 80 chars) | 3D生成 | ICLR 2026 | 17:24 | 65 |
| 51 | [BV1YY8q6gEf3](https://www.bilibili.com/video/BV1YY8q6gEf3) | CoMVS-GS (title cut at 80 chars) | 3D重建 | - | 15:26 | 355 |
| 52 | [BV1Yrg76eEM2](https://www.bilibili.com/video/BV1Yrg76eEM2) | SceneEval (title cut at 80 chars) | 3D生成·Benchmark | WACV 2026 | 15:42 | 20 |
| 53 | [BV1Yyg76aEK5](https://www.bilibili.com/video/BV1Yyg76aEK5) | StreetCrafter (title cut at 80 chars) | 神经渲染 | CVPR 2025 | 18:09 | 130 |
| 54 | [BV1cU896NErE](https://www.bilibili.com/video/BV1cU896NErE) | TransHands | 3D理解 | - | 15:46 | 74 |
| 55 | [BV1cqtW6VEZE](https://www.bilibili.com/video/BV1cqtW6VEZE) | MILO (title cut at 80 chars) | 3D重建 | - | 15:18 | 138 |
| 56 | [BV1dogj6eEA7](https://www.bilibili.com/video/BV1dogj6eEA7) | Pyramid Diffusion for Fine 3D Large Scene Generation | 3D生成 | ECCV 2024 | 16:33 | 35 |
| 57 | [BV1fGhA6SE7N](https://www.bilibili.com/video/BV1fGhA6SE7N) | DDMS | 3D理解 | - | 16:28 | 346 |
| 58 | [BV1hHhG6vE7d](https://www.bilibili.com/video/BV1hHhG6vE7d) | DiGS-Avatar (title cut at 80 chars) | 3D重建 | - | 17:16 | 49 |
| 59 | [BV1hQgJ6vEaT](https://www.bilibili.com/video/BV1hQgJ6vEaT) | OpenGraph (title cut at 80 chars) | 3D理解 | RA-L 2024 | 18:07 | 189 |
| 60 | [BV1hq8q6qEDv](https://www.bilibili.com/video/BV1hq8q6qEDv) | LT-Mem (title cut at 80 chars) | 3D理解 | IROS 2026 | 15:02 | 56 |
| 61 | [BV1iD8S6jExT](https://www.bilibili.com/video/BV1iD8S6jExT) | AquaFlow (title cut at 80 chars) | SLAM | - | 18:53 | 248 |
| 62 | [BV1iMg568EzA](https://www.bilibili.com/video/BV1iMg568EzA) | SLAMFormer-∞ | SLAM | - | 13:42 | 253 |
| 63 | [BV1iQ8S61EA6](https://www.bilibili.com/video/BV1iQ8S61EA6) | Photorealistic Novel View Synthesis of Human Faces using Next-Scale Transf (title cut at 80 chars) | 3D重建 | - | 14:29 | 67 |
| 64 | [BV1ivg76BEyo](https://www.bilibili.com/video/BV1ivg76BEyo) | RayZer | 神经渲染 | ICCV 2025 | 16:12 | 65 |
| 65 | [BV1j5hG6gEPy](https://www.bilibili.com/video/BV1j5hG6gEPy) | M2Depth | 深度估计 | - | 15:35 | 126 |
| 66 | [BV1jugj6qESP](https://www.bilibili.com/video/BV1jugj6qESP) | ReViV (title cut at 80 chars) | 3D重建 | ECCV 2026 | 14:43 | 91 |
| 67 | [BV1kHhV6WEc4](https://www.bilibili.com/video/BV1kHhV6WEc4) | TopoSurfel (title cut at 80 chars) | 3D重建 | - | 21:18 | 417 |
| 68 | [BV1mDgL6SExs](https://www.bilibili.com/video/BV1mDgL6SExs) | RichDreamer (title cut at 80 chars) | 3D生成 | CVPR 2024 | 16:34 | 100 |
| 69 | [BV1mVg76XEuC](https://www.bilibili.com/video/BV1mVg76XEuC) | Representing Long Volumetric Video with Temporal Gaussian Hierarc (title cut at 80 chars) | 神经渲染 | TOG 2024 | 16:58 | 84 |
| 70 | [BV1mhtN6eEYG](https://www.bilibili.com/video/BV1mhtN6eEYG) | LingBot-Depth | 深度估计 | - | 14:43 | 590 |
| 71 | [BV1nC8B6pEdm](https://www.bilibili.com/video/BV1nC8B6pEdm) | GaussianGPT | 3D生成 | ECCV 2026 | 15:38 | 506 |
| 72 | [BV1nTgE62Eco](https://www.bilibili.com/video/BV1nTgE62Eco) | UniDepthV2 (title cut at 80 chars) | 深度估计 | TPAMI 2026 | 17:11 | 218 |
| 73 | [BV1oR8M6aEYm](https://www.bilibili.com/video/BV1oR8M6aEYm) | LumiTokens | 神经渲染 | - | 17:24 | 362 |
| 74 | [BV1oXgj6TEr3](https://www.bilibili.com/video/BV1oXgj6TEr3) | PanSplat (title cut at 80 chars) | 3DGS | CVPR 2025 | 18:13 | 44 |
| 75 | [BV1ohgL6YE5Y](https://www.bilibili.com/video/BV1ohgL6YE5Y) | UniversalSG | 3D理解 | CVPR 2025 | 18:32 | 61 |
| 76 | [BV1pN8g6yEDo](https://www.bilibili.com/video/BV1pN8g6yEDo) | HiCo-GS (title cut at 80 chars) | 3D重建 | ACM MM 2026 | 15:31 | 294 |
| 77 | [BV1rQtn6KEWR](https://www.bilibili.com/video/BV1rQtn6KEWR) | Per-View Gaussian Predictions Enable Training-Free Distractor Filtering in (title cut at 80 chars) | 3DGS | - | 15:28 | 449 |
| 78 | [BV1regH6REwW](https://www.bilibili.com/video/BV1regH6REwW) | UVGS (title cut at 80 chars) | 3DGS | CVPR 2025 | 18:35 | 147 |
| 79 | [BV1rpg762EQE](https://www.bilibili.com/video/BV1rpg762EQE) | RoboGSim | 3DGS | - | 16:55 | 257 |
| 80 | [BV1rwhA64ECf](https://www.bilibili.com/video/BV1rwhA64ECf) | Luce | 3D生成 | - | 16:16 | 187 |
| 81 | [BV1sog76WEaK](https://www.bilibili.com/video/BV1sog76WEaK) | ScanNet (title cut at 80 chars) | 3D重建·Dataset | CVPR 2017 | 15:44 | 47 |
| 82 | [BV1tDg76tEUc](https://www.bilibili.com/video/BV1tDg76tEUc) | SGFormer (title cut at 80 chars) | 3D理解 | CVPR 2025 | 16:42 | 129 |
| 83 | [BV1vpbf6YEDs](https://www.bilibili.com/video/BV1vpbf6YEDs) | GroupForward (title cut at 80 chars) | 3D重建 | - | 19:47 | 272 |
| 84 | [BV1w68B6sES3](https://www.bilibili.com/video/BV1w68B6sES3) | Lyra 2.0 | 3D生成 | - | 17:04 | 146 |
| 85 | [BV1wxg761EjA](https://www.bilibili.com/video/BV1wxg761EjA) | RelationField | 3D理解 | CVPR 2025 | 17:59 | 74 |
| 86 | [BV1xRg76REQk](https://www.bilibili.com/video/BV1xRg76REQk) | SAR3D | 3D生成 | CVPR 2025 | 15:12 | 90 |
| 87 | [BV1yJg76UEM4](https://www.bilibili.com/video/BV1yJg76UEM4) | RoboOcc (title cut at 80 chars) | 3D理解 | - | 17:09 | 202 |
| 88 | [BV1yogL61EXT](https://www.bilibili.com/video/BV1yogL61EXT) | WorldScore (title cut at 80 chars) | 3D理解·Benchmark | ICCV 2025 | 20:42 | 77 |
| 89 | [BV1yv876TE2h](https://www.bilibili.com/video/BV1yv876TE2h) | MegaParts (title cut at 80 chars) | 3D生成 | - | 16:00 | 57 |
| 90 | [BV1zggE6yEzt](https://www.bilibili.com/video/BV1zggE6yEzt) | ViewCrafter (title cut at 80 chars) | 3D重建 | TPAMI 2025 | 19:10 | 76 |
| 91 | [BV1zhg763EM4](https://www.bilibili.com/video/BV1zhg763EM4) | R3DS | 3D理解 | ECCV 2024 | 17:07 | 60 |
| 92 | [BV1zsgL6qE3G](https://www.bilibili.com/video/BV1zsgL6qE3G) | VistaDream | 3D重建 | ICCV 2025 | 16:15 | 86 |
| 93 | [BV1Eitg6iEQ1](https://www.bilibili.com/video/BV1Eitg6iEQ1) | MAGP (title cut at 80 chars) | 深度估计 | - | 15:23 | 140 |
| 94 | [BV1eTtg64Epo](https://www.bilibili.com/video/BV1eTtg64Epo) | ABot-Recon | 3D重建 | - | 16:06 | 355 |
| 95 | [BV1Bctg68EYU](https://www.bilibili.com/video/BV1Bctg68EYU) | Cyc3D (title cut at 80 chars) | 3D生成 | - | 16:14 | 70 |
| 96 | [BV1yrtT6vEVJ](https://www.bilibili.com/video/BV1yrtT6vEVJ) | Manifold4D (title cut at 80 chars) | 3D重建 | - | 15:07 | 360 |
| 97 | [BV1A2tT6AEt2](https://www.bilibili.com/video/BV1A2tT6AEt2) | WilLaGS (title cut at 80 chars) | 3DGS | - | 17:07 | 236 |
| 98 | [BV1Untg62E3M](https://www.bilibili.com/video/BV1Untg62E3M) | GeoFF3D (title cut at 80 chars) | 3D重建 | - | 15:08 | 232 |
| 99 | [BV12RtL6ZEN8](https://www.bilibili.com/video/BV12RtL6ZEN8) | SPAR (title cut at 80 chars) | 3D重建 | - | 15:56 | 326 |
| 100 | [BV1izt76mEsF](https://www.bilibili.com/video/BV1izt76mEsF) | Generation of High-Level Concepts in 3D Scene Graphs via Autoregressive Di (title cut at 80 chars) | 3D生成 | - | 14:26 | 300 |
| 101 | [BV1LBt76EEk4](https://www.bilibili.com/video/BV1LBt76EEk4) | ReconSplat | 3D重建 | - | 15:20 | 542 |
| 102 | [BV1J8t769EGt](https://www.bilibili.com/video/BV1J8t769EGt) | Chat-Edit-3D++ (title cut at 80 chars) | 3D理解 | - | 15:41 | 144 |
| 103 | [BV1Zat76HE6N](https://www.bilibili.com/video/BV1Zat76HE6N) | ScenePilot (title cut at 80 chars) | 3D生成 | - | 15:49 | 82 |
| 104 | [BV16jtn6FEcv](https://www.bilibili.com/video/BV16jtn6FEcv) | CapFrame (title cut at 80 chars) | 3DGS | - | 15:51 | 90 |
| 105 | [BV1vHtn6dEmq](https://www.bilibili.com/video/BV1vHtn6dEmq) | Lucida (title cut at 80 chars) | 3D重建 | - | 14:58 | 268 |
| 106 | [BV1vttR6SEV9](https://www.bilibili.com/video/BV1vttR6SEV9) | On-the-Fly3R | 3D重建 | - | 13:53 | 372 |
| 107 | [BV1x2tR6qEvZ](https://www.bilibili.com/video/BV1x2tR6qEvZ) | PLANET (title cut at 80 chars) | 3D理解 | - | 14:04 | 285 |
| 108 | [BV1bxtZ6UEe9](https://www.bilibili.com/video/BV1bxtZ6UEe9) | Monocular Depth Estimation from a Single Image | 深度估计 | - | 15:12 | 304 |
| 109 | [BV1zFtd6ZES1](https://www.bilibili.com/video/BV1zFtd6ZES1) | RESELF | 3D理解 | - | 15:26 | 325 |
| 110 | [BV1nZte6zEJD](https://www.bilibili.com/video/BV1nZte6zEJD) | TAPVid-MV (title cut at 80 chars) | 3D理解·Benchmark | - | 15:10 | 44 |
| 111 | [BV1note6gE91](https://www.bilibili.com/video/BV1note6gE91) | Query Rewriting for Complex Object Segmentation in 4D Gaussian Representat (title cut at 80 chars) | 3DGS | - | 13:23 | 132 |
| 112 | [BV1fktv6BEcD](https://www.bilibili.com/video/BV1fktv6BEcD) | InceptionGS (title cut at 80 chars) | 3D生成 | - | 15:41 | 285 |
| 113 | [BV1E8tB65EdW](https://www.bilibili.com/video/BV1E8tB65EdW) | RoGe (title cut at 80 chars) | 3D重建 | - | 13:10 | 178 |
| 114 | [BV1GKbW6tEFM](https://www.bilibili.com/video/BV1GKbW6tEFM) | Puffin-World (title cut at 80 chars) | 3D理解 | - | 14:54 | 92 |
| 115 | [BV15QbE6HEYG](https://www.bilibili.com/video/BV15QbE6HEYG) | SPAR3S (title cut at 80 chars) | 3D生成 | - | 15:12 | 491 |
| 116 | [BV1ajbE6LERG](https://www.bilibili.com/video/BV1ajbE6LERG) | Rethinking 3D Noise (title cut at 80 chars) | 3DGS | - | 16:00 | 348 |
| 117 | [BV1uubW6xEtX](https://www.bilibili.com/video/BV1uubW6xEtX) | Z3D (title cut at 80 chars) | 3D生成 | - | 15:24 | 269 |
| 118 | [BV1hJbE6VE4g](https://www.bilibili.com/video/BV1hJbE6VE4g) | Scal3R (title cut at 80 chars) | 3D重建 | - | 16:03 | 159 |
| 119 | [BV1h5bE62E6D](https://www.bilibili.com/video/BV1h5bE62E6D) | Stabilizing Camera-Controlled Novel View Synthesis at Inference Time | 神经渲染 | - | 15:42 | 145 |
| 120 | [BV1Wzb367EwJ](https://www.bilibili.com/video/BV1Wzb367EwJ) | NavArena (title cut at 80 chars) | 3D重建 | - | 17:41 | 561 |
| 121 | [BV1ecbG6wEfu](https://www.bilibili.com/video/BV1ecbG6wEfu) | PriorEdit3D | 3D理解 | - | 14:59 | 201 |
| 122 | [BV1WAbV6SEou](https://www.bilibili.com/video/BV1WAbV6SEou) | CrossDepth (title cut at 80 chars) | 深度估计 | - | 15:34 | 436 |
| 123 | [BV1cKbV6mEB7](https://www.bilibili.com/video/BV1cKbV6mEB7) | MINT (title cut at 80 chars) | 3D重建 | - | 15:49 | 243 |
| 124 | [BV15GeJ6iELz](https://www.bilibili.com/video/BV15GeJ6iELz) | VS-Splat (title cut at 80 chars) | 3D重建 | - | 16:20 | 297 |
| 125 | [BV1dEYK6FEAx](https://www.bilibili.com/video/BV1dEYK6FEAx) | FIRE3D | 3D重建 | - | 15:18 | 461 |
| 126 | [BV1xRYN62EDC](https://www.bilibili.com/video/BV1xRYN62EDC) | PRG-Fusion (title cut at 80 chars) | 3D重建 | - | 15:29 | 129 |
| 127 | [BV1T9YN67ESr](https://www.bilibili.com/video/BV1T9YN67ESr) | AVSplat (title cut at 80 chars) | 3D重建 | - | 14:34 | 232 |
| 128 | [BV1TZYN6yEwV](https://www.bilibili.com/video/BV1TZYN6yEwV) | PASTEL | 3D重建 | - | 16:05 | 181 |
| 129 | [BV1EhYN6AEbf](https://www.bilibili.com/video/BV1EhYN6AEbf) | Scaling 3D Generative Priors to Large-Scale Scene Meshes from Multi-View I (title cut at 80 chars) | 3D生成 | - | 16:27 | 377 |
| 130 | [BV1tTY566EvD](https://www.bilibili.com/video/BV1tTY566EvD) | Guiding Image-to-3D Generation with Test-Time Partial Observations | 3D生成 | - | 14:30 | 717 |
| 131 | [BV13AY56VEyD](https://www.bilibili.com/video/BV13AY56VEyD) | VGPA (title cut at 80 chars) | 3D重建 | - | 15:45 | 379 |
| 132 | [BV1fUYV6XEv5](https://www.bilibili.com/video/BV1fUYV6XEv5) | OmniPoint | 深度估计 | - | 15:14 | 320 |
| 133 | [BV1LcYE6cEpr](https://www.bilibili.com/video/BV1LcYE6cEpr) | Geometry Without Coordinates | 3D理解 | - | 14:28 | 117 |
| 134 | [BV1PBYV6hEbR](https://www.bilibili.com/video/BV1PBYV6hEbR) | RouteBridge (title cut at 80 chars) | 3D重建 | - | 15:32 | 83 |
| 135 | [BV1ZiYD6xEZC](https://www.bilibili.com/video/BV1ZiYD6xEZC) | RIDE | 深度估计 | - | 16:20 | 189 |
| 136 | [BV1UXYD6yECx](https://www.bilibili.com/video/BV1UXYD6yECx) | SAMV-DUSt3R | 3D重建 | - | 15:49 | 152 |
| 137 | [BV1e4Y96FEkk](https://www.bilibili.com/video/BV1e4Y96FEkk) | LangStreet | 3DGS | - | 14:51 | 208 |
| 138 | [BV17Lec6DEnf](https://www.bilibili.com/video/BV17Lec6DEnf) | Tele360 (title cut at 80 chars) | 3D重建 | - | 15:21 | 253 |
| 139 | [BV1Vnec67EzF](https://www.bilibili.com/video/BV1Vnec67EzF) | RIGOR | SLAM | - | 14:55 | 314 |
| 140 | [BV1B3ec6WEMj](https://www.bilibili.com/video/BV1B3ec6WEMj) | CGGT (title cut at 80 chars) | 3D重建 | - | 15:06 | 474 |
| 141 | [BV1ckeM6jEDJ](https://www.bilibili.com/video/BV1ckeM6jEDJ) | Bi-FlowGS (title cut at 80 chars) | 3D重建 | - | 14:33 | 376 |
| 142 | [BV11YeM6HEnU](https://www.bilibili.com/video/BV11YeM6HEnU) | DecoGS (title cut at 80 chars) | 3D重建 | - | 15:59 | 223 |
| 143 | [BV1KheM69EaE](https://www.bilibili.com/video/BV1KheM69EaE) | The Neverwhere Visual Parkour Benchmark Suite | 3D重建·Benchmark | - | 15:14 | 204 |
| 144 | [BV1YfeM6vEZK](https://www.bilibili.com/video/BV1YfeM6vEZK) | G3AR (title cut at 80 chars) | 3D重建 | - | 15:25 | 184 |
| 145 | [BV1WPeG6ZEgE](https://www.bilibili.com/video/BV1WPeG6ZEgE) | SceneHI (title cut at 80 chars) | 3D理解 | - | 15:15 | 144 |
| 146 | [BV1r2ey6EEqq](https://www.bilibili.com/video/BV1r2ey6EEqq) | IRIS | 3D重建 | - | 16:11 | 263 |
| 147 | [BV1tSeC6tEbD](https://www.bilibili.com/video/BV1tSeC6tEbD) | Track, Articulate, Act | 3D重建 | - | 14:14 | 202 |
| 148 | [BV1K9eC6REWx](https://www.bilibili.com/video/BV1K9eC6REWx) | CADSplat (title cut at 80 chars) | 3D重建 | - | 17:06 | 236 |
| 149 | [BV1Wpe169E4L](https://www.bilibili.com/video/BV1Wpe169E4L) | WeaveRL (title cut at 80 chars) | 3D重建 | - | 15:02 | 103 |
| 150 | [BV1znet6wEZD](https://www.bilibili.com/video/BV1znet6wEZD) | GRF-Recon (title cut at 80 chars) | SLAM | - | 17:20 | 343 |
| 151 | [BV1MAet6yEE5](https://www.bilibili.com/video/BV1MAet6yEE5) | ParticleSplat | 3D重建 | - | 15:13 | 330 |
| 152 | [BV1P8e46TEMT](https://www.bilibili.com/video/BV1P8e46TEMT) | FunArt (title cut at 80 chars) | 3D生成 | - | 15:27 | 77 |
| 153 | [BV1fze46FEjf](https://www.bilibili.com/video/BV1fze46FEjf) | AMB3R-SLAM | SLAM | - | 15:18 | 504 |
| 154 | [BV1txhk65E72](https://www.bilibili.com/video/BV1txhk65E72) | Adaptive World Memory 3D Foundation Model for Scalable 3D Mapping, Localiz (title cut at 80 chars) | SLAM | - | 14:53 | 273 |
| 155 | [BV1tZh76LEDm](https://www.bilibili.com/video/BV1tZh76LEDm) | VoxelTTO (title cut at 80 chars) | 3D重建 | - | 14:42 | 464 |
| 156 | [BV1H5hn6GE1Z](https://www.bilibili.com/video/BV1H5hn6GE1Z) | LoG-VGGT (title cut at 80 chars) | 3D重建 | - | 15:17 | 631 |
| 157 | [BV1pGhn6yEUK](https://www.bilibili.com/video/BV1pGhn6yEUK) | 4DGS-Fixer (title cut at 80 chars) | 3D生成 | - | 16:44 | 265 |
| 158 | [BV1umhp6tEco](https://www.bilibili.com/video/BV1umhp6tEco) | VGGT-CAD | 3D重建 | - | 15:45 | 359 |
| 159 | [BV1M1hp6fEiS](https://www.bilibili.com/video/BV1M1hp6fEiS) | Info3R | 深度估计 | - | 14:59 | 225 |
| 160 | [BV13Hhy6RE3z](https://www.bilibili.com/video/BV13Hhy6RE3z) | OREN-X | 3D重建 | - | 14:42 | 346 |
| 161 | [BV1G7hy6bELh](https://www.bilibili.com/video/BV1G7hy6bELh) | SplatLabel | 3DGS | - | 14:16 | 265 |
| 162 | [BV1CZhC63Eny](https://www.bilibili.com/video/BV1CZhC63Eny) | GrapeSplat (title cut at 80 chars) | 3D重建 | - | 15:20 | 204 |
| 163 | [BV1xXhC6yEFH](https://www.bilibili.com/video/BV1xXhC6yEFH) | VDGS | 3D重建 | - | 13:32 | 443 |
| 164 | [BV1oDh26kEzU](https://www.bilibili.com/video/BV1oDh26kEzU) | M3GD (title cut at 80 chars) | 3D生成 | - | 15:24 | 136 |
| 165 | [BV16Sh265EAU](https://www.bilibili.com/video/BV16Sh265EAU) | OREO | 3D生成 | - | 15:13 | 72 |
| 166 | [BV1Rdh26uECW](https://www.bilibili.com/video/BV1Rdh26uECW) | CODA (title cut at 80 chars) | 3D重建 | - | 15:38 | 202 |
| 167 | [BV1odh26uEJq](https://www.bilibili.com/video/BV1odh26uEJq) | $\phi$-RIE (title cut at 80 chars) | 3D重建 | - | 16:43 | 210 |
| 168 | [BV13wpx67ET2](https://www.bilibili.com/video/BV13wpx67ET2) | PePESeg3D (title cut at 80 chars) | 3DGS | - | 16:06 | 244 |
| 169 | [BV159ps6XEru](https://www.bilibili.com/video/BV159ps6XEru) | Mira-Scene | 3D生成 | - | 15:01 | 215 |
| 170 | [BV19Xps6pEmT](https://www.bilibili.com/video/BV19Xps6pEmT) | GAPS (title cut at 80 chars) | 3DGS | - | 15:14 | 71 |
| 171 | [BV1Vdps6HEFr](https://www.bilibili.com/video/BV1Vdps6HEFr) | AgentSTAR | 3D重建 | - | 15:58 | 93 |
| 172 | [BV1bsps6kELP](https://www.bilibili.com/video/BV1bsps6kELP) | Fysiverse-3D-Vision Technical Report | 3D生成 | - | 16:09 | 83 |
| 173 | [BV1Aqps6eEG8](https://www.bilibili.com/video/BV1Aqps6eEG8) | HARMONY (title cut at 80 chars) | 3D生成 | - | 15:51 | 55 |
| 174 | [BV1NVpt6mEDp](https://www.bilibili.com/video/BV1NVpt6mEDp) | OmniCam (title cut at 80 chars) | 3D理解 | - | 15:57 | 54 |
| 175 | [BV1PJpt6CEzY](https://www.bilibili.com/video/BV1PJpt6CEzY) | S2Tok | 3D重建 | - | 15:16 | 59 |
| 176 | [BV1cspt6gEbH](https://www.bilibili.com/video/BV1cspt6gEbH) | Argos (title cut at 80 chars) | 3D重建 | - | 15:15 | 55 |
| 177 | [BV16Cp46MED4](https://www.bilibili.com/video/BV16Cp46MED4) | Tetris3D | 3D生成 | - | 15:26 | 11 |
| 178 | [BV1nCp46ME7o](https://www.bilibili.com/video/BV1nCp46ME7o) | ActiveLang (title cut at 80 chars) | 3DGS | - | 13:58 | 5 |
| 179 | [BV1F2p46KEnd](https://www.bilibili.com/video/BV1F2p46KEnd) | DynStream (title cut at 80 chars) | 3D重建 | - | 14:01 | 100 |
| 180 | [BV1QApt6WE18](https://www.bilibili.com/video/BV1QApt6WE18) | NeRFifyMesh (title cut at 80 chars) | 3D重建 | - | 15:28 | 30 |
| 181 | [BV18sp46nEPo](https://www.bilibili.com/video/BV18sp46nEPo) | PlenoCI (title cut at 80 chars) | 3DGS | - | 14:54 | 21 |
| 182 | [BV1ABp46rELF](https://www.bilibili.com/video/BV1ABp46rELF) | TRACKGRAPH (title cut at 80 chars) | 3D理解 | - | 14:58 | 35 |
| 183 | [BV1crp46zE2C](https://www.bilibili.com/video/BV1crp46zE2C) | Reliability-Regulated Trajectory Optimization for Progressive COLMAP-Free | 3D重建 | - | 15:35 | 78 |
| 184 | [BV1Nap461Emi](https://www.bilibili.com/video/BV1Nap461Emi) | Spackle | 3D重建 | - | 15:55 | 45 |
| 185 | [BV1yvp46CER7](https://www.bilibili.com/video/BV1yvp46CER7) | GraphWrit3R | 3D理解 | - | 14:59 | 34 |
| 186 | [BV1tzph64ET2](https://www.bilibili.com/video/BV1tzph64ET2) | SceneScaffold (title cut at 80 chars) | 3D理解 | - | 14:23 | 280 |
| 187 | [BV1A8pa6pEvS](https://www.bilibili.com/video/BV1A8pa6pEvS) | TrackEverything (title cut at 80 chars) | 3D理解 | - | 15:36 | 171 |
| 188 | [BV1ofph6kEJP](https://www.bilibili.com/video/BV1ofph6kEJP) | GenNVS | 3D生成 | - | 15:33 | 72 |
| 189 | [BV1nSph6SEXn](https://www.bilibili.com/video/BV1nSph6SEXn) | NAMVIS | 神经渲染 | - | 15:44 | 57 |
| 190 | [BV1Rupe6CEg3](https://www.bilibili.com/video/BV1Rupe6CEg3) | OuroWorld (title cut at 80 chars) | 3D生成 | - | 14:55 | 32 |
| 191 | [BV1cBpi6YEUM](https://www.bilibili.com/video/BV1cBpi6YEUM) | LVSPM | 神经渲染 | - | 15:44 | 22 |
| 192 | [BV1fApi6xEKh](https://www.bilibili.com/video/BV1fApi6xEKh) | LVS (title cut at 80 chars) | 神经渲染 | - | 16:18 | 38 |
| 193 | [BV1k9pv6YEXg](https://www.bilibili.com/video/BV1k9pv6YEXg) | GenIA | 3D生成 | - | 15:40 | 33 |
| 194 | [BV13vpv61ED8](https://www.bilibili.com/video/BV13vpv61ED8) | GATOR | 3D生成 | - | 15:42 | 23 |
| 195 | [BV186pv6GE8c](https://www.bilibili.com/video/BV186pv6GE8c) | FounRef (title cut at 80 chars) | 深度估计 | - | 15:38 | 17 |
| 196 | [BV1Vepv6jEvF](https://www.bilibili.com/video/BV1Vepv6jEvF) | WildHSR (title cut at 80 chars) | 3D重建 | - | 14:54 | 16 |
| 197 | [BV11Dpv6vEbX](https://www.bilibili.com/video/BV11Dpv6vEbX) | DepthEvidence | 深度估计 | - | 14:31 | 68 |
| 198 | [BV1bopu6vE6e](https://www.bilibili.com/video/BV1bopu6vE6e) | VGGT-Diff (title cut at 80 chars) | 3D重建 | - | 15:39 | 11 |
| 199 | [BV1Kwpg6wE14](https://www.bilibili.com/video/BV1Kwpg6wE14) | Fysiverse-3D-SimReady Technical Report (title cut at 80 chars) | 3D重建 | - | 16:17 | 13 |
| 200 | [BV17Jpg6SER3](https://www.bilibili.com/video/BV17Jpg6SER3) | LEGO-Anything | 3D重建 | - | 15:06 | 21 |
| 201 | [BV1wupg64EAy](https://www.bilibili.com/video/BV1wupg64EAy) | OTT3R | 3D重建·Dataset | - | 16:39 | 29 |
| 202 | [BV1m1pG6zEiP](https://www.bilibili.com/video/BV1m1pG6zEiP) | Scene Retargeting | 3D理解 | - | 15:52 | 14 |
| 203 | [BV18BpG6VEgt](https://www.bilibili.com/video/BV18BpG6VEgt) | Matisse | 3D重建 | - | 15:08 | 45 |
| 204 | [BV1DipG61EeK](https://www.bilibili.com/video/BV1DipG61EeK) | SPOON (title cut at 80 chars) | 3D生成 | - | 15:03 | 17 |
| 205 | [BV1UrpG6GEEw](https://www.bilibili.com/video/BV1UrpG6GEEw) | Reconstructing the Dynamic World (title cut at 80 chars) | 3D重建 | - | 15:43 | 22 |
| 206 | [BV1SrpG6GEBr](https://www.bilibili.com/video/BV1SrpG6GEBr) | AdaOcc | 3D理解 | - | 15:44 | 11 |
| 207 | [BV1yTpG6iEQw](https://www.bilibili.com/video/BV1yTpG6iEQw) | Emergent Multi-View Geometry Through Self-Distillation | 3D理解 | - | 14:26 | 19 |
| 208 | [BV1NTpG6iEtX](https://www.bilibili.com/video/BV1NTpG6iEtX) | HIGS (title cut at 80 chars) | SLAM | - | 15:40 | 100 |
| 209 | [BV17rp36WEFs](https://www.bilibili.com/video/BV17rp36WEFs) | DSSR-3D | 3DGS | - | 15:39 | 121 |
| 210 | [BV1j1p36DEh9](https://www.bilibili.com/video/BV1j1p36DEh9) | Dyna3 (title cut at 80 chars) | 深度估计 | - | 17:08 | 31 |
| 211 | [BV1v1p36DEio](https://www.bilibili.com/video/BV1v1p36DEio) | ARROW (title cut at 80 chars) | 3D重建 | - | 17:13 | 36 |
| 212 | [BV1nip36oEk6](https://www.bilibili.com/video/BV1nip36oEk6) | DecomVoxel (title cut at 80 chars) | 3D生成 | - | 16:12 | 14 |
| 213 | [BV1G9p36LEzH](https://www.bilibili.com/video/BV1G9p36LEzH) | SCION | 3D重建 | - | 15:39 | 22 |
| 214 | [BV139p36LEoA](https://www.bilibili.com/video/BV139p36LEoA) | PAISS (title cut at 80 chars) | 3D理解·Benchmark | - | 15:59 | 13 |
| 215 | [BV1vUp36UE5m](https://www.bilibili.com/video/BV1vUp36UE5m) | OmniAct3D (title cut at 80 chars) | 3D理解 | - | 16:05 | 8 |
| 216 | [BV15mp36JErr](https://www.bilibili.com/video/BV15mp36JErr) | T3lescope (title cut at 80 chars) | 3D生成 | - | 14:53 | 6 |
| 217 | [BV1Rmp36JEA6](https://www.bilibili.com/video/BV1Rmp36JEA6) | UniDynamics (title cut at 80 chars) | 3D生成 | - | 16:43 | 15 |
| 218 | [BV1GDp367E2E](https://www.bilibili.com/video/BV1GDp367E2E) | Less Decoder is More Encoder | 神经渲染 | - | 14:53 | 10 |
| 219 | [BV1YGp36VELS](https://www.bilibili.com/video/BV1YGp36VELS) | VGGT-Bridge | SLAM | - | 15:30 | 40 |
| 220 | [BV19gp36yEVx](https://www.bilibili.com/video/BV19gp36yEVx) | Lens3D (title cut at 80 chars) | 3D理解 | - | 15:26 | 13 |
| 221 | [BV1hLp363Eja](https://www.bilibili.com/video/BV1hLp363Eja) | Less Context, Better Geometry (title cut at 80 chars) | 3D理解 | - | 13:59 | 23 |
| 222 | [BV1hVp36kEfW](https://www.bilibili.com/video/BV1hVp36kEfW) | DistScene | 3D生成 | - | 17:14 | 7 |
| 223 | [BV1sbp36aExS](https://www.bilibili.com/video/BV1sbp36aExS) | ElasticFit | 3D生成 | - | 14:35 | 11 |
| 224 | [BV1nYp36fEaQ](https://www.bilibili.com/video/BV1nYp36fEaQ) | OpenSplatGraph (title cut at 80 chars) | 3DGS | - | 14:52 | 20 |
| 225 | [BV1pYp36fEHT](https://www.bilibili.com/video/BV1pYp36fEHT) | DensiTok | 3D重建 | - | 14:02 | 14 |
| 226 | [BV1Cap368Eb9](https://www.bilibili.com/video/BV1Cap368Eb9) | RenderBench (title cut at 80 chars) | 3D重建·Benchmark | - | 15:24 | 19 |
| 227 | [BV11sp36NEhJ](https://www.bilibili.com/video/BV11sp36NEhJ) | Building Rome from a Single Image | 3D重建 | - | 16:04 | 65 |
| 228 | [BV18jp366ERv](https://www.bilibili.com/video/BV18jp366ERv) | Sparse-View 4D Gaussian Splatting via Spatiotemporal Priors and Generative (title cut at 80 chars) | 3DGS | - | 15:59 | 27 |
| 229 | [BV1uCp56SEss](https://www.bilibili.com/video/BV1uCp56SEss) | StereoGaussians | 3DGS | - | 15:00 | 41 |


---

*2026-10-11 快照。标题为 B 站原文，含 80 字符截断。*