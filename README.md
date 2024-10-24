# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Burak Suyunu

**Date:** 31 October 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Clustering for Protein Representation Learning](https://openaccess.thecvf.com/content/CVPR2024/html/Quan_Clustering_for_Protein_Representation_Learning_CVPR_2024_paper.html)

**Citation:** Quan, Ruijie, Wenguan Wang, Fan Ma, Hehe Fan, and Yi Yang. "Clustering for protein representation learning." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 319-329. 2024.

**Abstract:**

Protein representation learning is a challenging task that aims to capture the structure and function of proteins from their amino acid sequences. Previous methods largely ignored the fact that not all amino acids are equally important for protein folding and activity. In this article we propose a neural clustering framework that can automatically discover the critical components of a protein by considering both its primary and tertiary structure information. Our framework treats a protein as a graph where each node represents an amino acid and each edge represents a spatial or sequential connection between amino acids. We then apply an iterative clustering strategy to group the nodes into clusters based on their 1D and 3D positions and assign scores to each cluster. We select the highest-scoring clusters and use their medoid nodes for the next iteration of clustering until we obtain a hierarchical and informative representation of the protein. We evaluate on four protein-related tasks: protein fold classification enzyme reaction classification gene ontology term prediction and enzyme commission number prediction. Experimental results demonstrate that our method achieves state-of-the-art performance.

**Availability and implementation:**

https://github.com/QUANRJ/ClusteringPRL

