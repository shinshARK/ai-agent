# AI Agent in Python (Boot.dev Guided Project Course)

This project is a guided implementation of an AI agent, following the curriculum from the **[Build an AI Agent course on Boot.dev](https://boot.dev/courses/build-ai-agent-python)**. The goal is to learn the fundamentals of creating and interacting with Large Language Models (LLMs) in a structured way.

---

## 📜 About The Project

This repository serves as my personal workspace for the course. It includes the source code for the AI agent, along with a detailed [Learning Log](./LEARNING_LOG.md) to document progress, challenges, and key takeaways from each chapter.

### 📚 Course Information
* **Provider:** Boot.dev
* **Course Link:** [https://boot.dev/courses/build-ai-agent-python](https://boot.dev/courses/build-ai-agent-python)

---

## 🚀 Getting Started

This section outlines the steps to set up and run this project locally.

### Prerequisites
* Python 3.10+
* `uv` or `pip` for package management
* A Google Gemini API Key

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/shinshARK/ai-agent.git](https://github.com/shinshARK/ai-agent.git)
    cd ai-agent
    ```

2.  **Install dependencies:**
    ```sh
    # Using uv
    uv sync
    ```

3.  **Set up environment variables:**
    * Create a file named `.env` in the root directory.
    * Add your API key to this file:
    ```
    GEMINI_API_KEY="YOUR_API_KEY_HERE"
    ```

---

## 💻 Usage

To run the agent, use the following command from the root directory:

```sh
python main.py "Your prompt for the agent goes here"