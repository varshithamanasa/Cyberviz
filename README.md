# Cyber-Vizard-AI (Open Source)

**An AI-driven framework for generating immersive 3D cybersecurity analytics and virtual reality training environments in WorldViz Vizard.**

---

## 🚀 Overview
**Cyber-Vizard-AI** is an open-source project dedicated to automating the creation of high-fidelity virtual reality (VR) spaces for cybersecurity operations and education. By leveraging **multi-agent Large Language Model (LLM) systems**, this framework generates interpretable Python code for **Vizard 8** and **SightLab**, transforming raw threat data into interactive 3D visualizations like helical network traffic maps and ransomware response simulators.

Research integrated into this project demonstrates that **Immersive Analytics (IA)** significantly scales cognitive capabilities, with VR-enhanced exercises showing a **4.7 vs. 4.1 Likert scale engagement** advantage over traditional tabletop methods.

---

## ✨ Core Features
*   **Automated SightLab Code Generation:** Dynamically script VR environments for participant tracking and data collection.
*   **VizardRAG Knowledge Base:** A specialized **Retrieval-Augmented Generation (RAG)** system built from Vizard and SightLab API documentation to ensure the production of executable, version-specific Python code.
*   **Multi-Agent Workflow:** Coordinates a squad of specialized AI agents:
    *   **Planner:** Decomposes complex cybersecurity scenarios into manageable 3D sub-tasks.
    *   **Retrieval:** Queries **VizardRAG** for precise API syntax and examples.
    *   **Coding:** Writes the functional Python/Vizard scripts (powered by models like Claude 3.7 Sonnet).
    *   **Critic & Verification:** Uses **Vision-Language Models (VLM)** to render the environment and automatically detect disconnected geometry or visual artifacts.
*   **Securing AI-Generated Code:** Integrates self-learning agents (Vulnerability Scanner, Red Teamer, and Patching Agent) to identify and fix flaws in generated scripts at machine speed.
*   **3D Helical Visualization:** Incorporates advanced **CyberCopter** topologies to highlight periodic patterns in malicious network traffic.

---

## 🛠 Technical Workflow
The project follows a rigorous four-phase procedure to move from raw data to a functional VR space:

1.  **Scenario Design:** Map **CISA Situation Manuals** (e.g., Ransomware Tabletop Exercises) into logical VR branching paths.
2.  **Dataset Injection:** Feed specialized datasets (e.g., malicious NetFlow traffic) into sequence models for text-domain symbolic encoding.
3.  **Model Fine-Tuning:** Utilize **QLoRA** and **Unsloth** to optimize small instruct models (like Llama 3.1 8B) for domain-specific code generation.
4.  **MAS Execution:** Coordinate the agent team to write, test, and refine the scripts in a shared code context.

---

## 📦 Requirements & Setup
*   **Platform:** WorldViz Vizard 8 / SightLab.
*   **Languages:** Python 3.x.
*   **AI Backend:** Compatible with OpenAI (GPT-4o), Anthropic (Claude 3.7), and local models via Unsloth/Hugging Face.
*   **Toolboxes:** Includes the `vexptoolbox` for behavioral experiment recording (eye/motion tracking).

---

## 🤝 Contributing
We welcome contributions from the VR, AI, and Cybersecurity communities! Specifically, we are looking for:
*   **API Expansion:** Adding documentation to the **VizardRAG** knowledge base.
*   **New Scenarios:** Contributing 3D visualization modules for DDoS, SQL injection, or insider threat detection.
*   **Agent Optimization:** Improving **Chain-of-Thought (CoT)** training for domain-specific code accuracy.
*   **VLM Refinement:** Enhancing the spatial awareness of visual critic agents.

*Please feel free to report bugs or submit feature suggestions via GitHub Issues or Pull Requests.*
