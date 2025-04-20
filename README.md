💬 ChatBot GPT
A FastAPI + OpenAI GPT-powered chatbot with a modular front-end design.

🌐 Live Demo: https://chat-bot-gpt-1.onrender.com

🧠 Features
FastAPI backend to process GPT requests

Jinja2-based HTML templates (layout.html, navbar.html)

CSS and JS are loaded from .txt files for simplicity

Deployed using Render

Easy to extend with image routes, authentication, or chat history

📁 Project Structure
graphql
Копіювати
Редагувати
chat-bot-gpt/
├── first.py                  # Main FastAPI app
├── requirements.txt          # Python dependencies
├── templates/                # HTML templates (Jinja2)
│   ├── home.html
│   ├── image.html
│   ├── layout.html
│   └── navbar.html
├── resources/                # JS and CSS code in .txt format
│   ├── css_code.txt
│   ├── final_js_code.txt
│   └── first_js_code.txt
└── .gitignore
🚀 How to Run Locally
1. Clone the repo
bash
Копіювати
Редагувати
git clone https://github.com/uliana0203/chat-bot-gpt.git
cd chat-bot-gpt
2. Create and activate virtual environment
bash
Копіювати
Редагувати
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies
bash
Копіювати
Редагувати
pip install -r requirements.txt
4. Set your OpenAI API key
In terminal or .env file:

bash
Копіювати
Редагувати
export OPENAI_API_KEY=your_key_here
5. Run the app
bash
Копіювати
Редагувати
uvicorn first:app --reload
Then open http://127.0.0.1:8000 in your browser.

🌍 Deployment
The app is deployed using Render.

🔗 Live version: https://chat-bot-gpt-1.onrender.com

📝 Notes
JS and CSS are stored in text files and dynamically injected

Layout uses partials (layout.html) for modular front-end design

Ideal for experimentation and rapid prototyping with GPT

