# Personalized Recommendation System

## Overview

This project implements a Personalized Recommendation System using the Netflix Prize Dataset. The objective is to learn user preferences from historical movie ratings and generate relevant movie recommendations.

The system explores recommendation techniques such as Collaborative Filtering and Matrix Factorization to predict user ratings and recommend unseen content. Performance is evaluated using industry-standard recommendation metrics including RMSE and MAP@10.

---

## Problem Statement

Modern streaming platforms rely on recommendation systems to improve user experience and content discovery.

The goal of this project is to:

- Learn user preferences from historical interactions
- Predict ratings for unseen movies
- Generate Top-K personalized recommendations
- Compare recommendation approaches
- Evaluate recommendation quality

---

## Dataset

Netflix Prize Dataset

Dataset contains:

- 100M+ movie ratings
- 480K+ users
- 17K+ movies
- Rating scale: 1–5
- Movie metadata

Each record contains:

- User ID
- Movie ID
- Rating
- Timestamp

---

## Project Workflow

### 1. Data Preprocessing

- Data loading
- Cleaning and validation
- User-item interaction matrix construction
- Train-test split

### 2. Exploratory Data Analysis

- Rating distribution
- User activity analysis
- Movie popularity trends
- Data sparsity analysis

### 3. Recommendation Model Development

Implemented recommendation techniques:

- Collaborative Filtering
- Matrix Factorization
- SVD-based Recommendation

### 4. Recommendation Generation

- Rating prediction
- Top-K recommendation generation
- User preference modeling

### 5. Model Evaluation

Evaluation metrics:

- RMSE (Root Mean Squared Error)
- MAP@10 (Mean Average Precision @ 10)

Additional metrics:

- MAE
- Precision@K
- Recall@K

---

## Results

The recommendation system successfully:

- Learns user preferences
- Predicts unseen ratings
- Generates personalized recommendations
- Improves content discovery

Model performance is reported using RMSE and ranking-based evaluation metrics.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---
