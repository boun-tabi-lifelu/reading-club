# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Gökçe Uludoğan

**Date:** 24 October 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [DeepGOZero: improving protein function prediction from sequence and zero-shot learning based on ontology axioms](https://academic.oup.com/bioinformatics/article/38/Supplement_1/i238/6617515)

**Citation:** Kulmanov, Maxat, and Robert Hoehndorf. "DeepGOZero: improving protein function prediction from sequence and zero-shot learning based on ontology axioms." Bioinformatics 38.Supplement_1 (2022): i238-i245.

**Abstract:**

Protein functions are often described using the Gene Ontology (GO) which is an ontology consisting of over 50 000 classes and a large set of formal axioms. Predicting the functions of proteins is one of the key challenges in computational biology and a variety of machine learning methods have been developed for this purpose. However, these methods usually require a significant amount of training data and cannot make predictions for GO classes that have only few or no experimental annotations.
We developed DeepGOZero, a machine learning model which improves predictions for functions with no or only a small number of annotations. To achieve this goal, we rely on a model-theoretic approach for learning ontology embeddings and combine it with neural networks for protein function prediction. DeepGOZero can exploit formal axioms in the GO to make zero-shot predictions, i.e., predict protein functions even if not a single protein in the training phase was associated with that function. Furthermore, the zero-shot prediction method employed by DeepGOZero is generic and can be applied whenever associations with ontology classes need to be predicted.

**Availability and implementation:**

http://github.com/bio-ontology-research-group/deepgozero

