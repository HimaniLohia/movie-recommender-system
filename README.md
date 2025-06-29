# movie-recommender-system
This repository contains a Movie Recommendation System project developed using Python and Flask. It leverages machine learning techniques to recommend movies based on user preferences and historical data.

# features
Content-Based Filtering: Recommends movies based on their metadata, such as genres, cast, crew, and descriptions.
Interactive Web Interface: Built using Flask, allowing users to search for movies and view personalized recommendations.
Machine Learning Workflow
Data Preprocessing:

Utilized the TMDB dataset from Kaggle, which includes rich metadata on movies.
Cleaned and preprocessed data to handle missing values, duplicates, and inconsistencies.
Parallelized preprocessing tasks using Pandarallel for improved efficiency.
Feature Engineering:

Extracted relevant features such as genres, keywords, and cast information.
Employed natural language processing (NLP) techniques to process textual data.
Employed SpaCy for advanced text cleaning.
Similarity Calculation:

Implemented K-Nearest Neighbors (KNN) and TF-IDF vectorization to measure the closeness of movie features.
Created a similarity matrix to efficiently retrieve recommendations.
Model Deployment:

Integrated the recommendation logic into a Flask web application.
Ensured scalable and efficient query handling for real-time recommendations.
Tools and Libraries Used
Programming Language: Python
Web Framework: Flask
Data Analysis: Pandas, Pandarallel, NumPy
Machine Learning: Scikit-learn (KNN, TF-IDF Vectorizer)
Natural Language Processing: SpaCy, Scikit-learn (TF-IDF Vectorizer)
Installation
Follow these steps to set up the project locally:

Clone the repository:

git clone https://github.com/HimaniLohia/movie-recommender-system
Navigate to the project directory:

cd movie-recommendation-system
Install the required dependencies:

pip install -r requirements.txt
Run the Flask application:

python app.py
Open your browser and go to http://127.0.0.1:5000/ to use the application.

Dataset
The project uses the TMDB dataset, which can be downloaded from Kaggle.

Ensure the dataset is placed in the appropriate directory (/data/) before running the application.

Future Enhancements
Integrate a hybrid recommendation system combining content-based and collaborative filtering.
Implement advanced techniques like Matrix Factorization or Deep Learning for improved recommendations.
Deploy the application on cloud platforms like AWS or Heroku for wider accessibility.
Contribution
Contributions are welcome! If you have ideas to improve the project or want to fix any issues, follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix:
git checkout -b feature-name
Commit your changes:
git commit -m "Description of changes"
Push to the branch:
git push origin feature-name
Submit a pull request detailing your changes.

Contact
If you have any questions or feedback, feel free to reach out:

Name: Himani Lohia
Email: himani99lohia@gmail.com
LinkedIn: https://www.linkedin.com/in/himanilohia/
