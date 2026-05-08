# Tracking AI Trends Through NLP-Powered Text Mining and Knowledge Extraction

## Overview
End-to-end NLP project analyzing over 16,000 AI media articles to track emerging AI trends, extract knowledge, and build an 
intelligent Q&A system.

Completed as part of the Computational Language Technologies course at 
HSLU, in collaboration with Anacode GmbH and Google DeepMind.

## Project Stages

### Stage 1: Data Cleaning, Preprocessing & Exploratory Analysis
- Text cleaning, tokenization, lemmatization, stop word removal
- Temporal and sentiment analysis of AI media discourse
- Named entity recognition (NER) using spaCy / Hugging Face
- Knowledge graph construction using NetworkX
- Topic modeling with LDA / BERTopic

### Stage 2: Embedding Models & Fine-Tuning
- Classical embeddings: Word2Vec, FastText, Doc2Vec
- Fine-tuning compact open-source LLMs (TinyLlama, Qwen3, Gemma)
- Comparative evaluation on trend classification and sentiment detection

### Stage 3: RAG System for Question Answering
- Built a Retrieval-Augmented Generation (RAG) pipeline
- Integrated knowledge graph with text retrieval
- Evaluated text-only RAG vs. graph-augmented RAG
- 200–300 Q&A pairs across factual, analytical, and comparative categories

## Dataset
AI Media Dataset (publicly available on Kaggle):  
https://www.kaggle.com/datasets/jannalipenkova/ai-media-dataset

## Requirements
Python with: transformers, spaCy, gensim, networkx, 
bertopic, langchain, sentence-transformers

## Authors
Samuel Amuzu, Nick Schaufelberger, Julian Purtschert
