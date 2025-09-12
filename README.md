# Project Description

This project is an extension on the [MSK-CHORD paper by Jee *et al*. (2024)](https://doi.org/10.1038/s41586-024-08167-5 "Automated real-world data integration improves cancer outcome prediction"). The authors developed the Memorial Sloan Kettering clinicogenomic, harmonized oncologic real-world dataset (MSK-CHORD), which is a collection of clinicogenomic data and structured real-world data (RWD), captured from unstructured medical text using natural language processing (NLP). The dataset includes data from non-small-cell lung (n = 7,809), breast (n = 5,368), colorectal (n = 5,543), prostate (n = 3,211) and pancreatic (n = 3,109) cancers. In their paper, the authors demonstrated the usefulness of RWD by showing how random forest (RF) models perform at predicting overall survival (OS). The models that included NLP-derived features outperformed those based on genomic data alone.

In this project, I am aiming to extend this project. I will be focusing on predicting progression-free survival (PFS) after colorectal cancer surgery. I will assess different models and combinations of features to find the optimal prediction model. Models to be tested include RF.

The reason to focus on PFS is that it has more clinical utility than OS.

# Data

The full MSK-CHORD dataset was downloaded from [cBioPortal](https://www.cbioportal.org/study/summary?id=msk_chord_2024 "cBioPortal: MSK-CHORD") on the 10th of June, 2025.
