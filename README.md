# Savage PR Reviewer 🤖🔥

## 🚀 Overview
Welcome to the **Savage PR Reviewer**! This is an AI-powered GitHub bot that doesn't just review your code; it roasts it mercilessly. Built for developers who can take a joke and want to improve their coding skills. 

When a Pull Request is opened, this bot analyzes the code changes, delivers a highly critical and sarcastic review, and then (because it's actually helpful) provides the perfect, clean, and optimized solution.

## ✨ Features
* **Automated Code Review:** Instantly triggers when a PR is opened or synchronized.
* **AI-Powered Roasting:** Uses Google's **Gemini 2.5 Flash** model for context-aware, savage feedback.
* **Redemption:** Always provides the correct and professional code fixes after destroying your ego.

## 🛠️ Tech Stack
* **Python 3**
* **FastAPI:** Lightning-fast framework to handle incoming Webhooks.
* **PyGithub:** Seamless integration with the GitHub API.
* **Google Generative AI:** The "brains" and the "attitude" behind the bot.
* **Uvicorn:** High-performance ASGI server.

## ⚙️ How it Works
1. A developer opens a Pull Request with potentially questionable code.
2. GitHub sends a Webhook payload to the FastAPI server.
3. The server extracts the patch/diffs and prompts the Gemini AI to act as a toxic, elite senior engineer.
4. The bot comments directly on the PR with its fiery review.

---
*Built with ❤️, Python, and a lot of sarcasm.*
