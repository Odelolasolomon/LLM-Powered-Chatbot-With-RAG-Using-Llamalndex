# LLM-Powered-Chatbot-With-RAG-Using-Llamalndex

## RAG-Based Chat Assistant Using Wikipedia Pages

## Overview

This project implements a Chat Assistant that utilizes **Retrieval Augmented Generation (RAG)** to answer questions based on a selected Wikipedia page. The RAG approach enhances the language model's ability to retrieve up-to-date and relevant information without requiring retraining, thus reducing hallucinations. This project also leverages the **ReAct (Reasoning and Act)** prompting framework to guide the agent in reasoning, using tools, and observing outcomes before generating a response.



## ReAct Framework

The ReAct framework assists the agent in determining when and how to use tools to find information. This reasoning process is crucial for generating accurate responses to complex questions, as depicted in the flow below.

![ReAct Framework](Capture2.png)

## Project Structure

The project is built using Python and consists of the following scripts:

- **`utils.py`**: This script handles reading the OpenAI API key from a YAML configuration file, allowing the use of the ChatGPT API.
  
- **`index_wikipages.py`**: This script is responsible for loading Wikipedia pages into memory, indexing them for easy search and retrieval.

- **`chat_agent.py`**: This script creates a ReAct agent with a chat UI that leverages OpenAI's language models to answer complex questions about topics indexed from Wikipedia pages.

## Prerequisites

- Python 3.x installed.
- OpenAI API key with available account credit.
- Required Python libraries installed (see [Installation](#installation)).

## Installation

1. Clone the repository to your local machine.
2. Install the required dependencies:

  


