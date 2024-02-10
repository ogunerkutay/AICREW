# AICrew Project

## Overview

**AICrew** is an innovative approach to simulating a software development process. It leverages advanced Python tools and libraries to create a virtual environment where different aspects of software development are handled by AI agents. Each agent in the AICrew represents a role in a software development team, such as a Backend Developer, DevOps Engineer, or Database Expert. These agents interact with each other to simulate the development of a mobile game.

## Installation

Before running AICrew, ensure you have the required libraries installed. Run the following commands to install necessary dependencies:

```bash
pip install python-dotenv
pip install gitpython
pip install langchain
pip install langchain-community
pip install langchain_google_genai
pip install faiss-gpu
pip install wikipedia
pip install crewai
```

## Usage

To use AICrew, clone the repository and navigate to the project directory. Run the Jupyter Notebook to start the simulation:

```bash
git clone https://github.com/ogunerkutay/AICrew.git
cd AICrew
jupyter notebook AICrew.ipynb
```

## Components

**AICrew** consists of several components:

- **Environment Setup:** Initialize the environment and import necessary libraries.
- **Configuration and Initialization:** Set up LangChain and Google Generative AI embeddings.
- **Document Processing:** Functions for loading and processing documents.
- **RetrievalQA Chain:** Set up a retrieval-based question-answering chain.
- **Tools Initialization:** Initialize various tools for agents, including Wikipedia Query, File Management, and custom tools for specific functions.
- **Agents and Crew Initialization:** Define roles for each agent in the software development process.
- **Execution and Results Handling:** Kick off the crew and handle results of the development process.

## Contributing

Contributions to AICrew are welcome! Feel free to fork the repository and submit pull requests.
