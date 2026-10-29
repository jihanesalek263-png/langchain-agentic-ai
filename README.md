# Agentic AI with LangChain and LangGraph

A hands-on notebook exploring AI agents using LangChain, LangGraph, and Ollama.

## Overview

This project demonstrates how to create an AI agent, define custom tools, and allow the agent to select tools according to the user's request.

## Concepts Covered

- Creating AI agents with LangChain
- Defining custom tools with `@tool`
- Tool calling and agent execution
- Using an Ollama-hosted language model
- Managing conversation state with LangGraph
- PostgreSQL checkpointing for conversation persistence
- Loading environment variables with `python-dotenv`

## Technologies

- Python
- LangChain
- LangGraph
- Ollama
- PostgreSQL
- Jupyter Notebook

## Tools Implemented

- **Search:** Demonstrates a basic news-search tool.
- **Weather:** Demonstrates a weather-information tool.
- **Employee Information:** Returns sample employee information.

*Note: The search, weather, and employee tools use demonstration data unless connected to real data sources.*

## Getting Started

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install the required dependencies.
4. Install and configure Ollama with a compatible model.
5. Configure PostgreSQL if running the checkpointing section.
6. Open `AI_Agentic.ipynb` in Jupyter Notebook or VS Code.
7. Execute the notebook cells in order.

## Security

Do not commit passwords, API keys, database credentials, or your `.env` file. Use environment variables for sensitive configuration.

## Author

Jihane Salek

Master's Student in Artificial Intelligence & Digital Computing
