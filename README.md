Classifying Breast Cancer using SVM
Project Overview
This project focuses on classifying breast cancer using Support Vector Machines (SVM). The goal is to develop a machine learning model that can accurately classify breast cancer as either benign or malignant based on a given set of features. The project leverages a comprehensive dataset of breast cancer cases, performing data preprocessing, exploratory data analysis, feature selection, and model training and evaluation using SVM.

Key Features and Methodology
1. Data Collection and Preprocessing
Dataset: The project uses the Breast Cancer Wisconsin (Diagnostic) dataset, which includes features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
Preprocessing: Data cleaning steps include handling missing values, normalizing feature scales, and splitting the data into training and testing sets.
2. Exploratory Data Analysis (EDA)
Visualization: Various visualization techniques such as histograms, scatter plots, and correlation matrices are used to understand the distribution of data and the relationships between features.
Statistical Analysis: Summary statistics and data distributions are analyzed to gain insights into the dataset.
3. Feature Selection
Correlation Matrix: A correlation matrix is created to identify highly correlated features.
Dimensionality Reduction: Techniques like Principal Component Analysis (PCA) are employed to reduce the dimensionality of the data while retaining significant variance.
4. Model Building
Support Vector Machine (SVM): An SVM model is trained to classify the breast cancer data. Different kernel functions (linear, polynomial, RBF) are experimented with to determine the best-performing model.
Hyperparameter Tuning: Grid search and cross-validation techniques are used to tune hyperparameters and optimize the model performance.
5. Model Evaluation
Performance Metrics: The model's performance is evaluated using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
ROC Curve: Receiver Operating Characteristic (ROC) curve and Area Under the Curve (AUC) are plotted to assess the classifier's performance.
Project Structure
Data: Contains the dataset used for training and testing.
Notebooks: Jupyter notebooks containing the code for data preprocessing, EDA, feature selection, model building, and evaluation.
Scripts: Python scripts for different stages of the project (data processing, model training, etc.).
Results: Output files including visualizations, model performance metrics, and saved models.
Docs: Documentation files providing detailed explanations of the project methodology and findings.
