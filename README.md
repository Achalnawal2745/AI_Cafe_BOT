# AI_Cafe_BOT
# ☕ Cafe Recommendation Chatbot using Sentiment Analysis & AI

This project builds a sentiment-aware chatbot assistant that can suggest cafes and answer user queries using a dataset of cafe attributes. It leverages machine learning (decision trees), natural language processing (TextBlob), and Google's Gemini generative AI model.

---

## 🚀 Features

- Analyze sentiment from customer reviews
- Train a Decision Tree model for polarity classification
- Use Gemini AI to answer **user queries based on real dataset**
- Support for questions like:
  - "Show cafes in Mumbai with vegetarian options"
  - "Which cafe has the best review?"
  - "What’s the rating and contact of Starbucks?"
- Chunked dataset feeding for large input handling

---

## 🧠 Technologies Used

- `Pandas` for data preprocessing
- `TextBlob` for sentiment analysis
- `scikit-learn` for classification (DecisionTree)
- `SMOTE` for balancing classes
- `Google Generative AI (Gemini)` for conversational intelligence

---

## 🗃️ Dataset Columns

- `cafes name`
- `Overall_Rating`
- `location`
- `Opening_Hours`
- `Cuisine`
- `Special_Features`
- `Dietary_Options`
- `Rate for two`
- `Review`
- `Contact_Number`

---
