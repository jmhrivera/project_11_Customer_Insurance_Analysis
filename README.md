**project_11_Customer_Insurance_Analysis**

### README

---

# Project 11: Customer Insurance Analysis with Machine Learning

## Overview
Sure Tomorrow, an insurance company, aims to tackle multiple tasks using machine learning. The tasks include:
1. Finding customers similar to a given customer to assist agents with marketing.
2. Predicting the probability that a new customer will receive an insurance benefit and comparing this with a dummy model.
3. Predicting the number of insurance benefits a new customer might receive using linear regression.
4. Protecting customer personal data by developing a data masking algorithm without affecting the performance of machine learning models.

## Dataset Description
The dataset is stored in the file `insurance_us.csv`. The relevant columns include customer demographics and historical insurance benefits.

## Project Structure
- `data_preprocessing.py`: Code for loading, cleaning, and preprocessing the dataset.
- `feature_engineering.py`: Code for creating and encoding features.
- `task_1_knn_similarity.py`: Code for finding similar customers using k-nearest neighbors.
- `task_2_classification.py`: Code for predicting the likelihood of insurance benefits using classification models.
- `task_3_linear_regression.py`: Code for predicting the number of insurance benefits using linear regression.
- `task_4_data_masking.py`: Code for protecting customer data and evaluating its impact on model performance.
- `results_summary.py`: Code for summarizing the results and providing conclusions.

## Requirements
- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Seaborn
- Matplotlib
- Imbalanced-learn

## Setup
1. Clone the repository:
```sh
git clone https://github.com/your_username/project_11_Customer_Insurance_Analysis.git
cd project_11_Customer_Insurance_Analysis
```

2. Install the required packages:
```sh
pip install -r requirements.txt
```

3. Download and place the dataset (`insurance_us.csv`) in the project directory.
