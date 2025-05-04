🏏 IPL Winning Prediction Model using Machine Learning

Welcome to the IPL Winning Prediction Model repository!

This project uses machine learning to predict the winning team of an IPL (Indian Premier League) match based on real-time inputs such as team names, venue, toss winner, and match conditions. The model is built and trained using Google Colab ☁️ and provides fast and fairly accurate predictions 🔮.

🔧 Tech Stack :

🐍 Python 3

📊 Pandas, NumPy

📈 Scikit-learn

📍 Matplotlib, Seaborn (for visualization)

🤖 Machine Learning Algorithms: Logistic Regression / Random Forest / XGBoost (depending on your implementation)

☁️ Google Colab (development environment)

📂 Project Structure :

python

Copy

Edit

📁 IPL-Winning-Prediction-ML

├── 📄 README.md

├── 📄 ipl_prediction.ipynb        ← Main Jupyter Notebook

├── 📄 dataset.csv                 ← IPL match data (cleaned & preprocessed)

├── 📁 assets                      ← (Optional) Plots or images used

└── 📄 requirements.txt            ← Dependencies

🧠 About the Model :

The model takes into account factors such as:

🏟️ Venue

🎲 Toss Winner & Decision

🏏 Teams Playing (Batting & Bowling)

🔢 Match statistics

It was trained on historical IPL data and aims to give a probability of each team winning. The model was evaluated using accuracy, confusion matrix, and cross-validation.

🚀 How to Run :

📁 Clone the repository

bash

Copy

Edit 

git clone https://github.com/NagatejaswiniSaparay34/IPL-Winning-Predictor/edit/main/README.md
cd IPL-Winning-Prediction-ML

🟢 Open in Google Colab

You can run the notebook directly in Google Colab:

✅ Run all cells to train the model and test predictions.

📷 Sample Prediction Output

python

Copy

Edit

Input    :      Team A vs Team B, Venue: Mumbai, Toss Winner: Team B, Decision: Bat

Output   :      🔮 Predicted Winner: Team A (Confidence: 65.3%)

📌 Requirements

Install all required packages using:

bash

Copy

Edit

pip install -r requirements.txt

Or manually in Colab:

python

Copy

Edit

!pip install pandas numpy matplotlib seaborn scikit-learn xgboost

sakareyprakash@gmail.com











