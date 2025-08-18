# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting
**Presenter:** Burak Suyunu

**Date:** 21 August 2025, 10:00 UTC+3 (Istanbul)

**Paper:** [Protein Structure Tokenization: Benchmarking and New Recipe](https://arxiv.org/abs/2503.00089)

**Citation:** 
Yuan, X., Wang, Z., Collins, M., & Rangwala, H. (2025). Protein structure tokenization: Benchmarking and new recipe. arXiv preprint arXiv:2503.00089.

**Abstract:**

Recent years have witnessed a surge in the development of protein structural tokenization methods, which chunk protein 3D structures into discrete or continuous representations. Structure tokenization enables the direct application of powerful techniques like language modeling for protein structures, and large multimodal models to integrate structures with protein sequences and functional texts. Despite the progress, the capabilities and limitations of these methods remain poorly understood due to the lack of a unified evaluation framework. We first introduce StructTokenBench, a framework that comprehensively evaluates the quality and efficiency of structure tokenizers, focusing on fine-grained local substructures rather than global structures, as typical in existing benchmarks. Our evaluations reveal that no single model dominates all benchmarking perspectives. Observations of codebook under-utilization led us to develop AminoAseed, a simple yet effective strategy that enhances codebook gradient updates and optimally balances codebook size and dimension for improved tokenizer utilization and quality. Compared to the leading model ESM3, our method achieves an average of 6.31% performance improvement across 24 supervised tasks, with sensitivity and utilization rates increased by 12.83% and 124.03%, respectively. Source code and model weights are available at https://github.com/KatarinaYuan/StructTokenBench.

