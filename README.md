# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Amirreza (Emir Rıza) Sattarzadeh

**Date:** 25 September 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [ProLLaMA: A Protein Large Language Model for
Multi-Task Protein Language Processing](https://doi.org/10.1109/TAI.2025.3564914)

**Citation:** L. Lv et al., "ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing," in IEEE Transactions on Artificial Intelligence, doi: 10.1109/TAI.2025.3564914.
keywords: {Proteins;Training;Annotations;Protein engineering;Biology;Natural language processing;Decoding;Tuning;Multitasking;Biological system modeling;Biotechnology;Large language models;Protein engineering},

**Abstract:**

Recent advances in Protein Language Models (PLMs) have transformed protein engineering, yet unlike their counterparts in Natural Language Processing (NLP), current PLMs exhibit a fundamental limitation: they excel in either Protein Language Understanding (PLU) or Protein Language Generation (PLG), but rarely both. This fragmentation hinders progress in protein engineering. To bridge this gap, we introduce ProLLaMA, a multitask protein language model enhanced by the Evolutionary Protein Generation Framework (EPGF). We construct a comprehensive instruction dataset containing approximately 13 million samples with over 11,000 superfamily annotations to facilitate better modeling of sequence-function landscapes. We leverage a two-stage training approach to develop ProLLaMA, a multitask LLM with protein domain expertise. Our EPGF addresses the mismatch between statistic language modeling and biological constraints through three innovations: a multi-dimensional interpretable scorer, hierarchical efficient decoding, and a probabilistic-biophysical joint selection mechanism. Extensive experiments demonstrate that ProLLaMA excels in both unconditional and controllable protein generation tasks, achieving superior structural quality metrics compared to existing PLMs. Additionally, ProLLaMA demonstrates strong understanding capabilities with a 67.1% exact match rate in superfamily prediction. EPGF significantly enhances the biological viability of generated sequences, as evidenced by improved biophysical scores (+4.3%) and structural metrics (+14.5%).
