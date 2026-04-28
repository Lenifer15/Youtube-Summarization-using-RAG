# 🎥 YouTube Summarization and Q&A with Granite, LangChain and RAG

## 📌 Project Overview
This project builds an intelligent system that can analyze YouTube videos, extract transcripts, and generate concise summaries along with accurate answers to user queries. It leverages Retrieval-Augmented Generation (RAG) to ensure responses are context-aware and grounded in the actual video content, using Granite LLM and LangChain for orchestration.

---
## 🚀 Features
- 🎯 Automatic YouTube transcript extraction
- 🧠 Context-aware summarization of long videos
- ❓ Interactive Q&A over video content
- ⚡ Fast semantic search using vector embeddings
- 🔍 Relevant chunk retrieval using FAISS
- 🔗 Modular pipeline with LangChain
- 🤖 Powered by Granite LLM

---
## 🧠 Technologies Used
- Python
- LangChain
- Granite (LLM)
- FAISS (Vector Store)
- YouTube Transcript API
- HuggingFace Embeddings

---
## ⚙️ How It Works
1. Extract transcript from a YouTube video.
2. Split transcript into smaller chunks.
3. Convert chunks into embeddings.
4. Store embeddings in FAISS vector database.
5. Retrieve relevant chunks based on user query.
6. Pass retrieved context to Granite LLM.
7. Generate summary or answer based on context.

---
## 🛠️ Installation
git clone https://github.com/your-username/youtube-rag.git  
cd youtube-rag  
pip install -r requirements.txt  

---
## ▶️ Usage
python app.py  

---
## 💡 Example
Input:  
"Summarize this video"  

Output:  
"A concise summary highlighting the key points discussed in the video."  

Input:  
"What is the main idea of the video?"  

Output:  
"The video explains the core concept of..."  

---
## 📁 Folder Structure
youtube-rag/
│── app.py
│── requirements.txt
│── utils/
│   ├── transcript.py
│   ├── embeddings.py
│   └── retriever.py
│── data/
│── README.md

---
## 🤝 Contributing
- Fork the repository
- Create a new branch
- Make your changes
- Submit a pull request

---
## Author
Jessica Lenifer R.
