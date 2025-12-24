# AI_Cafe_BOT
# ☕ Agentic RAG Cafe Recommendation Chatbot

This project builds an intelligent cafe recommendation chatbot using **Retrieval-Augmented Generation (RAG)** with vector search and AI. The system understands user queries, filters cafes intelligently, and provides personalized recommendations using Google's Gemini AI.

---

## 🚀 Features

- **Agentic RAG System**: Automatically understands query intent (recommendations, counting, filtering, general chat)
- **Semantic Search**: Uses FAISS vector database and sentence embeddings for intelligent cafe matching
- **Smart Filtering**: Automatically detects and applies filters (city, cuisine, ambiance, etc.)
- **Dynamic Retrieval**: Adapts the number of results based on query type
- **Conversational AI**: Powered by Google Gemini for natural language responses
- **Sentiment Analysis Model**: Optional Decision Tree classifier for review sentiment

---

## 🧠 Technologies Used

### RAG Chatbot (`rag_bot_agentic.ipynb`)
- `FAISS` for vector similarity search
- `Sentence-Transformers` for text embeddings (all-MiniLM-L6-v2)
- `Google Generative AI (Gemini)` for query understanding and response generation
- `Pandas` for data processing

### Sentiment Model (`Untitled5.ipynb`)
- `TextBlob` for sentiment analysis
- `scikit-learn` for Decision Tree classification
- `SMOTE` for class balancing

---

## 🛠️ Setup & Usage

### 1. Create a Virtual Environment (Recommended)
open terminal and run the following command:
```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# Mac/Linux
python3 -m venv venv
source venv/bin/activate
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Chatbot
-   Open `rag_bot_agentic.ipynb` in Jupyter Notebook/Lab.
-   Add your **Google Gemini API Key** in the setup cell.
-   Run all cells to start the Agentic RAG bot.

### 4. Train Sentiment Model (Optional)
-   Run `Untitled5.ipynb` to train the Decision Tree classifier.

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
