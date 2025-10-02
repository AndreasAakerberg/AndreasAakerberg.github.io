---
title: "A method of training a neural network, apparatus and computer program for carrying out the method"
collection: publications
category: patents
permalink: /publication/2024-09-12-a-method-of-training-a-neural-network-apparatus-and-computer
excerpt: ""
date: 2024-09-12
venue: "US Patent App. 18/595,002"
paperurl: 'https://patents.google.com/patent/US20240303783A1/en'
citation: "AAKERBERG, Andreas and NASROLLAHI, Kamal and Moeslund, Thomas B (2024). &quot;A method of training a neural network, apparatus and computer program for carrying out the method.&quot; <i>US Patent App. 18/595,002</i>."
---

Training a neural network to extract a degradation map from a degraded image comprises generating training data comprising pairs of images, each pair of images comprising a clean source image and a degraded source image by, for each clean source image, generating a corresponding noisy image by adding spatially invariant noise to the clean source image, and blending the noisy image with the clean source image according to varying intensity levels defined by a spatially variant mask to obtain the degraded image. The training data is used to train the neural network by inputting each degraded source image to the neural network and extracting a degradation map from the degraded source image such that when the degradation map is applied to its corresponding clean source image the loss between the degraded source image and its corresponding clean source image after the degradation map is …