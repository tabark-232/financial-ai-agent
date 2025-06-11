# financial-ai-agent
A hybrid AI agent that analyzes financial data from Google Drive using LLMs and RAG with LangChain.
# 📊 Smart Financial AI Agent

A hybrid AI agent for analyzing both internal financial documents and live market data using LangChain, RAG, and LLMs (GPT-3.5).  
This project automates financial insights generation by connecting directly to Google Drive and processing CSV/Excel files.

---

## 🧠 Project Overview

This intelligent agent is built to assist in financial decision-making by:

- Accessing financial data from Google Drive (e.g., reports, statements).
- Parsing and understanding structured (CSV/Excel) and unstructured data.
- Applying Retrieval-Augmented Generation (RAG) to answer complex financial questions.
- Leveraging LangChain to orchestrate tools and memory.
- Optionally incorporating real-time market data (e.g., stock prices, trends).

---

## 🚀 Features

- 📂 **Google Drive Integration**: Reads CSV/Excel files directly from Drive.
- 🧾 **Internal Data Analysis**: Extracts insights from uploaded financial data.
- 📉 **Stock Market Analysis** *(Optional)*: Retrieves and summarizes stock trends.
- 🤖 **RAG-Enhanced QA**: Uses vector search and LLMs for smart Q&A over data.
- 🔄 **Hybrid Agent Architecture**: Combines tools, memory, and logic flow with LangChain.

---

## 🛠️ Tech Stack

- **[LangChain](https://www.langchain.com/)** – Agent framework for LLM-powered workflows.
- **OpenAI GPT-3.5** – Language model for natural language understanding.
- **Google Drive API** – File access and management.
- **Pandas** – Data manipulation and analysis.
- **FAISS / ChromaDB** – Vector store for RAG.
- **Streamlit** *(optional)* – For building a simple UI.

---

## 📁 Project Structure


