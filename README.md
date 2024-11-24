# 🎥 Movie Recommendation System

## 📋 Project Overview
The Movie Recommendation System is designed to help users discover new movies they'll love. Using a dataset from TMDB, this project implements a **Content-Based Filtering** approach, recommending movies based on metadata such as genres, directors, and cast. Additionally, it aims to integrate a dialogue-based recommendation using **T5-small**, enhancing the user experience by providing conversational movie suggestions.

## 🎯 Why This Project Exists
The goal of this project is to provide a personalized movie recommendation experience. By leveraging metadata, users can find movies similar to their favorites. The future addition of a dialogue-based recommendation feature will allow users to engage more interactively, refining their movie search based on conversational feedback.

## 🚀 How to Clone and Run
1. **Clone the Repository**  
Open your terminal and run the following command:

  ```bash
  git clone https://github.com/yourusername/movie-recommendation-system.git
  cd movie-recommendation-system
  ```

2. **Install Dependencies**
Make sure you have Python installed. Then, install the required packages:

  ```bash
  pip install -r requirements.txt
  ```

3. **Run the Application**
Launch the application:

    python app.py

📦 Dependencies

Ensure you have the following dependencies installed:

    Python 3.7+
    Pandas for data manipulation
    Scikit-learn for building recommendation algorithms
    T5-small for dialogue-based recommendations (optional)
    Flask (or any other web framework) for serving the application

You can install all required dependencies using the requirements.txt file provided in the repository.
📚 Dataset

This project uses the TMDB 5000 Movie Dataset to build the recommendation system.
🛠️ Methodology

    Content-Based Filtering: Recommends movies based on metadata (e.g., genre, director, actors).
    Dialogue-Based Recommendation (WIP): Uses T5-small for conversational suggestions, tailored to smaller datasets for efficient processing.

💡 Future Enhancements

    Complete integration of dialogue-based recommendations.
    Optimize filtering algorithms for better recommendation accuracy.

Feel free to contribute to the project or raise any issues if you encounter them!
