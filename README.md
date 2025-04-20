💬 ChatBot GPT

A FastAPI + OpenAI GPT-powered chatbot web app with modular design and clean deployment.

🔗 Live Demo: https://chat-bot-gpt-1.onrender.com

🧠 Features
🧾 FastAPI backend to handle GPT queries

🧱 Modular HTML templates via Jinja2 (layout.html, navbar.html)

💅 CSS and JS loaded from .txt files in /resources

🌐 Deployed on Render and publicly accessible

🧩 Easy to extend with new input types or routes

🗂 Project Structure

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
git clone https://github.com/uliana0203/chat-bot-gpt.git
cd chat-bot-gpt

2. Create and activate virtual environment
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate

3. Install requirements
bash
Копіювати
Редагувати
pip install -r requirements.txt
4. Set OpenAI API key
Add to terminal or create .env file:

bash
Копіювати
Редагувати
export OPENAI_API_KEY=your_key_here
5. Launch the app
bash
Копіювати
Редагувати
uvicorn first:app --reload
Then go to: http://127.0.0.1:8000

📦 Deployment
This app is deployed on Render:

👉 Try it now: https://chat-bot-gpt-1.onrender.com

📌 Notes
JS and CSS are stored in text files and dynamically injected

Layout uses layout.html + partials for clean separation of structure

Designed for experimentation and rapid prototyping with GPT

