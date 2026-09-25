# Past Meetings — 2026

## 25 September 2026

**Presenter:** Gökçe Uludoğan

**Date:** 25 September 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Conditional diffusion with locality-aware modal alignment for generating diverse protein conformational ensembles](https://www.nature.com/articles/s42256-026-01198-9)

**Citation:** Wang, B., Wang, C., Chen, J., Liu, D., Sun, C., Zhang, J., Zhang, K., & Li, H. (2026). Conditional diffusion with locality-aware modal alignment for generating diverse protein conformational ensembles. Nature Machine Intelligence, 8(3).

**Material:**
- [Slides](25-09-2026_MacDiff.pdf)

**Abstract:**

Recent advances in AI have enabled the accurate prediction of a single stable protein structure solely based on its amino acid sequence. However, capturing the complete conformational landscape of a protein and its dynamic flexibility remains challenging. In this work, we developed Modal-aligned conditional Diffusion (Mac-Diff), a score based diffusion model for generating the conformational ensembles for unseen proteins. Central to Mac-Diff is an innovative attention module that enforces a delicate, locality-aware alignment between the conditional view (protein sequence) and the target view (residue pair geometry) to compute highly contextualized features for effective structural denoising. Furthermore, Mac-Diff leverages semantically rich sequence embedding from Protein Language Models like ESM-2 in enforcing the protein sequence condition that captures evolutionary, structural and functional information. This compensates for protein structural heterogeneity more effectively than embeddings from structure prediction models that are possibly biased to the dominant conformation. Mac-Diff showed promising results in generating realistic and diverse protein structures. It successfully recovered conformational distributions of fast folding proteins, captured multiple meta-stable conformations that were only observed in long MD simulation trajectories and efficiently predicted alternative conformations for allosteric proteins. We believe that Mac-Diff offers a useful tool to improve understanding of protein dynamics and structural variability, with broad implications for structural biology, drug discovery, and protein engineering.

## 18 September 2026

**Presenter:** Burak Suyunu

**Date:** 18 September 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Protein language models are accidental taxonomists](https://link.springer.com/article/10.1186/s12859-026-06491-3)

**Citation:** Hallee, L. P., Peleg, T., Rafailidis, N., & Gleghorn, J. P. (2026). Protein language models are accidental taxonomists. BMC Bioinformatics, 27, 188.

**Abstract:**

Protein-protein interactions (PPIs) are fundamental to nearly all biological processes, yet their experimental characterization remains costly and time-consuming. While computational methods, particularly those using protein language models (pLMs), offer higher-throughput solutions, they often report unexpectedly high performance on multi-species datasets. Here, we introduce the accidental taxonomist hypothesis, proposing that neural networks can exploit the phylogenetic distances across labels in protein datasets rather than genuine interaction features. We show that in PPI datasets with random negative sampling, protein pairs for real PPIs are almost exclusively from the same species, while negatives almost always originate from different species. We then demonstrate that pLM embeddings can be used to accurately distinguish whether two proteins share a taxonomic origin, allowing models to "cheat" by learning phylogeny instead of genuine PPI features. By employing a strategic sampling strategy that restricts negative examples to protein pairs from the same species, we reveal a marked drop in model performance, confirming our hypothesis. Compellingly, these strategically trained models still outperform single-species models, suggesting that multi-species data can improve performance if carefully curated. These findings suggest that accidental taxonomist behavior is a particularly influential confounder for PPI, and it is also broadly applicable to any supervised-learning protein dataset.

## 11 September 2026

**Presenter:** Buse Giledereli

**Date:** 11 September 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Accurate identification and mechanistic evaluation of pathogenic missense variants with Rhapsody-2](https://www.pnas.org/doi/10.1073/pnas.2418100122)

**Citation:** Banerjee, A., Bogetti, A. T., & Bahar, I. (2025). Accurate identification and mechanistic evaluation of pathogenic missense variants with Rhapsody-2. Proceedings of the National Academy of Sciences, 122(18).

**Abstract:**

Understanding the effects of missense mutations or single amino acid variants (SAVs) on protein function is crucial for elucidating the molecular basis of diseases/disorders and designing rational therapies. We introduce here Rhapsody-2, a machine learning tool for discriminating pathogenic and neutral SAVs, significantly expanding on a precursor limited by the availability of structural data. With the advent of AlphaFold2 as a powerful tool for structure prediction, Rhapsody-2 is trained on a significantly expanded dataset of 117,525 SAVs corresponding to 12,094 human proteins reported in the ClinVar database. Adopting a broad set of descriptors composed of sequence evolutionary, structural, dynamic, and energetics features in the training algorithm, Rhapsody-2 achieved an AUROC of 0.94 in 10-fold cross-validation when all SAVs of a particular test protein (mutant) were excluded from the training set. Benchmarking against a variety of testing datasets demonstrated the high performance of Rhapsody-2. While sequence evolutionary descriptors play a dominant role in pathogenicity prediction, those based on structural dynamics provide a mechanistic interpretation. Notably, residues involved in allosteric communication and those distinguished by pronounced fluctuations in the high-frequency modes of motion or subject to spatial constraints in soft modes usually give rise to pathogenicity when mutated. Overall, Rhapsody-2 provides an efficient and transparent tool for accurately predicting the pathogenicity of SAVs and unraveling the mechanistic basis of the observed behavior, thus advancing our understanding of genotype-to-phenotype relations.

## 28 August 2026

**Presenter:** Özlem Şimşek

**Date:** 28 August 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Interpreting Protein Language Models: high attention sites predict functional regions](https://www.biorxiv.org/content/10.64898/2026.07.29.741641v1)

**Citation:** Pribus, S. J., Altman, R. B., & Nayar, G. (2026). Interpreting Protein Language Models: high attention sites predict functional regions. bioRxiv.

**Abstract:**

Computational proteomics has revolutionized biomedical research, guiding targeted experimental exploration to accelerate protein-based mechanistic discovery. Protein Language Models (PLMs) enable scalable, resource-efficient study; through large-scale training on only primary protein sequences, PLMs generate vector representations of protein structure that have been shown to capture biochemical, evolutionary, and structural properties. A core component of PLMs is the attention mechanism, which specifically captures long-range interactions across a protein sequence in attention matrices. Using the Evolutionary Scale Modelling 2 (ESM-2) PLM, we previously developed a novel method to identify "High Attention" (HA) sites. HA sites are specific residues that ESM-2 assigns the most attention to early during encoding. Here, we further characterize these HA sites across structural and functional metrics. Using unsupervised clustering, we find HA sites can be categorized as "structural core", "structural pathogenic", "core pathogenic", or "low-confidence". We further use AlphaMissense pathogenicity predictions and the pan-cancer analysis of whole genomes (PCAWG)-labeled pathogenic variant positions to show that HA sites predict protein regions with high pathogenic risk. Finally, we explore the utility of HA sites for suggesting candidate binding sites, identifying multiple cancer protein examples where HA sites identified regions with previously undiscovered high interaction likelihood and thus potential therapeutic utility. Our work demonstrates the biological interpretability of PLM representations and offers a valuable method to prioritize functionally relevant protein residues for targeted biomedical research.

## 11 August 2026

**Presenter:** Amirreza Sattarzadeh (Emir Rıza Settarzade)

**Date:** 11 August 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Task- and dataset-specific information in protein language models](https://arxiv.org/abs/2608.12090)

**Citation:** Joeres, R., Senatorov, I., Kolchina, A., Klakow, D., & Kalinina, O. V. (2026). Task- and dataset-specific information in protein language models. arXiv preprint arXiv:2608.12090.

**Abstract:**

Protein language models (PLMs) have transferred the latest advances from natural language processing to computational biology. These models, trained on large corpora of protein sequence data, are widely used to translate amino acid sequences into latent-space embeddings, ready for use in diverse downstream tasks (DTs). By consensus, embeddings from the models' last layers are used, while the models' internal behavior remains poorly understood. We analyzed 13 PLMs across 15 DTs and 9 datasets to assess the value of embeddings from intermediate PLM layers. We trained probe models on embeddings from each layer, compared their performance, and showed that the last layers of PLMs rarely produced embeddings that led to the best results on downstream tasks. Furthermore, we identified a connection between how models learn a certain DT and the similarity between that DT and the pre-training objective. For example, for residue-level downstream tasks, we observed a steady increase in performance across almost all PLM layers, which we attributed to their similarity to most PLMs' pre-training objectives. To allow the community to capitalize on our findings, we provide PLMSommelier, a Python package that automatically identifies the best PLM layer for a given DT with ~98% accuracy and creates a truncated model using only the early layers up to the best-performing layer. This will help users save time and memory during inference and yield better predictive performance.

## 7 August 2026

**Presenter:** Özdeniz Dolu

**Date:** 7 August 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [A Diffusion Model to Shrink Proteins While Maintaining Their Function](https://arxiv.org/abs/2511.07390)

**Citation:** Baron, E., Amin, A. N., Weitzman, R., Marks, D., & Wilson, A. G. (2025). A Diffusion Model to Shrink Proteins While Maintaining Their Function. ICML 2025 Workshop on Generative AI and Biology; arXiv preprint arXiv:2511.07390.

**Material:**
- [Code (SCISOR)](https://github.com/baronet2/SCISOR)
- [Slides](07-08-26_Ozdeniz_SCISOR_slides.pdf)

**Abstract:**

Many proteins useful in modern medicine or bioengineering are challenging to make in the lab, fuse with other proteins in cells, or deliver to tissues in the body, because their sequences are too long. Shortening these sequences typically involves costly, time-consuming experimental campaigns. Ideally, we could instead use modern models of massive databases of sequences from nature to learn how to propose shrunken proteins that resemble sequences found in nature. Unfortunately, these models struggle to efficiently search the combinatorial space of all deletions, and are not trained with inductive biases to learn how to delete. To address this gap, we propose SCISOR, a novel discrete diffusion model that deletes letters from sequences to generate protein samples that resemble those found in nature. To do so, SCISOR trains a de-noiser to reverse a forward noising process that adds random insertions to natural sequences. As a generative model, SCISOR fits evolutionary sequence data competitively with previous large models. In evaluation, SCISOR achieves state-of-the-art predictions of the functional effects of deletions on ProteinGym. Finally, we use the SCISOR de-noiser to shrink long protein sequences, and show that its suggested deletions result in significantly more realistic proteins and more often preserve functional motifs than previous models of evolutionary sequences.

## 31 July 2026

**Presenter:** Ahmet Yigit

**Date:** 31 July 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [From Static Structures to Ensembles: Studying and Harnessing Protein Structure Tokenization](https://arxiv.org/abs/2511.10056) (NeurIPS 2025)

**Citation:** Liu, Z., Feng, B., Cao, H., & Li, Y. (2025). From Static Structures to Ensembles: Studying and Harnessing Protein Structure Tokenization. Advances in Neural Information Processing Systems (NeurIPS 2025).

**Abstract:**

Protein structure tokenization converts 3D structures into discrete or vectorized representations, enabling the integration of structural and sequence data. Despite many recent works on structure tokenization, the properties of the underlying discrete representations are not well understood. In this work, we first demonstrate that the successful utilization of structural tokens in a language model for structure prediction depends on using rich, pre-trained sequence embeddings to bridge the semantic gap between the sequence and structural "language". The analysis of the structural vocabulary itself then reveals significant semantic redundancy, where multiple distinct tokens correspond to nearly identical local geometries, acting as "structural synonyms". This redundancy, rather than being a flaw, can be exploited with a simple "synonym swap" strategy to generate diverse conformational ensembles by perturbing a predicted structure with its structural synonyms. This computationally lightweight method accurately recapitulates protein flexibility, performing competitively with state-of-the-art models. Our study provides fundamental insights into the nature of discrete protein structure representations and introduces a powerful, near-instantaneous method for modeling protein dynamics.

## 24 July 2026

**Presenter:** Gökçe Uludoğan

**Date:** 24 July 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Deep models of protein evolution in time generate realistic evolutionary trajectories and functional proteins](https://www.biorxiv.org/content/10.64898/2026.02.19.706898v1)

**Citation:** Koehl, A., Prillo, S., Liu, M., Xiong, J., Weng, L., Savage, D. F., & Song, Y. S. (2026). Deep models of protein evolution in time generate realistic evolutionary trajectories and functional proteins. bioRxiv.

**Material:**
- [Slides](24-07-26_Gökçe_Deep%20models%20of%20protein%20evolution%20in%20time%20generate%20realistic%20evolutionary%20trajectories%20and%20functional%20proteins.pdf)

**Abstract:**

Models of protein evolution are foundational to biology, underpinning essential techniques such as phylogenetic tree inference, ancestral sequence reconstruction, multiple sequence alignment, variant effect prediction, and protein design. Historically, for computational tractability, these models have relied on the simplifying - but biologically unrealistic - assumption that sites in a given protein evolve independently of each other. A crucial test of any evolutionary model is its ability to simulate realistic evolutionary trajectories, but the independent-sites assumption leads to simulations that poorly reflect the complexity of natural protein evolution. Here we introduce PEINT (Protein Evolution IN Time), a flexible and generalizable deep learning framework for modeling how the entire protein sequence evolves over time while incorporating complex interactions between sites. This framework enables learning realistic patterns of constrained evolutionary transitions directly from millions of protein sequences spanning diverse fold families. Furthermore, unlike classical models that require pre-aligned sequences, PEINT learns indel dynamics directly from raw, unaligned sequences, thereby eliminating potential biases from alignment errors that can lead to incorrect inference of evolutionary patterns. By capturing higher-order epistatic interactions and modeling insertion-deletion processes that classical models typically ignore, PEINT accurately reproduces key signatures of natural evolution, including conservation patterns and family-specific dynamics. When simulating evolution along phylogenetic trees, PEINT generates highly novel sequences that preserve protein function, which we validate through experimental characterization of simulated carbonic anhydrase variants that retain enzymatic activity. PEINT thus enables realistic simulation of protein evolution that explores new sequence space while respecting structural and functional constraints. This evolution-informed generative modeling framework offers a powerful new tool for advancing both phylogenetic inference and protein engineering.

## 19 June 2026

**Presenter:** Amirreza Sattarzadeh (Emir Rıza Settarzade)

**Date:** 19 June 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Learning protein representations with conformational dynamics](https://doi.org/10.1093/bioinformatics/btag254)

**Citation:** Kalifa, D., Horvitz, E., & Radinsky, K. (2026). Learning protein representations with conformational dynamics. Bioinformatics, 42(5).

**Abstract:**

**Motivation:** Proteins change shape as they work, and these changing states control whether binding sites are exposed, signals are relayed, and catalysis proceeds. Most protein language models (PLMs) pair a sequence with a single structural snapshot, which can miss state-dependent features central to interaction, localization, and enzyme activity. Studies also indicate that many proteins assume multiple, functionally relevant shapes, motivating approaches that learn from this variability.

**Results:** We present DynamicsPLM, a PLM conditioned on ensembles of computationally generated conformations to derive state-aware representations. DynamicsPLM improves predictive performance across protein–protein interaction, subcellular localization, enzyme classification, and metal-ion binding. On a widely used protein–protein interaction benchmark, it achieves a four-point accuracy gain over the strongest baseline. On a curated test set enriched for proteins with multiple conformational states, the margin increases to eleven points. These findings argue for a shift from static to dynamics-aware modeling, in which conformational variability is treated as informative. By elevating conformational state to a central element of machine learning in protein biology, this work advances modeling toward mechanisms that better reflect how proteins operate in cells and provides a route to actionable hypotheses about when and how binding, signaling, and catalysis occur.

## 22 May 2026

**Presenter:** Buse Giledereli

**Date:** 22 May 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [ENSEMBITS: an alphabet of protein conformational ensembles](https://arxiv.org/abs/2605.13789)

**Citation:** Shi, K., & Oliver, C. (2026). ENSEMBITS: an alphabet of protein conformational ensembles. arXiv preprint arXiv:2605.13789.

**Abstract:**

Protein structure tokenizers serve as essential tools in protein language modeling and evolutionary analysis, yet existing approaches only encode static structural geometry while overlooking protein dynamics. This work introduces Ensembits, representing the first tokenizer designed specifically for protein conformational ensembles. The method addresses key challenges in encoding dynamics: developing meaningful geometric representations across different conformations, achieving permutation-invariance for variable-sized ensembles, and managing sparsity issues inherent to dynamics datasets. Built using a Residual VQ-VAE with frame distillation training on molecular dynamics data, Ensembits demonstrates superior performance on RMSF prediction and motion amplitude assessment. Remarkably, it matches or surpasses static tokenizers on enzyme classification, gene ontology, binding predictions, and zero-shot mutation analysis despite requiring substantially less training data. A distinctive capability enables predicting dynamics tokens from single predicted structures, helping mitigate data scarcity challenges. The authors position this as an essential discrete vocabulary for integrating protein dynamics into emerging ensemble generation and design paradigms.

## 15 May 2026

**Presenter:** Burak Suyunu

**Date:** 15 May 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [FoldToken: Learning Protein Language via Vector Quantization and Beyond](https://ojs.aaai.org/index.php/AAAI/article/view/31998)

**Citation:** Gao, Z., Tan, C., Wang, J., Huang, Y., Wu, L., & Li, S. Z. (2025, April). Foldtoken: Learning protein language via vector quantization and beyond. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 39, No. 1, pp. 219-227).

**Material:**
- [Slides](15-05-26_Burak_FoldToken.pdf)

## 17 April 2026

**Presenter:** Beyza Nur Deniz

**Date:** 17 April 2026, 11:00 UTC+3 (Istanbul)

**Paper:** [Disentangling coevolutionary constraints for modeling protein conformational heterogeneity](https://www.nature.com/articles/s42004-026-01940-9)

**Citation:** Li, S., Zhang, C., Kong, L., Xue, Y., Liu, S., & Gao, Y. Q. (2026). Disentangling coevolutionary constraints for modeling protein conformational heterogeneity. Communications Chemistry, 9, 146.

**Abstract:**

Accurate characterization of multi-state protein conformations is crucial for understanding their functional mechanisms and advancing targeted therapies. Extracting coevolutionary constraints from homologous sequences helps reveal protein structure and function, which can be automatically captured by MSA Transformer leveraging attention mechanisms. Making use of the multi-conformational coevolutionary signals captured by MSA Transformer, we introduce in this study EvoSplit to disentangle coevolutionary signals associated with distinct conformations to guide protein structure predictions. EvoSplit outperforms AF-Cluster on 85 fold-switching proteins and successfully models the conformations of proteins beyond AlphaFold2's training set. We then identify 54 candidates with potential conformational diversity for cancer-related human proteins. Notably, for five GTPases, EvoSplit consistently predicts two conformations, one of which has not been previously reported. As an important example, the protein–protein interaction analysis provides new insights into novel HRAS function-associated conformations. Furthermore, the validity of these newly identified conformations is examined by evolutionary analysis and extensive molecular dynamics simulations.

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

