Daily Portfolio News Updater – Case Study

This folder contains a simple, replicable workflow that uses Retrieval-Augmented Generation (RAG) to deliver daily, ticker-specific news summaries for your investment portfolio.

If you’re looking for a lightweight way to stay on top of material news across your holdings, this notebook gives you a nice start.

Get Started

Open the Jupyter notebook: News Updater.ipynb

The notebook walks through how to build an AI-powered news briefing system that pulls fresh articles from financial news sources, matches them to your portfolio tickers, and produces a concise summary.

Key Takeaways

By the end of this notebook, you’ll learn how to:
	•	Build a News Aggregator with RAG
Learn how to ingest real-time news from RSS feeds, index it in a vector database, and surface relevant articles for a portfolio of stocks.
	•	Embed and Query Financial News
Use OpenAI embeddings and vector search to find relevant news stories per ticker, regardless of where the news is published.
	•	Summarize with GPT
Use generative models to condense multiple articles into a readable daily brief, organized by ticker.
	•	Automate the Workflow
Learn how this pipeline can be scheduled and deployed via GitHub Actions to deliver daily emails with your portfolio’s news.

This notebook is a practical starting point for anyone looking to experiment with automated news summarization using large language models.