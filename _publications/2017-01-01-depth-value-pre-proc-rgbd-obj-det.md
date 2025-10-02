---
title: "Depth value pre-processing for accurate transfer learning based RGB-D object recognition"
collection: publications
category: conferences
permalink: /publication/2017-depth-value-pre-proc-rgbd-obj-det
excerpt: ""
date: 2017-01-01
venue: "International Joint Conference on Computational Intelligence"
paperurl: 'https://www.scitepress.org/Papers/2017/65115/65115.pdf'
citation: "Andreas Aakerberg, Kamal Nasrollahi, Christoffer Bøgelund Rasmussen, Thomas B Moeslund (2017). &quot;Depth value pre-processing for accurate transfer learning based RGB-D object recognition.&quot; <i>International Joint Conference on Computational Intelligence</i>."
---

Object recognition is one of the important tasks in computer vision which has found enormous applications. Depth modality is proven to provide supplementary information to the common RGB modality for objectrecognition. In this paper, we propose methods to improve the recognition performance of an existing deeplearning based RGB-D object recognition model, namely the FusionNet proposed by Eitel et al. First, we showthat encoding the depth values as colorized surface normals is beneficial, when the model is initialized withweights learned from training on ImageNet data. Additionally, we show that the RGB stream of the FusionNetmodel can benefit from using deeper network architectures, namely the 16-layered VGGNet, in exchange forthe 8-layered CaffeNet. In combination, these changes improves the recognition performance with 2.2% incomparison to the original FusionNet, when evaluating on the Washington RGB-D Object Dataset.