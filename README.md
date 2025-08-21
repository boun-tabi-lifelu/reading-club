# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting
**Presenter:** Özlem Şimşek

**Date:** 28 August 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Prot2Chat: protein large language model with early fusion of text, sequence, and structure](https://academic.oup.com/bioinformatics/article/41/8/btaf396/8215464)

**Citation:** 
Zhicong Wang, Zicheng Ma, Ziqiang Cao, Changlong Zhou, Jun Zhang, Yi Qin Gao, Prot2Chat: protein large language model with early fusion of text, sequence, and structure, Bioinformatics, Volume 41, Issue 8, August 2025, btaf396, https://doi.org/10.1093/bioinformatics/btaf396

**Abstract:**

Motivation: Proteins are of great significance in living organisms. However, understanding their functions encounters numerous challenges, such as insufficient integration of multimodal information, a large number of training parameters, limited flexibility of classification-based methods, and the lack of systematic evaluation metrics for protein question answering systems. To tackle these issues, we propose the Prot2Chat framework.

Results: We modified ProteinMPNN to encode protein sequence and structural information in a unified way. We used a large language model (LLM) to encode questions into vectors and developed a protein-text adapter to compress protein information into virtual tokens based on these vectors, achieving the early fusion of text and protein information. Finally, the same LLM reads the virtual tokens and the questions to generate answers. To optimize training efficiency, we froze the encoder and employed low-rank adaptation (LoRA) techniques for the LLM. Experiments on two datasets show that both automated metrics and expert evaluations demonstrate the superior performance of our model, and zero-shot prediction results highlight its generalization ability. We have developed an easy-to-use web interactive platform and a rapid installation option, allowing users to swiftly engage with Prot2Chat.

Availability and implementation: The models and codes are available at https://github.com/wangzc1233/Prot2Chat.
