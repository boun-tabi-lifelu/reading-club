# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Özdeniz Dolu

**Date:** 20 February 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Prediction of virus-host associations using protein language models and multiple instance learning](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012597)

**Citation:** Liu, D., Young, F., Lamb, K. D., Robertson, D. L., & Yuan, K. (2024). Prediction of virus-host associations using protein language models and multiple instance learning. PLOS Computational Biology, 20(11), 1-25. 

**Abstract:**

Predicting virus-host associations is essential to determine the specific host species that viruses interact with, and discover if new viruses infect humans and animals. Currently, the host of the majority of viruses is unknown, particularly in microbiomes. To address this challenge, we introduce EvoMIL, a deep learning method that predicts the host species for viruses from viral sequences only. It also identifies important viral proteins that significantly contribute to host prediction. The method combines a pre-trained large protein language model (ESM) and attention-based multiple instance learning to allow protein-orientated predictions. Our results show that protein embeddings capture stronger predictive signals than sequence composition features, including amino acids, physiochemical properties, and DNA k-mers. In multi-host prediction tasks, EvoMIL achieves median F1 score improvements of 10.8%, 16.2%, and 4.9% in prokaryotic hosts, and 1.7%, 6.6% and 11.5% in eukaryotic hosts. EvoMIL binary classifiers achieve impressive AUC over 0.95 for all prokaryotic hosts and range from roughly 0.8 to 0.9 for eukaryotic hosts. Furthermore, EvoMIL identifies important proteins in the prediction task, capturing key functions involved in virus-host specificity.
