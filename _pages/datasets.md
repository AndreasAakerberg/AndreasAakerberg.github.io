---
permalink: /datasets/
title: "Datasets, Code & Challenges"
author_profile: true
---

Datasets and benchmarks I have created or co-created, and the challenges built
around them. Please check each dataset's licence and cite the associated paper
if you use it.

## Datasets

### LTDv2 — Long-Term Thermal Drift
<img src="/images/ltdv2.png" alt="Example images from the LTDv2 dataset" class="align-right" width="400">
A large-scale thermal surveillance dataset for studying multi-object detection
under long-term concept drift: seasonal change, weather, sensor re-calibration,
and time-of-day shift across an extended capture period. Built to test whether
detectors hold up when reality moves away from the training distribution.

[Download (Hugging Face)](https://huggingface.co/datasets/vapaau/LTDv2) ·
[Paper (TechRxiv)](https://www.techrxiv.org/doi/full/10.36227/techrxiv.175339329.95323969) ·
[Code & starting kit](https://github.com/MarcoParola/RTIOD)

*Parola, Aakerberg, Johansen, Nikolov, Cimino, Nasrollahi & Moeslund (2025).*

### SVSR — Spatially Variant Super-Resolution benchmark
<img src="/images/svsr.png" alt="Example images from the SVSR dataset" class="align-right" width="400">
1,119 real low-resolution images degraded by complex noise of varying intensity
and type, each paired with real noise-free ×2 and ×4 high-resolution ground
truth. Built to test how robust real-world super-resolution methods are when
degradation varies across the image rather than being uniform; it also works as
a denoiser benchmark.

[Download (Zenodo, 2.1 GB)](https://doi.org/10.5281/zenodo.10044260) ·
[Paper (WACV 2024)](https://openaccess.thecvf.com/content/WACV2024/papers/Aakerberg_PDA-RWSR_Pixel-Wise_Degradation_Adaptive_Real-World_Super-Resolution_WACV_2024_paper.pdf) ·
DOI: [10.5281/zenodo.10044260](https://doi.org/10.5281/zenodo.10044260) ·
Licence: CC BY-NC-SA 4.0

*Aakerberg (2023). Companion benchmark to PDA-RWSR.*

### RELLISUR — Real Low-Light Image Super-Resolution
<img src="/images/rellisur.png" alt="Example images from the Rellisur dataset" class="align-right" width="400">
12,750 paired images: real low-light low-resolution captures with normal-light
high-resolution references, across multiple resolution scales and degrees of
underexposure. Closes the gap between low-light enhancement and super-resolution,
which the literature had treated separately even though real-world visibility is
usually limited by both at once.

Published at **NeurIPS 2021, Datasets & Benchmarks Track**. Now over 2,000 downloads.

[Download (Zenodo, 8.9 GB)](https://doi.org/10.5281/zenodo.5234969) ·
[Paper (NeurIPS 2021)](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/7ef605fc8dba5425d6965fbd4c8fbe1f-Paper-round2.pdf) ·
DOI: [10.5281/zenodo.5234969](https://doi.org/10.5281/zenodo.5234969) ·
Licence: CC BY 4.0

*Aakerberg, Nasrollahi & Moeslund (2021).*

## Challenges

### RTIOD — Robust Thermal-Image Object Detection Challenge
Hosted at the 6th Real-World Surveillance workshop, WACV 2026. Participants build
detectors that stay accurate as thermal imagery drifts over months and seasons,
evaluated on held-out periods from LTDv2. A YOLO starting kit and COCO-format
dataset loader are provided.

[Challenge (Codabench)](https://www.codabench.org/competitions/10954/) ·
[Repository & starting kit](https://github.com/MarcoParola/RTIOD) ·
[Challenge report](https://vbn.aau.dk/en/publications/robust-thermal-image-object-detection-challenge-advancing-multi-o/)

### Real-World Surveillance Workshop & Challenge — IEEE/CVF WACV
I co-organise the Real-World Surveillance workshop, now in its sixth edition,
along with its associated challenge. The workshop brings together researchers
working on surveillance problems as they actually occur: uncontrolled capture,
degraded imagery, long deployment horizons, and operational constraints.

[Workshop site](https://vap.aau.dk/rws/)
