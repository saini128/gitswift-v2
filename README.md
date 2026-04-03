# 🚀 Gitswift v2

**Gitswift v2** is a high-performance, local-first CLI tool built in **Rust** that generates intelligent commit messages using tiny, quantized Large Language Models (LLMs).

Unlike its predecessor which relied on the Groq API, **v2 runs entirely on your local hardware**. This makes it the ideal choice for enterprise environments with strict data privacy policies or for developers who prefer to work offline without managing API keys.

---

## ✨ Key Features

* **🔒 Privacy First:** Your source code never leaves your machine. Designed for enterprise-grade security and air-gapped environments.
* **🔌 Zero Dependencies:** No internet connection or API keys (like Groq or OpenAI) required. Comes packed with a TinyLM model.
* **🦀 Built with Rust:** Blazing fast execution and memory safety.
* **🧠 Local Intelligence:** Powered by highly efficient, quantized models that run on standard CPUs.

---

## 🤖 Supported Models

The project focuses on "Tiny LLMs"—models with small parameter counts that punch way above their weight class:

| Model | Status | Notes |
| :--- | :--- | :--- |
| **Qwen2.5 (Quantized)** | 🧪 Testing | Primary model for development; excellent reasoning for its size. |
| **SmolLM2 (Quantized)** | 🧪 Testing | Evaluating for ultra-low resource environments. |
| **Llama 3.2 (1B)** | 📅 Roadmap | Planned for future benchmarking. |

---


## 🚀 Getting Started (Dev Phase)

> **Warning:** This project is currently in the **Development Phase**. APIs and model implementations are subject to change.

### Prerequisites
* [Rust](https://www.rust-lang.org/) (latest stable version)
* Git
* Python for notebook research and testing