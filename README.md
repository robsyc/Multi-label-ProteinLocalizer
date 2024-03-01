# Multi-label-ProteinLocalizer
ML project on fluorescentrly stained microscopic images of cells and tissues. `data` and `predictions` folders should be added to run this notebook. These data can be downloaded from the [orginal Kaggle competition site](https://www.kaggle.com/competitions/jovian-pytorch-z2g/overview)

Some interesting notes and strategies
- Pre-trained ImageNet models are the best...
- Applying [progressive learning](https://arxiv.org/abs/2104.00298) dramatically improves training time
- Class-imbalances can be addressed through a cost re-weighting strategy **during** training
- Esembling has marginal effect on overall performance but dramatically improves model confidence (assessed through uncertainty estimation)
