# 🤖 Nestlé HR Chatbot

This is an offline chatbot that answers HR policy questions using a local AI model. It uses a PDF (Nestlé HR Policy) and a smart search engine to find the answer from the document.

---

## 📁 Project Files

- `Nesle_HR_Policy.ipynb`: The main notebook that runs the chatbot
- `the_nestle_hr_policy_pdf_2012.pdf`: The PDF file with company policies
- `.env`: HUGGINGFACEHUB_API_KEY=your_token_here 

---

## 🚀 How to Run

1. Clone or download the project.
2. Open the Jupyter notebook: `Nesle_HR_Policy.ipynb`
3. Follow the instructions in the notebook to:
   - Load the PDF
   - Ask your HR-related question

---

## 🔧 Setup

Install required packages using: 

```bash
pip install langchain faiss-cpu sentence-transformers transformers accelerate



