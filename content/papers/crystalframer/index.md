---
title: "Rethinking the role of frames for SE(3)-invariant crystal structure modeling" 
date: 2025-04-24
lastmod: 2025-04-24
tags: []
author: ["Yusei Ito*","Tatsunori Taniai*", "Ryo Igarashi", "Yoshitaka Ushiku", "Kanta Ono"]
description: "This paper proposes dynamic atom-wise frames aligned with attention-based interatomic interactions on the structure, rather than with the structure itself. Published in ICLR2025." 
summary: "This paper proposes dynamic atom-wise frames aligned with attention-based interatomic interactions on the structure, rather than with the structure itself. Published in ICLR2025." 
cover:
    image: "teaser.png"
    alt: "Figure 1 of the paper"
    relative: false
editPost:
    URL: "https://openreview.net/forum?id=gzxDjnvBDa"
    Text: "ICLR2025"

---

---

##### Links

+ [Paper](https://openreview.net/forum?id=gzxDjnvBDa)
+ [Project page](https://omron-sinicx.github.io/crystalframer/)
+ [Code](https://github.com/omron-sinicx/crystalframer)

---

##### Abstract

Crystal structure modeling with graph neural networks is essential for various applications in materials informatics, and capturing SE(3)-invariant geometric features is a fundamental requirement for these networks. A straightforward approach is to model with orientation-standardized structures through structure-aligned coordinate systems, or “frames.” However, unlike molecules, determining frames for crystal structures is challenging due to their infinite and highly symmetric nature. In particular, existing methods rely on a statically fixed frame for each structure, determined solely by its structural information, regardless of the task under consideration. Here, we rethink the role of frames, questioning whether such simplistic alignment with the structure is sufficient, and propose the concept of dynamic frames. While accommodating the infinite and symmetric nature of crystals, these frames provide each atom with a dynamic view of its local environment, focusing on actively interacting atoms. We demonstrate this concept by utilizing the attention mechanism in a recent transformer-based crystal encoder, resulting in a new architecture called CrystalFramer. Extensive experiments show that CrystalFramer outperforms conventional frames and existing crystal encoders in various crystal property prediction tasks.

---

##### Citation

```BibTeX
@inproceedings{ito2025crystalframer,
  year      = {2025},
  title     = {Rethinking the role of frames for SE(3)-invariant crystal structure modeling},
  author    = {Yusei Ito and 
               Tatsunori Taniai and
               Ryo Igarashi and
               Yoshitaka Ushiku and
               Kanta Ono},
  booktitle = {The Thirteenth International Conference on Learning Representations (ICLR 2025)},
  url       = {https://openreview.net/forum?id=gzxDjnvBDa}
}
```
