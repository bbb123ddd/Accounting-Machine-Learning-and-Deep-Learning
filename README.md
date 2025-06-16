# Accounting Machine Learning and Deep Learning

This repository contains machine learning and deep learning projects for analyzing accounting data, with a focus on **profit prediction** based on real-world financial indicators.

## 📊 Project Overview

- Data source: `利益予測データベース_20250330.xlsx` (Profit Prediction Database)
- Task: Use various machine learning (ML) and deep learning (DL) algorithms—including DNN—to predict company profit (利益, profit) based on historical accounting and financial data.
- Models:Includes DNN (Deep Neural Network), and plans for adding other ML/DL methods.
- Applications: Financial forecasting, risk analysis, and anomaly detection in accounting data.

## 🔍 Data Description

The dataset contains various accounting indicators (features) and the target variable "profit" to be predicted. Each row represents a company-year (or observation period) with corresponding financial metrics.

| Sample | group | ... | financial indicators (features) | profit (target) |
|--------|-------|-----|-------------------------------|-----------------|
|        |       | ... |                               |                 |

- Input features: financial/accounting indicators (e.g. sales, assets, liabilities, etc.)
- Target: profit (`利益`)

## 🚀 Methods

- Data preprocessing and exploratory analysis
- Feature engineering (selecting and transforming accounting indicators)
- Model training with DNN and other machine learning algorithms
- Performance evaluation using MAE, confidence intervals, and visualization

## 📦 How to Use

1. Clone this repository
2. Prepare the dataset (`利益予測データベース_20250330.xlsx`)
3. Run the provided Jupyter Notebooks (`DNN_model.ipynb`, etc.)
4. Analyze prediction results and model performance

## 📚 Future Work

- Add more ML/DL models (e.g. RandomForest, XGBoost, LSTM)
- Extend to other financial prediction tasks

---

## 中文简介

本项目以《利益予測データベース_20250330.xlsx》为数据基础，利用机器学习和深度学习方法，对会计和财务指标进行建模，重点任务是**利润预测**。项目已实现DNN等模型，后续将加入更多方法，适用于财务预测、风险分析、异常检测等应用场景。

---

*Feel free to contact or contribute!*
