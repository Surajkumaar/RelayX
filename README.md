RelayX

Core idea
A lightweight multi-agent orchestrator. The system consists of a single manager agent and several sub-agents, each focused on a specific task.

How the multi-agent system works in this project
	- `funny_nerd`: tells nerdy jokes about various topics.
	- `news_analyst`: fetches and summarizes news using a search tool.
	- `stock_analyst`: looks up current stock prices.

Key properties

Tech stack
- Each sub-agent returns a structured response (e.g., a joke, news summary, or stock price info).

- The manager formats and returns the final answer to the user.
