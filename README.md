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

## Usage

# Training Pipeline
Update Dataset Path
Modify the dataset path in both BERT and CatBoost code sections:


data = pd.read_excel("/path/to/dataset")  # Update to your dataset path
Run Full Training

Train BERT model (saved to ./bert_model)
Train CatBoost model (saved to ./cat_boost_model)
Evaluate both models
Save optimal thresholds (BERT: 0.25, CatBoost: auto-tuned)


# Inference

BERT-based Classification
Load the saved BERT model and tokenizer for inference:

CatBoost-based Classification
Load the saved CatBoost model and TF-IDF vectorizer for inference:
