# Enhanced-QA-Chatbot-With-Ollama 🤖

This repository contains an enhanced Question Answering (QA) chatbot built using LangChain, Ollama, Python, Streamlit, and LangSmith.  It offers the capability to switch between two different language models: "llama3.2" and "gemma:2b". 🧠

## Overview

This chatbot leverages the power of Ollama to run large language models locally. 🏠 It provides a user-friendly interface through Streamlit, allowing users to interact with the chosen model for question answering tasks.  LangChain facilitates the integration of different components and provides powerful tools for chain-of-thought prompting and other advanced features. LangSmith is used for experiment tracking and evaluation of the chatbot performance. 📈

## Technologies Used

*   **LangChain:** Framework for building applications with LLMs. ⛓️
*   **Ollama:** Tool for running and managing Large Language Models locally. 🦙
*   **Python:** Programming language used for development. 🐍
*   **Streamlit:** Framework for creating interactive web applications. streamlit
*   **LangSmith:** Platform for debugging, testing, and evaluating LLM applications. 🔬
*   **llama3.2:** One of the supported language models.
*   **gemma:2b:** The other supported language model.

![Tech Stack Image]([img1.png])🖼️
![Tech Stack Image]([img2.png])🖼️
![Tech Stack Image]([img3.png])🖼️

## Features

*   **Model Switching:** Easily switch between the "llama3.2" and "gemma:2b" models. 🔄
*   **User-Friendly Interface:** Interactive web interface built with Streamlit. ✨
*   **Local LLM Execution:** Leverages Ollama for running models locally, ensuring privacy and potentially faster inference. 🔒
*   **LangChain Integration:** Utilizes LangChain for advanced prompting techniques and chain management. 🚀
*   **Experiment Tracking:** Uses LangSmith for experiment tracking and evaluation. 📊

## Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/laavanjan/Enhanced-QA-Chatbot-With-Ollama.git](https://github.com/laavanjan/Enhanced-QA-Chatbot-With-Ollama.git)
    cd Enhanced-QA-Chatbot-With-Ollama
    ```

2.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Install Ollama and download the models:**

    Follow the instructions on the [Ollama website](https://ollama.ai/) to install Ollama.  Then, download the "llama3.2" and "gemma:2b" models.  Make sure Ollama is running. ✅

4.  **Set up LangSmith:**

    Create an account on LangSmith and obtain your API key. Set the environment variables `LANGSMITH_API_KEY` and optionally `LANGSMITH_HOST` as described in the LangSmith documentation. 🔑

## Usage

1.  **Run the Streamlit application:**

    ```bash
    streamlit run app.py
    ```

2.  **Access the application:**

    Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`). 🌐

3.  **Interact with the chatbot:**

    Use the interface to ask questions and switch between the available models.  💬

## Contributing

Contributions are welcome! 🎉 Please open an issue or submit a pull request. 🤝

## License

This project is licensed under the GPL License - see the [LICENSE](LICENSE) file for details. 📜

## Acknowledgements

Leave a like 👍 if you found it useful! 😊
