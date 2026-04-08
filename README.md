# OS and DFS prediction after CRC surgery in the MSK-CHORD dataset

## Overview

This repository contains the code used for the analyses presented in the manuscript:

"Routine Clinical Data Enables Robust Risk Stratification of Disease-Free Survival in Stage I–III Colorectal Cancer"
Quarles van Ufford, P., Fan, B., Olsen, L.R., Gögenur, I., Krauthammer, M., & Lund, O.
2026

The goal of this repository is to enable reproducibility of the analyses and allow other researchers to apply or extend the methods used in the study.

The repository includes code for:
- Data preprocessing
- Model training
- Model evaluation and post-hoc analyses
- Generation of figures and tables used in the manuscript

## Requirements
Software:
- R >= 4.3

Packages used in this repository:
- tidyverse
- rsample
- janitor
- fastDummies
- survival
- caret
- survminer
- glmnet
- pROC
- randomForestSRC
- ggpubr
- patchwork

## Data Availability

To reproduce the results, first download the MSK CHORD dataset from [cBioPortal](https://www.cbioportal.org/study/summary?id=msk_chord_2024 "cBioPortal: MSK-CHORD") and place it in data/_raw/

## Reproducing the Analysis

The analyses can be reproduced by running each of the scripts in order. All outputs will be saved in results/

## Methods Implemented

This repository includes implementations or applications of the following methods
- Univariate Cox proportional hazards models
- Multivariate Cox proportional hazards models
- LASSO and Elastic Net Regularization
- Stepwise forward feature selection
- Random Survival Forest

## Contact

For questions or issues related to this repository, please contact:

Puck Quarles van Ufford
Technical University of Denmark
puqu@dtu.dk
