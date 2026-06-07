⚖️ AI Law & Society Chatbot
📌 Overview

The AI Law & Society Chatbot is a Streamlit-based intelligent assistant that provides easy-to-understand legal awareness information using the Groq LLM API. It helps users learn about Indian laws, rights, and social/legal issues in a simple conversational format.

The chatbot is designed for educational and awareness purposes only, making legal knowledge more accessible to everyone.

🚀 Features
💬 AI-powered legal Q&A chatbot (Groq LLaMA 3.1 model)
⚖️ Covers Indian law, cybercrime, FIR process, consumer rights, women rights, etc.
📊 Multiple response modes:
Short
Medium
Detailed
Extra Detailed
📑 Auto-formatted responses:
Tables for comparisons
Step-by-step instructions
Bullet points & headings
💾 Chat history saved using SQLite database
🗂 View / delete individual chat history
🧹 Delete all chat history option
🎨 Clean Streamlit UI with sidebar controls
🔐 Secure API key handling using .env
🏗️ Tech Stack
🐍 Python
🎈 Streamlit (Frontend UI)
🧠 Groq API (LLaMA 3.1 8B Instant Model)
🗄 SQLite (Database for chat history)
🔑 python-dotenv (Environment variable management)
📂 Project Structure
law-awareness-chatbot/
│
├── app.py                # Main Streamlit application
├── chat_history.db       # SQLite database (auto-created)
├── api.env               # Environment variables (GROQ_API_KEY)
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/law-awareness-chatbot.git
cd law-awareness-chatbot
2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Setup Environment Variables

Create a file named:

api.env

Add your Groq API key:

GROQ_API_KEY=your_api_key_here
▶️ Run the Application
streamlit run app.py

Then open in browser:

http://localhost:8501
💡 Example Questions

You can ask:

What is FIR and how to file it?
What are women’s rights in India?
Explain cybercrime laws
Difference between IPC sections 302 and 304
How to file a consumer complaint?
Traffic rules and penalties in India
🧠 How It Works
User enters a legal question in chat
Prompt is sent to Groq LLaMA 3.1 model
System instructions ensure:
Simple language
Structured formatting
Tables for comparisons
Step-by-step responses when needed
Response is displayed in Streamlit UI
Chat is saved in SQLite database
🗃 Chat History System
All conversations are stored in chat_history.db
Sidebar allows:
Viewing past chats
Deleting individual chats
Deleting all chats
⚠️ Disclaimer

This chatbot is built for educational and informational purposes only.

❌ It does NOT provide official legal advice
❌ It should NOT be used as a substitute for a lawyer
✔ Always consult a qualified legal professional for real cases

📈 Future Improvements
🌐 Multilingual support (Hindi + regional languages)
📱 Mobile-friendly UI
🔊 Voice-based chatbot
📚 Integration with Indian legal database (IPC/CrPC/Rights)
🧾 PDF export of chat history
🔍 Semantic search over legal documents (RAG system)
🤝 Contributing

Contributions are welcome!

Steps:

Fork the repository
Create a new branch
Make changes
Submit a pull request
📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Developed as an AI-powered legal awareness project using Streamlit + Groq API.
