# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Özlem Şimşek

**Date:** 20 March 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Fine-tuning protein language models boosts predictions across diverse tasks](https://www.nature.com/articles/s41467-024-51844-2)

**Citation:** Schmirler, R., Heinzinger, M., & Rost, B. (2024). Fine-tuning protein language models boosts predictions across diverse tasks. Nature Communications, 15, 2024

**Abstract:**

Prediction methods inputting embeddings from protein language models have reached or even surpassed state-of-the-art performance on many protein prediction tasks. In natural language processing fine-tuning large language models has become the de facto standard. In contrast, most protein language model-based protein predictions do not back-propagate to the language model. Here, we compare the fine-tuning of three state-of-the-art models (ESM2, ProtT5, Ankh) on eight different tasks. Two results stand out. Firstly, task-specific supervised fine-tuning almost always improves downstream predictions. Secondly, parameter-efficient fine-tuning can reach similar improvements consuming substantially fewer resources at up to 4.5-fold acceleration of training over fine-tuning full models. Our results suggest to always try fine-tuning, in particular for problems with small datasets, such as for fitness landscape predictions of a single protein. For ease of adaptability, we provide easy-to-use notebooks to fine-tune all models used during this work for per-protein (pooling) and per-residue prediction tasks.
