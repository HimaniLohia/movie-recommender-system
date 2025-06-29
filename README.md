Movie Recommendation System
This repository contains a Movie Recommendation System developed using Python and Flask, designed to provide personalized movie suggestions based on content similarity. It uses machine learning and NLP techniques to analyze movie metadata and recommend similar titles to users.

 Features
Content-Based Filtering: Recommends movies based on genres, cast, keywords, overview, and more.

Real-Time Web Interface: Built using Flask for an interactive movie search and recommendation experience.

Similarity Search: Uses text vectorization and KNN to find and rank similar movies.

Machine Learning Workflow
Data Preprocessing
Dataset Used: TMDB Movie Dataset (from Kaggle).

Cleaned null values, standardized movie metadata, removed duplicates.

Used Pandarallel for parallel processing to speed up data preparation.

Feature Engineering
Extracted important features like genres, keywords, cast, and crew.

Combined features into a single textual field.

Applied SpaCy and NLP techniques for advanced text cleaning and tokenization.

Similarity Calculation
Vectorized text data using TF-IDF.

Implemented K-Nearest Neighbors (KNN) to calculate movie similarity.

Created a similarity matrix for efficient recommendations.

Deployment
Integrated the model into a Flask web app.

Designed a clean UI for users to input a movie and receive top 5 recommendations instantly.

Tools and Technologies Used
Programming Language: Python

Web Framework: Flask

Libraries: Pandas, NumPy, Pandarallel, Scikit-learn, SpaCy

ML Techniques: TF-IDF Vectorizer, KNN Algorithm

Deployment: Flask-based Web App

How to Run the Project Locally
Clone the repository:

bash
Copy
Edit
git clone 
Navigate to the project directory:

bash
Copy
Edit
cd Movie-Recommender-System
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask application:

bash
Copy
Edit
python app.py
Open your browser and go to:
http://127.0.0.1:5000/ to start using the app.

Dataset
This project uses the TMDB 5000 Movie Dataset available on Kaggle.
Make sure to place the dataset inside the /data/ directory before running the app.

Future Enhancements
Integrate collaborative filtering or build a hybrid recommender system.

Use Matrix Factorization or deep learning models for improved personalization.

Deploy the app using Heroku, Render, or AWS EC2 for public access.

Contribution
Contributions are welcome! Here’s how to contribute:

Fork the repository.

Create a new branch:

bash
Copy
Edit
git checkout -b feature-branch
Make your changes and commit:

bash
Copy
Edit
git commit -m "Added new feature"
Push to your fork:

bash
Copy
Edit
git push origin feature-branch
Submit a pull request describing your changes.

📬 Contact
Name: Himani Lohia
Email: himani99lohia@gmail.com
LinkedIn: https://www.linkedin.com/in/himanilohia/

Thank you for exploring the Movie Recommendation System project!

