---
title: "Transformer as a Neural Knowledge Graph" 
date: 2025-04-23
lastmod: 2025-04-23
tags: []
author: ["Yuki Nishihori", "Yusei Ito", "Yuta Suzuki", "Ryo Igarashi", "Yoshitaka Ushiku", "Kanta Ono"]
description: "Propose a transformer-based neural knowledge graph to integrate contextual knowledge into contrastive learning between crystal structures and linguistic physical properties. Published in AI4MAT-ICLR-2025." 
summary: "Propose a transformer-based neural knowledge graph to integrate contextual knowledge into contrastive learning between crystal structures and linguistic physical properties. Published in AI4MAT-ICLR-2025." 
cover:
    image: "teaser.png"
    alt: "Figure 1 of the paper"
    relative: false
editPost:
    URL: "https://openreview.net/forum?id=vGVvvRwYMR"
    Text: "AI4MAT-ICLR-2025"

---

---

##### Links

+ [Paper](https://openreview.net/forum?id=vGVvvRwYMR)

---

##### Abstract

In this study, we propose an effective contrastive learning method that bridges crystal structures with their linguistic properties (e.g., superconductor). Contrastive learning enables both the retrieval of crystal structures based on linguistic characteristics and the inference of linguistic properties from crystal structures, which are essential for accelerating materials discovery. However, a major challenge lies in the limitation of available datasets, which currently include only crystal structures paired with their corresponding article titles and abstracts. Because many papers depend on referenced works and shared domain knowledge—often explored in detail within the main text—titles and abstracts alone do not sufficiently capture the full characteristics of a crystal. To address this issue, we introduce a neural knowledge graph by incorporating a transformer into the text encoder of the existing contrastive learning framework, rather than expanding the dataset. This modification enables the model to dynamically incorporate related knowledge, thereby enhancing its representation of linguistic properties and facilitating more accurate correlations between crystal structures and their properties.

---

##### Citation

```BibTeX
@inproceedings{nishihori2025nkg,
  year      = {2025},
  title     = {Transformer as a Neural Knowledge Graph},
  author    = {Yuki Nishihori and 
               Yusei Ito and
               Yuta Suzuki and
               Ryo Igarashi and
               Yoshitaka Ushiku and
               Kanta Ono},
  booktitle = {AI for Accelerated Materials Design - ICLR 2025},
  url       = {https://openreview.net/forum?id=vGVvvRwYMR}
}
```
