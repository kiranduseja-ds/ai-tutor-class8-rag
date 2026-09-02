# 📚 NCERT Class 8 Science AI Tutor

### Retrieval-Augmented Generation (RAG) Question Answering System

An AI-powered tutor that answers questions using the **NCERT Class 8 Science textbook** as its knowledge source.

## 🎯 Objective

The goal of this project is to build a RAG-based AI tutor that retrieves relevant textbook content before generating an answer.

This approach helps keep responses grounded in the provided NCERT content and reduces unsupported answers.

## 🔄 RAG Pipeline

```text
NCERT Science Corpus
        ↓
Data Cleaning & Preparation
        ↓
Text Chunking
        ↓
Sentence Embeddings
        ↓
FAISS Vector Index
        ↓
User Question
        ↓
Relevant Context Retrieval
        ↓
LLM
        ↓
AI Tutor Answer
```

## 🛠️ Technologies

* Python
* Jupyter Notebook
* Sentence Transformers
* FAISS
* Haystack
* Large Language Models (LLMs)
* Retrieval-Augmented Generation (RAG)
* NLP

## 📁 Files

| File                    | Description                                |
| ----------------------- | ------------------------------------------ |
| `ai_tutor_class8.ipynb` | Complete RAG implementation and evaluation |
| `class8_science.json`   | Cleaned NCERT Class 8 Science corpus       |

## 💡 Example Questions

The tutor is designed to handle questions such as:

* Why should we wash our hands frequently?
* What is photosynthesis?
* What are microorganisms?
* Why do some materials conduct electricity?
* What happens during combustion?

## 🧪 Evaluation

The notebook includes testing and evaluation of the retrieval and question-answering pipeline using predefined questions.

## 📌 Key Learning

This project demonstrates an end-to-end RAG workflow:

**Data Preparation → Embeddings → Vector Search → Retrieval → LLM Generation → Evaluation**

## 🚀 Future Improvements

* Streamlit web interface
* Conversational memory
* Hybrid search
* Improved evaluation metrics
* Source citations
* Deployment as an online AI tutor

## 👩‍💻 Author

**Kiran Duseja**

Aspiring Data Scientist | Generative AI | RAG | LLM Applications
