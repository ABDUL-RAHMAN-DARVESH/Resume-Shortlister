# AI-Powered Resume Redaction Tool 🚀

This project is an **AI-powered tool** that processes resumes/PDF files and **removes personal information**. It uses **Flask** for the backend and **Streamlit** for the frontend. 📝🔒

## 🌟 Features
- 📂 **Upload resume/PDF files**
- 🤖 **AI-based personal information redaction**
- 🖥️ **User-friendly Streamlit interface**
- ⚙️ **Flask-powered backend processing**

## 🛠️ Technologies Used
- 🐍 **Python**
- 🌐 **Flask** (Backend API)
- 🎨 **Streamlit** (Frontend UI)
- 📄 **PDFPlumber / PyMuPDF** (Extract text from PDFs)
- 🧠 **NLTK / Spacy** (For text processing)

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 🏃‍♂️ Usage

1. **Start the Flask backend:**
   ```bash
   python app.py
   ```

2. **Run the Streamlit frontend:**
   ```bash
   streamlit run frontend.py
   ```

3. **Open the Streamlit app in your browser and upload a resume to test the redaction process.**

## 📂 Folder Structure
```
.
├── app.py          # Flask Backend
├── frontend.py     # Streamlit Frontend
├── requirements.txt
├── models/         # AI models & NLP processing
├── static/         # Static assets (if any)
├── templates/      # Frontend templates (if needed)
└── README.md
```

## 🔑 Setting Up Groq API Key

I can't provide my own API key, but I can guide you on how to set up your `.env` file properly for using **Groq API**. Here's how:

### 📌 Steps to Set Up Your `.env` File:
1. Create a new file named `.env` in your project directory.
2. Add the following content:

```
GROQ_API_KEY=your_api_key_here
```

3. Replace `your_api_key_here` with your actual API key.
4. Ensure your code loads environment variables using `dotenv` in Python.

💡 Need help integrating it? Let me know! 🤝

## 🤝 Contributing
Pull requests are welcome! If you want to make major changes, please open an issue first to discuss the improvements. 🚀

## 📜 License
This project is **licensed under the MIT License**.

🔖👨🏻‍💻 **Made By Abdul Rahman Darvesh ✨**

