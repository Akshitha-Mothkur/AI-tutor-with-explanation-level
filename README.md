# 🎓 Advanced AI Tutor using Gemini API + Gradio

An interactive AI Tutor application built using Python, Google Gemini API, and Gradio.
Users can ask any question and control the explanation difficulty level using a slider — from beginner-friendly explanations to advanced expert-level responses.

---

# 🚀 Features

* 🤖 Powered by Gemini API
* 🎚️ Adjustable explanation levels
* ⚡ Real-time streaming responses
* 🌐 Simple Gradio web interface
* 🔐 Secure API key handling using `.env`

---

# 🛠️ Technologies Used

* Python
* Google Gemini API
* Gradio
* python-dotenv

---

# 📦 Installation

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/advanced-ai-tutor.git
cd advanced-ai-tutor
```

---

## 2. Install Dependencies

```bash
pip install -q -U google-genai
pip install python-dotenv
pip install gradio
```

Or create a `requirements.txt` file:

```txt
google-genai
python-dotenv
gradio
```

Then install:

```bash
pip install -r requirements.txt
```

---

# 🔑 Setup Gemini API Key

Generate an API key from Google AI Studio.

Create a `.env` file in the project folder:

```env
GEMINI_API_KEY=your_api_key_here
```

---

# ▶️ Run the Application

```bash
python app.py
```

The Gradio interface will launch in your browser.

---

# 🎚️ Explanation Levels

| Level | Explanation Style            |
| ----- | ---------------------------- |
| 1     | Like I'm 5 years old         |
| 2     | Like I'm 10 years old        |
| 3     | High school student          |
| 4     | College student              |
| 5     | Expert in the field          |
| 6     | Einstein PhD-level scientist |

---

# 📸 Project Preview

The application contains:

* Question input textbox
* Explanation level slider
* AI-generated streamed responses

---

# 📂 Project Structure

```bash
├── app.py
├── .env
├── requirements.txt
└── README.md
```

---

# 💡 Example Questions

* Explain Neural Networks
* What is Quantum Computing?
* Explain Recursion
* How does the Internet work?
* What is Machine Learning?

---

# 🌟 Future Improvements

* Chat history support
* Voice input/output
* Dark mode UI
* Multiple AI model selection
* PDF export of explanations

---

# 👩‍💻 Author

Developed by Akshitha

---
