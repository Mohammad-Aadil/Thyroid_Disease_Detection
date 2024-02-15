# Thyroid Disease Detection

## Introduction
Thyroid disease affects many people worldwide. Detecting it early is crucial for effective treatment. This project aims to predict thyroid disease risk using machine learning.

## Problem

Thyroid disease is a common cause of medical diagnosis and prediction, with an onset that is difficult to forecast in medical research. The thyroid gland is one of our body's most vital organs. Thyroid hormone releases are responsible for metabolic regulation. Hyperthyroidism and hypothyroidism are one of the two common diseases of the thyroid that releases thyroid hormones in regulating the rate of the body's metabolism.

The main goal is to predict the estimated risk on a patient's chance of obtaining thyroid disease or not.

## Dataset
The dataset contains medical and demographic info like age, sex, and thyroid hormone levels. The target is the type of thyroid disease.

## Data Prep
- Missing values were replaced with 'nan'.
- Dropped irrelevant columns and encoded categorical variables.
- Imputed missing values and applied log transformation to skewed data.
- Balanced dataset using RandomOverSampler.

## Model Building
- Trained Random Forest Classifier and K-Nearest Neighbors.
- Tuned hyperparameters using GridSearchCV.
- Saved the best model for future use.

## File Structure
- **hypothyroid.csv**: Dataset.
- **Thyroid_Disease_Detection.ipynb**: Jupyter Notebook with code.
- **enc.pickle**: Serialized model.

## How to Use
1. Clone the repository.
2. Install Python and required libraries.
3. Run `Thyroid_Disease_Detection.ipynb`.
4. Follow instructions for data prep, model training, and evaluation.
5. Use saved model (`enc.pickle`) for predictions.

## Contact
For questions or feedback:
- Email: shaikhaadil8855@gmail.com
- LinkedIn: https://www.linkedin.com/in/mrmohammadaadil/


