# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

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



## Old Meetings

**Presenter:** Burak Suyunu

**Date:** 3 October 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Chainsaw: protein domain segmentation with fully convolutional neural networks](https://academic.oup.com/bioinformatics/article/40/5/btae296/7667299)

**Citation:** Wells, J., Hawkins-Hooker, A., Bordin, N., Sillitoe, I., Paige, B., & Orengo, C. (2024). Chainsaw: protein domain segmentation with fully convolutional neural networks. Bioinformatics, 40(5), btae296.

**Abstract:**

Motivation: Protein domains are fundamental units of protein structure and play a pivotal role in understanding folding, function, evolution, and design. The advent of accurate structure prediction techniques has resulted in an influx of new structural data, making the partitioning of these structures into domains essential for inferring evolutionary relationships and functional classification.

Results: This article presents Chainsaw, a supervised learning approach to domain parsing that achieves accuracy that surpasses current state-of-the-art methods. Chainsaw uses a fully convolutional neural network which is trained to predict the probability that each pair of residues is in the same domain. Domain predictions are then derived from these pairwise predictions using an algorithm that searches for the most likely assignment of residues to domains given the set of pairwise co-membership probabilities. Chainsaw matches CATH domain annotations in 78% of protein domains versus 72% for the next closest method. When predicting on AlphaFold models, expert human evaluators were twice as likely to prefer Chainsaw’s predictions versus the next best method.

Availability and implementation: [github.com/JudeWells/Chainsaw](https://github.com/JudeWells/Chainsaw)
