# Past Meetings

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
