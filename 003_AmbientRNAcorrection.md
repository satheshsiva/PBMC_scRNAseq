---
Title:  "Porcine immune cell atlas single cell RNA sequencing analysis pipeline"
Author: "Sathesh K. Sivasankaran"
Date:   "Feb 15, 2021"
---

# Porcine Immune Single Cell Atlas

## Ambient RNA correction
Ambient RNA in scRNA-seq samples were cleaned using R package SoupX (v1.4.5; https://github.com/constantAmateur/SoupX) in Rstudio (v1.1.447; R v3.6.2).
Required packages: dplyr, scran, knitr, ggplot2, Rtsne, cowplot, Seurat, tidyr, DropletUtils, SoupX.
```
pacman::p_load(dplyr, scran, knitr, ggplot2, Rtsne, cowplot, Seurat, limma, tidyr, DropletUtils, SoupX, DoubletFinder)

```

### A
