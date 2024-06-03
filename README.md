# Physiological Signal Classification Using LSTM Networks

This repository contains MATLAB code designed to analyze and classify physiological signals using Long Short-Term Memory (LSTM) networks. These signals include oral-nasal pressure and thoracic impedance obtained from real data in various young and elderly subjects. Access to these specific data sets is restricted.

## Objectives

The aim of these codes is to leverage LSTM networks to differentiate and classify different physiological states and conditions based on the signals. Specifically, the objectives are:

1. **Young vs. Elderly Classification**:
   - **File**: `elderly_young.mlx`
   - **Objective**: To classify signals to determine if there is a distinguishable difference between young and elderly subjects.
   
2. **Recovery vs. Rest in Young Subjects**:
   - **File**: `recovery_restpostrecovery.mlx`
   - **Objective**: To differentiate between the recovery phase (after physical activity) and the rest phase in the same signal from young subjects.
   
3. **Post-Recovery Rest vs. Total Rest**:
   - **File**: `restposrecovery_totalrest.mlx`
   - **Objective**: To see if there are differences between the rest phase after recovery (signal 1) and signals taken during total rest (signal 2).

## Description of Files

1. **elderly_young.mlx**:
   - **Description**: This code processes oral-nasal pressure or thoracic impedance signals to classify whether the subject is young or elderly. It includes data loading, preprocessing, and LSTM network training and evaluation.
   
2. **recovery_restpostrecovery.mlx**:
   - **Description**: This code focuses on young subjects and processes signals to differentiate between the recovery phase (immediately after physical activity) and the rest phase following the recovery.
   
3. **restposrecovery_totalrest.mlx**:
   - **Description**: This code compares the rest phase following recovery with signals taken during total rest. It aims to identify any significant differences between these two states.

## Data Access

The data used in these analyses are proprietary and restricted. They include detailed physiological measurements from various young and elderly subjects. Access to these data sets is limited to authorized personnel only.

## Methodology

1. **Data Loading and Preprocessing**:
   - Each code begins by loading the specific data set and performing necessary preprocessing steps, such as segmentation and normalization.

2. **Feature Extraction**:
   - Spectrograms, instantaneous frequency, and spectral entropy are extracted from the signals to enhance the feature set used for training the LSTM networks.

3. **LSTM Network Training**:
   - The preprocessed signals and extracted features are used to train LSTM networks. Training parameters are tuned to optimize classification performance.


## How to View the Code

You can view the MATLAB code files directly in this repository:
- [https://github.com/Bachelorsthesis/LSTM/blob/main/elderly_young_classification/elderly_young.mlx](./elderly_young.mlx)
- [https://github.com/Bachelorsthesis/LSTM/tree/main/recovery_postrecovery_classification](./recovery_restpostrecovery.mlx)
- [https://github.com/Bachelorsthesis/LSTM/tree/main/restpostrecovery_totalrest_classification](./restposrecovery_totalrest.mlx)


## Acknowledgments

Special thanks to all contributors and the institution providing the proprietary data.

