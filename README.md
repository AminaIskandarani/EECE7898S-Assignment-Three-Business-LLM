# EECE7898S-Assignment-Three-Business-LLM
readme = """# ☀️ SolarWave Energy Assistant

An agent-powered business chatbot built for the **C3 – Agent-Powered Business Assistant** assignment.

---

#Objective
SolarWave’s virtual assistant can:
- Answer customer questions about our solar products and services.
- Record customer leads (name, email, inquiry) to `customer_leads.json`.
- Log unanswered or off-topic questions as feedback in `customer_feedback.json`.
- Run using Google **Gemini 2.0 Flash** API inside a **Gradio** interface.

---

#Project Structure
business_bot/
├── me/
│ ├── about_business.pdf
│ └── business_summary.txt
├── business_agent.ipynb
├── app.py
├── requirements.txt
├── customer_leads.json
├── customer_feedback.json
└── README.md

---

# Setup Instructions (Colab or Local)

#Option 1 — Run in Google Colab
1. Upload all files or clone your GitHub repo.  
2. Run the notebook `business_agent.ipynb`.  
3. Set your Gemini API key:
   ```python
   import os
   os.environ["GOOGLE_API_KEY"] = "YOUR_GEMINI_KEY_HERE"
##option two: run locally

