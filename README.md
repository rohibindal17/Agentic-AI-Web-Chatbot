# 🤖 Agentic AI Web Chatbot

An **Agentic AI powered web chatbot** that uses modern **LLM agent
frameworks** to reason, plan, and execute actions through external tools
in order to answer user queries.

Unlike traditional chatbots that simply generate responses, this system
demonstrates **Agentic AI workflows**, where the model dynamically
decides **how to solve a problem**, which **tools to use**, and how to
**retrieve external information** before producing a final answer.

This project showcases practical usage of **LLM agents, tool usage, and
web interfaces** for building intelligent AI assistants.

------------------------------------------------------------------------

# 🚀 Motivation

Large Language Models alone are powerful, but they often lack:

-   Access to **real-time information**
-   Ability to **perform external actions**
-   Structured **multi-step reasoning**

Agentic architectures solve this by enabling LLMs to:

1.  **Plan tasks**
2.  **Select tools**
3.  **Retrieve information**
4.  **Execute actions**
5.  **Generate final responses**

This repository demonstrates how to build such a system using modern AI
tooling.

------------------------------------------------------------------------

# ✨ Features

-   🧠 **Agentic reasoning workflow**
-   🌐 **Web-based chatbot interface**
-   🔎 **Tool-augmented LLM responses**
-   ⚡ **Real-time interaction**
-   🧩 **Modular architecture**
-   📦 **Easy setup and extensibility**
-   🔌 **API integration support**

------------------------------------------------------------------------

# 🏗 System Architecture

    User
     │
     ▼
    Web UI (Streamlit)
     │
     ▼
    Agent Controller
     │
     ├── LLM Model
     │
     ├── Tool Layer
     │   ├── Web Search
     │  
     │
     ▼
    Reasoning + Tool Execution
     │
     ▼
    Final Response
     │
     ▼
    Displayed to User

### Agent Workflow

1.  **User Query** enters the system\

2.  The **Agent analyzes the intent**\

3.  The Agent decides whether to:

    -   Answer directly
    -   Use a tool
    -   Retrieve information

4.  Tool outputs are fed back to the LLM\

5.  The LLM generates the **final response**

------------------------------------------------------------------------

# 🧠 Agentic AI Concept

Traditional chatbot:

    User → LLM → Response

Agentic chatbot:

    User
     ↓
    LLM Reasoning
     ↓
    Tool Selection
     ↓
    Information Retrieval
     ↓
    Final Response

------------------------------------------------------------------------

# 🛠 Tech Stack

### Programming Language

-   Python

### AI / LLM Frameworks

-   LangChain
-   OpenAI API or compatible LLM APIs

### Web Interface

-   Streamlit

### Supporting Libraries

-   dotenv
-   requests
-   JSON tools
-   agent orchestration utilities

------------------------------------------------------------------------

# ⚙️ Installation

### 1️⃣ Clone the repository

``` bash
git clone https://github.com/rohibindal17/Agentic_ai_web_chatbot.git
cd Agentic_ai_web_chatbot
```

### 2️⃣ Create a virtual environment

``` bash
python -m venv venv
```

Activate it:

Windows

    venv\Scripts\activate

Mac/Linux

    source venv/bin/activate

### 3️⃣ Install dependencies

``` bash
pip install -r requirements.txt
```

### 4️⃣ Configure environment variables

Create a `.env` file:

    OPENAI_API_KEY=your_api_key
    TAVILY_API_KEY=your_api_key

------------------------------------------------------------------------

# ▶️ Running the Application

Start the chatbot:

    streamlit run main.py

Then open:

    http://localhost:8501

------------------------------------------------------------------------

# 💬 Example Interaction

    User: What is the latest newsin the world?

------------------------------------------------------------------------

# 🔬 Use Cases

This system can be used for:

-   AI research prototypes
-   LLM agent experimentation
-   Conversational assistants
-   Knowledge retrieval systems
-   Educational AI tools

------------------------------------------------------------------------

# 🤝 Contributing

Contributions are welcome.

Steps:

1.  Fork the repository
2.  Create a branch

```{=html}
<!-- -->
```
    git checkout -b feature-name

3.  Commit changes

```{=html}
<!-- -->
```
    git commit -m "Add new feature"

4.  Push to GitHub
5.  Open a Pull Request

------------------------------------------------------------------------

# 📜 License

This project is licensed under the **MIT License**.

------------------------------------------------------------------------

# 👨‍💻 Author

**Rohi Bindal**

AI/ML Researcher\
MSc Machine Learning --- Stevens Institute of Technology

GitHub: https://github.com/rohibindal17

⭐ If you found this project helpful, please **star the repository**.
