# RAG-based Knowledge Retrieval System

This project demonstrates a **Retrieval-Augmented Generation (RAG)** pipeline for accurate, context-aware question answering over custom knowledge bases.

## Overview

The system retrieves relevant documents using semantic search and combines them with an LLM to generate grounded responses, reducing hallucinations and improving answer quality.

## Key Features

- Text embedding generation using sentence transformers  
- Semantic search with vector databases (FAISS / Chroma)  
- Retrieval-Augmented Generation (RAG) workflow  
- LLM-powered question answering  
- End-to-end pipeline implemented in Python  

## Tech Stack

- Python  
- LangChain  
- Sentence Transformers  
- FAISS / Chroma  
- OpenAI / GPT-based LLMs  
- Jupyter Notebook  

## Workflow

1. Ingest and preprocess documents  
2. Generate embeddings  
3. Store embeddings in a vector database  
4. Retrieve top-k relevant chunks  
5. Pass retrieved context to the LLM for response generation  

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/moatazsaad/LLM_Engineering_Portfolio.git
````

2. Navigate to the RAG project folder:

   ```bash
   cd "RAG-based Knowledge Retrieval System"
   ```

3. Install dependencies from the local `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebook:

   ```bash
   jupyter notebook "RAG-based Knowledge Retrieval System.ipynb"
   ```

5. Add your documents to the `knowledge-base` folder.

6. Run the notebook cells to:

   * Generate embeddings
   * Store them in the vector database
   * Query the system with natural language questions

## Use Cases

* Knowledge base Q&A
* Document search and summarization
* Enterprise and internal data assistants
