# Awesome-Medical-Image-Restoration [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Yaziwel/Awesome-RWKV-in-Vision) 

![](./assets/Awsome_MedIR.png)

**Medical Image Restoration (MedIR)** aims to recover high-quality medical images from degraded low-quality observations.

**Two Criteria for inclusion in this MedIR repository:**

- **General-purpose MedIR**: The method must be applicable to *more than one* MedIR task, demonstrated across multiple modalities or multiple degradation types within a single modality.
- **Open-source**: The code and/or data must be *publicly available* to enable reproduction of results.

## Table of Contents 

- [All-in-One MedIR](#all-in-one-medir)
  - [2024](#2024) | [2025](#2025)| [2026](#2026)

- [Single-Task MedIR](#single-task-medir)
  - [2024](#2024-1) | [2025](#2025-1) | [2026](#2026-1) 

- [Benchmarks](#benchmarks)

### All-in-One MedIR

#### 2024

| Title                                                        |                             Code                             |                             Link                             | N (Modalities / Degradations) |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------------------: |
| All-in-One Medical Image Restoration via Task-Adaptive Routing | [![Star](https://img.shields.io/github/stars/Yaziwel/All-In-One-Medical-Image-Restoration-via-Task-Adaptive-Routing.svg?style=social&label=Star)](https://github.com/Yaziwel/All-In-One-Medical-Image-Restoration-via-Task-Adaptive-Routing) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.19769) |             3M3D              |

#### 2025

|                            Title                             |                             Code                             |                             Link                             | N (Modalities / Degradations) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------------------: |
| TAT: Task-Adaptive Transformer for All-in-One Medical Image Restoration | [![Star](https://img.shields.io/github/stars/Yaziwel/TAT.svg?style=social&label=Star)](https://github.com/Yaziwel/TAT) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.19769) |             3M3D              |
| EndoIR: Degradation-Agnostic All-in-One Endoscopic Image Restoration via Noise-Aware Routing Diffusion | [![Star](https://img.shields.io/github/stars/DavisMeee/EndoIR.svg?style=social&label=Star)](https://github.com/DavisMeee/EndoIR) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.05873) |             1M3D              |

#### 2026

| Title                                                        |                             Code                             |                             Link                             | N (Modalities / Degradations) |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------------------: |
| UniH<sup>3</sup>: Unifying Hierarchical Homogeneity and Heterogeneity for All-in-One Medical Image Restoration | [![Star](https://img.shields.io/github/stars/Yaziwel/UniH3.svg?style=social&label=Star)](https://github.com/Yaziwel/UniH3) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2609.11156) |             7M7D              |
| An all-in-one foundation model for multimodal medical image restoration and enhancement | [![Star](https://img.shields.io/github/stars/caoluyang0830/All-in-One-Medical-Image-Restoration.svg?style=social&label=Star)](https://github.com/caoluyang0830/All-in-One-Medical-Image-Restoration) |  [NMI](https://www.nature.com/articles/s42256-026-01310-z)   |             7M7D              |
| SGF-RWKV: Semantic-Guided and Frequency-Enhanced RWKV for Unified Medical Image Denoising | [![Star](https://img.shields.io/github/stars/zwj666a/SGF_RWKV.svg?style=social&label=Star)](https://github.com/zwj666a/SGF_RWKV) |         [LINK](https://github.com/zwj666a/SGF_RWKV)          |             4M4D              |
| All-In-One Medical Image Restoration via Text-Guided Prompting and Dual-Domain Modeling | [![Star](https://img.shields.io/github/stars/gluucose/UniMedIR.svg?style=social&label=Star)](https://github.com/gluucose/UniMedIR) | [LINK](https://www.sciencedirect.com/science/article/pii/S1566253526004367) |             3M3D              |

### Single-Task MedIR

#### 2024

|                            Title                             |                             Code                             |                             Link                             | N (Modalities / Degradations) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------------------: |
| Restore-RWKV: Efficient and Effective Medical Image Restoration with RWKV | [![Star](https://img.shields.io/github/stars/Yaziwel/Restore-RWKV.svg?style=social&label=Star)](https://github.com/Yaziwel/Restore-RWKV) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.11087) |             3M3D              |
|  Region Attention Transformer for Medical Image Restoration  | [![Star](https://img.shields.io/github/stars/Yaziwel/Region-Attention-Transformer-for-Medical-Image-Restoration.svg?style=social&label=Star)](https://github.com/Yaziwel/Region-Attention-Transformer-for-Medical-Image-Restoration) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.09268) |             3M3D              |

#### 2025

|                            Title                             |                             Code                             |                             Link                             | N (Modalities / Degradations) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------------------: |
| Directional Adaptive Shuffle-Based Visual State-Space Models for Medical Image Restoration | [![Star](https://img.shields.io/github/stars/cc111mp/DASMamba-MedIR.svg?style=social&label=Star)](https://github.com/cc111mp/DASMamba-MedIR) | [MICCAI25](https://papers.miccai.org/miccai-2025/paper/0433_paper.pdf) |             3M3D              |

#### 2026

|                            Title                             |                             Code                             |                             Link                             | N (Modalities / Degradations) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------------------: |
| ContiLNN: Mitigating Slice Sampling Discontinuity with Liquid Neural Networks for Medical Image Restoration | [![Star](https://img.shields.io/github/stars/Noah-hjl/ContiLNN.svg?style=social&label=Star)](https://github.com/Noah-hjl/ContiLNN) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2610.12337) |             3M3D              |

### Benchmarks

|                            Title                             |                             Code                             |                             Link                             | N (Modalities / Degradations) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------------------: |
| All-in-One Medical Image Restoration via Task-Adaptive Routing | [![Star](https://img.shields.io/github/stars/Yaziwel/All-In-One-Medical-Image-Restoration-via-Task-Adaptive-Routing.svg?style=social&label=Star)](https://github.com/Yaziwel/All-In-One-Medical-Image-Restoration-via-Task-Adaptive-Routing) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.19769) |             3M3D              |
| Benchmarking Endoscopic Surgical Image Restoration and Beyond | [![Star](https://img.shields.io/github/stars/PJLallen/Surgical-Image-Restoration.svg?style=social&label=Star)](https://github.com/PJLallen/Surgical-Image-Restoration) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.19161) |             1M3D              |
| UniH<sup>3</sup>: Unifying Hierarchical Homogeneity and Heterogeneity for All-in-One Medical Image Restoration | [![Star](https://img.shields.io/github/stars/Yaziwel/UniH3.svg?style=social&label=Star)](https://github.com/Yaziwel/UniH3) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2609.11156) |             7M7D              |
| An all-in-one foundation model for multimodal medical image restoration and enhancement | [![Star](https://img.shields.io/github/stars/caoluyang0830/All-in-One-Medical-Image-Restoration.svg?style=social&label=Star)](https://github.com/caoluyang0830/All-in-One-Medical-Image-Restoration) |  [NMI](https://www.nature.com/articles/s42256-026-01310-z)   |             7M7D              |
