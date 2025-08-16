# Email-Spam-Detection
This project implements an Email Spam Detection System using Natural Language Processing (NLP) and Machine Learning. The model classifies incoming emails as Spam or Ham (Not Spam) with high accuracy by analyzing text features.

# 🚀 Features

Preprocesses raw email text (cleaning, tokenization, stopword removal, stemming/lemmatization).

Converts text into numerical features using TF-IDF.

Trains a Logistic Regression model with hyperparameter tuning.

Achieves 99% accuracy on the test dataset.

Provides easy-to-use functions for real-time spam detection.

# 🛠️ Tech Stack

Language: Python

Libraries:

scikit-learn – ML algorithms & evaluation

pandas, numpy – data handling

nltk – NLP preprocessing

matplotlib, seaborn – visualization


# 📊 Dataset
Dataset used: Kaggle SMS Spam Collection / SpamAssassin (Emails.csv).

Columns:

label → spam / ham

message → email text

# ⚙️ Installation & Usage

Clone the repository

git clone https://github.com/your-username/email-spam-detection.git
cd email-spam-detection


Install dependencies

pip install -r requirements.txt


Run model training

python src/train_model.py


Test on a new email

python src/predict.py "Congratulations! You've won a free prize..."

