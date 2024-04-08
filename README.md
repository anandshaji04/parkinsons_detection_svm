# Parkinson's Disease Detection using Support Vector Machine (SVM)

## Overview

This project aims to detect Parkinson's disease using machine learning techniques, specifically Support Vector Machine (SVM) classification. The dataset used for training and evaluation contains biomedical voice measurements from individuals, with the main goal being to discriminate healthy people from those with Parkinson's disease based on various voice features.

## Dataset

The dataset consists of biomedical voice measurements from 31 individuals, 23 with Parkinson's disease (PD). Each record in the dataset represents a voice sample with various acoustic features extracted. The target variable indicates the health status of the individual, with '0' representing healthy and '1' representing Parkinson's disease.

### Attribute Information:

- **name**: ASCII subject name and recording number
- **MDVP:Fo(Hz)**: Average vocal fundamental frequency
- **MDVP:Fhi(Hz)**: Maximum vocal fundamental frequency
- **MDVP:Flo(Hz)**: Minimum vocal fundamental frequency
- **MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP**: Measures of variation in fundamental frequency
- **MDVP:Shimmer, MDVP:Shimmer(dB), Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ, Shimmer:DDA**: Measures of variation in amplitude
- **NHR, HNR**: Measures of ratio of noise to tonal components in the voice
- **status**: Health status of the subject (1 for Parkinson's, 0 for healthy)
- **RPDE, D2**: Nonlinear dynamical complexity measures
- **DFA**: Signal fractal scaling exponent
- **spread1, spread2, PPE**: Nonlinear measures of fundamental frequency variation

## Requirements

To run this project, you need:

- Python (version >= 3.6)
- Required libraries: scikit-learn, numpy, pandas, matplotlib

## Usage

1. Open `Parkinsons_Disease_Detection_SVM.ipynb` in colab notebook.
2. Follow the instructions provided in the notebook to load and preprocess the dataset, train the SVM model, and evaluate its performance.
3. Experiment with different SVM kernels, hyperparameters, and feature engineering techniques to improve classification accuracy.

## Workflow

![workflow](https://github.com/anandshaji04/parkinsons_detection_svm/assets/95977186/fc06b519-ed77-49e3-bc93-2c0c725b2de2)


## Results

Provide details of the model's performance metrics such as accuracy score on the test set.
