# RAG-Based Chatbot for Pizza Shop Reviews

This project is an AI-powered chatbot built using **Retrieval-Augmented Generation (RAG)** architecture, designed to answer questions based on customer reviews from a pizza shop.

It leverages **Llama 3.2**, **ChromaDB** as a vector database, and **LangChain** to create an intelligent assistant capable of responding with contextually accurate information from real customer feedback.

---

## **Key Features**

 Uses **Llama 3.2** language model for natural language responses  
 Implements **ChromaDB** for vector storage and retrieval of review embeddings  
 Processes a **CSV file of pizza shop reviews** as the knowledge base  
 Interactive chatbot that answers questions grounded in the review data  
 Built using **LangChain** for seamless RAG integration  

---

##  **Tech Stack**

- Python
- LangChain
- ChromaDB
- Llama 3.2
- Streamlit (optional: if you’re using it for UI)

---

## **How it works**

1. Reads reviews from a CSV file
2. Converts reviews into embeddings and stores them in ChromaDB
3. When a user asks a question, retrieves relevant reviews
4. Passes retrieved content to Llama 3.2 for generating an informed response

---

## **Running the Project**

###  Install dependencies

pip install -r requirements.txt
