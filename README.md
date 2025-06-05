# 📚 Book Recommender with Machine Learning

This project is a machine learning-based book recommendation system that suggests books similar to a user's selected title. It utilizes collaborative filtering techniques and is deployed as a web application using Streamlit.

## 🚀 Features

- Personalized book recommendations based on user input.
- Interactive web interface built with Streamlit.
- Preprocessed data for efficient performance.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit

## 📂 Project Structure

- `app.py`: Main application script for the Streamlit web app.
- `Recommender.ipynb`: Jupyter notebook containing the recommendation logic and data preprocessing steps.
- `Data/`: Directory containing datasets and preprocessed files:
  - `books.pkl`: Pickle file containing book metadata.
  - `popular.pkl`: Pickle file containing data on popular books.
  - `pt.pkl`: Pickle file containing the pivot table used for recommendations.
  - `similarity_scores.pkl`: Pickle file containing precomputed similarity scores between books.

## 🔗 Live Demo

Check out the live application here: [Streamlit App](https://bookrecommenderwithmachinelearning-qxfkefk9upb7yzstedn5z2.streamlit.app/)

## 📈 How It Works

1. The user selects or inputs a book title.
2. The system retrieves similar books based on precomputed similarity scores.
3. Recommendations are displayed on the web interface.

## 📋 Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries:
  - pandas
  - numpy
  - scikit-learn
  - streamlit

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/BEERAMHARSHITHREDDY/BookRecommenderwithMachineLearning.git
   cd BookRecommenderwithMachineLearning
