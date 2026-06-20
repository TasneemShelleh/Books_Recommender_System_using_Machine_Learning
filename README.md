# Books Recommender System using Machine Learning

A machine learning-based book recommender system that provides personalized book recommendations using collaborative filtering techniques. The project compares different recommendation approaches, including K-Nearest Neighbors (KNN), Artificial Neural Networks / Neural Collaborative Filtering (NCF), and Clustering.

## Overview

This project aims to recommend books to users based on their previous rating behavior and the behavior of similar users. Recommendation systems are widely used to personalize user experiences by predicting items that users may like. In this project, the system analyzes user-book interactions and generates recommendations using machine learning models.

The project focuses on collaborative filtering, where recommendations are made by learning patterns from user ratings rather than relying only on book content. Three main approaches were implemented and compared:

- K-Nearest Neighbors (KNN)
- Neural Collaborative Filtering / Artificial Neural Network (ANN)
- K-Means Clustering

According to the project paper, the system uses collaborative filtering to analyze user preferences and rating patterns, and evaluates the models using accuracy, precision, recall, and F1-score. :contentReference[oaicite:0]{index=0}

## Repository Contents

```text
Books-Recommender-System-using-Machine-Learning/
│
├── ANN.py                  # Neural Collaborative Filtering / ANN model
├── KNN.py                  # KNN-based recommender system
├── ClusterApp.py           # Clustering-based recommender system
├── interface.py            # User interface file
├── mainApp.py              # Main application runner
├── ncf_model.h5            # Trained Neural Collaborative Filtering model
├── projectPaper.pdf        # Project paper and documentation
├── testingAi.pdf           # Testing or evaluation document
└── README.md
