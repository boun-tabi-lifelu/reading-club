# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Özdeniz Dolu

**Date:** 17 October 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [ProteinMAE: masked autoencoder for protein surface self-supervised learning](https://academic.oup.com/bioinformatics/article/39/12/btad724/7455256)

**Citation:** Mingzhi Yuan, Ao Shen, Kexue Fu, Jiaming Guan, Yingfan Ma, Qin Qiao, Manning Wang, ProteinMAE: masked autoencoder for protein surface self-supervised learning, Bioinformatics, Volume 39, Issue 12, December 2023, btad724, https://doi.org/10.1093/bioinformatics/btad724

**Abstract:**
The biological functions of proteins are determined by the chemical and geometric properties of their surfaces. Recently, with the booming progress of deep learning, a series of learning-based surface descriptors have been proposed and achieved inspirational performance in many tasks such as protein design, protein–protein interaction prediction, etc. However, they are still limited by the problem of label scarcity, since the labels are typically obtained through wet experiments. Inspired by the great success of self-supervised learning in natural language processing and computer vision, we introduce ProteinMAE, a self-supervised framework specifically designed for protein surface representation to mitigate label scarcity. Specifically, we propose an efficient network and utilize a large number of accessible unlabeled protein data to pretrain it by self-supervised learning. Then we use the pretrained weights as initialization and fine-tune the network on downstream tasks. To demonstrate the effectiveness of our method, we conduct experiments on three different downstream tasks including binding site identification in protein surface, ligand-binding protein pocket classification, and protein–protein interaction prediction. The extensive experiments show that our method not only successfully improves the network’s performance on all downstream tasks, but also achieves competitive performance with state-of-the-art methods. Moreover, our proposed network also exhibits significant advantages in terms of computational cost, which only requires less than a tenth of memory cost of previous methods.

**Availability and implementation**
https://github.com/phdymz/ProteinMAE
