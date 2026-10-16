# Analisis Kinerja Algoritma _Decision Tree_ dan _Random Forest_ pada Klasifikasi Multikelas Cuitan X Menggunakan TF-IDF (Studi Kasus: Data Cuitan Terkait Grup K-pop aespa)

A research project analyzing the performance of Decision Trees and Random Forests for multi-class classification of public posts on X related to the K-pop group aespa.

## Project Overview

This project investigates how traditional machine learning algorithms perform when classifying text-based social media content into multiple categories. Text data are transformed into numerical features using Term Frequency–Inverse Document Frequency (TF-IDF) before model training and evaluation.

## Objectives

- Prepare and preprocess text data for classification.
- Represent text documents using TF-IDF features.
- Train and compare Decision Tree and Random Forest classifiers.
- Evaluate model performance using appropriate classification metrics.
- Examine the strengths and limitations of each approach.

## Methods

1. **Data preparation:** Review the dataset and prepare text for analysis.
2. **Text preprocessing:** Clean and normalize text according to the research methodology.
3. **Feature extraction:** Convert text into numerical representations using TF-IDF.
4. **Model training:** Train Decision Tree and Random Forest classifiers.
5. **Model evaluation:** Compare model performance using a holdout test set and cross-validation, where applicable.

## Models and Evaluation

The models are evaluated using classification metrics such as accuracy, precision, recall, and F1-score. Confusion matrices are used to examine classification errors across classes.

The final report should distinguish test-set results from cross-validation results and specify the averaging method used for multiclass metrics.

## Repository Structure

- `Code/` — Research source code.
- `Data Penelitian/` — Research data or data documentation, subject to applicable sharing restrictions.
- `README.md` — Project overview and documentation.

## Results

Final performance metrics, visualizations, and interpretation will be documented here after verification against the completed research results.

## Limitations

Model performance may be affected by class imbalance, the quality of manual labels, the limited context available in individual posts, and the representational limitations of TF-IDF.

The findings apply to the dataset and experimental setup used in this study and should not automatically be generalized to all X posts or other topics.

## Reproducibility

The code, package requirements, data preparation steps, and model evaluation procedure should be documented so that the experiment can be reproduced where the required data are lawfully available.

## Research Context

This project was developed as part of an undergraduate Mathematics research project with a concentration in Statistics.
