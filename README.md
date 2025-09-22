# MachineLearningPhytoplanktonPaper
Analysis and figure scripts for the paper "Using Machine Learning to Predict Phytoplankton Blooms in the Salish Sea"

[![DOI](https://zenodo.org/badge/1050632297.svg)](https://doi.org/10.5281/zenodo.17180298)

## General Format
Scripts are organized based on the phytoplankton variable of interest. Each variable folder has 3 files inside, which refer to the data processing. The folder Figures contains all the figures displayed in the paper and the supporting information.

## Data Processing
Each variable folder has 3 files: The Analysis file includes the data cleaning, training, and evaluation of the proposed models for each variable. Additional plots from the training of the models are shown. The Feature Selection file includes the data processing performed in order to evaluate the impact of each input feature on the proposed models. The Bootstrap file includes bootstrap runs of 100 repetitions, which were used for hyper-tuning and selecting the proper set of input features for each model.
