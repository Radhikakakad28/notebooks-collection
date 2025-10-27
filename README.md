📊 Dataset Details

MovieLens 100K dataset

100,000 ratings from 943 users on 1682 movies

Publicly provided by GroupLens

Dataset Info:
https://grouplens.org/datasets/movielens/

🛠 Installation and Setup

Install required libraries:

pip install tensorflow scikit-learn pandas numpy surprise
▶️ How to Run

Open the notebook in Google Colab

Run cells to load data, preprocess, train, and evaluate the model

Model will be saved as:

Movie_Recommendation_NCF.keras


You can load this model later to predict new recommendations

📈 Model Performance

Evaluation Metric: RMSE (Root Mean Squared Error)

Loss decreases as training progresses indicating learning

Provides top recommended movies for any selected user

🔍 Recommendation Example

Input: User ID
Output: Top N Movie Titles with predicted ratings

📦 Project Structure
├── notebook.ipynb
├── Movie_Recommendation_NCF.keras
├── README.md

🚀 Future Improvements

Integrate movie genres and metadata for hybrid recommendations

Deploy as a web or mobile application

Add user interface for real-time recommendations
