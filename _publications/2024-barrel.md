---
title: "Pose Estimation of Buried Deep-Sea Objects using 3D Vision Deep Learning Models"
collection: publications
category: conferences
permalink: /publications/2024-barrel
excerpt: "Rigid 6DoF pose estimation of buried barrels in the seafloor from ROV footage."
date: 2024-09-23
venue: 'OCEANS 2024 - Halifax'
paperurl: 'https://arxiv.org/abs/2410.01061'
image: '/images/fit-barrel4.png'
highlight: false
bibtexurl: '/files/bibtex/bibtex-2024-barrel.bib'
---

We present an approach for pose and burial fraction estimation of debris field barrels found on the seabed in the Southern California San Pedro Basin. Our computational workflow leverages recent advances in foundation models for segmentation and a vision transformer-based approach to esti-mate the point cloud which defines the geometry of the barrel. We propose BarrelNet for estimating the 6DoF pose and radius of buried barrels from the barrel point clouds as input. We train BarrelNet using synthetically generated barrel point clouds, and qualitatively demonstrate the potential of our approach using remotely operated vehicle (ROV) video footage of barrels found at a historic dump site. We compare our method to a traditional least squares fitting approach and show significant improvement according to our defined benchmarks.
