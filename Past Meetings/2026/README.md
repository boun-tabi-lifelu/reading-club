# Past Meetings — 2026

## 15 May 2026

**Presenter:** Burak Suyunu

**Date:** 15 May 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [FoldToken: Learning Protein Language via Vector Quantization and Beyond](https://ojs.aaai.org/index.php/AAAI/article/view/31998)

**Citation:** Gao, Z., Tan, C., Wang, J., Huang, Y., Wu, L., & Li, S. Z. (2025, April). Foldtoken: Learning protein language via vector quantization and beyond. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 39, No. 1, pp. 219-227).

**Material:**
- [Slides](15-05-26_Burak_FoldToken.pdf)

## 10 April 2026

**Presenter:** Gökçe Uludoğan 

**Date:** 10 April 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Compressing the collective knowledge of ESM into a single protein language model]([https://www.biorxiv.org/content/10.64898/2026.01.29.702509v1](https://www.nature.com/articles/s41592-026-03050-9))

**Citation:** Dinh, T., Jang, S. K., Zaitlen, N., & Ntranos, V. (2026). Compressing the collective knowledge of ESM into a single protein language model. Nature Methods, 1-13.

**Material:**
- [Slides](10-04-2026-VESM.pdf)

**Abstract:**

Protein function and other biological properties often depend on structural dynamics, yet most machine-learning predictors rely on static representations. Physics-based molecular simulations can describe conformational variability but remain computationally prohibitive at scale. Generative models provide a more efficient alternative, though their ability to produce accurate conformational ensembles is still limited. In this work, we bypass expensive simulations by leveraging residue–residue distance probability distributions (distograms) from structure predictors such as AlphaFold2. Our approach provides a scalable way to encode dynamic information into protein representations, aiming to improve function prediction without explicit conformational sampling.

## 6 March 2026

**Presenter:** Gökçe Uludoğan 

**Date:** 6 March 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Learning Dynamic Protein Representations at Scale with Distograms](https://www.biorxiv.org/content/10.64898/2026.01.29.702509v1)

**Citation:** Portal, N., Karroucha, W., Mallet, V., & Bonomi, M. (2026). Learning Dynamic Protein Representations at Scale with Distograms. bioRxiv, 2026-01.

**Material:**
- [Slides](6-03-2026-Gokce-Learning-Dynamic-Protein Representations-at-Scale-with-Distograms.pdf)

**Abstract:**

Protein function and other biological properties often depend on structural dynamics, yet most machine-learning predictors rely on static representations. Physics-based molecular simulations can describe conformational variability but remain computationally prohibitive at scale. Generative models provide a more efficient alternative, though their ability to produce accurate conformational ensembles is still limited. In this work, we bypass expensive simulations by leveraging residue–residue distance probability distributions (distograms) from structure predictors such as AlphaFold2. Our approach provides a scalable way to encode dynamic information into protein representations, aiming to improve function prediction without explicit conformational sampling.

## 20 February 2026
**Presenter:** Beyza Nur Deniz

**Date:** 20 February 2026

**Paper:** [Protein Language Modeling beyond static folds reveals sequence-encoded flexibility](https://www.biorxiv.org/content/10.64898/2026.01.21.700698v1)

**Citation:** Protein Language Modeling beyond static folds reveals sequence-encoded flexibility
Finn H. Lüth, Victor Mihaila, Milot Mirdita, Martin Steinegger, Burkhard Rost, Michael Heinzinger
bioRxiv 2026.01.21.700698; (https://doi.org/10.64898/2026.01.21.700698)

**Material:**
- [Slides](20-02-26_Beyza_PresentationProtProfileMD.pdf)
- [Paper](20-02-26_Beyza_PresentationProtProfileMD.pdf)

**Abstract:**

**Motivation:** Proteins function through motion. Yet, most discoveries still commence with static representations of protein structures. Here, we investigated the feasibility of leveraging protein dynamics to improve homology detection.

**Results:** We introduce ProtProfileMD, a sequence-to-3D-probability model that predicts, from an amino acid sequence, a profile of discrete structural representations capturing protein dynamics. We applied supervised parameter-efficient finetuning of the ProstT5 protein Language Model (pLM) to predict per-residue distributions over Foldseek’s 3Di alphabet derived from motions observed in molecular dynamics. This original result reveals that the 3Di tokens, despite being coarse-grained descriptors of 3D structure, still offer sufficient resolution to capture aspects of conformational changes. This is evidenced by a correlation between fluctuations in the 3D protein structure over the course of a molecular dynamics trajectory and the entropy of 3Di states. Based on this insight, we introduce a proof-of-concept for making remote homology detection of proteins more sensitive by leveraging a protein’s distinctive dynamic fingerprint captured by our model. Our method recovers flexibility signals with a fidelity that is biologically relevant, improving search and complementing protein structure predictions, for example, by flagging flexible, disordered, or other functionally relevant regions.

## 13 February 2026
**Presenter:** Başar Temiz

**Date:** 13 February 2026

**Paper:** [Protein Language Models Trained on Biophysical Dynamics Inform Mutation Effects](https://doi.org/10.1101/2024.10.11.617911)

**Citation:** Hou, C., Zhao, H., & Shen, Y. (2026). Protein Language Models Trained on Biophysical Dynamics Inform Mutation Effects. bioRxiv. https://doi.org/10.1101/2024.10.11.617911

**Material:**
- [Slides](12-2-26%20Basar%20presentation%20seqdance.key)
- [Paper](12-02-26_Basar_PaperSeqDance.pdf)

**Abstract:**
Structural dynamics are fundamental to protein functions and mutation effects. Current protein deep learning
models are predominantly trained on sequence and/or static structure data, which often fail to capture the
dynamic nature of proteins. To address this, we introduce SeqDance and ESMDance, two protein language
models trained on dynamic biophysical properties derived from molecular dynamics simulations and normal
mode analyses of over 64,000 proteins. Both models can be directly applied to predict dynamic properties of
unseen ordered and disordered proteins. SeqDance, trained from scratch, has attentions that capture dynamic
interaction and co-movement between residues, and its embeddings encode rich representations of protein
dynamics that can be further utilized to predict conformational properties beyond the training tasks via transfer
learning. SeqDance predicted dynamic property changes reflect mutation effect on protein folding stability.
ESMDance, built upon ESM2 (Evolutionary Scale Model II) outputs, substantially outperforms ESM2 in zero-
shot prediction of mutation effects for designed and viral proteins which lack evolutionary information.
Together, SeqDance and ESMDance offer a new framework for integrating protein dynamics into language
models, enabling more generalizable predictions of protein behavior and mutation effects.

## 05 February 2026

**Presenter:** Buse Giledereli

**Date:** 05 February 206, 14:00 UTC+3 (Istanbul)

**Paper:** [Zero-shot segmentation using embeddings from a protein language model identifies functional regions in the human proteome
](https://doi.org/10.1371/journal.pcbi.1012929)

**Citation:** Sangster, A. G., Dufault, C., Qu, H., Le, D., Forman-Kay, J. D., & Moses, A. M. (2025). Zero-shot segmentation using embeddings from a protein language model identifies functional regions in the human proteome. PLoS computational biology, 21(11), e1012929. https://doi.org/10.1371/journal.pcbi.1012929



**Material:** 
- [Slides](05-02-26_Buse_Slides_ZPS.pdf)
- [Paper](05-02-26_Buse_Paper_ZPS.pdf)
 
**Abstract:**

Protein structure is central to biological function, and enabling multimodal protein models requires joint reasoning over sequence, structure, and function. A key barrier is the lack of principled protein structure tokenizers (PSTs): existing approaches fix token size or rely on continuous vector codebooks, limiting interpretability, multi-scale control, and transfer across architectures. We introduce GEOBPE, a geometry-grounded PST that transforms continuous, noisy, multiscale backbone conformations into discrete “sentences” of geometry while enforcing global constraints. Analogous to byte-pair encoding, GEOBPE generates a hierarchical vocabulary of geometric primitives by iteratively (i) clustering Geo-Pair occurrences with k-medoids to yield a resolution-controllable vocabulary; (ii) quantizing each Geo-Pair to its closest medoid prototype; and (iii) reducing drift through differentiable inverse kinematics that optimizes boundary glue angles under an SE(3) end-frame loss. GEOBPE offers compression (>10× reduction in bits-per-residue at similar distortion rate), data efficiency (>10× less training data), and generalization (maintains test/train distortion ratio of 1.0 − 1.1). It is architecture-agnostic: (a) its hierarchical vocabulary provides a strong inductive bias for coarsening residue-level embeddings from large PLMs into motif- and protein-level representations, consistently outperforming leading PSTs across 12 tasks and 24 test splits; (b) paired with a transformer, GEOBPE supports unconditional backbone generation via language modeling; and (c) tokens align with CATH functional families and support expert-interpretable case studies, offering functional meaning absent in prior PSTs. Code is available at https://github.com/shiningsunnyday/PT-BPE/.

