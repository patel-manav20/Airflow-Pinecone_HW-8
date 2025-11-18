# Airflow + Pinecone Project (Homework 8)

A short overview of the class assignment — running a **Pinecone job as an Airflow DAG**.

---

## Goal

Build an **Airflow pipeline** that:
1. Downloads and preprocesses the Medium dataset  
2. Creates a **Pinecone** index  
3. Generates embeddings using **Sentence-Transformers**  
4. Uploads the embeddings to Pinecone  
5. Performs a semantic search query  

---

### Modify docker-compose.yaml 
Add the following packages in `_PIP_ADDITIONAL_REQUIREMENTS`:

<img width="938" height="290" alt="image" src="https://github.com/user-attachments/assets/24a5dd66-b510-448f-8767-9ba517bdf48f" />

