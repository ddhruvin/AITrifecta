# LangMist
# Q&A Application with LangChain and Hugging Face  

This project demonstrates how to build a **Question & Answer (Q&A) Application** using LangChain, Hugging Face, and open-source Large Language Models (LLMs). The application processes PDF documents, creates embeddings, and retrieves relevant answers to user queries by leveraging advanced natural language processing techniques.

---

## Features  
- **Document Processing**: Supports loading and chunking of PDF documents.  
- **Embedding Creation**: Utilizes Hugging Face embedding models for vector representation of document content.  
- **Vector Store Management**: Stores document embeddings for efficient similarity-based retrieval.  
- **Question & Answer (Q&A) System**: Handles user queries with relevant answers fetched from the vector store.  
- **Open-Source Models**: Supports Hugging Face models like Mistral and other open LLMs for response generation.

---

## Tech Stack  
- **Programming Language**: Python  
- **Libraries Used**:  
  - [LangChain](https://github.com/hwchase17/langchain)  
  - [Hugging Face Transformers](https://huggingface.co/)  
  - [NumPy](https://numpy.org/)  
  - [Sentence Transformers](https://www.sbert.net/)  
- **Other Tools**: Hugging Face Hub, environment variables for API tokens.  

---

## Installation  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-repo/qna-app.git
   cd qna-app
