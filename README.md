# Eyes-Gender-Classification-Keras

This repository contains a project focused on implementing a gender classification classifier based on eye images using neural networks in the Keras framework. The goal of the project is to build and evaluate three different classification models to determine gender by analyzing eye images.

## Task

The project tasks are outlined as follows:

### 1. Exploratory Data Analysis (EDA) and Data Preprocessing
- Perform EDA on the dataset.
- Conduct data preprocessing as required.

### 2. Classification Models
- Implement three classification models:
   a. Model 1 - Benchmark model (SVM or KNN Classifier from Sklearn)
   b. Model 2 - Multilayer Perceptron Model (without using Sklearn Algorithms)
   c. Model 3 - Convolutional Neural Network (CNN) model
- For the neural net models (Model 2 & Model 3):
   i. Explain the intuition behind the architecture.
   ii. Use techniques like dropout, L1/L2 regularization, Early Stopping, Data Augmentation, and experiment with hyperparameters as needed.
   iii. Plot training loss and validation loss.
   iv. Plot training accuracy and validation accuracy.

### 3. Model Evaluation
- For each model, calculate performance metrics (accuracy, precision, recall).
- Use classification report from sklearn.

### 4. Model Comparison
- Compare the performance of the three models.

### 5. Observations and Conclusion
- Provide observations and reasoning throughout the analysis.
- Include a conclusion section at the end of the notebook.
