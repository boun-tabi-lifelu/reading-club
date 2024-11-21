# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Gökçe Uludoğan

**Date:** 28 November 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [InterPLM: Discovering Interpretable Features in Protein Language Models via Sparse Autoencoders](https://www.biorxiv.org/content/10.1101/2024.11.14.623630v1)

**Citation:** Simon, E., & Zou, J. (2024). InterPLM: Discovering Interpretable Features in Protein Language Models via Sparse Autoencoders. bioRxiv, 2024-11.

**Abstract:**

Protein language models (PLMs) have demonstrated remarkable success in protein modeling and design, yet their internal mechanisms for predicting structure and function remain poorly understood. Here we present a systematic approach to extract and analyze interpretable features from PLMs using sparse autoencoders (SAEs). By training SAEs on embeddings from the PLM ESM-2, we identify up to 2,548 human-interpretable latent features per layer that strongly correlate with up to 143 known biological concepts such as binding sites, structural motifs, and functional domains. In contrast, examining individual neurons in ESM-2 reveals up to 46 neurons per layer with clear conceptual alignment across 15 known concepts, suggesting that PLMs represent most concepts in superposition. Beyond capturing known annotations, we show that ESM-2 learns coherent concepts that do not map onto existing annotations and propose a pipeline using language models to automatically interpret novel latent features learned by the SAEs. As practical applications, we demonstrate how these latent features can fill in missing annotations in protein databases and enable targeted steering of protein sequence generation. Our results demonstrate that PLMs encode rich, interpretable representations of protein biology and we propose a systematic framework to extract and analyze these latent features. In the process, we recover both known biology and potentially new protein motifs. As community resources, we introduce InterPLM ([interPLM.ai](https://interPLM.ai)), an interactive visualization platform for exploring and analyzing learned PLM features, and release code for training and analysis at [github.com/ElanaPearl/interPLM](https://github.com/ElanaPearl/interPLM).

