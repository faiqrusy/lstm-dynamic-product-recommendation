# Sequence Sensibility: LSTM for Dynamic Product Recommendations

## Project Overview
This project aims to utilize Long Short-Term Memory (LSTM) networks to predict future basket items for customers based on their previous transactions. The goal is to develop a predictive model that aids decision-making processes by forecasting future customer purchases, offering benefits to both consumers and businesses.

## Objectives
- To leverage LSTM networks to capture long-term dependencies in transaction data and predict future purchases.
- To provide dynamic product recommendations that enhance customer experience and optimize business operations.

## Dataset
The analysis uses a dataset from the UCI Machine Learning Repository covering transactions from a UK-based online retail store. It includes data from December 1, 2010, to December 9, 2011, featuring a wide range of products sold to mostly wholesalers.

## Methodology
- Exploratory Data Analysis (EDA): Analysis focused on understanding product popularity and transaction patterns using word clouds and sales data analysis.
- Data Preprocessing and Cleaning: Techniques included handling missing values, removing duplicates and negative quantities, and encoding descriptions numerically.
- Model Development:
  - Initial Approach: Basic LSTM model using label encoding.
  - Second Approach: Reduced complexity by focusing on frequently purchased items.
  - Final Approach: Employed the Universal Sentence Encoder to enhance item description processing and incorporated the LSTM model for sequential data handling.

## Model Architecture
The LSTM model architecture involves multiple layers designed to process and predict sequential data efficiently. It includes embedding layers, LSTM layers, and dense layers to output predictions for future purchases.

## Challenges
- Imperfect Data Entries: Variations in data recording affected the model's training and accuracy.
- Large Number of Unique Items: Managed the complexity and computational demand due to a large inventory of products.
- Limited Computing Resources: Constrained resources affected the model's training efficiency and exploration of different architectures.

## Conclusion
The project achieved moderate success, demonstrating the capability of LSTM networks in predicting future purchases based on historical data. Although the model achieved an accuracy of 40%, there is substantial scope for improvement in refining the model's predictions and enhancing its practical application in real-world scenarios.

## Future Work
- Further optimization of the model to improve accuracy and efficiency.
- Exploration of additional features and modeling techniques to better capture consumer behavior patterns.
