# Books Recommender System using Machine Learning

This project is a book recommender system that provides personalized book suggestions using collaborative filtering and machine learning techniques. The system analyzes user rating behavior and recommends books based on similarities between users and books.

## Project Overview

The goal of this project is to compare different machine learning approaches for building a book recommendation system. The implemented models are:

- K-Nearest Neighbors (KNN)
- Neural Collaborative Filtering / ANN
- K-Means Clustering

The system uses user-book rating patterns to generate recommendations and evaluates the models using accuracy, precision, recall, and F1-score.

## Dataset

The project uses a book recommendation dataset containing:

- Books information such as title, author, ISBN, year of publication, and publisher
- Users information such as user ID, location, and age
- Ratings given by users to books

During preprocessing, zero ratings were removed because they represent missing or unimportant ratings. Users and books with very few ratings were also filtered to improve recommendation quality.

## Models Used

### K-Nearest Neighbors

KNN recommends books by finding users with similar rating patterns. Cosine similarity is used to measure similarity between users.

### Neural Collaborative Filtering

The neural model learns user and book embeddings and captures hidden relationships between users and books. It combines matrix factorization and neural network layers.

### K-Means Clustering

K-Means groups users with similar preferences into clusters. Recommendations are generated based on books liked by users in the same cluster.

## Evaluation Results

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Neural Collaborative Filtering | 0.87 | 0.90 | 0.96 | 0.93 |
| KNN | 0.74 | 0.92 | 0.69 | 0.79 |
| Clustering | 0.27 | 0.89 | 0.20 | 0.33 |

Neural Collaborative Filtering achieved the best overall performance based on the reported results.

## Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Truncated SVD
- KNN
- K-Means Clustering
  
## How to Run
python mainApp.py

## Repository Files

```text
ANN.py              Neural Collaborative Filtering model
KNN.py              KNN recommendation model
ClusterApp.py       Clustering-based recommendation model
interface.py        User interface file
mainApp.py          Main application file
ncf_model.h5        Saved trained neural model
projectPaper.pdf    Project report
testingAi.pdf       Testing/evaluation document
```
## Authors
- Tasneem Shelleh
- Layan Salem
- Raghad Jamhour

