# EEG Classification Model

## Project Overview

This project classifies EEG signals into seizure and non-seizure categories using machine learning algorithms. The dataset is sourced from Bonn University's Epileptology department, including EEG recordings from 500 individuals. This work aids in diagnosing disorders like epilepsy.

## Table of Contents

- [Project Overview](#project-overview)
- [What is Epilepsy?](#what-is-epilepsy)
- [What is EEG?](#what-is-eeg)
- [Data Pre-processing and Feature Extraction](#data-pre-processing-and-feature-extraction)
- [Model Architecture and Training Details](#model-architecture-and-training-details)
- [Conclusion and Future Work](#conclusion-and-future-work)
- [Installation](#installation)

## What is Epilepsy?

Epilepsy is a chronic disorder of the central nervous system characterized by recurrent seizures. It affects millions worldwide and can be triggered by factors such as head trauma, infections, or genetic predisposition.

## What is EEG?

EEG, or electroencephalogram, is a non-invasive technique that measures electrical activity in the brain. It is widely used for diagnosing neurological disorders and studying brain dynamics.

## Data Pre-processing and Feature Extraction

The dataset includes five sets (Z, O, N, F, S) representing different conditions. Key steps include:

- **Checking for Missing Values**: Ensured data completeness.
- **Noise Reduction**: Applied bandpass filters.
- **Normalization**: Standardized data for consistency.
- **Data Augmentation**: Added noise to enhance model robustness.
- **Feature Extraction**: Extracted time-domain and frequency-domain features.

## Model Architecture and Training Details

Several models were employed:

1. **Logistic Regression**: Achieved 79% accuracy.
2. **Random Forest**: Achieved 96% accuracy.
3. **Decision Tree**: Achieved 88% accuracy.
4. **Support Vector Machine (SVM)**: Achieved 80% accuracy.
5. **Neural Network**: Achieved 91% accuracy.

## Conclusion and Future Work

The Random Forest model showed the best performance with an accuracy of 96%. Future work includes exploring advanced neural network architectures like RNNs or CNNs and improving feature engineering techniques.

## Installation

Clone the repository:

```bash
git clone https://github.com/dheeraj932/EEG-Classification.git
cd EEG-Classification
