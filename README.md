**🍽️ Zomato vs Swiggy Sentiment Analysis**
**📌 Project Overview**
This project analyzes user sentiments from social media (tweets) related to Zomato and Swiggy using Natural Language Processing (NLP) and Machine Learning.
The system classifies sentiments as Positive, Negative, or Neutral and compares both platforms based on user opinions.

**🎯 Objectives**
Analyze customer opinions about Zomato and Swiggy
Perform sentiment classification using ML models
Compare platform performance based on user feedback
Visualize insights for better understanding

**🛠️ Technologies Used**
Python
Pandas, NumPy
NLTK (VADER Sentiment Analysis)
Scikit-learn
Matplotlib / Seaborn
Streamlit (for UI)

**📂 Dataset**
Dataset contains tweets related to Zomato and Swiggy
Columns include:
tweetText
Sentiment labels (generated using VADER)

**⚙️ Project Workflow**
1. Data Collection
Dataset collected from social media platforms (Twitter/Kaggle)
2. Data Preprocessing
Remove URLs, mentions, hashtags
Convert text to lowercase
Remove punctuation
Clean unwanted spaces
3. Sentiment Analysis
Used VADER Sentiment Analyzer to assign sentiment scores
Categorized into:
Positive
Negative
Neutral
4. Feature Extraction
Used Bag of Words (CountVectorizer)
5. Model Training
Model used: Logistic Regression
Trained on cleaned tweet data
6. Evaluation
Accuracy score
Confusion matrix
Classification report

**📊 Results**
Successfully classified sentiments of tweets
Compared Zomato and Swiggy based on:
Positive feedback
Negative feedback
Provided insights into customer preferences

**💡 Key Features**
Text preprocessing pipeline
Sentiment classification model
Platform comparison (Zomato vs Swiggy)
Easy-to-use interface (Streamlit)

**▶️ How to Run the Project**
1.Clone the repository
git clone <your-repo-link>
2.Install dependencies
pip install -r requirements.txt
3.Run the application
streamlit run app.py

**📁 Project Structure**
├── app.py
├── model.pkl
├── vectorizer.pkl
├── dataset.csv
├── README.md

**🔮 Future Enhancements**
Use deep learning models (LSTM, BERT)
Real-time tweet analysis using API
Advanced dashboard with graphs
Multi-language sentiment analysis
Real-time tweet analysis using API
Advanced dashboard with graphs
Multi-language sentiment analysis
