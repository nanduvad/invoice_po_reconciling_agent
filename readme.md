🧾 Invoice-PO Reconciliation Agent
📘 Overview

The Invoice-PO Reconciliation Agent is an AI-powered tool that automatically compares Invoices and Purchase Orders (POs) to detect mismatches in fields like quantity, amount, item codes, and vendor details.
It uses OCR and Gemini AI to extract, analyze, and reconcile data from PDF documents efficiently — reducing manual effort and human error.

⚙️ Tech Stack

Backend: FastAPI (Python)

AI Model: Google Gemini API

OCR: PDFPlumber / PyMuPDF

Deployment: Uvicorn

🚀 Setup & Run Commands
1️⃣ Clone the Repository
git clone https://github.com/nanduvad/invoice_po_reconcile_agent.git
cd invoice-po-reconcile-agent

2️⃣ Create Virtual Environment
python -m venv .venv

3️⃣ Activate Environment

Windows

.venv\Scripts\activate

Mac/Linux

source .venv/bin/activate

4️⃣ Install Dependencies
pip install -r requirements.txt

5️⃣ Add Environment Variable

Create a .env file in the project root:

GEMINI_API_KEY=your_google_gemini_api_key

6️⃣ Run the FastAPI Server
uvicorn backend.main:app --reload

7.Run streamlit 
streamlit run frontend/app.py



Open in browser → http://127.0.0.1:8000
