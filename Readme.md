<h1>🧠 Question Paper Generator (Flask + Gemini AI)</h1>
<h2>📋 Overview</h2>

The Question Paper Generator is a Flask web application that automatically creates professional exam question papers using AI (Google Gemini API).
Users can upload study material (PDF, DOCX, or TXT) or paste text manually — the system then generates:

Multiple Choice Questions (MCQs)

Short Answer Questions

Long Answer Questions

Each question paper is generated in TXT and PDF formats with customizable exam details.

<h2>🧩 Tech Stack</h2>

Frontend: HTML and CSS

Backend: Python (Flask)

AI Model: Google Gemini 2.5 Pro (google-generativeai package)

PDF Creation: FPDF

Document Parsing: pdfplumber, python-docx

File Handling: Werkzeug
