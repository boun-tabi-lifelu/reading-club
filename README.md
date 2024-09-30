# LifeLU Reading Group

This repository contains announcements and materials for the LifeLU reading group, which presents works related to protein understanding.

## Next Meeting

**Presenter:** Burak Suyunu

**Date:** 3 October 2024, 10:00 UTC+3 (Istanbul)

**Paper:** [Chainsaw: protein domain segmentation with fully convolutional neural networks](https://academic.oup.com/bioinformatics/article/40/5/btae296/7667299)

**Citation:** Wells, J., Hawkins-Hooker, A., Bordin, N., Sillitoe, I., Paige, B., & Orengo, C. (2024). Chainsaw: protein domain segmentation with fully convolutional neural networks. Bioinformatics, 40(5), btae296.

**Abstract:**

Motivation: Protein domains are fundamental units of protein structure and play a pivotal role in understanding folding, function, evolution, and design. The advent of accurate structure prediction techniques has resulted in an influx of new structural data, making the partitioning of these structures into domains essential for inferring evolutionary relationships and functional classification.

Results: This article presents Chainsaw, a supervised learning approach to domain parsing that achieves accuracy that surpasses current state-of-the-art methods. Chainsaw uses a fully convolutional neural network which is trained to predict the probability that each pair of residues is in the same domain. Domain predictions are then derived from these pairwise predictions using an algorithm that searches for the most likely assignment of residues to domains given the set of pairwise co-membership probabilities. Chainsaw matches CATH domain annotations in 78% of protein domains versus 72% for the next closest method. When predicting on AlphaFold models, expert human evaluators were twice as likely to prefer Chainsaw’s predictions versus the next best method.

Availability and implementation: [github.com/JudeWells/Chainsaw](https://github.com/JudeWells/Chainsaw)