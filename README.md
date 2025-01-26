# Job Title Classification with BERT and CatBoost

## Overview
Multi-label classification of job titles using transformer-based and machine learning approaches.

## Project Structure
- Data preprocessing
- Two classification methods:
  1. BERT Transformer Model
  2. CatBoost Algorithm

## Installation
```bash
pip install -r requirements.txt
```

## Key Features
- Multi-label classification
- Threshold optimization
- Performance metrics calculation

## Model Performance
- Evaluated using precision, recall, F1 score, and accuracy
- Threshold optimization for best results

## Usage
```python
# Classify job titles
bert_predictions = classify_with_bert(job_titles)
catboost_predictions = classify_with_catboost(job_titles)
```

## Potential Improvements
- Hyperparameter tuning
- Experiment with more advanced architectures
- Collect more training data

## Note
Dataset is not included due to privacy considerations.
