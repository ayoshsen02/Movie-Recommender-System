# Movie Recommender System (AIML Project)
A content-based recommendation engine built using NLP (TF-IDF) and Cosine Similarity.

## 🧠 Architecture
This project uses a decoupled architecture to ensure scalability:
- **Backend:** FastAPI (Python) for processing AI logic and serving recommendations.
- **Frontend:** Streamlit for a responsive, user-friendly UI.
- **AI Engine:** Content-based filtering leveraging TF-IDF vectorization and Cosine Similarity.

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run Backend: `uvicorn main:app --reload`
4. Run Frontend: `streamlit run app.py`

## 📊 Methodology
We convert movie overviews into numerical vectors to calculate similarity scores between user-selected movies and our database.
