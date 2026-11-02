# CL-HSA-ResCNN: A Hyperbolic Attention Residual CNN for Multi-Stage Alzheimer's Disease Classification

## Overview

This repository provides the implementation framework for **CL-HSA-ResCNN**, a deep learning approach designed for multi-stage Alzheimer's disease classification using structural brain MRI data.

The proposed framework integrates a Residual Convolutional Neural Network (ResCNN) with Hyperbolic Self-Attention to capture complex hierarchical relationships in brain imaging features. Chef-Leader Optimization (CLO) is incorporated into the optimization framework to support hyperparameter selection and improve model performance.

## Key Components

- **Residual CNN:** Extracts discriminative spatial features from MRI volumes.
- **Hyperbolic Self-Attention:** Models hierarchical relationships in learned feature representations using hyperbolic geometry.
- **Chef-Leader Optimization:** Supports hyperparameter optimization.
- **Data Preprocessing:** Provides utilities for MRI preparation and normalization.
- **Model Training:** Supports subject-wise five-fold cross-validation and early stopping.
- **Performance Evaluation:** Includes accuracy, precision, recall, F1-score, confusion matrices, and statistical analysis.
- **Visualization:** Provides scripts for generating performance curves and evaluation plots.

## Datasets

The framework is designed for evaluation using three publicly managed research datasets:

1. Alzheimer's Disease Neuroimaging Initiative (ADNI)
2. Open Access Series of Imaging Studies (OASIS-3)
3. Australian Imaging, Biomarkers and Lifestyle (AIBL)

Access to these datasets must be obtained directly from their respective providers. MRI scans are not redistributed in this repository.

## Reported Performance

The manuscript reports the following classification accuracies:

| Dataset | Reported Accuracy |
|---|---:|
| ADNI | 95.8% |
| OASIS-3 | 93.2% |
| AIBL | 92.6% |

These values are manuscript-reported results and should not be interpreted as independently reproduced results from the supplied code.

## Reproducibility

The repository contains model implementation files, configuration settings, data preparation utilities, training and evaluation scripts, and a Jupyter Notebook demonstrating the main training workflow.

**Note:** The exact original Chef-Leader Optimization update equations are not fully specified in the manuscript. The provided CLO implementation is therefore an approximation and should be validated against the original experimental implementation before claiming exact reproduction.

## Intended Use

This repository is intended for academic research, experimentation, and further development of deep learning methods for Alzheimer's disease classification.

## Citation

If you use this implementation in your research, please cite the associated publication:

**CL-HSA-ResCNN: A Hyperbolic Attention Residual CNN for Multi-Stage Alzheimer's Disease Classification.**

## License

See the LICENSE file for the applicable terms of use.
