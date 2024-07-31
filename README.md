# Cosmsodbnosql-generative-AI-sampleAI

please find the architecture diagram 

be sure you execute 

![image](https://github.com/user-attachments/assets/806de3af-f2eb-4db4-a441-787adfd6f66b)


Features
Vector search using Azure Cosmos DB for NoSQL
Create embeddings using Azure OpenAI text-embedding

Requirements
Tested only with Python 3.11
Azure OpenAI account
Azure Cosmos DB for NoSQL account

Setup
Create virtual environment: python -m venv .venv
Activate virtual ennvironment: .venv\scripts\activate
Install required libraries: pip install -r requirements.txt
Copy .env.template to .env
Replace keys with your own values

Demo script
Open "cosmosddbnosql.ipynb.ipynb" python notebook
Run the cells to create the database (with vector support), create the container and populate the Cosmos DB database with different data 
The last cell launch Gradio UI 
