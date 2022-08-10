# Cation-Ordering-ML

This repository is associated with the study of cation ordering, as detailed in the manuscript, 
namely "Insights of cation ordering in double perovskites oxides from machine learning".

Publication:
A. Ghosh, G. Palanichamy, D. P. Trujillo, M. Shaikh, and S. Ghosh
Insights into Cation Ordering of Double Perovskite Oxides from Machine Learning and Causal Relations, Chem. Mater. 2022.
https://doi.org/10.1021/acs.chemmater.2c00217

Link to Datasets: https://doi.org/10.5281/zenodo.6570994

Manuscript link: https://arxiv.org/abs/2201.04970

Datasets utilized to construct all models as mentioned in the manuscript can be found under the folder 'Datasets' in this repository.
The naming conventions follow the same order as used in the paper.

Notebook shows:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aghosh92/Cation-Ordering-ML/blob/main/RandomForestClassifier.ipynb)

1. How Random Forest Classification models can be trained and tested on a DFT-based dataset followed by visualizing trees 
and downselecting important features.

2. Probabilistic confidence bound along with interactive plots can be utilized to test accuracies of models.

Notebook shows:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aghosh92/Cation-Ordering-ML/blob/main/CausalModel.ipynb)

How causal networks can be constructed using the important features to investigate structure-property relationships.

Notebook shows:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aghosh92/Cation-Ordering-ML/blob/main/SissoRegression.ipynb)

How SISSO approach can be implemented within a regression environment to find the best combination of non-linearized 
features with respect to the target using Matminer and Automatminer.
