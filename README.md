# XENOTRON: Revolutionary AI Training Platform

## 🚀 Overview

XENOTRON is a cutting-edge AI training platform that empowers users to create, train, and deploy their own intelligent AI assistants on any topic or problem domain. Unlike traditional AI tools that are limited to predefined functionalities, XENOTRON allows you to plug in your own API-based AI and teach it specialized knowledge—whether it's solving complex mathematical problems, mastering a new language, becoming an expert in quantum physics, or developing expertise in any field you choose.

## 🌟 Key Features

### 🧠 Self-Learning Capabilities
- **Learn from Internet Webpages**: Extract and assimilate knowledge from any webpage automatically
- **Guided Topic Learning**: Conduct focused research sessions on specific subjects
- **Thought Process Visualization**: Watch the AI's thinking, reasoning, and realizations in real-time
- **Emotional State Monitoring**: Observe the AI's emotional journey (curious, confused, satisfied, frustrated) during learning

### 🔧 Flexible Architecture
- **Plug-and-Play API Integration**: Connect any compatible AI API (NVIDIA, OpenRouter, Ollama, etc.)
- **Modular Tool-Based Architecture**: Extend functionality with custom tools
- **Backward Compatible Configuration**: Seamlessly upgrade from existing ULTRON setups
- **Environment Variable Configuration**: Easy setup with XENOTRON_* variables (with ULTRON_* fallback)

### 💾 Intelligent Knowledge Management
- **Persistent Knowledge Vault**: Store and retrieve learned information permanently
- **Training Store System**: JSONL-based knowledge persistence with scoring and recall
- **Knowledge Forgetting Mechanism**: Remove outdated or incorrect information
- **Profile & Voice Customization**: Define AI personality traits and communication style

### 📊 Advanced Monitoring & Visualization
- **Web-Based Admin Console**: Monitor learning sessions, thoughts, and emotions in real-time
- **Terminal Commands**: Powerful CLI interface for advanced users
- **Liquid Confidence Scoring**: Dynamic quality assessment of AI responses
- **Skills System**: Modular extensions for specialized capabilities

### ⚙️ Powerful Automation
- **Workflow Automation**: Create and execute complex action sequences
- **Window Management**: Control and automate desktop applications
- **Screen Capture & OCR**: Extract information from screenshots
- **Input Simulation**: Mouse clicks, keyboard typing, and hotkeys

## 🎯 Use Case:

Imagine you want to create an AI that excels at solving mathematical problems:

1. **Plug in Your Math API**: Connect XENOTRON to a mathematics-focused API (like Wolfram Alpha, Symbolab, or a custom math LLM)
2. **Teach Mathematical Concepts**: Guide the AI through learning sessions on:
   - Basic arithmetic and algebra
   - Calculus and differential equations
   - Linear algebra and matrix operations
   - Statistics and probability
   - Geometry and trigonometry
3. **Monitor Learning Process**: Watch as the AI develops understanding, shows confusion when encountering difficult concepts, and expresses satisfaction upon mastery
4. **Deploy Your Math Expert**: Use the trained AI to solve complex math problems with step-by-step explanations

The AI doesn't just memorize formulas—it develops genuine mathematical intuition through guided learning sessions, just like a human student.

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.10+
- API key from your preferred AI provider (NVIDIA, OpenRouter, or Ollama setup)
- Optional: pygetwindow, pyautogui, pytesseract for advanced automation features

### Key Commands
Available through the CLI interface:
- `/learn_web <topic>`: Learn from webpages on a topic
- `/learn_topic <topic>`: Guided learning session on specific subject
- `/show_thoughts`: Display recent AI thinking process
- `/show_emotions`: Display AI emotional state history
- `/remember <info>`: Store information in knowledge vault
- `/recall <query>`: Retrieve information from knowledge vault
- `/workflow <definition>`: Execute automated workflows

## 🏗️ Architecture

```
XENOTRON Platform
│
├── CLI Interface (jarvis.py)
│   ├── Command Processing
│   ├── Tool Execution System
│   └── Learning Engine Integration
│
├── Web Admin Console (server.py)
│   ├── Real-time Learning Monitoring
│   ├── Thought & Emotion Visualization
│   └── Knowledge Vault Browser
│
├── Core Systems
│   ├── LearningEngine: Guided learning sessions
│   ├── TrainingStore: Persistent knowledge storage
│   ├── WebExtractor: Intelligent content extraction
│   ├── LiquidSystem: Response quality scoring
│   └── AutomationController: Workflow & desktop automation
│
└── Extensibility Framework
    ├── Tool System: Add custom capabilities
    ├── Skills System: Modular feature extensions
    └── Plugin Architecture: Third-party integrations
```

## 🔄 How Learning Works

1. **Session Initiation**: User starts a learning session on a specific topic
2. **Research Phase**: AI extracts and analyzes relevant webpage content
3. **Processing Phase**: AI thinks through the information, forming connections and insights
4. **Emotional Tracking**: System monitors AI's cognitive-emotional state throughout
5. **Knowledge Storage**: Processed information is saved to the TrainingStore with metadata
6. **Application**: Learned knowledge is applied to future interactions and problem-solving




We welcome contributions from the community! Whether you want to:
- Add new tools or skills
- Improve the learning algorithms
- Enhance the visualization components
- Fix bugs or improve performance


XENOTRON is a research tool designed for educational and experimental purposes. While it implements advanced AI training techniques, users should validate outputs for critical applications. The platform is intended to augment human intelligence, not replace it.

---

**Ready to train your own AI genius?** Start your journey with XENOTRON today and build the intelligent assistant you've always envisioned!

*XENOTRON: Where Artificial Intelligence Meets Genuine Understanding*
