# 🚀 UnityCopilot

> 🧠 Your AI Copilot for Unity Development — Built Right into the Editor

![MIT License](https://img.shields.io/badge/license-MIT-green)
![Unity](https://img.shields.io/badge/unity-2023%20LTS-blue)
![Status](https://img.shields.io/badge/status-Early%20Development-orange)

---

## 📚 Table of Contents

- [About](#-about)
- [Demo](#-demo)
- [Features](#-features)
- [Getting Started](#-getting-started)
- [Configuration](#-configuration)
- [Architecture](#-architecture)
- [Contributing](#-contributing)
- [License](#-license)
- [Stay Connected](#-stay-connected)

---

## 💡 About

**UnityCopilot** is an open-source AI assistant designed for Unity developers.
It integrates directly into the Unity Editor to help you:

* Generate scripts and logic via prompts
* Build scenes and connect components intelligently
* Audit your project and fix common issues
* Learn Unity concepts with explainable AI

> 🧑‍💻 Think of it as your **AI-powered senior dev sitting next to you**

---

## ✨ Features

<details>  
<summary>🧪 MVP Features</summary>  
<ul>  
<li>🧠 Prompt-based MonoBehaviour/script generation</li>  
<li>🧱 Prefab/Component placement from prompt</li>  
<li>🔍 Project audit: detect broken scripts, references</li>  
<li>🔌 Plug-and-play AI adapters (OpenAI, Claude, Gemini)</li>  
<li>🧰 Built with Unity 2023 LTS + UIToolkit Editor UI</li>  
</ul>  
</details>  

<details>  
<summary>🛠️ Upcoming Features</summary>  
<ul>  
<li>🎮 Guided scene assembly (e.g., Tower Defense builder)</li>  
<li>📐 Design pattern templates (Singleton, MVVM, etc.)</li>  
<li>🧪 Test stub generation</li>  
<li>🔁 Refactor + explain existing code</li>  
<li>📦 Unused asset detector</li>  
</ul>  
</details>  

---

## 🎬 Demo

<!-- Add screenshots or GIFs here when available -->
*Coming soon: Screenshots and demo videos of UnityCopilot in action*

---

## 🚀 Getting Started

### 📋 Prerequisites

- Unity 2023 LTS or later (Unity 6.x recommended)
- Git installed on your system
- Basic knowledge of Unity Editor

### 🧰 Installation

1. **Clone the repository:**
```bash
git clone https://github.com/GameDevKaran/UnityCopilot.git
cd UnityCopilot
```

2. **Open in Unity:**
   - Open Unity Hub
   - Click "Add" and select the cloned UnityCopilot folder
   - Open the project in Unity (the Unity project is named "UnityPilot")

3. **Access UnityCopilot:**
   - In Unity Editor, go to `Window > UnityPilot`
   - The UnityCopilot panel will open

4. **Start using:**
   - Enter a prompt like: *"Create a script that spawns a cube every 2 seconds"*
   - Watch UnityCopilot generate and apply the code!

---

## 🔑 Configuration

### AI Provider Setup (Coming Soon)

UnityCopilot will support multiple AI providers:

- **OpenAI GPT** (GPT-4, GPT-3.5)
- **Anthropic Claude**
- **Google Gemini**
- **Local models** (via Ollama)

Configuration will be available directly in the Unity Editor.

---

## 🧠 Architecture

<details>  
<summary>Click to Expand 🔍</summary>  

### 📁 Folder Structure

```
Assets/
└── UnityCopilot/
    └── Editor/
        ├── UI/         # Unity Editor window (UIToolkit)
        ├── Core/       # Prompt handler & templates
        ├── AI/         # OpenAI, Claude adapters
        ├── CodeGen/    # Script creation logic
        └── SceneTools/ # Prefab placement, audits
```

### 🔁 Data Flow

```
[UnityCopilot Window] → [Prompt Handler] → [AI Adapter] → [Code Generator] → [Scene Manager]
```

📄 See: `Docs/UnityCopilot_Design_Document.pdf`

</details>  

---

## 🤝 Contributing

We welcome contributions! UnityCopilot is currently under active development, but we're open to:

- 🐛 **Bug reports** - Help us identify and fix issues
- 💡 **Feature suggestions** - Share your ideas for new functionality  
- 📝 **Documentation** - Improve our guides and examples
- 🧪 **Testing** - Try out new features and provide feedback

### Getting Started with Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

💬 **Want to discuss ideas?** [Open a Discussion](https://github.com/GameDevKaran/UnityCopilot/discussions)

For more details, see our `CONTRIBUTING.md` (coming soon).

---

## ⚠️ Disclaimer

**UnityCopilot is in early development.** This is an active work-in-progress project. Current functionality is limited, and the codebase is evolving rapidly. Star ⭐ the repo to follow development progress!

---

## 📄 License

This project is licensed under the **MIT License**.
You're free to use, modify, and share — just credit the original authors.

---

## 🙌 Stay Connected

Follow updates and progress on:

* [GitHub Repository](https://github.com/GameDevKaran/UnityCopilot)
* [Discussions](https://github.com/GameDevKaran/UnityCopilot/discussions)

> Made with ❤️ for the Unity community 🚀


