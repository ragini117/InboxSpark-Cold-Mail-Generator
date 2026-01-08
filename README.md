🚀 Cold Email Generator (LLM + Vector Search

This project is a Cold Email Generator built for service-based companies using Groq LLM, LangChain, Streamlit, and a Vector Database.
It automates the process of extracting job requirements from company career pages and generates highly personalized cold emails for business outreach.)
The system demonstrates how LLMs + semantic search can be used to match job requirements with relevant portfolio links and dynamically craft targeted emails.

✨ Features
🔗 Accepts a company careers page URL
🧠 LLM-powered job extraction from unstructured web pages
📄 Structured job data extraction in JSON format
🧩 Vector database for semantic similarity search
🔍 Intelligent retrieval of relevant portfolio/project links
✉️ Personalized cold email generation from a business development perspective
🖥️ Interactive Streamlit UI

🏗️ Architecture & Workflow Overview
🔄 System Flow
1️⃣ Career Page URL Input

Users provide a company’s careers page URL (e.g., Nike, Amazon, etc.).

2️⃣ Job Extraction (LLM-Powered)

The careers page content is parsed and analyzed using an LLM.

Job postings are extracted into a structured JSON format:

{
  "job_title": "",
  "skills": [],
  "experience": "",
  "job_description": ""
}

3️⃣ Vector Store Integration

Extracted job descriptions are converted into embeddings.

These embeddings are stored in a Vector Database.

Portfolio/project links are retrieved using semantic similarity search.

4️⃣ Cold Email Generation

Job details + matched portfolio links are passed to the LLM.

A highly personalized cold email is generated from a business development executive’s perspective.

🧠 Tech Stack

LLM: Groq

Framework: LangChain

Frontend: Streamlit

Vector Database: FAISS / Chroma (or equivalent)

Data Source: CSV-based portfolio links

Language: Python

⚠️ Important Note

The portfolio and project links used in this application are dummy/sample links.

These links are stored in a CSV file and ingested into the vector database.

For testing and demonstration purposes, the CSV currently contains my own portfolio links.

🔄 Real-World Production Usage

In a real-world setup, these dummy links would be replaced with:

✅ Actual company case studies

✅ Client project portfolios

✅ Service-specific landing pages
This implementation demonstrates how relevant portfolio links can be semantically matched with job descriptions and dynamically inserted into cold emails.

📊 Results:
<img width="1920" height="1020" alt="Screenshot 2026-01-08 132416" src="https://github.com/user-attachments/assets/4748cba6-09b2-40e8-a162-d134f00d075d" />


























