# Movie Recommendation System

This repository contains a **Movie Recommendation System** project developed using Python and Flask. It leverages machine learning techniques to recommend movies based on user preferences and metadata similarity.

## Features

- **Content-Based Filtering**: Suggests similar movies based on textual metadata such as genres, cast, crew, and overview.
- **Interactive Web Interface**: Users can input a movie name and receive personalized recommendations via a simple Flask-based UI.

## Machine Learning Workflow

1. **Data Preprocessing**  
   - Used the TMDB 5000 Movies and Credits datasets from Kaggle.  
   - Merged and cleaned datasets, removed null values, and handled inconsistencies.  
   - Applied parallel processing with Pandarallel to speed up preprocessing.

2. **Feature Engineering**  
   - Extracted and combined fields like genres, keywords, overview, cast, and crew into a single metadata field.  
   - Performed text normalization and vectorization using NLP techniques.  
   - Used SpaCy for advanced tokenization and lemmatization.

3. **Similarity Calculation**  
   - Converted processed text into vectors using TF-IDF vectorizer.  
   - Applied K-Nearest Neighbors (KNN) to identify top similar movies.  
   - Created a similarity matrix to efficiently retrieve movie recommendations.

4. **Model Deployment**  
   - Deployed the logic in a Flask web application.  
   - Designed a minimal front-end UI to take user input and show recommendations in real-time.

## Tools and Libraries Used

- **Programming Language**: Python  
- **Web Framework**: Flask  
- **Data Analysis**: Pandas, Pandarallel, NumPy  
- **Machine Learning**: Scikit-learn (KNN, TF-IDF Vectorizer)  
- **Natural Language Processing**: SpaCy, Scikit-learn  

## Installation

To set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/HimaniLohia/movie-recommender-system
   ```

2. Navigate to the project directory:
   ```bash
   cd movie-recommender-system
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:
   ```bash
   python app.py
   ```

5. Open your browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

## Dataset

This project uses the **TMDB 5000 Movie Dataset**, which can be downloaded from [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).

Make sure to place the CSV files in the appropriate `/data/` directory before running the app.

## Future Enhancements

- Combine content-based and collaborative filtering to form a hybrid recommender.
- Use matrix factorization or deep learning (e.g., autoencoders) for better prediction accuracy.
- Deploy on Heroku, Render, or AWS for cloud access.

## Contribution

Contributions are welcome. To contribute:

1. Fork the repository.  
2. Create a new feature branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Added feature or fixed issue"
   ```
4. Push to your fork:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request explaining your changes.

## Contact

- **Name**: Himani Lohia  
- **Email**: himani99lohia@gmail.com  
- **LinkedIn**: https://www.linkedin.com/in/himanilohia/

---
