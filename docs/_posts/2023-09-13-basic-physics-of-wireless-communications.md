---
layout: post
title:  "MOSFET Models"
date:   2023-09-16 19:49:28 -0400
usemathjax: true
---

- Output characteristics: I_DS vs. V_DS for some V_GS
- Transfer characteristics: I_DS vs. V_GS for some V_DS

Regions of Operation
|     | Cutoff | Linear | Saturation |
| --- | ------ | ------ | ---------- |
| nMOS | Vgs < Vtn | Vgs > Vtn | Vgs > Vtn |
|      |           | Vds < Vov | Vds > Vov |
| pMOS | Vgs > Vtp | Vgs < Vtp | Vgs < Vtp |
|      |           | Vds > Vov | Vds < Vov | 