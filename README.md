# Chatbot Web UI

This project is a Gradio-based chatbot application that leverages the power of LangChain and Hugging Face models to perform both conversational AI and PDF document retrieval. The chatbot is capable of handling text-based queries, generating responses based on Large Language Models (LLMs), customize text generation parameters and retrieving information from uploaded PDF documents.

![web-interface](images/web-interface.png)

## Features

* Provides Parameters Control
  - temperature
  - token limit
  - top-k
  - top-p
* Provides a RESET PARAMETERS Button to Restore Default Parameters Setting
* Provides a Clear Button to Reset the Conversation in the Interface
* Supports PDF-Based Retrieval-Augmented Generation (RAG)
* Supports embedding model
  - [all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)
* Supports text generation model
  - [Phi-3-mini-4k-instruct](https://huggingface.co/microsoft/Phi-3-mini-4k-instruct)

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/QinWenFeng/chatbot-web-ui.git
cd chatbot-web-ui
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the following command to start the chatbot interface:

```bash
python3 app.py
```

2. Once the server is running, open your web browser and navigate to http://127.0.0.1:7860 to access the chatbot interface.




