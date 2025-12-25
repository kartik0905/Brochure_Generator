# 📄 Sales Brochure Generator With OpenAI

![Gradio](https://img.shields.io/badge/Gradio-Interface-orange)
![OpenAI](https://img.shields.io/badge/OpenAI-Chat%20Completions-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🚀 Overview

The **Sales Brochure Generator** is an AI-powered application that automatically generates professional, persuasive sales brochures using the **OpenAI Chat Completions API**.  
It leverages **Gradio** to provide a clean and interactive web interface where users can input product or service details and instantly receive a well-structured brochure.

This project is ideal for marketers, startups, and businesses looking to quickly create high-quality promotional content.

---

## ✨ Features

- 🧠 AI-powered brochure generation using OpenAI
- 🎨 Clean and interactive UI built with Gradio
- ⚡ Instant text generation
- 📝 Customizable inputs (product name, description, target audience, tone, etc.)
- 📄 Generates ready-to-use sales copy

---

## 🛠️ Tech Stack

- **Python**
- **OpenAI Chat Completions API**
- **Gradio**
- **dotenv** (for environment variable management)

---

## 📂 Project Structure

```bash
├── app.py                # Main Gradio application
├── requirements.txt      # Project dependencies
├── .env.example          # Example environment variables
├── README.md             # Project documentation
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory and add your OpenAI API key:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

---

## ▶️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/sales-brochure-generator.git
   cd sales-brochure-generator
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

5. Open your browser and navigate to:
   ```
   http://127.0.0.1:7860
   ```

---

## 🧪 Example Use Case

- Enter your product name
- Describe the product or service
- Select tone (professional, friendly, persuasive)
- Click **Generate**
- Get a complete AI-generated sales brochure ✨

---

## 📌 Future Improvements

- 📥 Export brochure as PDF
- 🌐 Multi-language support
- 🎯 Advanced tone and audience targeting
- 💾 Save brochure history

---

## 🙌 Acknowledgements

- OpenAI for the powerful language models
- Gradio for the intuitive UI framework

---

### ⭐ If you like this project, consider giving it a star!
