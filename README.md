# Chatbot-Gemma

This repository contains a demonstration of a chatbot using the LangChain framework, integrated with the Gemma model from Ollama, and deployed using Streamlit. The chatbot is designed to respond to user queries as a helpful assistant.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)


## Overview
Chatbot-Gemma is a simple yet powerful chatbot application built using the LangChain framework and the Gemma model from Ollama. It leverages Streamlit for a user-friendly web interface. The chatbot is designed to provide helpful responses to user queries.

## Features
- Uses LangChain framework for chaining language models and prompts.
- Integrated with the Gemma model from Ollama.
- Simple web interface using Streamlit.
- Environment variable management using `dotenv`.

## Installation

### Prerequisites
- Python 3.10
- `virtualenv` (recommended)

### Steps

1. **Clone the repository:**
    ```sh
    git clone https://github.com/abhisheksakhare1000/chatbot-gemma.git
    cd chatbot-gemma
    ```

2. **Create and activate a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Set up environment variables:**
    - Create a `.env` file in the root directory of the project.
    - Add your LangChain API key to the `.env` file:
      ```
      LANGCHAIN_API_KEY=your_langchain_api_key_here
      ```

## Usage
1. **Run the Streamlit application:**
    ```sh
    streamlit run localama.py
    ```

2. **Interact with the chatbot:**
    - Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`).
    - Enter a topic or question in the input field and get responses from the chatbot.
