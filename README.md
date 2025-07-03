# 📝 AI-Powered Student Profile Analyzer using RAG, LangChain & Gemini

Student Profile Analyzer is an intelligent web-based application that generates highly personalized and professional cover letters for students by analyzing their resumes. It leverages the power of Retrieval-Augmented Generation (RAG) with Google's Gemini LLM, LangChain framework, and FAISS vector search.

Users simply upload their student profile as a PDF, enter job-specific details like company name, address, and position — and the system generates a high-quality, customized cover letter in seconds. The generated letter is also available for download as a formatted PDF.

This project demonstrates the real-world use of LLMs integrated with vector databases, enabling contextual awareness and personalization by retrieving relevant data before generation — the core idea behind modern RAG pipelines.




**🚀 Key Features:**

📥 Upload your student resume as a PDF

🧠 Automatically analyze resume content using vector search

🔍 Retrieve the most relevant details from the resume for the current job

📝 Generate a customized cover letter with accurate, job-specific context

🌐 Use a beautiful web interface powered by Gradio

📄 Download the generated cover letter as a PDF

🔒 Secure API access using your Google Gemini API key



**🧠 Workflow Overview:**

1) Upload student PDF resume 📄

2) Resume is split into chunks 📚

3) Chunks are embedded into vectors 🔢

4) Vectors are stored in FAISS

5) Retriever pulls context based on student name 🔍

6) Prompt template is filled with this context and other inputs ✍️

7) Gemini LLM generates a full cover letter 💬

R) esult is displayed and downloadable as a PDF 📥



**🔗 Clone This Repository:**

git clone https://github.com/Adityahaha/Student-Profile-Analyzer-Cover-Letter-Generator.git
cd Student-Profile-Analyzer-Cover-Letter-Generator


