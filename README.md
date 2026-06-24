# Azure_GenAI

# Azure GenAI Data Engineering Project

## Technologies Used

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Databricks
- PySpark
- HuggingFace
- LangChain
- FAISS
- Streamlit
- Power BI 


## Architecture

Source Files
      ↓
ADF
      ↓
ADLS Bronze
      ↓
Databricks + PySpark
      ↓
Silver Layer
      ↓
Gold Layer
      ↓
LangChain + FAISS
      ↓
OpenAI (Huggingface)
      ↓
Streamlit Chatbot
      ↓
Power BI

#Screenshots

ADF Pipeline
<img width="1107" height="511" alt="image" src="https://github.com/user-attachments/assets/b0e5963b-ad46-47ba-9f15-82987c6c3cab" />


ADLS Bronze Layer
<img width="870" height="435" alt="image" src="https://github.com/user-attachments/assets/f0de3630-6f6b-446c-a474-c1cf426d2acf" />


Databricks + PySpark
(Silver Layer and Gold Layer)

<img width="1312" height="798" alt="image" src="https://github.com/user-attachments/assets/22252c7f-6c91-4962-b19b-87b169cd2c0c" />
<img width="973" height="646" alt="image" src="https://github.com/user-attachments/assets/85907868-2d3f-4f0e-88ff-f61332c3b285" />
<img width="1273" height="658" alt="image" src="https://github.com/user-attachments/assets/2f9ef419-bf58-40b5-849b-01fc71e466eb" />
<img width="1158" height="670" alt="image" src="https://github.com/user-attachments/assets/664d33e2-a5ed-49b5-bde6-0a58118ccd37" />

RAG Pipeline

<img width="1378" height="706" alt="image" src="https://github.com/user-attachments/assets/fda9cfe8-175a-4703-847a-de958271c36f" />
<img width="1084" height="808" alt="image" src="https://github.com/user-attachments/assets/8792fc87-d9aa-43f9-9f43-e4af4a5bde61" />
<img width="1360" height="735" alt="image" src="https://github.com/user-attachments/assets/9095b110-bf1f-4be7-99a0-6877d586f7ab" />

Huggingface

<img width="1180" height="790" alt="image" src="https://github.com/user-attachments/assets/5004248c-b63e-4cc7-b228-d761cdd68e9d" />


Streamlit Chatbot

<img width="1279" height="706" alt="image" src="https://github.com/user-attachments/assets/3139f0f8-9cdf-4a58-b3e0-a78d33b3a231" />



Power BI Dashboard

<img width="1224" height="726" alt="image" src="https://github.com/user-attachments/assets/c7ef4b4a-775a-4733-9bcc-5b37d8bafb1b" />

## Features

- Automated ingestion using Azure Data Factory
- Bronze-Silver-Gold architecture
- Data cleaning and transformation using PySpark
- RAG-based question answering
- Vector search using FAISS
- AI chatbot using HuggingFace(opensource)

