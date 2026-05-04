# Breast Cancer Classification Using Machine Learning and Deep Learning

This project compares multiple machine learning and deep learning models for classifying breast cancer tumors as benign or malignant using the Wisconsin Breast Cancer Diagnostic dataset.

The goal of the project is to evaluate how well different classification algorithms perform on structured diagnostic tumor features and to compare traditional machine learning models with more complex neural network approaches.

## Dataset

The project uses the Wisconsin Breast Cancer Diagnostic dataset, which contains diagnostic measurements computed from breast mass cell nuclei. Each sample is classified as either:

- Malignant
- Benign

The dataset includes 30 numerical diagnostic features, such as radius, texture, perimeter, area, smoothness, compactness, concavity, and symmetry.

## Models Evaluated

The project evaluates several classification methods, including:

- Support Vector Machine (SVM)
- Random Forest
- AdaBoost
- K-Nearest Neighbors (KNN)
- XGBoost
- Bagging
- Naive Bayes
- Artificial Neural Network (ANN)
- Long Short-Term Memory (LSTM)
- Bidirectional LSTM (Bi-LSTM)
- 1D Convolutional Neural Network (1D-CNN)
- CNN-BiLSTM-Attention
- CNN-LSTM
- CDIL-CNN

## Evaluation Metrics

Models were evaluated using the following performance metrics:

- Training accuracy
- Validation accuracy
- Test accuracy
- F1-score
- Cohen’s kappa
- Matthews Correlation Coefficient (MCC)
- Recall / sensitivity
- Specificity
- Precision
- Area Under the Curve (AUC)

In this project, malignant tumors were treated as the positive class. Therefore, recall represents sensitivity for detecting malignant cases.

## Main Results

The strongest overall model was K-Nearest Neighbors, which achieved the highest test accuracy and strong performance across most evaluation metrics. Support Vector Machine also performed very well and achieved the highest AUC score.

Overall, the results suggest that traditional machine learning models such as KNN and SVM can perform as well as, or better than, more complex deep learning models on this structured tabular dataset.

## Repository Contents

```text
BC 11 Methods.ipynb              Main notebook with classical ML and basic deep learning models
CNN_BiLSTM_Attention.ipynb       CNN-BiLSTM-Attention model notebook
CNN_LSTM_BC.ipynb                CNN-LSTM hybrid model notebook
CDIL-CNN_BC.ipynb                CDIL-CNN model notebook
