# chatbot-clinica-sofia

# 🤖 ChatBot Clínica Sofia — AI Agent for Medical Clinics

An intelligent virtual assistant that handles patient inquiries, 
schedules appointments, and saves data automatically to Google Sheets — 
running 24/7 without human intervention.

## ✨ Features

- 💬 Natural conversation with memory (remembers context)
- 📅 Automatic appointment scheduling
- 📊 Real-time data saved to Google Sheets
- 🔄 Auto-retry on server errors (tenacity)
- 🏥 Custom personality per clinic (System Prompt)

## 🛠️ Built With

- Python
- Google Gemini API (gemini-3.6-flash)
- Google Sheets API (gspread)
- Google Cloud (Service Account)
- Tenacity (error handling)

## 🚀 How it Works

Patient sends message
│
▼
Sofia (AI) responds instantly
│
▼
If appointment confirmed → saves to Google Sheets
│
▼
Clinic owner sees all data in real time


## ⚙️ Setup

1. Clone this repo
2. Install dependencies:
   pip install google-genai gspread google-auth tenacity
3. Add your API keys:
   - GEMINI_API_KEY → Google AI Studio
   - Google Service Account JSON → Google Cloud Console
4. Run:
   python chatbot_clinica.py

## 📊 Demo Results

- ✅ Responds in natural Spanish 24/7
- ✅ Remembers patient name and context
- ✅ Auto-calculates service totals
- ✅ Saves appointments with timestamp

## 👩‍💻 Author
Angie — Industrial Engineer learning AI Development
Lima, Peru 🇵🇪
