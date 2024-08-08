# Movie-Recommender-System-Using-LLM 🎥 

This project leverages Large Language Models (LLMs) and vector stores to build a sophisticated movie recommender system. It provides personalized movie recommendations based on user preferences and historical data. 🌟

------------------------------------------------------------------------------------------------------------------------------------------------------------

## Architecture

```plaintext
Movies Dataset
  ├── 🎬 Title
  ├── 📝 Description
  ├── 📅 Release Date
  ├── 🎭 Cast
  ├── 🎞️ Genre
  ├── 🎬 Director
  └── 📦 Additional Attributes

       ↓

Convert Data into Vectors (Embeddings)
  ├── 📜 Create Textual Representations
  └── 🔢 Generate Embeddings 

       ↓

LLama -> FAISS (Vector Storage)
  └── 💾 Store Embeddings for Efficient Similarity Search

```


## Key Points 📌

1. **Load Data from Kaggle**
    - [Kaggle Movie Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
2. **Create Textual Representations** as per requirements.
3. **Generate Embeddings** using LLMs.
4. **Write and Load Index** with FAISS.
5. **Perform Similarity Search** for features like favorite movies.
6. **Create Prompt for Favorite Movie** embedding.
7. **Use Embeddings for Similarity Search**.


## Installation

- [Ollama](https://www.ollama.com/)
- [Kaggle](https://www.kaggle.com/)



## 💬 Feedback & Support

I'm always looking to improve! Share your thoughts and suggestions:

- **Email:** mansi.more943@gmail.com
- **GitHub:** [MansiMore99](https://github.com/MansiMore99)

## 📢 Contributing

Would you be interested in contributing? I welcome your improvements and ideas. You can Fork the repository, make changes, and submit a pull request!




<a href="https://www.linkedin.com/in/mansi-more-0943/"> ![LinkedIn Profile](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white) </a>
