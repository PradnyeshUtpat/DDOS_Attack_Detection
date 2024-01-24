# DDOS_Attack_Detection
## Dataset - https://www.kaggle.com/datasets/pradnyeshutpat/ddos-dataset


## Overview

This repository contains the code and analysis for a machine learning project focused on classifying network requests as benign or malicious based on various features. The project includes data analysis, visualization, and the implementation of classical machine learning models.

## Dataset

The dataset used for this project is stored in the `dataset_sdn.csv` file. It includes information about network requests, such as source and destination IP addresses, packet count, byte count, and other relevant features. The target variable, `label`, indicates whether a request is benign (0) or malicious (1).

## Data Analysis and Visualization

The initial data analysis involves exploring the dataset, checking for missing values, and visualizing key features. Various visualizations include bar plots for IP addresses, histograms for duration and transmitted bytes, and pie charts for the distribution of benign and malicious requests.

## Classical ML Models

The project implements several classical machine learning models, including:
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

For each model, the code includes data preprocessing, model training, and evaluation metrics such as accuracy, precision, recall, and F1-score.

## Feature Selection

The feature selection process involves choosing a subset of important features based on weights assigned to them. The selected features are used in the machine learning models for improved performance.

## Running the Code

To run the code, follow these steps:

1. Install the required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.
2. Clone the repository: `git clone https://github.com/PradnyeshUtpat/DDOS_Attack_Detection.git`.
3. Navigate to the project directory: `cd DDOS_Attack_Detection`.
4. Run the main script or notebooks.

## Results

Include a summary of the results obtained from each model. Discuss the model with the highest accuracy and any interesting findings or challenges faced during the analysis.

## Future Work

If applicable, discuss potential future improvements or additional analyses that could enhance the project.

## Contributors

## Contributors

- [Pradnyesh Utpat](https://github.com/PradnyeshUtpat)
- [Rohit Shidid](https://github.com/rohitshidid) 
- [Soham Mahajan](https://github.com/sohamm3) 





