# Past Meetings

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

## 26 December 2024

**Presenter:** Burak Suyunu

**Date:** 26 December 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Exploring structural diversity across the protein universe with The Encyclopedia of Domains](https://www.science.org/doi/10.1126/science.adq4946)

**Citation:** Lau, A. M., Bordin, N., Kandathil, S. M., Sillitoe, I., Waman, V. P., Wells, J., Orengo, C. A., & Jones, D. T. (2024). Exploring structural diversity across the protein universe with The Encyclopedia of Domains. Science. https://doi.org/adq4946

**Material:** 
- [Slides](LifeLU_Reading-261224-Burak-The_Encyclopedia_of_Domains.pdf)

**Abstract:**

The AlphaFold Protein Structure Database (AFDB) contains more than 214 million predicted protein structures composed of domains, which are independently folding units found in multiple structural and functional contexts. Identifying domains can enable many functional and evolutionary analyses but has remained challenging because of the sheer scale of the data. Using deep learning methods, we have detected and classified every domain in the AFDB, producing The Encyclopedia of Domains. We detected nearly 365 million domains, over 100 million more than can be found by sequence methods, covering more than 1 million taxa. Reassuringly, 77% of the nonredundant domains are similar to known superfamilies, greatly expanding representation of their domain space. We uncovered more than 10,000 new structural interactions between superfamilies and thousands of new folds across the fold space continuum.


## 19 December 2024

**Presenter:** Özdeniz Dolu

**Date:** 19 December 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Probing the Embedding Space of Protein Foundation Models through Intrinsic Dimension Analysis](https://openreview.net/forum?id=r9OUQpwhVo)

**Citation:** Soojung Yang, Juno Nam, Tynan Perez, Jinyeop Song, Xiaochen Du, and Rafael Gomez-Bombarelli. "Probing the Embedding Space of Protein Foundation Models through Intrinsic Dimension Analysis." NeurIPS 2024 Workshop on AI for New Drug Modalities, 2024.

**Material:** 
- [Slides](19-12-24_Ozdeniz_Slides_Intrinsic_Dimension.pdf)
- [Paper](19-12-24_Ozdeniz_Paper_Intrinsic_Dimension.pdf)

**Abstract:**

Protein foundation models produce embeddings that are valuable for various downstream tasks, yet the structure and information content of these embeddings remain poorly understood, particularly in relation to diverse pre-training tasks and input modalities. We apply intrinsic dimension analysis to quantify the complexity of protein embeddings from several widely used models, including ESM-2, ESM-IF, ProstT5, and ProteinMPNN. We also employ intrinsic dimension correlation to measure the shared information between different embeddings. Our results reveal a universality in protein embeddings, with similar scales across models and strong correlations between protein and residue embeddings. We observe significant redundancy, with Id values much smaller than the original embedding dimensions. We also show that models capture both spatial and sequential long-range correlation, with correlation decay rate differing based on the input modalities and pre-training tasks. Lastly, we analyze mutant embeddings, revealing that mutations cluster effectively by site, and fine-tuning further reduces the Id to capture task-specific representations.

## 12 December 2024

**Presenter:** Mehmet Efe Akça

**Date:** 12 December 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Bacterial protein function prediction via multimodal deep learning](https://www.biorxiv.org/content/10.1101/2024.10.30.621035v1.full)

**Citation:** Muzio, G., Adamer, M., Fernandez, L., Borgwardt, K., & Avican, K. (2024). Bacterial protein function prediction via multimodal deep learning. bioRxiv, 2024-10.

**Abstract:**

Bacterial proteins are specialized with extensive functional diversity for survival in diverse and stressful environments. A significant portion of these proteins remains functionally uncharacterized, limiting our understanding of bacterial survival mechanisms. Hence, we developed Deep Expression STructure (DeepEST), a multimodal deep learning framework designed to accurately predict protein function in bacteria by assigning Gene Ontology (GO) terms. DeepEST comprises two modules: a multi-layer perceptron that takes gene expression and location as input features, and a protein structure-based predictor. Within DeepEST, we integrated these modules through a learnable weighted linear combination and introduced a novel masked loss function to fine-tune the structure-based predictor for bacterial species. We showed that DeepEST strongly outperforms existing protein function prediction methods relying solely on amino acid sequence or protein structure. Moreover, DeepEST predicts GO terms for unclassified hypothetical proteins across 25 human bacterial pathogens, facilitating the design of experimental setups for characterization studies.


## 5 December 2024

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


## 28 November 2024

**Presenter:** Gökçe Uludoğan

**Date:** 28 November 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [InterPLM: Discovering Interpretable Features in Protein Language Models via Sparse Autoencoders](https://www.biorxiv.org/content/10.1101/2024.11.14.623630v1)

**Citation:** Simon, E., & Zou, J. (2024). InterPLM: Discovering Interpretable Features in Protein Language Models via Sparse Autoencoders. bioRxiv, 2024-11.

**Material:** 
- [Slides](InterPLM_28_November_2024.pdf)

**Abstract:**

Protein language models (PLMs) have demonstrated remarkable success in protein modeling and design, yet their internal mechanisms for predicting structure and function remain poorly understood. Here we present a systematic approach to extract and analyze interpretable features from PLMs using sparse autoencoders (SAEs). By training SAEs on embeddings from the PLM ESM-2, we identify up to 2,548 human-interpretable latent features per layer that strongly correlate with up to 143 known biological concepts such as binding sites, structural motifs, and functional domains. In contrast, examining individual neurons in ESM-2 reveals up to 46 neurons per layer with clear conceptual alignment across 15 known concepts, suggesting that PLMs represent most concepts in superposition. Beyond capturing known annotations, we show that ESM-2 learns coherent concepts that do not map onto existing annotations and propose a pipeline using language models to automatically interpret novel latent features learned by the SAEs. As practical applications, we demonstrate how these latent features can fill in missing annotations in protein databases and enable targeted steering of protein sequence generation. Our results demonstrate that PLMs encode rich, interpretable representations of protein biology and we propose a systematic framework to extract and analyze these latent features. In the process, we recover both known biology and potentially new protein motifs. As community resources, we introduce InterPLM ([interPLM.ai](https://interPLM.ai)), an interactive visualization platform for exploring and analyzing learned PLM features, and release code for training and analysis at [github.com/ElanaPearl/interPLM](https://github.com/ElanaPearl/interPLM).


## 21 November 2024

**Presenter:** Burak Suyunu

**Date:** 21 November 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Fast and accurate protein structure search with Foldseek](https://www.nature.com/articles/s41587-023-01773-0)

**Citation:** Van Kempen, Michel, Stephanie S. Kim, Charlotte Tumescheit, Milot Mirdita, Jeongjae Lee, Cameron LM Gilchrist, Johannes Söding, and Martin Steinegger. "Fast and accurate protein structure search with Foldseek." Nature biotechnology 42, no. 2 (2024): 243-246, https://doi.org/10.1038/s41587-023-01773-0.

**Abstract:**

As structure prediction methods are generating millions of publicly available protein structures, searching these databases is becoming a bottleneck. Foldseek aligns the structure of a query protein against a database by describing tertiary amino acid interactions within proteins as sequences over a structural alphabet. Foldseek decreases computation times by four to five orders of magnitude with 86%, 88% and 133% of the sensitivities of Dali, TM-align and CE, respectively.

**Availability and implementation:** https://github.com/steineggerlab/foldseek and https://search.foldseek.com/


## 14 November 2024
**Presenter:** Özdeniz Dolu

**Date:** 14 November 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Coarse-graining protein structures into their dynamic communities with DCI, a dynamic community identifier](https://academic.oup.com/bioinformatics/article/38/10/2727/6550056)

**Citation:** Ambuj Kumar, Pranav M Khade, Karin S Dorman, Robert L Jernigan, Coarse-graining protein structures into their dynamic communities with DCI, a dynamic community identifier, Bioinformatics, Volume 38, Issue 10, May 2022, Pages 2727–2733, https://doi.org/10.1093/bioinformatics/btac159.

**Material:** 
- [Slides](14-11-24_Ozdeniz_Slides_Dynamic_Communities.pdf)
- [Paper](14-11-24_Ozdeniz_Paper_Dynamic_Communities.pdf)

**Abstract:**

A new dynamic community identifier (DCI) is presented that relies upon protein residue dynamic cross-correlations generated by Gaussian elastic network models to identify those residue clusters exhibiting motions within a protein. A number of examples of communities are shown for diverse proteins, including GPCRs. It is a tool that can immediately simplify and clarify the most essential functional moving parts of any given protein. Proteins usually can be subdivided into groups of residues that move as communities. These are usually densely packed local sub-structures, but in some cases can be physically distant residues identified to be within the same community. The set of these communities for each protein are the moving parts. The ways in which these are organized overall can aid in understanding many aspects of functional dynamics and allostery. DCI enables a more direct understanding of functions including enzyme activity, action across membranes and changes in the community structure from mutations or ligand binding.

**Availability and implementation:** Available as a package under PACKMAN: https://github.com/Pranavkhade/PACKMAN/blob/master/packman/apps/dci.py


## 7 November 2024
**Presenter:** Özlem Şimşek

**Date:** 7 November 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Combining protein sequences and structures with transformers and equivariant graph neural networks to predict protein function](https://academic.oup.com/bioinformatics/article/39/Supplement_1/i318/7210446?login=false)

**Citation:** Boadu, F., Cao, H., & Cheng, J. (2023). Combining protein sequences and structures with transformers and equivariant graph neural networks to predict protein function. Bioinformatics, 39, i318–i325.

**Abstract:**

Motivation: Millions of protein sequences have been generated by numerous genome and transcriptome sequencing projects. However,
experimentally determining the function of the proteins is still a time consuming, low-throughput, and expensive process, leading to a large
protein sequence-function gap. Therefore, it is important to develop computational methods to accurately predict protein function to fill the gap.
Even though many methods have been developed to use protein sequences as input to predict function, much fewer methods leverage protein
structures in protein function prediction because there was lack of accurate protein structures for most proteins until recently.

Results: We developed TransFun—a method using a transformer-based protein language model and 3D-equivariant graph neural networks to
distill information from both protein sequences and structures to predict protein function. It extracts feature embeddings from protein sequences
using a pre-trained protein language model (ESM) via transfer learning and combines them with 3D structures of proteins predicted by
AlphaFold2 through equivariant graph neural networks. Benchmarked on the CAFA3 test dataset and a new test dataset, TransFun outperforms
several state-of-the-art methods, indicating that the language model and 3D-equivariant graph neural networks are effective methods to leverage
protein sequences and structures to improve protein function prediction. Combining TransFun predictions and sequence similarity-based
predictions can further increase prediction accuracy.

**Availability and implementation:** The source code of TransFun is available at https://github.com/jianlin-cheng/TransFun


## 31 October 2024
**Presenter:** Burak Suyunu

**Date:** 31 October 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Clustering for Protein Representation Learning](https://openaccess.thecvf.com/content/CVPR2024/html/Quan_Clustering_for_Protein_Representation_Learning_CVPR_2024_paper.html)

**Citation:** Quan, Ruijie, Wenguan Wang, Fan Ma, Hehe Fan, and Yi Yang. "Clustering for protein representation learning." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 319-329. 2024.

**Material:** 
- [Slides](LifeLU_Reading-311024-Burak-Clustering_for_Protein_Representation_Learning.pdf)

**Abstract:**

Protein representation learning is a challenging task that aims to capture the structure and function of proteins from their amino acid sequences. Previous methods largely ignored the fact that not all amino acids are equally important for protein folding and activity. In this article we propose a neural clustering framework that can automatically discover the critical components of a protein by considering both its primary and tertiary structure information. Our framework treats a protein as a graph where each node represents an amino acid and each edge represents a spatial or sequential connection between amino acids. We then apply an iterative clustering strategy to group the nodes into clusters based on their 1D and 3D positions and assign scores to each cluster. We select the highest-scoring clusters and use their medoid nodes for the next iteration of clustering until we obtain a hierarchical and informative representation of the protein. We evaluate on four protein-related tasks: protein fold classification enzyme reaction classification gene ontology term prediction and enzyme commission number prediction. Experimental results demonstrate that our method achieves state-of-the-art performance.

**Availability and implementation:**

https://github.com/QUANRJ/ClusteringPRL


## 24 October 2024
**Presenter:** Gökçe Uludoğan

**Date:** 24 October 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [DeepGOZero: improving protein function prediction from sequence and zero-shot learning based on ontology axioms](https://academic.oup.com/bioinformatics/article/38/Supplement_1/i238/6617515)

**Citation:** Kulmanov, Maxat, and Robert Hoehndorf. "DeepGOZero: improving protein function prediction from sequence and zero-shot learning based on ontology axioms." Bioinformatics 38.Supplement_1 (2022): i238-i245.

**Material:** 
- [Slides](DeepGO-SE_24_October_2024.pdf)

**Abstract:**

Protein functions are often described using the Gene Ontology (GO) which is an ontology consisting of over 50 000 classes and a large set of formal axioms. Predicting the functions of proteins is one of the key challenges in computational biology and a variety of machine learning methods have been developed for this purpose. However, these methods usually require a significant amount of training data and cannot make predictions for GO classes that have only few or no experimental annotations.
We developed DeepGOZero, a machine learning model which improves predictions for functions with no or only a small number of annotations. To achieve this goal, we rely on a model-theoretic approach for learning ontology embeddings and combine it with neural networks for protein function prediction. DeepGOZero can exploit formal axioms in the GO to make zero-shot predictions, i.e., predict protein functions even if not a single protein in the training phase was associated with that function. Furthermore, the zero-shot prediction method employed by DeepGOZero is generic and can be applied whenever associations with ontology classes need to be predicted.

**Availability and implementation:**
http://github.com/bio-ontology-research-group/deepgozero


## 17 October 2024
**Presenter:** Özdeniz Dolu

**Date:** 17 October 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [ProteinMAE: masked autoencoder for protein surface self-supervised learning](https://academic.oup.com/bioinformatics/article/39/12/btad724/7455256)

**Citation:** Mingzhi Yuan, Ao Shen, Kexue Fu, Jiaming Guan, Yingfan Ma, Qin Qiao, Manning Wang, ProteinMAE: masked autoencoder for protein surface self-supervised learning, Bioinformatics, Volume 39, Issue 12, December 2023, btad724, https://doi.org/10.1093/bioinformatics/btad724

**Material:** 
- [Slides](<17-10-24_Ozdeniz_Slides_ProteinMAE.pdf>)
- [Paper](<17-10-24_Ozdeniz_Paper_ProteinMAE.pdf>)

**Abstract:**
The biological functions of proteins are determined by the chemical and geometric properties of their surfaces. Recently, with the booming progress of deep learning, a series of learning-based surface descriptors have been proposed and achieved inspirational performance in many tasks such as protein design, protein–protein interaction prediction, etc. However, they are still limited by the problem of label scarcity, since the labels are typically obtained through wet experiments. Inspired by the great success of self-supervised learning in natural language processing and computer vision, we introduce ProteinMAE, a self-supervised framework specifically designed for protein surface representation to mitigate label scarcity. Specifically, we propose an efficient network and utilize a large number of accessible unlabeled protein data to pretrain it by self-supervised learning. Then we use the pretrained weights as initialization and fine-tune the network on downstream tasks. To demonstrate the effectiveness of our method, we conduct experiments on three different downstream tasks including binding site identification in protein surface, ligand-binding protein pocket classification, and protein–protein interaction prediction. The extensive experiments show that our method not only successfully improves the network’s performance on all downstream tasks, but also achieves competitive performance with state-of-the-art methods. Moreover, our proposed network also exhibits significant advantages in terms of computational cost, which only requires less than a tenth of memory cost of previous methods.

**Availability and implementation**
https://github.com/phdymz/ProteinMAE


## 10 October 2024
**Presenter:** Özlem Şimşek

**Date:** 10 October 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [PANDA-3D: protein function prediction based on AlphaFold models](https://academic.oup.com/nargab/article/6/3/lqae094/7728018?login=false)

**Citation:** Zhao, C., Liu, T., & Wang, Z. (2024). PANDA-3D: protein function prediction based on AlphaFold models. NAR Genomics and Bioinformatics, 6.

**Abstract:**

Previous protein function predictors primarily make predictions from amino acid sequences instead of tertiary structures because of the limited
number of experimentally determined structures and the unsatisfying qualities of predicted structures. AlphaFold recently achieved promising
performances when predicting protein tertiary structures, and the AlphaFold protein structure database (AlphaFold DB) is fast-expanding. Therefore, we aimed to develop a deep-learning tool that is specifically trained with AlphaFold models and predict GO terms from AlphaFold models. We
developed an advanced learning architecture by combining geometric vector perceptron graph neural networks and variant transformer decoder
layers for multi-label classification. PANDA-3D predicts gene ontology (GO) terms from the predicted structures of AlphaFold and the embeddings
of amino acid sequences based on a large language model. Our method significantly outperformed a state-of-the-art deep-learning method that
was trained with experimentally determined tertiary structures, and either outperformed or was comparable with several other language-modelbased state-of-the-art methods with amino acid sequences as input. PANDA-3D is tailored to AlphaFold models, and the AlphaFold DB currently
contains over 200 million predicted protein structures (as of May 1st, 2023), making PANDA-3D a useful tool that can accurately annotate the
functions of a large number of proteins. PANDA-3D can be freely accessed as a web server from http://dna.cs.miami.edu/PANDA-3D/ and as a
repository from https://github.com/zwang-bioinformatics/PANDA-3D.


## 3 October 2024
**Presenter:** Burak Suyunu

**Paper:** [Chainsaw: protein domain segmentation with fully convolutional neural networks](https://academic.oup.com/bioinformatics/article/40/5/btae296/7667299)

**Citation:** Wells, J., Hawkins-Hooker, A., Bordin, N., Sillitoe, I., Paige, B., & Orengo, C. (2024). Chainsaw: protein domain segmentation with fully convolutional neural networks. Bioinformatics, 40(5), btae296.

**Material:** 
- [Slides](Chainsaw-Burak-03_October_2024.pdf)

**Abstract:**

Motivation: Protein domains are fundamental units of protein structure and play a pivotal role in understanding folding, function, evolution, and design. The advent of accurate structure prediction techniques has resulted in an influx of new structural data, making the partitioning of these structures into domains essential for inferring evolutionary relationships and functional classification.

Results: This article presents Chainsaw, a supervised learning approach to domain parsing that achieves accuracy that surpasses current state-of-the-art methods. Chainsaw uses a fully convolutional neural network which is trained to predict the probability that each pair of residues is in the same domain. Domain predictions are then derived from these pairwise predictions using an algorithm that searches for the most likely assignment of residues to domains given the set of pairwise co-membership probabilities. Chainsaw matches CATH domain annotations in 78% of protein domains versus 72% for the next closest method. When predicting on AlphaFold models, expert human evaluators were twice as likely to prefer Chainsaw’s predictions versus the next best method.

Availability and implementation: [github.com/JudeWells/Chainsaw](https://github.com/JudeWells/Chainsaw)


## 26 September 2024
**Presenter:** Gökçe Uludoğan

**Paper:** [Graph-theoretical prediction of biological modules in quaternary structures of large protein complexes](https://academic.oup.com/bioinformatics/article/40/3/btae112/7623586)

**Citation:** Gisdon, F. J., Zunker, M., Wolf, J. N., Prüfer, K., Ackermann, J., Welsch, C., & Koch, I. (2024). Graph-theoretical prediction of biological modules in quaternary structures of large protein complexes. Bioinformatics, 40(3), btae112.

**Material:** 
- [Slides](Graph-based-functional_model_detection_26_September_2024.pdf)

**Abstract:**

**Motivation:** The functional complexity of biochemical processes is strongly related to the interplay of proteins and their assembly into protein complexes. In recent years, the discovery and characterization of protein complexes have substantially progressed through **advances in cryo-electron microscopy, proteomics, and computational structure prediction. This development results in a strong need for computational approaches to analyse the data of large protein complexes for structural and functional characterization. Here, we aim to provide a suitable approach, which processes the growing number of large protein complexes, to obtain biologically meaningful information on the hierarchical organization of the structures of protein complexes.

**Results**: We modelled the quaternary structure of protein complexes as undirected, labelled graphs called complex graphs. In complex graphs, the vertices represent protein chains and the edges spatial chain–chain contacts. We hypothesized that clusters based on the complex graph correspond to functional biological modules. To compute the clusters, we applied the Leiden clustering algorithm. To evaluate our approach, we chose the human respiratory complex I, which has been extensively investigated and exhibits a known biological module structure experimentally validated. Additionally, we characterized a eukaryotic group II chaperonin TRiC/CCT and the head of the bacteriophage 
29. The analysis of the protein complexes correlated with experimental findings and indicated known functional, biological modules. Using our approach enables not only to predict functional biological modules in large protein complexes with characteristic features but also to investigate the flexibility of specific regions and coformational changes. The predicted modules can aid in the planning and analysis of experiments.


## 12 September 2024
**Presenter:** Gökçe Uludoğan

**Date:** 12 September 2024, 11:00 UTC+3 (Istanbul)

**Paper:** Predicting multiple conformations via sequence clustering and AlphaFold2

**Citation:** Wayment-Steele, H. K., Ojoawo, A., Otten, R., Apitz, J. M., Pitsawong, W., Hömberger, M., ... & Kern, D. (2024). Predicting multiple conformations via sequence clustering and AlphaFold2. Nature, 625(7996), 832-839.

**Material:** 
- [Slides](AF2-Cluster_12_September_2024.pdf)

**Abstract:**

AlphaFold2 has revolutionized structural biology by accurately predicting single protein structures. However, a protein's biological function often depends on multiple conformational substates, and disease-causing point mutations can alter the population of these substates. We show that clustering a multiple-sequence alignment by sequence similarity enables AlphaFold2 to sample alternative states of known metamorphic proteins with high confidence. Using this method, named AF-Cluster, we investigated the evolutionary distribution of predicted structures for the metamorphic protein KaiB5 and found that predictions of both conformations were distributed in clusters across the KaiB family. We used nuclear magnetic resonance spectroscopy to confirm an AF-Cluster prediction: a cyanobacteria KaiB variant is stabilized in the opposite state compared to the more widely studied variant. To test AF-Cluster's sensitivity to point mutations, we designed and experimentally verified a set of three mutations predicted to flip KaiB from Rhodobacter sphaeroides from the ground to the fold-switched state. Finally, screening for alternative states in protein families without known fold switching identified a putative alternative state for the oxidoreductase Mpt53 in Mycobacterium tuberculosis. Further development of such bioinformatic methods in tandem with experiments will likely have a significant impact on predicting protein energy landscapes, essential for illuminating biological function.
