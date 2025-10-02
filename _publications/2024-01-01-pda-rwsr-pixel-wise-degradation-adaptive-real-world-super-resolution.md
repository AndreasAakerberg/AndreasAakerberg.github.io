---
title: "Pda-rwsr: Pixel-wise degradation adaptive real-world super-resolution"
collection: publications
category: conferences
permalink: /publication/2024-01-01-pda-rwsr-pixel-wise-degradation-adaptive-real-world-super-re
excerpt: ""
date: 2024-01-01
venue: "Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision"
paperurl: 'https://openaccess.thecvf.com/content/WACV2024/papers/Aakerberg_PDA-RWSR_Pixel-Wise_Degradation_Adaptive_Real-World_Super-Resolution_WACV_2024_paper.pdf'
citation: "Aakerberg, Andreas and El Helou, Majed and Nasrollahi, Kamal and Moeslund, Thomas (2024). &quot;Pda-rwsr: Pixel-wise degradation adaptive real-world super-resolution.&quot; <i>Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision</i>."
---

While many methods have been proposed to solve the Super-Resolution (SR) problem of Low-Resolution (LR) images with complex unknown degradations, their performance still drops significantly when evaluated on images with challenging real-world degradations. One often overlooked factor contributing to this, is the presence of spatially varying degradations in real LR images. To address this issue, we propose a novel degradation pipeline capable of generating paired LR/High-Resolution (HR) images with spatially varying noise, a key contributor to reducedimage quality. Furthermore, to fully leverage such training data, we novelly propose a Pixel-Wise Degradation Adaptive Real-World Super-Resolution (PDA-RWSR) framework. Specifically, we design a new Restormer-based Real-World Super-Resolution (RWSR) model capable of adapting the reconstruction process based on pixel-wise degradation features extracted by a new supervised degradation estimation model. Along with our proposed method, we also introduce a new challenging real-world Spatially Variant Super-Resolution (SVSR) benchmarking dataset, where the images are degraded by complex noise of varying intensity and type, to evaluate the robustness of existing RWSR methods. Comprehensive experiments on synthetic and the proposed challenging real dataset demonstrates the superiority of our method over the current State-of-The-Art (SoTA).