Contributors: Alena Rzaeva, Stella Birlo, Elena Busam

# Summary

Based on information obtained from a tissue sample through Fine Needle Aspiration (FNA), machine learning was used to classify the tissue as either benign or malignant. To achieve this, three machine learning algorithms (XGBoost, Random Forest, Neural Network) were trained and validated using the existing Wisconsin breast cancer dataset. Furthermore, a Dashboard was implemented for visualization purposes and as a prediction application.

# Data

The Breast Cancer Wisconsin (Diagnostic) Data Set contains 569 samples of breast tissue that have been analyzed based on various characteristics. The dataset includes 33 columns that describe different properties of the samples. The goal of the dataset is to differentiate between benign (B) and malignant (M) tumors. Among the 30 numerical features used to describe the tissue samples are tumor size, texture, symmetry, and the number of cell nuclei.

For each of these features, three statistical values are provided:

Mean: The average value of the respective feature.
Standard Error: A measure of the variability of the feature within a sample.
Worst: The highest measured value of the feature in the sample.
The dataset was originally created by W. Wolberg, O. Mangasarian, N. Street, and W. Street at the University of Wisconsin-Madison and is available through the UCI Machine Learning Repository on Kaggle.
Source: Kaggle https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
