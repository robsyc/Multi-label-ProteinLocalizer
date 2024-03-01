# Multi-label-ProteinLocalizer
ML project on fluorescentrly stained microscopic images of cells and tissues.

Based upon [this Kaggle competition](https://www.kaggle.com/competitions/jovian-pytorch-z2g/overview)

Some interesting notes and strategies
- Pre-trained ImageNet models are the best...
- Class-imbalances can be addressed through a cost re-weighting strategy during training
- Esembling has marginal effect on overall performance but dramatically improves model confidence (assessed through uncertainty estimation)
