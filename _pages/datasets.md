---
permalink: /datasets/
title: "Datasets, Code & Challenges"
author_profile: true
---

Datasets and benchmarks I have created or co-created, and the challenges built
around them. Everything here is free to use for research; please cite the
associated paper if you do.

## Datasets

### LTDv2 — Long-Term Thermal Drift
A large-scale thermal surveillance dataset for studying multi-object detection
under long-term concept drift: seasonal change, weather, and time-of-day shift
across an extended capture period. Built to test whether detectors hold up when
the reality moves away from the training distribution.

⟨Download⟩ · [Paper (TechRxiv)](https://www.techrxiv.org/doi/pdf/10.36227/techrxiv.175339329.95323969) · ⟨Code⟩

*Parola, Aakerberg, Johansen, Nikolov, Cimino, Nasrollahi & Moeslund (2025).*

### SVSR — Spatially Variant Super-Resolution benchmark
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
The first dataset of real, aligned low-light low-resolution and normal-light
high-resolution image pairs, at multiple resolution scales and degrees of
underexposure. Enables joint low-light enhancement and super-resolution to be
studied without synthetic degradations.

Published at **NeurIPS 2021, Datasets & Benchmarks Track**.

⟨Download⟩ · [Paper](https://openreview.net/pdf?id=aqCD8RINP54) · ⟨Code⟩

*Aakerberg, Nasrollahi & Moeslund (2021).*

## Challenges

### Robust Thermal Image Object Detection Challenge
Hosted at the Real-World Surveillance workshop, WACV 2026. Participants trained
detectors that stay accurate as thermal imagery drifts over months and seasons,
evaluated on held-out periods from LTDv2.

[Challenge page](https://vap.aau.dk/rws/) · [Challenge report](https://vbn.aau.dk/en/publications/robust-thermal-image-object-detection-challenge-advancing-multi-o/)

### Real-World Surveillance Workshop & Challenge — IEEE/CVF WACV
I co-organise the Real-World Surveillance workshop, now in its sixth edition,
along with its associated challenge. The workshop brings together researchers
working on surveillance problems as they actually occur: uncontrolled capture,
degraded imagery, long deployment horizons, and operational constraints.

[Workshop site](https://vap.aau.dk/rws/)

