
🎬 Netflix Recommendation Engine using SVD
Welcome to my Netflix-style movie recommendation system!
This project uses Singular Value Decomposition (SVD) to predict how a user would rate unseen movies — and recommends the best ones based on those predictions.

📌 Overview
Movie recommendation systems are everywhere — Netflix, Amazon, YouTube, Spotify. This project dives into building one from scratch using a popular collaborative filtering technique: Matrix Factorization.

I built this project as part of an internship assignment to get hands-on with real-world recommendation systems.

🚀 What It Does
Predicts user-movie ratings using SVD

Recommends top N movies to a given user

Visualizes rating distributions and model performance

🔧 How It Works
Data Preprocessing
Loads user-movie ratings and converts them into a sparse matrix.

Matrix Factorization (SVD)
Decomposes the matrix into user and item latent factors.

Prediction
Reconstructs missing ratings using dot product of latent features.

Recommendation
For any user, it recommends the highest-rated movies they haven’t seen yet.

🧠 Tech Stack
Tool	Purpose
Python	Core programming language
NumPy, Pandas	Data processing
Scikit-learn / Surprise	Matrix factorization
Matplotlib, Seaborn	Visualizations

📁 Project Structure

netflix-recommender-svd/
│
├── data/             # Cleaned ratings & movie metadata
├── notebooks/        # EDA, training, evaluation notebooks
├── src/              # Python scripts (e.g., model, utils)
│
├── requirements.txt  # Python dependencies
├── .gitignore        # Files/folders to ignore
└── README.md         # You're reading it 🙂

📊 Key Highlights
Dataset: Based on MovieLens — includes user-movie rating history

Model: Trained with SVD via the Surprise library

Evaluation: Achieves ~0.87 RMSE on test data

Top-N Recommendations: Returns best movie picks for any user

Code Quality: Modular, notebook-driven, beginner-friendly

🧠 What I Learned
How collaborative filtering works in production systems

Implementing matrix factorization with real-world data

Building reusable machine learning pipelines

Evaluating recommender systems with metrics like RMSE

🧪 Sample Output
Top 5 Recommendations for User 123 (example):

🎞️ The Matrix (1999)

🥊 Fight Club (1999)

🌀 Inception (2010)

💼 Pulp Fiction (1994)

🧱 The Shawshank Redemption (1994)

Note: Recommendations depend on training split & user history

💻 Run It Yourself
If you want to try it out locally:

# Clone the repo
git clone https://github.com/Ayush120623/netflix-recommender-svd.git
cd netflix-recommender-svd

# Install dependencies
pip install -r requirements.txt

# Open notebooks and run cells
cd notebooks

👋 Connect

Want to chat, collaborate, or hire me?

📬 Email: ayushsharma.mee@gmail.com

💼 LinkedIn : www.linkedin.com/in/ayush-sharma-a975862b5

