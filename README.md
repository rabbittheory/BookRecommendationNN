# Book Recommendation System

This repository contains an implementation of a book recommendation system using PyTorch. The system leverages a neural network for embedding representations of books and employs K-Means clustering to group similar books based on these embeddings.

## Overview

The project aims to recommend books to users based on their similarity to other books. It involves the following main components:

1. **Data**: Utilizes a dataset from Kaggle(not included but featured in the link below) that contains information about various books.
2. **Neural Network Model**: A PyTorch-based neural network generates embeddings for books.
3. **K-Means Clustering**: Clusters the embeddings into groups, allowing the system to recommend books that are in the same cluster as a given book.

## Features

- **Book Embeddings**: Generate high-dimensional embeddings for books using a neural network model.
- **Clustering**: Apply K-Means clustering to group books based on their embeddings.
- **Recommendation**: Recommend books that belong to the same cluster as a specified book.

## Requirements

- Python 3.x
- PyTorch
- scikit-learn
- pandas
- Kaggle Dataset - https://www.kaggle.com/datasets/shayanshahid997/books-prediction
