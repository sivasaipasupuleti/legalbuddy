# LegalBuddy:- An AI-Powered Legal Assistant

# 🧠 LegalBuddy: AI-Powered Legal Assistant

LegalBuddy is a full-stack AI/ML-based LegalTech application that assists users by retrieving relevant legal information, case references, and simplified legal insights using **RAG (Retrieval-Augmented Generation)** and **Gemini LLM APIs**.

This project uses:
- 💻 **Frontend**: React + Vite  
- 🌐 **Backend**: Node.js  
- 🧠 **AI Layer**: Python (for RAG services) + Gemini APIs (Google Generative AI)  
- 🧾 **Domain**: LegalTech (Legal AI Assistant)

---

## 🚀 Features

- 🔍 Ask legal queries in plain English
- 🧠 RAG-powered legal document retrieval and summarization
- 🌐 Gemini LLM API integration
- 🗣️ Multilingual response support (optional)
- 📄 Generates legal summaries, affidavits, judgments, and case insights
- ⚙️ Full-stack integration with modern tech stack

---

## 🧰 Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | React + Vite       |
| Backend      | Node.js (Express)  |
| AI Services  | Python (RAG)       |
| LLM          | Gemini API (x2 Keys) |
| Styling      | Tailwind CSS / Custom CSS |

---

# 🛠️ Installation & Setup

## 1. Clone the Repository
```bash
git clone https://github.com/your-username/legalbuddy.git
cd legalbuddy
```

## 2. Install Frontend Dependencies
```bash
cd client  # or your frontend folder
npm install
npm run dev
```

## 3. Install Backend Dependencies
```bash
cd ../server  # or your backend folder
npm install
npm start
```

## 4. Install Python RAG Services
```bash
cd ../rag-services
pip install -r requirements.txt
python app.py
```

## 5. ✅ Set Environment Variables

### Python `.env` file (in rag-services folder)
```env
GEMINI_API_KEY_1=your-gemini-api-key
GEMINI_API_KEY_2=your-second-gemini-api-key
```

### Node.js `.env` file (in server folder)
```env
PORT=5000
```
