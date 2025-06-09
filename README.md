# Breast Cancer Classifier with a Neural Network from Scratch

## Overview
This project is an implementation of an artificial neural network, built using only Python and NumPy, to classify breast cancer tumors as malignant (M) or benign (B). The main goal was to apply fundamental deep learning concepts, including forward propagation, backpropagation, and hyperparameter tuning, on a real-world dataset.

This project was developed as part of my studies in the first module of my Machine Learning course.

## Dataset
The project uses the [Wisconsin Diagnostic Breast Cancer (WDBC)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) dataset from the UCI repository. The dataset contains 569 samples with 30 numerical features that were computed from digitized images of a fine-needle aspirate (FNA) of a breast mass.

## Technologies and Concepts Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
- **ML Concepts:**
  - Artificial Neural Networks
  - Forward Propagation & Backward Propagation (Backpropagation)
  - Activation Functions (Tanh and Sigmoid)
  - Cost Function (Cross-Entropy)
  - Gradient Descent
  - Data Preprocessing (Feature Scaling)
  - Data Splitting (Train/Test)
  - Model Evaluation (Accuracy, Classification Report)

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   ```
2. Navigate to the project folder:
   ```bash
   cd YOUR_REPOSITORY_NAME
   ```
3. Run the Python script or open the Jupyter Notebook.
   ```bash
   python your_script_name.py
   ```

## Results
The trained model achieved the following results on the test set:

- **Accuracy:** 97.37%  *(<-- Replace with your result!)*
- **Classification Report:**
  ```
  # Paste the output of your classification_report here
              precision    recall  f1-score   support

           0       0.98      0.98      0.98        71
           1       0.95      0.95      0.95        43
  ```
This demonstrates the model's ability to generalize well to unseen data, distinguishing with high accuracy between benign and malignant tumors.

## Possible Future Improvements
- Implement the model using a framework like TensorFlow or Keras to compare performance.
- Experiment with different optimizers, such as Adam.
- Add regularization techniques, like Dropout, to further improve generalization.
