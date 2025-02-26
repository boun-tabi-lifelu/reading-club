# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Gökçe Uludoğan

**Date:** 27 February 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [From Mechanistic Interpretability to Mechanistic Biology: Training, Evaluating, and Interpreting Sparse Autoencoders on Protein Language Models](https://www.biorxiv.org/content/10.1101/2025.02.06.636901v1)

**Citation:** Adams, E., Bai, L., Lee, M., Yu, Y., & AlQuraishi, M. (2025). From Mechanistic Interpretability to Mechanistic Biology: Training, Evaluating, and Interpreting Sparse Autoencoders on Protein Language Models. bioRxiv, 2025-02. 

**Abstract:**

Protein language models (pLMs) are powerful predictors of protein structure and function, learning through unsupervised training on millions of protein sequences. pLMs are thought to capture common motifs in protein sequences, but the specifics of pLM features are not well understood. Identifying these features would not only shed light on how pLMs work, but potentially uncover novel protein biology––studying the model to study the biology. Motivated by this, we train sparse autoencoders (SAEs) on the residual stream of a pLM, ESM-2. By characterizing SAE features, we determine that pLMs use a combination of generic features and family-specific features to represent a protein. In addition, we demonstrate how known sequence determinants of properties such as thermostability and subcellular localization can be identified by linear probing of SAE features. For predictive features without known functional associations, we hypothesize their role in unknown mechanisms and provide visualization tools to aid their interpretation. Our study gives a better understanding of the limitations of pLMs, and demonstrates how SAE features can be used to help generate hypotheses for biological mechanisms. We release our code, model weights and feature visualizer.1

