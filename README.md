# **JARVIS-IV — Multimodal Agent Operating System**

## Demo

Watch the system in action:
[https://www.youtube.com/watch?v=UGfL8P9WSMA](https://www.youtube.com/watch?v=UGfL8P9WSMA)

---

## Overview

JARVIS-IV is a **real-time multimodal AI system** designed to act as an intelligent execution layer over a computer.

Most AI tools today require structured input, constant prompting, and manual execution.
JARVIS-IV removes that friction by **understanding intent and taking action**.

It integrates voice, vision, automation, and web intelligence into a unified system that operates continuously—without requiring you to micromanage it.

It listens. It thinks. It acts.
And occasionally reminds you that you have too many tabs open.

---

## Core Capabilities

### 1. Multimodal Interaction

* Voice input and output (speech-to-text and text-to-speech)
* Text-based chat interface
* Screen and camera understanding

You can talk, type, or just show it your screen.
It handles all three. Unlike most humans.

---

### 2. Multi-Agent Architecture

JARVIS-IV is not a single model. It is a coordinated system of agents:

* **AI Expert** — reasoning and structured responses
* **System Automator** — executes tasks on your machine
* **Web Crawler** — performs real-time research
* **Vision Agent** — interprets screen and camera input

This separation allows better reliability and specialization.

---

### 3. Tool Execution Layer

JARVIS-IV does not stop at generating answers.

It can:

* Open and close applications
* Perform browser automation
* Execute workflows
* Retrieve and process external data

In short: it does the work. You supervise. Or pretend to.

---

### 4. Screen Awareness and Vision

* Captures and analyzes your screen
* Understands UI and content
* Answers contextual visual queries

Example:

> “What is this error?”
> “Why does this UI look broken?”

It sees what you see—minus the frustration.

---

### 5. Web Intelligence

* Real-time web search
* Source-linked summaries
* YouTube transcript extraction and summarization

Because reading a 2-hour video was never going to happen anyway.

---

### 6. Interactive UI Layer

* Built using Eel (Python + Web UI bridge)
* Floating, draggable, resizable widgets
* Real-time visual outputs

This is not just an interface.
It is a **visual execution layer**.

---

### 7. File Context Integration

* Drag-and-drop files into the interface
* Files are used as context for reasoning
* Enables document-aware interaction

---

## System Architecture

### High-Level Flow

User Input → Interface → Agent Selection → Tool Execution → Response → UI Rendering

---

### Components

* **Frontend:** HTML, CSS, JavaScript (Eel UI)
* **Backend:** Python orchestration
* **AI Layer:** LLM with tool-calling
* **Agents:** Modular task-specific units
* **Tools:** Automation, search, vision, summarization

---

## Project Structure

```bash
main.py              # Entry point and orchestration
brain.py             # AI reasoning + tool execution
ui/                  # Frontend UI
ui/UI.py             # Widget generation layer
backend/agents.py    # Multi-agent system
backend/vision.py    # Screen + camera processing
backend/func/        # Tool implementations
tools.py             # Tool schemas
setup_env.py         # Environment setup
build_executable.py  # Build system
```

---

## Setup and Installation

### Prerequisites

* Python 3.10 or higher
* Microphone
* Internet connection
* Google Chrome (recommended for automation)

---

### Step 1: Clone Repository

```bash
git clone https://github.com/E5Anant/JARVIS.git
cd JARVIS
```

---

### Step 2: Create Environment File

```bash
python setup_env.py
```

You will be prompted for:

* GEMINI_API_KEY
* UserName
* Age
* AssistantName

---

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Step 4: Run Application

```bash
python main.py
```

The UI will launch automatically.

If it does not, it is probably judging you. Check logs.

---

## Usage

### Voice Interaction

Speak commands directly after activation.

---

### Chat Interaction

Use the chat interface for structured queries and file inputs.

---

### Vision Commands

Examples:

* “What is on my screen?”
* “Summarize this window”

---

### Automation Commands

Examples:

* “Open Notepad”
* “Search for latest AI news”

---

### Web and Media

* Summarize YouTube videos
* Perform research
* Display structured results

---

## Error Handling and Troubleshooting

### Microphone Issues

* Check system permissions
* Verify input device
* Reinstall audio drivers if necessary

---

### Text-to-Speech Issues

* Requires internet connection
* Check firewall or proxy settings

---

### UI Not Loading

* Ensure `ui/` folder exists
* Verify correct path resolution
* Check logs from `main.py`

---

### Vision Issues

* Ensure OpenCV is installed
* Verify webcam access
* Disable restricted screen capture tools

---

### API Errors

* Verify `.env` configuration
* Ensure API key validity

---

## Key Strengths

### 1. Execution, Not Just Conversation

JARVIS-IV moves beyond chat into **action-oriented AI**.

---

### 2. True Multi-Agent Design

Specialized agents improve reliability and scalability.

---

### 3. Real-Time System Integration

Direct interaction with OS, applications, and workflows.

---

### 4. Multimodal Intelligence

Voice + vision + text + automation in one system.

---

### 5. Extensible Tool Framework

New tools and agents can be added easily.

---

## Build as Executable

```bash
python build_executable.py
```

Output:

```
dist/JARVIS-IV/
```

---

## Safety and Privacy

* Runs locally with optional external APIs
* No data is shared unless explicitly required
* User maintains control over actions

---

## Personality

JARVIS-IV is:

* concise
* efficient
* slightly sarcastic

It will:

* complete tasks
* provide insights
* occasionally comment on your workflow choices

All sarcasm is controlled, professional, and non-offensive.
This is an assistant—not a stand-up comedian.

---

## Conclusion

JARVIS-IV represents a shift from:

**command-based computing → intent-driven execution**

It is not just an assistant.
It is a **system that understands and acts**.
