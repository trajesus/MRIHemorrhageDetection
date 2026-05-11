# MRIHaemorrhageDetection

> Automated detection and segmentation of cerebral haemorrhages in T2* MRI using MONAI + PyTorch

## 🎯 Key Results
- Achieved 0.66 Dice score on micro-haemorrhage segmentation and 0.77 for macro-haemorrhages
- Addressed severe class imbalance via custom slice oversampling

## 🏗️ Architecture
- Framework: MONAI (UNet, DiceLoss, Compose transforms)
- Input: T2* MRI NIfTI volumes → 2D slice pipeline (256×256)
- Models: [./micro](micro)/ (micro-haemorrhages) | [./macro](macro)/ (macro-haemorrhages)

The code presented in this repo was submitted for a conference.\
[![DOI:<10.1007/978-3-031-45642-8_35>](https://img.shields.io/badge/DOI-10.1007/978--3--031--45642--8__35-blue)](https://doi.org/10.1007/978-3-031-45642-8_35)


Work developed by:
- Tiago Jesus
- Claudia Palma
- Tiago Gil Oliveira
- Victor Alves

# If you find our work useful, please consider to **⭐️ star and 📝cite this repository and our paper**.

``` bibtex
@misc{TiagoJesus_Haemorrhage_detection,
  author = {Tiago Jesus},
  title = {MRIHaemorrhageDetection},
  year = {2022},
  publisher = {GitHub},
  url = {https://github.com/trajesus/MRIHemorrhageDetection},
}
```

``` bibtex
@InProceedings{10.1007/978-3-031-45642-8_35,
author="Jesus, Tiago
and Palma, Cl{\'a}udia
and Oliveira, Tiago Gil
and Alves, Victor",
title="Automatic Hemorrhage Detection in Magnetic Resonance Imaging in Cerebral Amyloid Angiopathy",
booktitle="Information Systems and Technologies",
year="2024",
publisher="Springer Nature Switzerland",
pages="347--356",
isbn="978-3-031-45642-8"
}
```
