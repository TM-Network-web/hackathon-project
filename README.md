# hackathon-project
AI-powered code review web app built with Streamlit that scans repositories or single file and generates structured reviews using Groq or Ollama.

# AI Code Reviewer (Streamlit + Groq/Ollama)

A lightweight AI-powered code review tool built with **Streamlit** that scans Python repositories for common issues and then generates a detailed review using an LLM (Groq API or Ollama).

This project is designed to help developers quickly identify bad practices, security risks, and improvements in their codebase with both **static analysis** + **LLM-based feedback**.

---

## 🚀 Features

- Simple Streamlit UI
- Scan an entire local repository (recursive)
- Static analysis using Python AST
- Detects common issues like:
  - Long functions
  - Wildcard imports (`from x import *`)
  - Dangerous usage of `eval()` and `exec()`
  - Hardcoded passwords/secrets
- AI review modes:
  - **Junior Mode** (friendly + beginner explanation)
  - **Senior Mode** (strict production-level review)
- Supports two LLM providers:
  - **Groq API** (recommended for deployment)
  - **Ollama** (local LLM support)

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **AST Parsing (Static Analysis)**
- **Groq API (Llama Models)**
- **Ollama (DeepSeek Coder / Local Models)**
- **Requests (HTTP API calls)**

---

## 📂 Project Structure

