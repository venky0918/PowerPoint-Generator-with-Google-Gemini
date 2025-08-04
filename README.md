
# PowerPoint Generator with Google Gemini

This project demonstrates how to automatically generate PowerPoint presentations using **Google's Gemini AI**.  
The generator creates engaging and well-structured slides on any topic, making it useful for students, educators, and professionals.

---

## 🚀 Features
- Generate presentations on **any topic**.
- Choose the **number of slides** to create.
- Uses **Google Gemini API** for AI-powered slide content.
- Output is a formatted **PowerPoint (.pptx)** file.

---

## 🛠️ Requirements
- Python 3.8+
- Jupyter Notebook
- Dependencies:
  - `python-pptx`
  - `google-generativeai`
  - `dotenv`

---

## 🔑 Setup Gemini API Key
You need to obtain a Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey).

1. Create a `.env` file in your project root with:
   ```bash
   GEMINI_API_KEY=your_api_key_here
