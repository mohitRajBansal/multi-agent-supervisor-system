# NSE Stock Research Multi-Agent System

This project is a **multi-agent research and trading assistant** built with [LangGraph](https://github.com/langchain-ai/langgraph), [LangChain MCP adapters](https://github.com/langchain-ai/langchain-mcp), and OpenAI.  
It analyzes **Indian stock market (NSE)** data to provide short-term trading recommendations.

---

## 🚀 Features
- **Stock Finder Agent** → Picks 2 promising NSE stocks for short-term trading.  
- **Market Data Agent** → Collects price, volume, technical indicators (RSI, moving averages).  
- **News Analyst Agent** → Summarizes latest news and sentiment.  
- **Price Recommender Agent** → Provides Buy/Sell/Hold recommendations with entry/exit targets.  
- **Supervisor Agent** → Manages task handoff sequentially between all agents.  

