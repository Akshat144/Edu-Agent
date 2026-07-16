# 🧠 EduAgent – Multi-Agent AI Learning Platform

EduAgent is an AI-powered learning platform that helps students prepare for academics, technical interviews, and HR interviews using specialized AI agents. Built with **Python** and **Streamlit**, it provides an interactive learning experience through a clean, modern interface.

---

# ✨ Features

- 🔍 AI-powered Research Assistant
- 💻 Technical Interview Practice
- 💼 HR Interview Simulation
- 📚 Personalized study guidance
- 🎨 Modern dark-themed interface
- ⚡ Fast and responsive Streamlit application

---

# 🤖 AI Agents

### 🔍 Research Agent
- Generates structured study notes
- Summarizes research topics
- Organizes information into easy-to-read formats

### 💻 Technical Interview Agent
- Simulates coding interviews
- Supports Python, Java, and core Computer Science subjects
- Provides interactive technical practice

### 💼 HR Interview Agent
- Conducts behavioral interview sessions
- Helps improve communication skills
- Gives feedback on interview responses

---

# 📁 Project Structure

```text
edu_agent/
│
├── assets/
│   ├── styles.css          # Custom CSS and UI styling
│   └── animations/         # UI animations and effects
│
├── agents/
│   ├── __init__.py
│   ├── researcher.py       # Research agent
│   ├── interviewer.py      # Technical interview agent
│   └── hr_bot.py           # HR interview agent
│
├── app.py                  # Streamlit application
├── README.md
└── requirements.txt
```

---

# 🛠 Requirements

- Python 3.10 or above
- Streamlit
- Required Python packages listed in `requirements.txt`

---

# 📦 Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd edu_agent
```

### 2. Create a virtual environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS / Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

Start the Streamlit server:

```bash
streamlit run app.py
```

Once the server starts, open the local URL displayed in your terminal (typically `http://localhost:8501`) in your browser.

---

# 🎨 User Interface

EduAgent features a clean and modern interface designed for an engaging learning experience.

### Design Highlights

- 🌙 Dark theme
- ✨ Custom CSS styling
- 💡 Animated glowing orb effects
- 📱 Responsive layout
- 📂 Sidebar navigation for switching between AI agents

---

# 🏗 Architecture

The project follows a modular architecture, separating each AI agent into its own module for easier maintenance and scalability.

```
User
   │
   ▼
Streamlit Interface
   │
   ├── Research Agent
   ├── Technical Interview Agent
   └── HR Interview Agent
```

---

# 📚 Tech Stack

- Python
- Streamlit
- Custom CSS
- AI Agent Architecture

---

# 🚀 Future Improvements

- Voice-based interview practice
- Progress tracking dashboard
- PDF study guide generation
- Conversation history
- Additional programming language support
- Performance analytics

---

# 📄 License

This project is intended for educational and learning purposes.

---

# ✅ Before Running

- [ ] Install all dependencies from `requirements.txt`
- [ ] Activate the virtual environment
- [ ] Run the application using `streamlit run app.py`
- [ ] Ensure all required agent files are present inside the `agents` folder
