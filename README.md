# Credit Score Classification

This repository contains a machine learning pipeline for analyzing and classifying credit scores based on demographic and financial data. The project uses a CSV dataset (`train.csv`) and builds a predictive model using scikit-learn.

## 📂 Project Structure

```
├── train.py              # Main Python script converted from the original notebook
├── train.csv             # Dataset used for training
```

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8 or higher installed.

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python train.py
```

This will execute the full pipeline including data preprocessing, visualization, and model training.

## 📊 Dataset

- `train.csv`: Contains user demographic and financial features along with credit score labels (e.g., Poor, Standard, Good).

## 📈 Visualizations

The script includes visualization using Plotly to explore the distribution of credit scores across occupations.

## 🧠 Models

The project uses machine learning models from `scikit-learn` to classify credit scores. Preprocessing steps may include encoding, scaling, and data splitting.

