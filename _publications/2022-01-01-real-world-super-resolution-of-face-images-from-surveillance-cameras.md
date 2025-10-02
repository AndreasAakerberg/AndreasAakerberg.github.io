---
title: "Real-world super-resolution of face-images from surveillance cameras"
collection: publications
category: manuscripts
permalink: /publication/2022-01-01-real-world-super-resolution-of-face-images-from-surveillance
excerpt: ""
date: 2022-01-01
venue: "IET Image Processing"
paperurl: 'https://ietresearch.onlinelibrary.wiley.com/doi/pdfdirect/10.1049/ipr2.12359'
citation: "Aakerberg, Andreas and Nasrollahi, Kamal and Moeslund, Thomas B (2022). &quot;Real-world super-resolution of face-images from surveillance cameras.&quot; <i>IET Image Processing</i>."
---

Most existing face image Super‐Resolution (SR) methods assume that the Low‐Resolution (LR) images were artificially downsampled from High‐Resolution (HR) images with bicubic interpolation. This operation changes the natural image characteristics and reduces noise. Hence, SR methods trained on such data most often fail to produce good results when applied to real LR images. To solve this problem, a novel framework for the generation of realistic LR/HR training pairs is proposed. The framework estimates realistic blur kernels, noise distributions, and JPEG compression artifacts to generate LR images with similar image characteristics as the ones in the source domain. This allows to train an SR model using high‐quality face images as Ground‐Truth (GT). For better perceptual quality, a Generative Adversarial Network (GAN) based SR model is used, where the commonly used VGG‐loss [1] is exchanged …