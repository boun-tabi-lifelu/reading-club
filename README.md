# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Özlem Şimşek

**Date:** 5 December 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Hierarchical graph transformer with contrastive learning for protein function prediction](https://academic.oup.com/bioinformatics/article/39/7/btad410/7208864)

**Citation:** Gu, Z., Luo, X., Chen, J., Deng, M., & Lai, L. (2023). Hierarchical graph transformer with contrastive learning for protein function prediction. Bioinformatics, 39.

**Abstract:**

Motivation: In recent years, high-throughput sequencing technologies have made large-scale protein sequences accessible. However, their
functional annotations usually rely on low-throughput and pricey experimental studies. Computational prediction models offer a promising
alternative to accelerate this process. Graph neural networks have shown significant progress in protein research, but capturing long-distance
structural correlations and identifying key residues in protein graphs remains challenging.

Results: In the present study, we propose a novel deep learning model named Hierarchical graph transformEr with contrAstive Learning (HEAL)
for protein function prediction. The core feature of HEAL is its ability to capture structural semantics using a hierarchical graph Transformer,
which introduces a range of super-nodes mimicking functional motifs to interact with nodes in the protein graph. These semantic-aware supernode embeddings are then aggregated with varying emphasis to produce a graph representation. To optimize the network, we utilized graph contrastive learning as a regularization technique to maximize the similarity between different views of the graph representation. Evaluation of the
PDBch test set shows that HEAL-PDB, trained on fewer data, achieves comparable performance to the recent state-of-the-art methods, such as
DeepFRI. Moreover, HEAL, with the added benefit of unresolved protein structures predicted by AlphaFold2, outperforms DeepFRI by a significant margin on Fmax, AUPR, and Smin metrics on PDBch test set. Additionally, when there are no experimentally resolved structures available
for the proteins of interest, HEAL can still achieve better performance on AFch test set than DeepFRI and DeepGOPlus by taking advantage of
AlphaFold2 predicted structures. Finally, HEAL is capable of finding functional sites through class activation mapping.

Availability and implementation: Implementations of our HEAL can be found at https://github.com/ZhonghuiGu/HEAL.

