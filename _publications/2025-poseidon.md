---
title: "PoseIDON: 6DoF pose estimation with foundation model features for marine sediment burial mapping"
collection: publications
category: manuscripts
permalink: /publications/2025-6dof-barrel
excerpt: "Rigid 6DoF pose estimation of arbitrary buried objects in the seafloor from ROV footage using foundation models."
date: 2026-09-01
venue: 'ISPRS Journal of Photogrammetry and Remote Sensing + MS Thesis'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0924271626003382'
codeurl: 'https://github.com/jerukan/PoseIDON'
image: '/images/fit-overlays-barrelddt1.gif'
highlight: true
bibtexurl: '/files/bibtex/bibtex-2025-poseidon.bib'
---

The burial state of anthropogenic objects on the seafloor provides insight into localized sedimentation dynamics and is also critical for assessing ecological risks, potential pollutant transport, and the viability of recovery or mitigation strategies for hazardous materials such as munitions. Accurate burial depth estimation from remote imagery remains difficult due to partial occlusion, poor visibility, and object degradation. This work introduces a computer vision pipeline, called PoseIDON, which combines deep foundation model features with multiview photogrammetry to estimate six degrees of freedom object pose and the orientation of the surrounding seafloor from ROV video. Burial depth is inferred by aligning CAD models of the objects with observed imagery and fitting a local planar approximation of the seafloor. The method is validated using footage of 54 objects, including barrels and munitions, recorded at a historic ocean dumpsite in the San Pedro Basin. The model achieves a mean burial depth error of approximately 10 centimeters and resolves spatial burial patterns that reflect underlying sediment transport processes. This approach enables scalable, non-invasive mapping of seafloor burial and supports environmental assessment at contaminated sites.
