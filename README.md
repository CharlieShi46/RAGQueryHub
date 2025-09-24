# RAGQueryHub
🔎 A lightweight web app powered by LLM APIs with Retrieval-Augmented Generation (RAG), enabling users to query knowledge bases and get accurate, contextual answers.
# 📑 AI-Powered PDF Q&A Tool | AI智能PDF问答工具

This project is a **Streamlit web app** that enables users to upload PDF documents and interact with them using natural language.  
本项目是一个基于 **Streamlit** 的网页应用，用户可以上传 PDF 文档，并通过自然语言进行智能问答。

---

## 🚀 Features | 功能特点

- 📂 Upload a PDF file and ask questions directly  
  上传 PDF 文件并直接提问  
- 💬 Conversational memory to keep context across multiple questions  
  内置对话记忆，可在多轮问答中保留上下文  
- 🔎 Retrieval-Augmented Generation (RAG) with **FAISS** vector store  
  基于 **FAISS** 向量数据库的 RAG 技术  
- 🤖 Powered by **OpenAI GPT (ChatGPT API)**  
  基于 **OpenAI GPT (ChatGPT API)** 提供答案  
- 🖥️ Simple **Streamlit UI** for quick deployment  
  简洁的 **Streamlit 界面**，可快速部署使用  

---

## 🛠️ Installation | 安装步骤

1. Clone the repository  
   克隆仓库：
   ```bash
   git clone https://github.com/CharlieShi46/RAGQueryHub.git
   cd Agent-DataAnalysis

2. Install dependencies

   pip install -r requirements.txt

3. Run the Streamlit app

   streamlit run main.py


## 🔑 How to Use | 使用方法
	1.	Open the app in your browser (default: http://localhost:8501)
在浏览器中打开应用（默认：http://localhost:8501）
	2.	Enter your OpenAI API Key in the sidebar
在侧边栏输入你的 OpenAI API 密钥
	3.	Upload a PDF file
上传一个 PDF 文件
	4.	Ask questions in the input box
在输入框中提问
	5.	View answers and expand chat history to review past Q&A
查看答案，并可展开 历史消息 回顾之前的问答


## ⚠️ Notes | 注意事项
	•	You must have a valid OpenAI API Key
必须提供有效的 OpenAI API 密钥
	•	The app uses FAISS to store embeddings locally (in-memory)
本工具使用 FAISS 在本地存储向量（内存运行）
	•	Supports Chinese and English text in PDFs
支持中英文 PDF 文本处理


## 🌟 Example | 示例
<img width="1164" height="721" alt="Screenshot 2025-09-23 at 1 52 42 AM" src="https://github.com/user-attachments/assets/71e46f9f-544f-4d09-9ad4-51e11047632f" />
