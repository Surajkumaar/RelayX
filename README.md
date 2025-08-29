# **RelayX**

## Overview
RelayX is a **lightweight multi-agent orchestrator** that handles multiple specialized tasks through a manager–sub-agent architecture.  
The system consists of:
- **Manager Agent**: Coordinates tasks and aggregates responses.
- **Sub-Agents**: Each focused on a specific domain.

---

## How It Works
The manager agent receives a user request, determines which sub-agent(s) should handle it, and then orchestrates their responses into a unified output.

### **Sub-Agents**
- **🤓 funny_nerd** – Tells nerdy jokes about various topics.
- **📰 news_analyst** – Fetches and summarizes the latest news using a search tool.
- **📈 stock_analyst** – Looks up real-time stock prices.

---

## Key Features
- Modular **multi-agent architecture**.
- Each sub-agent returns a **structured response** (e.g., joke, news summary, stock info).
- Manager agent **combines and formats the final output**.
- Easily extensible – add more agents for additional tasks.

---

## Tech Stack
- **Language**: Python  
- **Tools**: APIs for search and stock data  
- **Architecture**: Manager + Sub-agents

---

## System Flow
1. User sends a request.
2. Manager identifies relevant sub-agent(s).
3. Sub-agent(s) process and return structured responses.
4. Manager aggregates and formats the final output.

---

## Getting Started
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-repo/relayx.git
   cd relayx
