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

## ⚙️ Installation & Setup

Install all required libraries:
```
pip install --upgrade langchain langchain-community langchain-openai langgraph
pip install --upgrade openai gradio pandas matplotlib seaborn faiss-cpu
pip install --upgrade pydantic typing-extensions datetime
pip install pandas==2.2.2
```


### 📦 Requirements

Python 3.9+
pip (latest version)

## 📥 Installation

Run the following commands to install all required dependencies:

```
pip install --upgrade \
  langchain langchain-community langchain-openai langgraph \
  openai gradio pandas matplotlib seaborn faiss-cpu \
  pydantic typing-extensions datetime

pip install pandas==2.2.2
```
## 🔧 Setup

1. Clone the repository:
```
git clone https://github.com/your-org/email-gen-system.git
cd email-gen-system
```
2. Set your OpenAI API key:
```
import os
os.environ["OPENAI_API_KEY"] = "your-key-here"
```
3. Launch the system:
```
python main.py
```
## 🧠 System Architecture


All agents operate on a shared EmailState and are orchestrated using LangGraph.

## 🧩 RAG Knowledge Base
The system uses a FAISS-based vector database for retrieving:
 Subject line best practices
 Structure and flow patterns
 Personalization strategies
 Tone and emotional guidelines

## 🛠 Troubleshooting

| Problem              | Fix                                                   |
|----------------------|--------------------------------------------------------|
| `OpenAI key not found` | Ensure `OPENAI_API_KEY` is set in `os.environ`        |
| `Knowledge base empty` | Check if `_initialize_knowledge_base()` ran successfully |
| `Gradio not launching` | Update `gradio` to the latest version                |


