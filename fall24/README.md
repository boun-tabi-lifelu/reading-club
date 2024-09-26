# Past Meetings




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
