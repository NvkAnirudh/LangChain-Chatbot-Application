# LangChain Demo With ChatOpenAI And Ollama

This repository contains a demonstration of integrating LangChain, a conversational AI framework, with ChatOpenAI and Ollama, a tool for running large language models (LLMs) locally. The project aims to showcase 
how to create conversational interfaces using OpenAI and local instances of LLMs.

## Features
* Allows users to interact with a conversational AI system.
* Supports querying various topics.
* Runs locally, ensuring data privacy and security.

## Prerequisites

Before running the project, make sure you have the following installed:

* Python 3.8 or higher
* Ollama (Installation instructions available at [Ollama GitHub repository](https://github.com/ollama/ollama))
* Streamlit (Install via pip: ```pip install streamlit```)
* Other dependencies listed in ```requirements.txt```

## Setup

* Clone this repository to your local machine.
* Install dependencies using ```pip install -r requirements.txt```.
* Set up Ollama following the instructions provided in the [Ollama GitHub repository](https://github.com/ollama/ollama).
* Create a ```.env``` file and add your API keys for both OpenAI and LangChain. For example:

  ```
  OPENAI_API_KEY=your_openai_api_key
  LANGCHAIN_API_KEY=your_langchain_api_key
  ```
* Run the application using Streamlit: ```streamlit run app.py```.
* Interact with the system by entering your queries in the provided text input field.

License
This project is licensed under the [MIT License].


