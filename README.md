# Fashion MNIST Image Classification

## Overview
This project builds and compares machine learning models on the Fashion MNIST dataset (60,000 training, 10,000 test images of 28×28 grayscale clothing items).  
The goal is to improve recall to reduce false negatives across classes, ensuring fewer misclassified clothing items.

## Methods
- **Models evaluated**: Logistic Regression, KNN, MLPClassifier, Random Forest, SVM  
- **Preprocessing**: Scaling, dimensionality reduction (optional PCA), train/validation split  
- **Hyperparameter Tuning**: RandomizedSearchCV with 5-fold cross-validation  
- **Evaluation Metrics**: Macro/micro recall, ROC/PR curves, confusion matrix  

## Results
- **Best model:** MLPClassifier (or your actual best)  
- **Performance:** Recall improved from 0.71 → 0.84 after tuning  
- **Takeaway:** Enhanced recall reduced false negatives, especially in confusing classes like shirts vs. t-shirts  
