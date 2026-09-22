# Past Meetings — 2025

## 18 December 2025

**Presenter:** Buse Giledereli

**Date:** 18 December 2025, 14:00 UTC+3 (Istanbul)

**Paper:** [Protein Structure Tokenization via Geometric Byte Pair Encoding
](https://doi.org/10.48550/arXiv.2511.11758)

**Citation:** Sun, M., Yuan, W., Liu, G., Matusik, W., & Zitnik, M. (2025). Protein structure tokenization via geometric byte pair encoding. arXiv preprint arXiv:2511.11758.



**Material:** 
- [Slides](18-12-2025_Buse_Slides_GeoBPE.pptx)
- [Paper](18-12-2025_Buse_Paper_GeoBPE.pdf)
 
**Abstract:**

Protein structure is central to biological function, and enabling multimodal protein models requires joint reasoning over sequence, structure, and function. A key barrier is the lack of principled protein structure tokenizers (PSTs): existing approaches fix token size or rely on continuous vector codebooks, limiting interpretability, multi-scale control, and transfer across architectures. We introduce GEOBPE, a geometry-grounded PST that transforms continuous, noisy, multiscale backbone conformations into discrete “sentences” of geometry while enforcing global constraints. Analogous to byte-pair encoding, GEOBPE generates a hierarchical vocabulary of geometric primitives by iteratively (i) clustering Geo-Pair occurrences with k-medoids to yield a resolution-controllable vocabulary; (ii) quantizing each Geo-Pair to its closest medoid prototype; and (iii) reducing drift through differentiable inverse kinematics that optimizes boundary glue angles under an SE(3) end-frame loss. GEOBPE offers compression (>10× reduction in bits-per-residue at similar distortion rate), data efficiency (>10× less training data), and generalization (maintains test/train distortion ratio of 1.0 − 1.1). It is architecture-agnostic: (a) its hierarchical vocabulary provides a strong inductive bias for coarsening residue-level embeddings from large PLMs into motif- and protein-level representations, consistently outperforming leading PSTs across 12 tasks and 24 test splits; (b) paired with a transformer, GEOBPE supports unconditional backbone generation via language modeling; and (c) tokens align with CATH functional families and support expert-interpretable case studies, offering functional meaning absent in prior PSTs. Code is available at https://github.com/shiningsunnyday/PT-BPE/.

## 11 December 2025

**Presenter:** Özdeniz Dolu

**Date:** 11 December 2025, 14:00 UTC+3 (Istanbul)

**Paper:** [Rewriting protein alphabets with language models
](https://doi.org/10.1101/2025.11.27.690975)

**Citation:** Pantolini, L., Studer, G., Engist, L., Pudziuvelyte, I., Pommerening, F., Waterhouse, A., Tauriello, G., Steinegger, M., Schwede, T., & Durairaj, J. (2025). Rewriting protein alphabets with language models. bioRxiv.



**Material:** 
- [Slides](11-12-25_Ozdeniz_Slides_Rewriting_Alphabet.pdf)
- [Paper](11-12-25_Ozdeniz_Paper_Rewriting_Alphabet.pdf)
 
**Abstract:**

Detecting remote homology with speed and sensitivity is crucial for tasks like function annotation and structure prediction. We introduce a novel approach using contrastive learning to convert protein language model embeddings into a new 20-letter alphabet, TEA, enabling highly efficient large-scale protein homology searches. Searching with our alphabet performs on par with and complements structure-based methods without requiring any structural information, and with the speed of sequence search. Ultimately, we bring the exciting advances in protein language model representation learning to the plethora of sequence bioinformatics algorithms developed over the past century, offering a powerful new tool for biological discovery.

## 25 September 2025

**Presenter:** Amirreza Sattarzadeh (Emir Rıza Settarzade)

**Date:** 25 September 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [ProLLaMA: A Protein Large Language Model for
Multi-Task Protein Language Processing](https://doi.org/10.1109/TAI.2025.3564914)

**Citation:** L. Lv et al., "ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing," in IEEE Transactions on Artificial Intelligence, doi: 10.1109/TAI.2025.3564914.

**Material:** 
- [Slides](25-09-25_Emir_Slides_ProLLaMA.pdf)
- [Paper](25-09-25_Emir_Paper_ProLLaMA.pdf)
 
**Abstract:**

Recent advances in Protein Language Models (PLMs) have transformed protein engineering, yet unlike their counterparts in Natural Language Processing (NLP), current PLMs exhibit a fundamental limitation: they excel in either Protein Language Understanding (PLU) or Protein Language Generation (PLG), but rarely both. This fragmentation hinders progress in protein engineering. To bridge this gap, we introduce ProLLaMA, a multitask protein language model enhanced by the Evolutionary Protein Generation Framework (EPGF). We construct a comprehensive instruction dataset containing approximately 13 million samples with over 11,000 superfamily annotations to facilitate better modeling of sequence-function landscapes. We leverage a two-stage training approach to develop ProLLaMA, a multitask LLM with protein domain expertise. Our EPGF addresses the mismatch between statistic language modeling and biological constraints through three innovations: a multi-dimensional interpretable scorer, hierarchical efficient decoding, and a probabilistic-biophysical joint selection mechanism. Extensive experiments demonstrate that ProLLaMA excels in both unconditional and controllable protein generation tasks, achieving superior structural quality metrics compared to existing PLMs. Additionally, ProLLaMA demonstrates strong understanding capabilities with a 67.1% exact match rate in superfamily prediction. EPGF significantly enhances the biological viability of generated sequences, as evidenced by improved biophysical scores (+4.3%) and structural metrics (+14.5%).

## 11 September 2025

**Presenter:** Özdeniz Dolu

**Date:** 11 September 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Deep learning models for unbiased sequence-based PPI prediction plateau at an accuracy of 0.65](https://doi.org/10.1093/bioinformatics/btaf192)

**Citation:** Timo Reim, Anne Hartebrodt, David B Blumenthal, Judith Bernett, Markus List, Deep learning models for unbiased sequence-based PPI prediction plateau at an accuracy of 0.65, Bioinformatics, Volume 41, Issue Supplement_1, July 2025, Pages i590–i598

**Material:** 
- [Slides](11-09-25_Ozdeniz_Slides_PPI_Plateau.pdf)
- [Paper](11-09-25_Ozdeniz_Paper_PPI_Plateau.pdf)
 
**Abstract:**

Motivation:
As most proteins interact with other proteins to perform their respective functions, methods to computationally predict these interactions have been developed. However, flawed evaluation schemes and data leakage in test sets have obscured the fact that sequence-based protein–protein interaction (PPI) prediction is still an open problem. Recently, methods achieving better-than-random performance on leakage-reduced PPI data have been proposed.
Results:
Here, we show that the use of ESM-2 protein embeddings explains this performance gain irrespective of model architecture. We compared the performance of models with varying complexity, per-protein, and per-token embeddings, as well as the influence of self- or cross-attention, where all models plateaued at an accuracy of 0.65. Moreover, we show that the tested sequence-based models cannot implicitly learn a contact map as an intermediate layer. These results imply that other input types, such as structure, might be necessary for producing reliable PPI predictions.

## 4 September 2025
**Presenter:** Gökçe Uludoğan

**Date:** 4 September 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Protriever: End-to-End Differentiable Protein Homology Search for Fitness Prediction](https://arxiv.org/abs/2506.08954)

**Citation:** Weitzman, R., Groth, P. M., Van Niekerk, L., Otani, A., Gal, Y., Marks, D., & Notin, P. (2025). Protriever: End-to-End Differentiable Protein Homology Search for Fitness Prediction. arXiv preprint arXiv:2506.08954.

**Material:** 
- [Slides](Protriever-4-09-2025.pdf)


**Abstract:**

Retrieving homologous protein sequences is essential for a broad range of protein modeling tasks such as fitness prediction, protein design, structure modeling, and protein-protein interactions. Traditional workflows have relied on a two-step process: first retrieving homologs via Multiple Sequence Alignments (MSA), then training models on one or more of these alignments. However, MSA-based retrieval is computationally expensive, struggles with highly divergent sequences or complex insertions & deletions patterns, and operates independently of the downstream modeling objective. We introduce Protriever, an end-to-end differentiable framework that learns to retrieve relevant homologs while simultaneously training for the target task. When applied to protein fitness prediction, Protriever achieves state-of-the-art performance compared to sequence-based models that rely on MSA-based homolog retrieval, while being two orders of magnitude faster through efficient vector search. Protriever is both architecture- and task-agnostic, and can flexibly adapt to different retrieval strategies and protein databases at inference time -- offering a scalable alternative to alignment-centric approaches.

## 28 August 2025
**Presenter:** Özlem Şimşek

**Date:** 28 August 2025, 10:00 UTC+3 (Istanbul)

**Paper:** Prot2Chat: protein large language model with early fusion of text, sequence, and structure

**Citation:** Zhicong Wang, Zicheng Ma, Ziqiang Cao, Changlong Zhou, Jun Zhang, Yi Qin Gao, Prot2Chat: protein large language model with early fusion of text, sequence, and structure, Bioinformatics, Volume 41, Issue 8, August 2025, btaf396, https://doi.org/10.1093/bioinformatics/btaf396

**Abstract:**

Motivation: Proteins are of great significance in living organisms. However, understanding their functions encounters numerous challenges, such as insufficient integration of multimodal information, a large number of training parameters, limited flexibility of classification-based methods, and the lack of systematic evaluation metrics for protein question answering systems. To tackle these issues, we propose the Prot2Chat framework.

Results: We modified ProteinMPNN to encode protein sequence and structural information in a unified way. We used a large language model (LLM) to encode questions into vectors and developed a protein-text adapter to compress protein information into virtual tokens based on these vectors, achieving the early fusion of text and protein information. Finally, the same LLM reads the virtual tokens and the questions to generate answers. To optimize training efficiency, we froze the encoder and employed low-rank adaptation (LoRA) techniques for the LLM. Experiments on two datasets show that both automated metrics and expert evaluations demonstrate the superior performance of our model, and zero-shot prediction results highlight its generalization ability. We have developed an easy-to-use web interactive platform and a rapid installation option, allowing users to swiftly engage with Prot2Chat.

Availability and implementation: The models and codes are available at https://github.com/wangzc1233/Prot2Chat.

## 21 August 2025

**Presenter:** Burak Suyunu

**Date:** 21 August 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Protein Structure Tokenization: Benchmarking and New Recipe](https://arxiv.org/abs/2503.00089)

**Citation:** 
Yuan, X., Wang, Z., Collins, M., & Rangwala, H. (2025). Protein structure tokenization: Benchmarking and new recipe. arXiv preprint arXiv:2503.00089.

**Material:** 
- [Slides](LifeLU_Reading-210825-Burak-Protein_Structure_Tokenization.pdf)

**Abstract:**

Recent years have witnessed a surge in the development of protein structural tokenization methods, which chunk protein 3D structures into discrete or continuous representations. Structure tokenization enables the direct application of powerful techniques like language modeling for protein structures, and large multimodal models to integrate structures with protein sequences and functional texts. Despite the progress, the capabilities and limitations of these methods remain poorly understood due to the lack of a unified evaluation framework. We first introduce StructTokenBench, a framework that comprehensively evaluates the quality and efficiency of structure tokenizers, focusing on fine-grained local substructures rather than global structures, as typical in existing benchmarks. Our evaluations reveal that no single model dominates all benchmarking perspectives. Observations of codebook under-utilization led us to develop AminoAseed, a simple yet effective strategy that enhances codebook gradient updates and optimally balances codebook size and dimension for improved tokenizer utilization and quality. Compared to the leading model ESM3, our method achieves an average of 6.31% performance improvement across 24 supervised tasks, with sensitivity and utilization rates increased by 12.83% and 124.03%, respectively. Source code and model weights are available at https://github.com/KatarinaYuan/StructTokenBench.

## 14 August 2025

**Presenter:** Amirreza Sattarzadeh (Emir Rıza Settarzade)

**Date:** 14 August 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [SSEmb: A joint embedding of protein sequence and structure enables robust variant effect predictions](https://doi.org/10.1038/s41467-024-53982-z)

**Citation:** 
Blaabjerg, L.M., Jonsson, N., Boomsma, W. et al. SSEmb: A joint embedding of protein sequence and structure enables robust variant effect predictions. Nat Commun 15, 9646 (2024). https://doi.org/10.1038/s41467-024-53982-z

**Material:** 
- [Slides](14-08-25_Emir_Slides_SSEmb.pdf)
- [Paper](14-08-25_Emir_Paper_SSEmb.pdf)
 

**Abstract:**

The ability to predict how amino acid changes affect proteins has a wide range of applications including in disease variant classification and protein engineering. Many existing methods focus on learning from patterns found in either protein sequences or protein structures. Here, we present a method for integrating information from sequence and structure in a single model that we term SSEmb (Sequence Structure Embedding). SSEmb combines a graph representation for the protein structure with a transformer model for processing multiple sequence alignments. We show that by integrating both types of information we obtain a variant effect prediction model that is robust when sequence information is scarce. We also show that SSEmb learns embeddings of the sequence and structure that are useful for other downstream tasks such as to predict protein-protein binding sites. We envisage that SSEmb may be useful both for variant effect predictions and as a representation for learning to predict protein properties that depend on sequence and structure.

## 7 August 2025

**Presenter:** Özdeniz Dolu

**Date:** 7 August 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Scaling down protein language modeling with MSA Pairformer](https://doi.org/10.1101/2025.08.02.668173)

**Citation:** 
Akiyama, Y., Zhang, Z., Mirdita, M., Steinegger, M., & Ovchinnikov, S. (2025). Scaling down protein language modeling with MSA Pairformer. bioRxiv.


**Material:** 
- [Slides](07-08-25_Ozdeniz_Slides_MSA_Pairformer.pdf)
- [Paper](07-08-25_Ozdeniz_Paper_MSA_Pairformer.pdf)
 
**Abstract:**

Recent efforts in protein language modeling have focused on scaling single-sequence models and their training data, requiring vast compute resources that limit accessibility. Although models that use multiple sequence alignments (MSA), such as MSA Transformer, offer parameter-efficient alternatives by extracting evolutionary information directly from homologous sequences rather than storing it in parameters, they generally underperform compared to single-sequence-based language due to memory inefficiencies that limit the number of sequences and averaging evolutionary signals across the MSA. We address these challenges with MSA Pairformer, a 111M parameter memory-efficient MSA-based protein language model that extracts evolutionary signals most relevant to a query sequence through bi-directional updates of sequence and pairwise representations. MSA Pairformer achieves state-of-the-art performance in unsupervised contact prediction, outperforming ESM2-15B by 6% points while using two orders of magnitude fewer parameters. In predicting contacts at protein-protein interfaces, MSA Pairformer substantially outperforms all methods with a 24% point increase over MSA Transformer. Unlike single-sequence models that deteriorate in variant effect prediction as they scale, MSA Pairformer maintains strong performance in both tasks. Ablation studies reveal triangle operations remove indirect correlations, and unlike MSA Transformer, MSA Pairformer does not hallucinate contacts after removing covariance, enabling reliable screening of interacting sequence pairs. Overall, our work presents an alternative to the current scaling paradigm in protein language modeling, enabling efficient adaptation to rapidly expanding sequence databases and opening new directions for biological discovery.

## 24 July 2025

**Presenter:** Gökçe Uludoğan

**Date:** 24 July 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Structural motif search across the protein-universe with Folddisco](https://www.biorxiv.org/content/10.1101/2025.07.06.663357v1.full.pdf)

**Citation:** 
Kim, H., Kim, R. S., Mirdita, M., & Steinegger, M. (2025). Structural motif search across the protein-universe with Folddisco. bioRxiv, 2025-07.


**Material:** 
- [Slides](Folddisco-24-07-25.pdf)
 
**Abstract:**

Detecting similar protein structural motifs, functionally crucial short 3D patterns, in large structure collections is computationally prohibitive. Therefore, we developed Folddisco, which overcomes this through an index of position-independent geometric features, including side-chain orientation, combined with a rarity-based scoring system. Folddisco indexes 53 million AFDB50 structures into 1.45 terabyte within 24 hours, enabling rapid detection of discontinuous or segment motifs. Folddisco is more accurate and storage-efficient than state-of-the-art methods, while being an order of magnitude faster. Folddisco is free software available at folddisco.foldseek.com and a webserver at search.foldseek.com/folddisco.



## 17 July 2025

**Presenter:** Amirreza Sattarzadeh (Emir Rıza Settarzade)

**Date:** 17 July 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [PETA: evaluating the impact of protein transfer learning with sub-word tokenization on downstream applications](https://doi.org/10.1186/s13321-024-00884-3)

**Citation:** Tan, Y., Li, M., Zhou, Z. et al. PETA: evaluating the impact of protein transfer learning with sub-word tokenization on downstream applications. J Cheminform 16, 92 (2024). https://doi.org/10.1186/s13321-024-00884-3

**Material:** 
- [Slides](17-07-25_Emir_Slides_PETA.pdf)
- [Paper](26-06-25_Emir_Paper_PETA.pdf)

**Abstract:**
Protein language models (PLMs) play a dominant role in protein representation learning. Most existing PLMs regard proteins as sequences of 20 natural amino acids. The problem with this representation method is that it simply divides the protein sequence into sequences of individual amino acids, ignoring the fact that certain residues often occur together. Therefore, it is inappropriate to view amino acids as isolated tokens. Instead, the PLMs should recognize the frequently occurring combinations of amino acids as a single token. In this study, we use the byte-pair-encoding algorithm and unigram to construct advanced residue vocabularies for protein sequence tokenization, and we have shown that PLMs pre-trained using these advanced vocabularies exhibit superior performance on downstream tasks when compared to those trained with simple vocabularies. Furthermore, we introduce PETA, a comprehensive benchmark for systematically evaluating PLMs. We find that vocabularies comprising 50 and 200 elements achieve optimal performance. Our code, model weights, and datasets are available at https://github.com/ginnm/ProteinPretraining. 

## 26 June 2025

**Presenter:** Özdeniz Dolu

**Date:** 26 June 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [DeepProSite: structure-aware protein binding site prediction using ESMFold and pretrained language model](https://doi.org/10.1093/bioinformatics/btad718)

**Citation:** Yitian Fang, Yi Jiang, Leyi Wei, Qin Ma, Zhixiang Ren, Qianmu Yuan, Dong-Qing Wei, DeepProSite: structure-aware protein binding site prediction using ESMFold and pretrained language model, Bioinformatics, Volume 39, Issue 12, December 2023, btad718, https://doi.org/10.1093/bioinformatics/btad718

**Material:** 
- [Slides](26-06-25_Ozdeniz_Slides_DeepProSite.pdf)
- [Paper](26-06-25_Ozdeniz_Paper_DeepProSite.pdf)

**Abstract:**
Motivation:
Identifying the functional sites of a protein, such as the binding sites of proteins, peptides, or other biological components, is crucial for understanding related biological processes and drug design. However, existing sequence-based methods have limited predictive accuracy, as they only consider sequence-adjacent contextual features and lack structural information.
Results:
In this study, DeepProSite is presented as a new framework for identifying protein binding site that utilizes protein structure and sequence information. DeepProSite first generates protein structures from ESMFold and sequence representations from pretrained language models. It then uses Graph Transformer and formulates binding site predictions as graph node classifications. In predicting protein–protein/peptide binding sites, DeepProSite outperforms state-of-the-art sequence- and structure-based methods on most metrics. Moreover, DeepProSite maintains its performance when predicting unbound structures, in contrast to competing structure-based prediction methods. DeepProSite is also extended to the prediction of binding sites for nucleic acids and other ligands, verifying its generalization capability. Finally, an online server for predicting multiple types of residue is established as the implementation of the proposed DeepProSite.


## 19 June 2025
**Presenter:** Burak Suyunu

**Date:** 19 June 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Accurate structure prediction of biomolecular interactions with AlphaFold 3](https://www.nature.com/articles/s41586-024-07487-w) (Part 3)

**Citation:** Abramson, J., Adler, J., Dunger, J. et al. Accurate structure prediction of biomolecular interactions with AlphaFold 3. Nature 630, 493–500 (2024). https://doi.org/10.1038/s41586-024-07487-w

**Material:** 
- [Slides](LifeLU_Reading-Alphafold3-Burak.pdf)

**Abstract:**

The introduction of AlphaFold 2 has spurred a revolution in modelling the structure of proteins and their interactions, enabling a huge range of applications in protein modelling and design. Here we describe our AlphaFold 3 model with a substantially updated diffusion-based architecture that is capable of predicting the joint structure of complexes including proteins, nucleic acids, small molecules, ions and modified residues. The new AlphaFold model demonstrates substantially improved accuracy over many previous specialized tools: far greater accuracy for protein–ligand interactions compared with state-of-the-art docking tools, much higher accuracy for protein–nucleic acid interactions compared with nucleic-acid-specific predictors and substantially higher antibody–antigen prediction accuracy compared with AlphaFold-Multimer v.2.3. Together, these results show that high-accuracy modelling across biomolecular space is possible within a single unified deep-learning framework.

**Extra Material:**

**Articles:**  
🔗 [The Illustrated AlphaFold](https://elanapearl.github.io/blog/2024/the-illustrated-alphafold/)

🔗 [AlphaFold3 and its improvements in comparison to AlphaFold2](https://medium.com/@falk_hoffmann/alphafold3-and-its-improvements-in-comparison-to-alphafold2-96815ffbb044)  

🔗 [AlphaFold2, AlphaFold-Multimer, AlphaFold3](https://310.ai/blog/alphafold2-alphafold-multimer-alphafold3)  

🔗 ["Sparks of Chemical Intuition"-and Gross Limitations!-in AlphaFold 3](https://towardsdatascience.com/sparks-of-chemical-intuition-and-gross-limitations-in-alphafold-3-8487ba4dfb53/)  

🔗 [AlphaFold3 Explained](https://www.ai4pharm.info/alphafold3)  

🔗 [Introduction to diffusion models for machine learning](https://www.superannotate.com/blog/diffusion-models)

🔗 [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)  

**Videos:**  
▶️ [AlphaFold 3 deep dive | Looking Glass Universe](https://www.youtube.com/watch?v=Or3iq4_9-wA)

▶️ [Diffusion Models for AI Image Generation | IBM Technology](https://www.youtube.com/watch?v=x2GRE-RzmD8	)



## 22 May 2025
**Presenter:** Burak Suyunu

**Date:** 22 May 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Accurate structure prediction of biomolecular interactions with AlphaFold 3](https://www.nature.com/articles/s41586-024-07487-w) (Part 2)

**Citation:** Abramson, J., Adler, J., Dunger, J. et al. Accurate structure prediction of biomolecular interactions with AlphaFold 3. Nature 630, 493–500 (2024). https://doi.org/10.1038/s41586-024-07487-w

**Abstract:**

The introduction of AlphaFold 2 has spurred a revolution in modelling the structure of proteins and their interactions, enabling a huge range of applications in protein modelling and design. Here we describe our AlphaFold 3 model with a substantially updated diffusion-based architecture that is capable of predicting the joint structure of complexes including proteins, nucleic acids, small molecules, ions and modified residues. The new AlphaFold model demonstrates substantially improved accuracy over many previous specialized tools: far greater accuracy for protein–ligand interactions compared with state-of-the-art docking tools, much higher accuracy for protein–nucleic acid interactions compared with nucleic-acid-specific predictors and substantially higher antibody–antigen prediction accuracy compared with AlphaFold-Multimer v.2.3. Together, these results show that high-accuracy modelling across biomolecular space is possible within a single unified deep-learning framework.

## 15 May 2025
**Presenter:** Burak Suyunu

**Date:** 15 May 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Accurate structure prediction of biomolecular interactions with AlphaFold 3](https://www.nature.com/articles/s41586-024-07487-w) (Part 1)

**Citation:** Abramson, J., Adler, J., Dunger, J. et al. Accurate structure prediction of biomolecular interactions with AlphaFold 3. Nature 630, 493–500 (2024). https://doi.org/10.1038/s41586-024-07487-w


**Abstract:**

The introduction of AlphaFold 2 has spurred a revolution in modelling the structure of proteins and their interactions, enabling a huge range of applications in protein modelling and design. Here we describe our AlphaFold 3 model with a substantially updated diffusion-based architecture that is capable of predicting the joint structure of complexes including proteins, nucleic acids, small molecules, ions and modified residues. The new AlphaFold model demonstrates substantially improved accuracy over many previous specialized tools: far greater accuracy for protein–ligand interactions compared with state-of-the-art docking tools, much higher accuracy for protein–nucleic acid interactions compared with nucleic-acid-specific predictors and substantially higher antibody–antigen prediction accuracy compared with AlphaFold-Multimer v.2.3. Together, these results show that high-accuracy modelling across biomolecular space is possible within a single unified deep-learning framework.

## 17 April 2025

**Presenter:** Gökçe Uludoğan

**Date:** 17 April 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Miniaturizing, Modifying, and Magnifying Nature’s Proteins with Raygun](https://www.biorxiv.org/content/10.1101/2024.08.13.607858v2)

**Citation:** Devkota, K., Shonai, D., Mao, J., Ko, Y. S., Wang, W., Soderling, S., & Singh, R. (2024). Miniaturizing, Modifying, and Magnifying Nature’s Proteins with Raygun. bioRxiv, 2024-08.

**Material:** 
- [Slides](Raygun_17_April_2025.pdf)

**Abstract:**

Proteins have evolved over billions of years through extensive and coordinated substitutions, insertions and deletions (indels). Computational protein design cannot yet fully mimic nature's ability to engineer new proteins from existing templates. Protein language models generate informative per-residue representations, but leveraging them to execute large-scale, function-preserving mutations and indels has remained beyond reach. We introduce Raygun, a generative AI framework that unlocks efficient miniaturization, modification, and augmentation of proteins, using a novel probabilistic encoding of protein sequences constructed from language model embeddings. Emulating evolution, Raygun shrinks proteins by 10-25% (sometimes over 50%) while preserving predicted structural integrity and fidelity, introduces extensive sequence diversity while preserving functional sites, and can expand proteins beyond their natural size. These capabilities unlock new opportunities in gene therapy and biotechnology. In cell-based validation, Raygun successfully miniaturized fluorescent proteins, two of which are smaller than 96% of fluorescent proteins reported in FPbase, as well as TurboID, a synthetic biotin ligase widely adopted for proteomics. It also successfully expanded Epidermal Growth Factor (EGF), a natural binding partner to the EGFR protein, generating EGF variants with higher binding affinity than the wildtype. Raygun's conceptual innovations in template-based protein design reveal that protein function can be encoded in a length-independent space. This fundamental insight bridges protein representation learning with evolutionary biology and could unlock the development of more efficient molecular tools and biological therapeutics.

## 10 April 2025

**Presenter:** Özdeniz Dolu

**Date:** 10 April 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Molecular grammars of intrinsically disordered regions that span the human proteome](https://www.biorxiv.org/content/10.1101/2025.02.27.640591v1)

**Citation:** Ruff, K. M., King, M. R., Ying, A. W., Liu, V., Pant, A., Lieberman, W. E., … Pappu, R. V. (2025). Molecular grammars of intrinsically disordered regions that span the human proteome. bioRxiv. doi:10.1101/2025.02.27.640591

**Material:** 
- [Slides](10-04-25_Ozdeniz_Slides_Molecular_Grammars.pdf)
- [Paper](10-04-25_Ozdeniz_Paper_Molecular_Grammars.pdf)

**Abstract:**

Intrinsically disordered regions (IDRs) of proteins are defined by functionally relevant molecular grammars. This refers to IDR-specific non-random amino acid compositions and non-random patterning of distinct pairs of amino acid types. Here, we introduce GIN (Grammars Inferred using NARDINI+) as a resource, which we have used to extract the molecular grammars of all human IDRs and classified them into thirty distinct clusters. Unbiased analyses of IDRome-spanning grammars reveals that specialized IDR grammar features direct biological processes, cellular localization preferences, and molecular functions. IDRs with exceptional grammars, defined as sequences with high-scoring non-random features, are harbored in proteins and complexes that enable spatial and temporal sorting of biochemical activities. Protein complexes within the nucleus recruit specific factors through top-scoring IDRs. These IDRs are frequently disrupted via cancer-associated mutations and fusion oncoproteins. Overall, GIN enables the decoding of sequence-function relationships of IDRs and can be deployed in IDR-specific and IDRome-wide analyses.

## 20 March 2025

**Presenter:** Özlem Şimşek

**Date:** 20 March 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Fine-tuning protein language models boosts predictions across diverse tasks](https://www.nature.com/articles/s41467-024-51844-2)

**Citation:** Schmirler, R., Heinzinger, M., & Rost, B. (2024). Fine-tuning protein language models boosts predictions across diverse tasks. Nature Communications, 15, 2024

**Abstract:**

Prediction methods inputting embeddings from protein language models have reached or even surpassed state-of-the-art performance on many protein prediction tasks. In natural language processing fine-tuning large language models has become the de facto standard. In contrast, most protein language model-based protein predictions do not back-propagate to the language model. Here, we compare the fine-tuning of three state-of-the-art models (ESM2, ProtT5, Ankh) on eight different tasks. Two results stand out. Firstly, task-specific supervised fine-tuning almost always improves downstream predictions. Secondly, parameter-efficient fine-tuning can reach similar improvements consuming substantially fewer resources at up to 4.5-fold acceleration of training over fine-tuning full models. Our results suggest to always try fine-tuning, in particular for problems with small datasets, such as for fitness landscape predictions of a single protein. For ease of adaptability, we provide easy-to-use notebooks to fine-tune all models used during this work for per-protein (pooling) and per-residue prediction tasks.

## 13 March 2025

**Presenter:** Burak Suyunu

**Date:** 13 March 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Highly accurate protein structure prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2) Part 2

**Citation:** Jumper, J., Evans, R., Pritzel, A. et al. Highly accurate protein structure prediction with AlphaFold. Nature 596, 583–589 (2021). https://doi.org/10.1038/s41586-021-03819-2

**Abstract:**

Proteins are essential to life, and understanding their structure can facilitate a mechanistic understanding of their function. Through an enormous experimental effort, the structures of around 100,000 unique proteins have been determined, but this represents a small fraction of the billions of known protein sequences. Structural coverage is bottlenecked by the months to years of painstaking effort required to determine a single protein structure. Accurate computational approaches are needed to address this gap and to enable large-scale structural bioinformatics. Predicting the three-dimensional structure that a protein will adopt based solely on its amino acid sequence—the structure prediction component of the ‘protein folding problem’—has been an important open research problem for more than 50 years. Despite recent progress, existing methods fall far short of atomic accuracy, especially when no homologous structure is available. Here we provide the first computational method that can regularly predict protein structures with atomic accuracy even in cases in which no similar structure is known. We validated an entirely redesigned version of our neural network-based model, AlphaFold, in the challenging 14th Critical Assessment of protein Structure Prediction (CASP14), demonstrating accuracy competitive with experimental structures in a majority of cases and greatly outperforming other methods. Underpinning the latest version of AlphaFold is a novel machine learning approach that incorporates physical and biological knowledge about protein structure, leveraging multi-sequence alignments, into the design of the deep learning algorithm.

**Material:** 
- [Slides](LifeLU_Reading-130325-Burak-AlphaFold2.pdf)


## 06 March 2025

**Presenter:** Burak Suyunu

**Date:** 6 March 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Highly accurate protein structure prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2) Part 1

**Citation:** Jumper, J., Evans, R., Pritzel, A. et al. Highly accurate protein structure prediction with AlphaFold. Nature 596, 583–589 (2021). https://doi.org/10.1038/s41586-021-03819-2

**Abstract:**

Proteins are essential to life, and understanding their structure can facilitate a mechanistic understanding of their function. Through an enormous experimental effort, the structures of around 100,000 unique proteins have been determined, but this represents a small fraction of the billions of known protein sequences. Structural coverage is bottlenecked by the months to years of painstaking effort required to determine a single protein structure. Accurate computational approaches are needed to address this gap and to enable large-scale structural bioinformatics. Predicting the three-dimensional structure that a protein will adopt based solely on its amino acid sequence—the structure prediction component of the ‘protein folding problem’—has been an important open research problem for more than 50 years. Despite recent progress, existing methods fall far short of atomic accuracy, especially when no homologous structure is available. Here we provide the first computational method that can regularly predict protein structures with atomic accuracy even in cases in which no similar structure is known. We validated an entirely redesigned version of our neural network-based model, AlphaFold, in the challenging 14th Critical Assessment of protein Structure Prediction (CASP14), demonstrating accuracy competitive with experimental structures in a majority of cases and greatly outperforming other methods. Underpinning the latest version of AlphaFold is a novel machine learning approach that incorporates physical and biological knowledge about protein structure, leveraging multi-sequence alignments, into the design of the deep learning algorithm.

**Extra Material:**

**Articles:**  
🔗 [AlphaFold 2 is here: What’s behind the structure prediction miracle?](https://www.blopig.com/blog/2021/07/alphafold-2-is-here-whats-behind-the-structure-prediction-miracle/)  
I’d say this is the first article to read after the main paper. It provides sufficient information about the model and offers insightful commentary.  

🔗 [From AlphaGo to AlphaFold, from games to science](https://www.ai4pharm.info/alphafold2)
Notion style, detailed, easy to understand explanations.

🔗 [Boris Burkov's Blog](https://borisburkov.net/2021-12-25-1/)  
This is the most detailed and explanatory article I’ve found on the model architecture. It covers supplementary material extensively and was the most helpful for understanding the model’s details.  

🔗 [The AlphaFold2 method paper: A fount of good ideas](https://moalquraishi.wordpress.com/2021/07/25/the-alphafold2-method-paper-a-fount-of-good-ideas/)  
This article highlights specific aspects of the model and provides valuable insights.  

**Videos:**  
▶️ [Nazim Bouatta | Machine learning for protein structure prediction, Part 2: AlphaFold2 architecture](https://www.youtube.com/watch?v=ri39B0Voujc)  
A great explanation of AF2. It does an excellent job of justifying why certain design choices were made, though it doesn’t go into the deepest architectural details. The best AF2 presentation I’ve seen.  

▶️ [Highly Accurate Protein Structure Prediction with AlphaFold | Simon Kohl](https://www.youtube.com/watch?v=tTN0MM2CQLU)  
A well-structured presentation that covers every part of the paper without diving into too much detail.

## 27 February 2025

**Presenter:** Gökçe Uludoğan

**Date:** 27 February 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [From Mechanistic Interpretability to Mechanistic Biology: Training, Evaluating, and Interpreting Sparse Autoencoders on Protein Language Models](https://www.biorxiv.org/content/10.1101/2025.02.06.636901v1)

**Citation:** Adams, E., Bai, L., Lee, M., Yu, Y., & AlQuraishi, M. (2025). From Mechanistic Interpretability to Mechanistic Biology: Training, Evaluating, and Interpreting Sparse Autoencoders on Protein Language Models. bioRxiv, 2025-02. 

**Abstract:**

Protein language models (pLMs) are powerful predictors of protein structure and function, learning through unsupervised training on millions of protein sequences. pLMs are thought to capture common motifs in protein sequences, but the specifics of pLM features are not well understood. Identifying these features would not only shed light on how pLMs work, but potentially uncover novel protein biology––studying the model to study the biology. Motivated by this, we train sparse autoencoders (SAEs) on the residual stream of a pLM, ESM-2. By characterizing SAE features, we determine that pLMs use a combination of generic features and family-specific features to represent a protein. In addition, we demonstrate how known sequence determinants of properties such as thermostability and subcellular localization can be identified by linear probing of SAE features. For predictive features without known functional associations, we hypothesize their role in unknown mechanisms and provide visualization tools to aid their interpretation. Our study gives a better understanding of the limitations of pLMs, and demonstrates how SAE features can be used to help generate hypotheses for biological mechanisms. We release our code, model weights and feature visualizer.


## 20 February 2025

**Presenter:** Özdeniz Dolu

**Date:** 20 February 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Prediction of virus-host associations using protein language models and multiple instance learning](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012597)

**Citation:** Liu, D., Young, F., Lamb, K. D., Robertson, D. L., & Yuan, K. (2024). Prediction of virus-host associations using protein language models and multiple instance learning. PLOS Computational Biology, 20(11), 1-25. 

**Material:** 
- [Slides](20-02-25_Ozdeniz_Slides_Predict_Virus-Host.pdf)
- [Paper](20-02-25_Ozdeniz_Paper_Predict_Virus-Host.pdf)

**Abstract:**

Predicting virus-host associations is essential to determine the specific host species that viruses interact with, and discover if new viruses infect humans and animals. Currently, the host of the majority of viruses is unknown, particularly in microbiomes. To address this challenge, we introduce EvoMIL, a deep learning method that predicts the host species for viruses from viral sequences only. It also identifies important viral proteins that significantly contribute to host prediction. The method combines a pre-trained large protein language model (ESM) and attention-based multiple instance learning to allow protein-orientated predictions. Our results show that protein embeddings capture stronger predictive signals than sequence composition features, including amino acids, physiochemical properties, and DNA k-mers. In multi-host prediction tasks, EvoMIL achieves median F1 score improvements of 10.8%, 16.2%, and 4.9% in prokaryotic hosts, and 1.7%, 6.6% and 11.5% in eukaryotic hosts. EvoMIL binary classifiers achieve impressive AUC over 0.95 for all prokaryotic hosts and range from roughly 0.8 to 0.9 for eukaryotic hosts. Furthermore, EvoMIL identifies important proteins in the prediction task, capturing key functions involved in virus-host specificity.

## 13 February 2025

**Presenter:** Özlem Şimşek

**Date:** 13 February 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [A comprehensive review and comparison of existing computational methods for protein function prediction](https://academic.oup.com/bib/article/25/4/bbae289/7696515)

**Citation:** Baohui Lin, Xiaoling Luo, Yumeng Liu, Xiaopeng Jin (2024). A comprehensive review and comparison of existing computational methods for protein function prediction. Briefings in Bioinformatics, Volume 25, Issue 4, July 2024.

**Abstract:**

Protein function prediction is critical for understanding the cellular physiological and biochemical processes, and it opens up new possibilities for advancements in fields such as disease research and drug discovery. During the past decades, with the exponential growth of protein sequence data, many computational methods for predicting protein function have been proposed. Therefore, a systematic review and comparison of these methods are necessary. In this study, we divide these methods into four different categories, including sequence-based methods, 3D structure-based methods, PPI network-based methods and hybrid information-based methods. Furthermore, their advantages and disadvantages are discussed, and then their performance is comprehensively evaluated and compared. Finally, we discuss the challenges and opportunities present in this field.


## 23 January 2025

**Presenter:** Arda Arslan

**Date:** 23 January 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Are genomic language models all you need? Exploring genomic language models on protein downstream tasks](https://academic.oup.com/bioinformatics/article/40/9/btae529/7745814)

**Citation:** Boshar, S., Trop, E., de Almeida, B. P., Copoiu, L., & Pierrot, T. (2024). Are genomic language models all you need? exploring genomic language models on protein downstream tasks. Bioinformatics, 40(9), btae529.


**Abstract:**

**Motivation:**
Large language models, trained on enormous corpora of biological sequences, are state-of-the-art for downstream genomic and proteomic tasks. Since the genome contains the information to encode all proteins, genomic language models (gLMs) hold the potential to make downstream predictions not only about DNA sequences, but also about proteins. However, the performance of gLMs on protein tasks remains unknown, due to few tasks pairing proteins with the coding DNA sequences (CDS) that can be processed by gLMs.

**Results:**
In this work, we curated five such datasets and used them to evaluate the performance of gLMs and proteomic language models (pLMs). We show that gLMs are competitive and even outperform their pLMs counterparts on some tasks. The best performance was achieved using the retrieved CDS compared to sampling strategies. We found that training a joint genomic-proteomic model outperforms each individual approach, showing that they capture different but complementary sequence representations, as we demonstrate through model interpretation of their embeddings. Lastly, we explored different genomic tokenization schemes to improve downstream protein performance. We trained a new Nucleotide Transformer (50M) foundation model with 3mer tokenization that outperforms its 6mer counterpart on protein tasks while maintaining performance on genomics tasks. The application of gLMs to proteomics offers the potential to leverage rich CDS data, and in the spirit of the central dogma, the possibility of a unified and synergistic approach to genomics and proteomics.

**Availability and implementation:**
We make our inference code, 3mer pre-trained model weights and datasets available.

## 16 January 2025

**Presenter:** Aslı Gök

**Date:** 16 January 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [DPFunc: accurately predicting protein function via deep learning with domain-guided structure information](https://www.nature.com/articles/s41467-024-54816-8)

**Citation:** Wang, W., Shuai, Y., Zeng, M., Fan, W., & Li, M. (2025). DPFunc: accurately predicting protein function via deep learning with domain-guided structure information. Nature Communications, 16(1), 70.

**Material:** 
- [Slides](Dpfunc_16_January_2025.pdf)
  
**Abstract:**

Computational methods for predicting protein function are of great significance in understanding biological mechanisms and treating complex diseases. However, existing computational approaches of protein function prediction lack interpretability, making it difficult to understand the relations between protein structures and functions. In this study, we propose a deep learning-based solution, named DPFunc, for accurate protein function prediction with domain-guided structure information. DPFunc can detect significant regions in protein structures and accurately predict corresponding functions under the guidance of domain information. It outperforms current state-of-the-art methods and achieves a significant improvement over existing structure-based methods. Detailed analyses demonstrate that the guidance of domain information contributes to DPFunc for protein function prediction, enabling our method to detect key residues or regions in protein structures, which are closely related to their functions. In summary, DPFunc serves as an effective tool for large-scale protein function prediction, which pushes the border of protein understanding in biological systems.


## 2 January 2025

**Presenter:** Gökçe Uludoğan

**Date:** 2 January 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Annotating protein functions via fusing multiple biological modalities](https://www.nature.com/articles/s42003-024-07411-y)

**Citation:** Ma, W., Bi, X., Jiang, H., Wei, Z., & Zhang, S. (2024). Annotating protein functions via fusing multiple biological modalities. Communications Biology, 7(1), 1705.
**Material:** 
- [Slides](MIF2GO_2_January_2025.pdf)

**Abstract:**

Understanding the function of proteins is of great significance for revealing disease pathogenesis and discovering new targets. Benefiting from the explosive growth of the protein universal, deep learning has been applied to accelerate the protein annotation cycle from different biological modalities. However, most existing deep learning-based methods not only fail to effectively fuse different biological modalities, resulting in low-quality protein representations, but also suffer from the convergence of suboptimal solution caused by sparse label representations. Aiming at the above issue, we propose a multiprocedural approach for fusing heterogeneous biological modalities and annotating protein functions, i.e., MIF2GO (Multimodal Information Fusion to infer Gene Ontology terms), which sequentially fuses up to six biological modalities ranging from different biological levels in three steps, thus leading to powerful protein representations. Evaluation results on seven benchmark datasets show that the proposed method not only considerably outperforms state-of-the-art performance, but also demonstrates great robustness and generalizability across species. Besides, we also present biological insights into the associations between those modalities and protein functions. This research provides a robust framework for integrating multimodal biological data, offering a scalable solution for protein function annotation, ultimately facilitating advancements in precision medicine and the discovery of novel therapeutic strategies.

