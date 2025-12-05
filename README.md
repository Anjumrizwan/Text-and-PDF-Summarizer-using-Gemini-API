Text-and-PDF-Summarizer-using-Gemini-API

Developed a Streamlit web application that automatically summarizes both uploaded PDF files and raw text inputs using Google’s Gemini generative AI. Implemented PDF text extraction with PyPDF2 and integrated Gemini’s API for concise, context-aware summarization. Enhanced user interaction with a simple and responsive web interface

🚀 Features

✅ Upload and summarize PDF files

✅ Paste and summarize raw text

✅ Powered by Google Gemini AI

✅ Simple and interactive Streamlit UI

✅ Fast and accurate summaries

✅ Secure API key handling with .env

🛠️ TECH STACK

✅ Python

✅ Streamlit – for frontend UI

✅ PyPDF2 – for PDF text extraction

✅ Google Generative AI (Gemini API) – for AI summarization

✅ python-dotenv – for environment variable management

📂 Project Structure

Text-Summarizer/

│

├── text.py          # Main Streamlit application

├── .env             # Stores API Key 

└── README.md


🔑 Setup Instructions (Mac & Windows)

1️⃣ Clone the Repository

git clone https://github.com/your-username/text-summarizer.git

cd text-summarizer


2️⃣ Install Dependencies

pip install streamlit PyPDF2 google-generativeai python-dotenv



3️⃣ Setup Gemini API Key

Create a .env file in the project root:


GOOGLE_API_KEY=your_api_key_here



⚠️ Never upload .env to GitHub


4️⃣ Run the Application

streamlit run text.py


App will run at:

http://localhost:8501

