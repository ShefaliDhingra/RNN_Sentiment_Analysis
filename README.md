# RNN_Sentiment_Analysis

This project implements a **Recurrent Neural Network (RNN)** to classify airline-related tweets as **negative** or **non-negative (positive/neutral)** using Twitter data. The goal is to help airlines understand customer sentiment and improve service quality.

## 📌 Key Features
- **Sentiment Classification**: Categorizes tweets as negative or non-negative.
- **RNN with LSTM**: Leverages sequential dependencies for better text understanding.
- **Dataset**: 14,000 tweets from major U.S. airlines.
- **Performance**: Achieves **82.79% accuracy** on test data.

## 📂 Dataset
- **Source**: Twitter data from February 2015.
- **Labels**: Sentiment (Negative, Positive, Neutral).
- **Usage**: Binary classification (Negative vs. Non-Negative).

## Results
- **Test Loss**: 0.496  
- **Test Accuracy**: 82.79%  

## 📜 Insights
- Identifies key airline service issues (e.g., delays, cancellations).  
- Helps airlines track sentiment trends and improve customer experience.  
- Can be extended to real-time sentiment monitoring.  

## ⚡ Installation
```bash
git clone https://github.com/yourusername/airline-sentiment-analysis.git
cd airline-sentiment-analysis
pip install -r requirements.txt


