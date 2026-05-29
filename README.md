# 🤖 CrewAI Software Engineering Team

## Summary

CrewAI Software Engineering Team is a multi-agent AI system that simulates a real-world software development workflow. Given a set of high-level requirements, the system automatically designs, develops, tests, and creates a frontend for a Python application using specialized AI agents.

The project demonstrates how autonomous AI agents can collaborate to perform software engineering tasks, including system design, backend implementation, frontend generation, and automated test creation.

---

## Features

* Multi-agent software development workflow using CrewAI
* Automated system design generation
* Python backend code generation
* Gradio frontend generation
* Automated unit test creation
* Sequential agent collaboration
* Modular and configurable architecture
* Powered by Groq LLMs
* YAML-based agent and task configuration

---

## Project Architecture

The project consists of four specialized AI agents:

### 1. Engineering Lead

**Responsibilities:**

* Analyzes project requirements
* Designs system architecture
* Defines classes and method signatures
* Creates implementation plans for developers

**Output:**

* Detailed design document

---

### 2. Backend Engineer

**Responsibilities:**

* Reads the design document
* Implements the complete Python backend module
* Generates production-ready code
* Follows the architecture defined by the Engineering Lead

**Output:**

* Python backend module

---

### 3. Frontend Engineer

**Responsibilities:**

* Creates a Gradio-based user interface
* Integrates with the generated backend
* Builds a simple demonstration application

**Output:**

* `app.py`

---

### 4. Test Engineer

**Responsibilities:**

* Creates unit tests for generated code
* Validates backend functionality
* Improves software reliability

**Output:**

* Automated test suite

---

## Workflow

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

## Project Structure

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

## Technologies Used

* CrewAI
* Groq LLM
* Python
* Gradio
* YAML Configuration
* Docker Safe Code Execution
* Unit Testing Frameworks

---


└── accounts_design.md
```

