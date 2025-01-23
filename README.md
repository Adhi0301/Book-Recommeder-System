# Book Recommender System

This project aims to recommend 4-5 books to users based on their previous reading history. The system is built as a Flask application, providing a website interface for users to find book recommendations.

## Project Overview

The project involves the following key steps:
- **Data Collection and Cleaning**: Utilized three datasets - users, ratings, and books. Cleaned the data to ensure accuracy and consistency.
- **Top 50 Books Identification**: Based on ratings and the number of users who rated the books, identified the top 50 books.
- **Recommendation Algorithm**: Used cosine similarity to recommend books similar to the user's previous reading book.

## Datasets

- **Users**: Information about the users.
- **Ratings**: User ratings for various books.
- **Books**: Metadata about books.

## Key Libraries Used

- Flask
- Pandas
- Scikit-learn

## Cosine Similarity

Cosine similarity is a metric used to measure how similar two items are. It calculates the cosine of the angle between two vectors in a multi-dimensional space, which in this case are book rating vectors. The value ranges from -1 to 1:
- **1** indicates that the two items are identical.
- **0** indicates no similarity.
- **-1** indicates complete dissimilarity.

Here's how it works:
- **Step 1**: Represent each book and user rating as a vector.
- **Step 2**: Calculate the dot product of the vectors.
- **Step 3**: Divide the dot product by the product of the magnitudes (lengths) of the vectors.
- **Step 4**: The resulting value is the cosine similarity score.

The formula for cosine similarity is:



\[ \text{cosine\_similarity} = \frac{A \cdot B}{||A|| ||B||} \]



## Getting Started

### Prerequisites

- Python 3.11
- Flask
- Pandas
- Scikit-learn
- Other dependencies listed in `requirements.txt`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Adhi0301/book-recommender-system.git


Dataset link = 'https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset'

