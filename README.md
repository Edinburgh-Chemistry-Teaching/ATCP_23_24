# Advanced Topics in Chemical Physics: Introduction to Machine Learning 

This repository contains three lectures and three workshop sessions on introducing machine learning concepts in the advanced physical chemistry module at UoE. 

## Author
Dr Antonia Mey -- antonia.mey@ed.ac.uk.  
Jasmin Güven

## Workshop Notebooks

| Units                | Materials |
|-----------|-------------------------|
|**Unit_01: Clustering and Dimensionality Reduction Reduction**||
|First noteboook: Clustering|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP_23_24/blob/main/Unit_01/01_clustering.ipynb) |
| Second notebook: Dimensionality reduction|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP_23_24/blob/main/Unit_01/02_dimensionality_reduction.ipynb) |
| Third notebook: Application|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP_23_24/blob/main/Unit_01/03_application.ipynb) |
|**Unit_02: Regression and Classification**| |
||Cancelled due to strike|
|**Unit_03:  Deep Learning for Solubility Classification**||
|First noteboook: Intro to Pytorch|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP_23_24/blob/main/Unit_03/01_Intro_to_pytorch.ipynb) |
| Second notebook: Solubility classification|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ATCP_23_24/blob/main/Unit_03/02_Solubility_classification.ipynb |

## Local installation

1. Install [anaconda](https://www.anaconda.com/products/distribution).
2. Create a new environment:

   `conda create -n ml_chem`
   
3. Activate the environment:

   `conda activate ml_chem`
   
4. Install [mamba](https://anaconda.org/conda-forge/mamba) to make the installation of packages faster.

   `conda install -c conda-forge mamba`
   
5. Install all the required packages with mamba:

   `mamba install -c conda-forge scikit-learn matplotlib pandas`

For Unit_03 you will also need to install

`mamba install -c conda-forge rdkit seaborn`

and

` mamba install pytorch torchvision torchinfo -c pytorch`

## Project

Release: week 4
Report Deadline: TBC  
Weight: 20%

## Summary of Lectures
### Lecture 1:
- What is machine learning?
- Examples of machine learning (in Chemistry)
- Introduction to unsupervised learning:
   - Clustering (k-means and others)
   - How does actual input data look like?
- Molecular fingerprints and nomenclature
- Unsupervised learning continued:
   - Dimensionality reduction (PCA)
   - Dimensionality reduction (tICA)
   - t-SNE

### Lecture 2:
- Optimization
- Regressions
- Classification
- Classifications in practice:
   - Random Forests
   - Support vector machine

### Lecture 3:

- Shallow Learning 
- Deep Learning
   - Multilayer perceptron 
   - GCN, Transformers 

## Learning Outcomes
- Understand the main pillars of machine learning
- Know about different clustering techniques as part of unsupervised learning
- Be able to use common nomenclature used in machine learning
- Use Principle component analysis to reduce the dimensions of a data set
- Understand how a regression problem can be cast as a machine learning problem 
- Be aware of how random forests and multilayer perceptrons can be used in a classification problem



## Additional Resources
A handout with additional resources can be found [here.](https://github.com/meyresearch/ML_for_chemistry/blob/main/Handout.pdf)
