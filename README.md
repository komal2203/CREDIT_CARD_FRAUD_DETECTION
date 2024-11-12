# CREDIT_CARD_FRAUD_DETECTION

This project detects fraudulent credit card transactions using machine learning. It includes a Jupyter notebook for data processing, model training, and evaluation.

## Goal
The goal is to identify fraudulent transactions using Logistic Regression and Random Forest models, with techniques to handle imbalanced data.

## Dataset
The dataset is too large to include here. Access it via:
`DATASET_LINK = 'https://drive.google.com/file/d/12mx3NXISlRP1GF61-11GfjPxfQ0zsaSi/view?usp=sharing'`

## Model Details
- **Algorithms**: Logistic Regression, Random Forest
- **Framework**: scikit-learn
- **Features**: Anonymized features (V1-V28), Time, Amount
- **Evaluation**: Accuracy, precision, recall, F1 score

## Workflow
1. **Load Data**: Import dataset into pandas.
2. **Visualize**: Explore data distribution.
3. **Handle Imbalance**: Apply under-sampling.
4. **Preprocess**: Scale features and split the data.
5. **Train Models**: Train Logistic Regression and Random Forest models.
6. **Evaluate**: Measure model performance.

## Files
- **Credit_Card_Fraud_Detection.ipynb**: Contains the code for training and evaluation.
- **README.md**: Project overview and setup instructions.
