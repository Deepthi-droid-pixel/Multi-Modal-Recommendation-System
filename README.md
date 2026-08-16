# Multi-Modal Recommendation System

A recommendation system that combines multiple sources of information to provide personalized movie recommendations.

## 📌 Project Overview

This project aims to develop a multi-modal movie recommendation system using the MovieLens dataset.

The system uses different types of information, including:

- Movie metadata and genres
- User-movie ratings
- User-generated tags
- External movie identifiers

These different information sources will be processed and combined during the recommendation-model development stage to improve the relevance of movie recommendations.

## 🎯 Objectives

- Understand and preprocess movie and user interaction data.
- Perform exploratory data analysis (EDA) to identify patterns and trends.
- Extract meaningful features from movie metadata.
- Develop recommendation models using multiple information sources.
- Evaluate the performance of the recommendation system.
- Integrate the recommendation system into an application interface.

## 📂 Project Structure

```text
Multi-Modal-Recommendation-System/
│
├── api/                    # Backend/API components
├── dashboard/              # Dashboard/application interface
│
├── data/
│   ├── raw/                # Original dataset files
│   └── processed/          # Processed datasets
│
├── models/                 # Trained models and model components
├── notebooks/              # Jupyter notebooks for analysis and experimentation
│   └── 01_data_understanding.ipynb
│
├── reports/                # Project reports and documentation
├── src/                    # Source code
├── tests/                  # Testing files
│
├── .gitignore
└── README.md
