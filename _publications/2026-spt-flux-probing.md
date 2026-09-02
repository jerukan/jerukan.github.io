---
title: "Spatiotemporal Flux Probing for Single-Photon Videography"
collection: publications
category: conferences
# Title in the Publications list links here (the standalone site):
link: /spt-flux-probing/
# This stub's own page lives at a path that does NOT collide with the
# static site served from /spt-flux-probing/ (see the spt-flux-probing/ dir):
permalink: /publications/2026-spt-flux-probing
excerpt: "Recovery of high-speed videos from dynamic scenes under extreme photon sparsity."
date: 2026-09-08
venue: 'ECCV'
image: '/images/sptfluxprobe_gamma_select.gif'
paperurl: null
highlight: true
bibtexurl: '/files/bibtex/bibtex-2026-sptfluxprobing.bib'
asterisk_authors:
  - Jerry Yan
  - Matteo Forlivesi
asterisk_note: "Equal contribution"
---

We address the problem of recovering high-speed videos from dynamic scenes under extreme photon sparsity. Existing methods rely on aggregating photon detections in local spatiotemporal windows to improve signal-to-noise ratio; however, this local grouping discards global structure and fails in low-light regimes where photon detections are sparse in space and time. In this work, we show that the information needed to recover both motion and illumination is encoded in correlations over the full space-time pattern of photon arrivals. Building on this insight, we develop a **spatiotemporal flux probing** theory and an algorithm that estimates the Fourier coefficients of the underlying intensity directly from the photon stream. We demonstrate that our approach (1) recovers fast motion and temporal illumination dynamics with substantially fewer photons than prior methods, (2) enables **velocity-selective videography** that automatically refocuses video onto specific detected motions, and (3) generalizes across sensing modalities including single-photon, event, and spike cameras. 
