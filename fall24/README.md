# Past Meetings

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
- [Slides](<17-10-24, Ozdeniz Dolu, ProteinMAE.pdf>)

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
