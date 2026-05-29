# 🤖 CrewAI Software Engineering Team

## 📖 Summary

CrewAI Software Engineering Team is a multi-agent AI system that simulates a real-world software development workflow. Given a set of high-level requirements, the system automatically designs, develops, tests, and creates a frontend for a Python application using specialized AI agents.

This project demonstrates how autonomous AI agents can collaborate to perform software engineering tasks, including system design, backend implementation, frontend generation, and automated test creation.

---

## ✨ Features

* 🤝 Multi-agent software development workflow using CrewAI
* 🏗️ Automated system design generation
* 🐍 Python backend code generation
* 🎨 Gradio frontend generation
* ✅ Automated unit test creation
* 🔄 Sequential agent collaboration
* ⚙️ Modular and configurable architecture
* 🚀 Powered by Groq LLMs
* 📄 YAML-based agent and task configuration

---

## 🏛️ Project Architecture

The project consists of four specialized AI agents working together as a software engineering team.

### 👨‍💼 Engineering Lead

**Responsibilities**

* Analyze project requirements
* Design system architecture
* Define classes and method signatures
* Create implementation plans for developers

**Output**

* Detailed design document

---

### 👨‍💻 Backend Engineer

**Responsibilities**

* Read the design document
* Implement the complete Python backend module
* Generate production-ready code
* Follow the architecture defined by the Engineering Lead

**Output**

* Python backend module

---

### 🎨 Frontend Engineer

**Responsibilities**

* Create a Gradio-based user interface
* Integrate with the generated backend
* Build a simple demonstration application

**Output**

* `app.py`

---

### 🧪 Test Engineer

**Responsibilities**

* Create unit tests for generated code
* Validate backend functionality
* Improve software reliability

**Output**

* Automated test suite

---

## 🔄 Workflow

```text
User Requirements
        │
        ▼
Engineering Lead
(System Design)
        │
        ▼
Backend Engineer
(Python Module)
        │
        ├──────────► Frontend Engineer
        │              (Gradio UI)
        │
        ▼
Test Engineer
(Unit Tests)
        │
        ▼
Generated Project Files
```

---

## 🔐 Environment Variables

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_api_key_here
```

Optional:

```env
CREWAI_TRACING_ENABLED=true
```

---

## 📁 Project Structure

```text
engineering_team/
│
├── src/
│   └── engineering_team/
│       ├── config/
│       │   ├── agents.yaml
│       │   └── tasks.yaml
│       │
│       ├── crew.py
│       └── main.py
│
├── output/
│   ├── accounts.py
│   ├── app.py
│   ├── test_accounts.py
│   └── accounts_design.md
│
├── .env
├── pyproject.toml
├── README.md
└── requirements.txt
```

---

## 🛠️ Technologies Used

* CrewAI
* Groq LLM
* Python
* Gradio
* YAML Configuration
* Docker Safe Code Execution
* Pytest / Unit Testing Frameworks

---


### Configure Environment Variables

Create a `.env` file and add your Groq API key.


## 🎯 Generated Output

Example generated files:

```text
output/
├── accounts.py
├── app.py
├── test_accounts.py
└── accounts_design.md
```


