# 10-Agent Email Generation System with RAG

### 🚀 Overview
 
This system leverages a multi-agent architecture to intelligently generate high-quality, personalized emails across various use cases (business, marketing, support, etc.). It integrates LangChain, LangGraph, and OpenAI LLMs with a RAG-enhanced knowledge base to ensure contextual relevance, stylistic accuracy, and personalization.

### 🚀 Features

  🔟 Specialized AI agents for modular processing
  🧠 RAG-enhanced insights from email best practices
  🎯 Supports multiple email types (business, marketing, support, etc.)
  🧩 Personalized content based on recipient profile
  📊 Quality scoring and improvement suggestions
  🌐 Intuitive Gradio interface for easy interaction

### ⚙️ Installation & Setup

Install all required libraries:
```
pip install --upgrade langchain langchain-community langchain-openai langgraph
pip install --upgrade openai gradio pandas matplotlib seaborn faiss-cpu
pip install --upgrade pydantic typing-extensions datetime
pip install pandas==2.2.2

### 📦 Requirements

Python 3.9+
pip (latest version)

```
pip install --upgrade \
  langchain langchain-community langchain-openai langgraph \
  openai gradio pandas matplotlib seaborn faiss-cpu \
  pydantic typing-extensions datetime

pip install pandas==2.2.2
