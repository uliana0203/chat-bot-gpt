# 💬 ChatBot GPT

A simple chatbot web app built using **FastAPI** and **OpenAI's GPT API**, with a clean modular structure and deployment on Render.

**🌐 Live Demo**: [https://chat-bot-gpt-1.onrender.com](https://chat-bot-gpt-1.onrender.com)

---

## 🧠 Features

- FastAPI backend to handle GPT queries  
- Modular Jinja2-based HTML templates  
- CSS and JavaScript are stored in `.txt` files and injected dynamically  
- Deployed on Render  
- Lightweight, easy to extend with new routes (e.g., image input, authentication)

---

## 📁 Project Structure

chat-bot-gpt/ ├── first.py # FastAPI application ├── requirements.txt # Python dependencies ├── templates/ # HTML templates (Jinja2) │ ├── home.html │ ├── image.html │ ├── layout.html │ └── navbar.html ├── resources/ # JS and CSS stored as .txt │ ├── css_code.txt │ ├── final_js_code.txt │ └── first_js_code.txt └── .gitignore

yaml
Копіювати
Редагувати

---

## 🚀 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/uliana0203/chat-bot-gpt.git
cd chat-bot-gpt
2. Create and activate a virtual environment
bash
Копіювати
Редагувати
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
3. Install dependencies
bash
Копіювати
Редагувати
pip install -r requirements.txt
4. Set your OpenAI API key
In your terminal or a .env file:

bash
Копіювати
Редагувати
export OPENAI_API_KEY=your_api_key_here
5. Run the app
bash
Копіювати
Редагувати
uvicorn first:app --reload
Open your browser and visit: http://127.0.0.1:8000

🌍 Deployment
This app is deployed using Render.

🔗 Live version: https://chat-bot-gpt-1.onrender.com

📝 Notes
JS and CSS are loaded from text files and injected into HTML dynamically

Layouts are managed using layout.html and partials for maintainability

Great for experimenting with GPT-based chatbot UIs

