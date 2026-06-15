# AI Finance Agent Team with Web Access

A multi-agent AI system that works as a collaborative financial analyst powered by GPT-4o, real-time web search, and live market data. Built in under 20 lines of Python.

---

## Overview

This project spins up a team of specialized AI agents that coordinate with each other to research, analyze, and summarize financial information on demand. Whether you want a stock breakdown, market trends, or company insights, the agent team handles it end to end.

---

## Features

- **Web Agent** - Searches the internet for the latest news and general research
- **Finance Agent** - Pulls real-time stock data, financials, and market metrics via YFinance
- **Team Agent** - Orchestrates the other agents and synthesizes their outputs
- Live financial data via **YFinance**
- Web search powered by **DuckDuckGo**
- Conversation history stored with **SQLite**

---

## Getting Started

### 1. Clone the repository

    git clone https://github.com/karishmaram-tech/ai_finance_agent_team.git
    cd ai_finance_agent_team

### 2. Install dependencies

    pip install -r requirements.txt

### 3. Set your OpenAI API key

    export OPENAI_API_KEY=your-api-key-here

### 4. Run the agent team

    python3 finance_agent_team.py

Open the URL shown in your terminal to interact with the agents through the playground interface.

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| GPT-4o | Core LLM powering all agents |
| YFinance | Real-time stock and financial data |
| DuckDuckGo | Web search for news and research |
| SQLite | Persistent storage of agent interactions |

---

## Author

Built by [karishmaram-tech](https://github.com/karishmaram-tech)
