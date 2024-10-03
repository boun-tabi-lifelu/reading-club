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
