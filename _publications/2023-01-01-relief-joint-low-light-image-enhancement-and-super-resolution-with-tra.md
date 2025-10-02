---
title: "RELIEF: Joint low-light image enhancement and super-resolution with transformers"
collection: publications
category: conferences
permalink: /publication/2023-01-01-relief-joint-low-light-image-enhancement-and-super-resolutio
excerpt: ""
date: 2023-01-01
venue: "Scandinavian Conference on Image Analysis"
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-31435-3_11'
citation: "Aakerberg, Andreas and Nasrollahi, Kamal and Moeslund, Thomas B (2023). &quot;RELIEF: Joint low-light image enhancement and super-resolution with transformers.&quot; <i>Scandinavian Conference on Image Analysis</i>."
---

The goal of Single-Image Super-Resolution (SISR) is to reconstruct a High-Resolution (HR) version of a degraded Low-Resolution (LR) image. Existing Super-Resolution (SR) methods mostly assume that the LR image is a result of blurring and downsampling the HR image, while in reality LR images are often degraded by additional factors such as low-light, low-contrast, noise, and color distortion. Due to this, current State-of-the-Art (SoTA) SR methods cannot reconstruct real low-light low-resolution images, and a straightforward strategy is, therefore, to first perform Low-Light Enhancement (LLE), followed by SR, using dedicated methods for each task. Unfortunately, this approach leads to poor performance, which motivates us to propose a method for joint LLE and SR. However, since LLE and SR are both ill-posed and ill-conditioned inverse problems, the joint reconstruction task becomes highly challenging …