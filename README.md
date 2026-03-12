# AI Resume Analyzer

## 📌 Project Overview

AI Resume Analyzer is a simple **Generative AI web application** that analyzes a candidate’s resume and provides intelligent feedback.
The user uploads a resume in **PDF format**, and the application uses a **Large Language Model (LLM)** to evaluate the resume and generate insights such as detected skills, missing skills, improvement suggestions, and an overall score.

This project demonstrates how **Generative AI can be integrated with a web interface to analyze real-world documents**.

---

## 🚀 Features

* Upload resume in **PDF format**
* Extract text from resume
* AI-powered resume analysis
* Identify **skills present in the resume**
* Suggest **missing or important skills**
* Provide **resume improvement recommendations**
* Generate an **overall resume score**

---

## 🛠️ Tech Stack

* **Python**
* Gradio – for building the web interface
* PyPDF – for extracting text from PDF files
* Groq – for running the Large Language Model
* **dotenv** – for managing API keys securely

---

## 🧠 How It Works

1. User uploads a **resume PDF**.
2. The system extracts the text from the PDF.
3. The extracted resume text is sent to an **LLM prompt**.
4. The AI model analyzes the resume and generates:

   * Skills detected
   * Missing skills
   * Suggestions for improvement
   * Resume score
5. The results are displayed in the **Gradio interface**.

