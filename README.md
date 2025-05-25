# book_reccomentation_knn

This project implements a **Book Recommendation System** using the **K-Nearest Neighbors (KNN)** algorithm. The system is built with the **Book-Crossings dataset**, providing personalized book recommendations based on user ratings.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Example Recommendations](#example-recommendations)
- [Results](#results)

---

## Project Overview

This recommendation system:
- Uses a user-item interaction matrix to model the relationships between books and users.
- Normalizes the data for improved performance.
- Applies the **cosine similarity** metric to identify similar books.
- Provides the top 5 book recommendations for a given title.

---

## Features
- Find similar books for any given title.
- Visualize user-book relationships in the form of a sparse matrix.
- Measure distances between books using cosine similarity.

---

## Dataset

The project uses the **Book-Crossings dataset**, which includes:
- **Books**: Information about books (ISBN, title, author).
- **Ratings**: User ratings for different books.

### Files:
1. `BX-Books.csv`: Contains book metadata.
2. `BX-Book-Ratings.csv`: Contains user ratings.

Dataset Source: [Book-Crossings dataset](https://cdn.freecodecamp.org/project-data/books/book-crossings.zip)

---

## Technologies Used
- Python
- Libraries: `NumPy`, `Pandas`, `scikit-learn`, `Matplotlib`
- Machine Learning: K-Nearest Neighbors (KNN)

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/book-recommendation-system.git
   cd book-recommendation-system
## **Example Recommendations**
Book Title: Where the Heart Is (Oprah's Book Club (Paperback))
Output:
The Lovely Bones: A Novel
I Know This Much Is True
The Surgeon
The Weight of Water
I'll Be Seeing You

---

## **Results**
Results
-The project successfully passed the recommendation test with the following results:
-Distances and indices are accurately calculated.
-Recommendations align closely with expected values.

---
