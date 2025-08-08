# SVM Classifier on Student Dataset (With PCA)

## Problem
We are trying to predict a student’s final status:
Graduated, Dropped Out, or Still Enrolled
The data includes background, education, and family details.

## Solution
We used Support Vector Machine (SVM) for prediction.
First trained on full data.
Then used PCA to reduce columns and make it faster.

## Accuracy
Without PCA: 0.7785

With PCA (18 columns): 0.7209
