# DocAiAgent

## 📌 Project Overview

**DocAiAgent** is an intelligent document-processing workflow designed and implemented during my internship at **CaptureDoc** (June 1, 2025 – August 1, 2025).

The project showcases the integration of **Artificial Intelligence within a low-code automation environment (n8n)** to analyze, classify, and extract structured metadata from documents automatically.

---

## 🚀 Objectives

- Automate end-to-end document processing
- Validate incoming files before analysis
- Extract text from various document formats
- Classify documents using an AI agent
- Extract relevant metadata based on predefined category rules
- Store results for traceability and auditing
- Detect anomalies and trigger automatic alerts

---

## 🧠 Workflow Architecture

The **DocAiAgent** workflow is built using **n8n** and includes the following stages:

1. **File Validation**  
   Ensures file type, format, and integrity before processing.

2. **Text Extraction**  
   Extracts textual content from documents (PDFs, scanned files, etc.).

3. **AI Agent – Document Classification & Metadata Extraction**  
   - Powered by **OpenAI models**
   - Automatically classifies document types
   - Extracts relevant metadata according to predefined category rules

4. **Prompt Engineering & Optimization**  
   - Design and refinement of prompts
   - Improved AI reasoning, classification accuracy, and metadata quality

5. **Metadata Storage**  
   - Structured metadata stored in **Airtable**
   - Enables traceability and process monitoring

6. **Conditional Logic & Alerts**  
   - Decision nodes to detect errors or inconsistencies
   - Automatic email notifications in case of anomalies or misclassification

---

## 🛠️ Technologies Used

- **n8n** – Low-code workflow automation
- **OpenAI API** – AI-powered document analysis
- **Airtable** – Metadata storage and tracking
- **Email Services** – Automated alerting
- **JSON** – Workflow export format

---

## 📂 Repository Content

- `DocAiAgent.json` – Exported n8n workflow containing the complete automation pipeline

---

## 🎯 Key Skills Demonstrated

- AI-driven document automation
- Low-code workflow design
- Prompt engineering and optimization
- Intelligent document classification
- Metadata extraction and validation
- Error handling and alerting mechanisms

---

## 🏢 Internship Context

This project was developed during an internship at **CaptureDoc**, a company specialized in:
- Digital transformation
- Document workflow digitization
- AI-powered process automation

---

## 👤 Author

**Sofia NOUREDDINE**  
Second-year Computer Science Student – USTHB (Algiers)  
AI & Automation Intern – CaptureDoc  

---

## 📄 Usage Notes

To run **DocAiAgent**:

1. Import the JSON workflow into **n8n**
2. Configure required credentials:
   - OpenAI API key
   - Airtable base and API token
   - Email service credentials
3. Customize document categories, rules, and prompts as needed
