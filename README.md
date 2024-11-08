# SVM-Dwelling-Ownership

## Project Title: Predicting Dwelling Ownership in Washington State: A Support Vector Machine Approach

## Abstract:
This project explores the prediction of dwelling ownership using Support Vector Machines (SVM). The goal is to classify whether an individual owns a dwelling or not based on a set of demographic and financial features. Through the application of SVMs, we built and evaluated a model capable of making accurate predictions regarding dwelling ownership. Hyperparameter tuning and cross-validation were performed to improve model performance. The findings provide valuable insights into the factors influencing dwelling ownership, which could be useful for real estate analysts and policy-makers.

## Project Structure:
**SVM-Dwelling-Ownership.ipynb: The Jupyter notebook containing the entire workflow, including data preprocessing, model training, and evaluation.
**SVM-Dwelling-Ownership-Report.pdf: The report summarizing the analysis, methodology, results, and conclusions.
**Housing.csv: The dataset used in the project, which includes features related to demographics, income, and dwelling ownership status.
**README.md: This file, providing an overview and instructions for the project.

## Installation:
Clone the repository using the following command:

git clone https://github.com/jananikrishnamurthy17/SVM-Dwelling-Ownership.git

Load the source CSV file into the project using Google Drive or any other preferred method.

Run the code in SVM-Dwelling-Ownership.ipynb to execute the analysis.

## Dataset:
The dataset used for this project contains information on various factors affecting dwelling ownership. It includes demographic variables like age, income, and education level, along with a binary target variable indicating dwelling ownership (0 for no ownership, 1 for ownership).

## Methodology:
1. Data Preprocessing: Cleaned and processed the dataset by handling missing values, encoding categorical features, and scaling numerical variables.
2. Model Development:
   SVM: We applied a Support Vector Machine (SVM) model to predict dwelling ownership.
   Hyperparameter Tuning: Grid search and cross-validation were used to find optimal SVM parameters for better classification performance.
3. Model Evaluation: The model was evaluated using accuracy, precision, recall, and F1-score.
   
## Results:
The SVM model achieved a classification accuracy of 85% after fine-tuning the hyperparameters.
Precision, recall, and F1-scores were calculated to assess model performance across different class distributions.

## Conclusion:
The SVM model successfully predicted dwelling ownership, highlighting important factors that influence the likelihood of an individual owning a dwelling. This can be applied to real estate market analysis and provide valuable predictions to aid in property investment strategies.
