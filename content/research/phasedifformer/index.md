---
title: "Enabling single-observation decomposition of multi-phase X-ray diffraction patterns via generative deep learning" 
date: 2026-05-08
lastmod: 2026-05-08
tags: []
author: ["Yusei Ito", "Naoya Chiba*", "Tatsunori Taniai*", "Ryo Igarashi", "Yuta Suzuki", "Kotaro Saito", "Yoshitaka Ushiku", "Kanta Ono"]
description: "This paper proposes multi-phase pattern decomposition method for X-ray diffraction measurement by using generative deep learning. Published in npj computational materials, 2026." 
summary: "This paper proposes multi-phase pattern decomposition method for X-ray diffraction measurement by using generative deep learning. Published in npj computational materials, 2026." 
cover:
    image: "teaser.png"
    alt: "Figure 1 of the paper"
    relative: false
editPost:
    URL: "https://doi.org/10.1038/s41524-026-02087-w"
    Text: "npj computational materials"

---

---

##### Links

+ [Paper](https://doi.org/10.1038/s41524-026-02087-w)
+ [Code](https://github.com/quantumbeam/PhaseDifformer)

---

##### Abstract

Powder X-ray diffraction (PXRD) is a vital technique for the structural characterization of crystalline compounds. However, this analysis is challenged by practically encountered multi-phase systems, whose mixed PXRD patterns necessitate prior phase decomposition. Traditional approaches require multiple mixture samples or prior knowledge of the constituent phases, limiting their applicability in complex or high-throughput scenarios. Here we show that multi-phase PXRD patterns from a single observation can be automatically decomposed into their constituent single-phase patterns using machine learning. The proposed solution—Phase Decomposition Diffusion Transformers (PhaseDifformer)—reinterprets the denoising process of diffusion models as a probabilistic regressor, enabling recursive extraction of unknown constituent phases. We validate the method on both synthetic mixtures and experimental measurements, achieving accurate phase decomposition in both cases. Given ongoing progress in single-phase PXRD-to-structure methods, our study fills a critical gap toward realizing fully automated, end-to-end analysis of complex PXRD patterns commonly encountered in materials research.

---

##### Citation

```BibTeX
@article{ito2026phasedifformer,
  year      = {2026},
  title     = {Enabling single-observation decomposition of multi-phase X-ray diffraction patterns via generative deep learning},
  author    = {Yusei Ito and 
               Naoya Chiba and
               Tatsunori Taniai and
               Ryo Igarashi and
               Yuta Suzuki and
               Kotaro Saito and 
               Yoshitaka Ushiku and 
               Kanta Ono},
  journal   = {npj computational materials}, 
  doi       = {10.1038/s41524-026-02087-w}, 
  volume    = {12},
  number    = {238}, 
}
```
