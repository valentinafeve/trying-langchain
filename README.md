# 🎥 Ask Questions to Any YouTube Video Using RAG

This project demonstrates how to ask natural-language questions about the content of any YouTube video using Retrieval-Augmented Generation (RAG). We combine [LangChain](https://www.langchain.com/) and [Cohere](https://cohere.com/) embeddings to extract transcripts, perform semantic search, and generate answers based on the video.

## 🚀 Features

- ✅ Automatically extract subtitles or transcribe video audio using Whisper.
- ✅ Split and embed transcripts into vector representations.
- ✅ Retrieve the most relevant text chunk using semantic similarity.
- ✅ Generate an answer with a Large Language Model (LLM) based on the retrieved content.

## 📦 Requirements

- LangChain
- Cohere
- Chroma or another vector store
