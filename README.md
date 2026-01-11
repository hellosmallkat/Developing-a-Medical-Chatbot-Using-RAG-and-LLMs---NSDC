
# Developing a Medical Chatbot Using RAG and LLMs

**NLP & AI Project for Healthcare Applications**


This project focuses on building a **medical chatbot** step by step, using modern NLP techniques and Large Language Models (LLMs). The chatbot provides preliminary health guidance based on symptoms, helping users access medical information conveniently. **Important:** This is a learning project and **not a substitute for professional medical advice**.



## About This Project

Medical chatbots are transforming digital healthcare by offering **quick symptom checks and basic health guidance**. In this project, I progress through **three levels of complexity**:

1. **Rule-Based Chatbot** – maps keywords from user queries to known conditions using **cosine similarity**.
2. **Retrieval-Augmented Generation (RAG)** – leverages **vector embeddings** to retrieve relevant information from a knowledge base.
3. **Fine-Tuned LLM** – uses **LLaMA-2**, fine-tuned with PyTorch and Hugging Face Transformers, to understand **medical terminology** and provide tailored responses.


## Environment

* **Platform:** Kaggle
* **Frameworks & Libraries:** PyTorch, Hugging Face Transformers, NLP libraries

##  Dataset

**Predict Disease Symptom Dataset (Kaggle)**

The dataset contains:

* A list of diseases
* Associated symptoms
* Structured for training and testing medical chatbot responses


### Tools & Libraries

* Python 
* PyTorch
* Hugging Face Transformers
* NLP and text-processing libraries
* Kaggle Notebooks with GPU support


##  Project Milestones

### Milestone 1: Data Preprocessing

* Clean and preprocess the symptoms dataset
* Prepare data for chatbot training

### Milestone 2: Rule-Based Chatbot

* Build a simple chatbot using **cosine similarity**
* Map keywords to diseases

### Milestone 3: Embeddings + RAG

* Generate embeddings for the knowledge base
* Implement **RAG** to retrieve relevant information dynamically

### Milestone 4: Fine-Tuning LLMs

* Fine-tune **LLaMA-2** using **LoRA/QLoRA**
* Test chatbot responses with domain-specific medical knowledge

