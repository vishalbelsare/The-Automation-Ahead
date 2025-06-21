# Daily Portfolio News Updater – Case Study

This folder contains a simple, replicable workflow that uses Retrieval-Augmented Generation (RAG) to deliver daily, ticker-specific news summaries for your investment portfolio.

If you’re looking for a lightweight way to stay on top of material news across your holdings, this notebook gives you a nice start.

## Get Started

Open the Jupyter notebook: `News Updater.ipynb`

The notebook walks through how to build an AI-powered news briefing system that pulls fresh articles from financial-news RSS feeds, matches them to your portfolio tickers, and produces a concise summary.

## Key Takeaways

By the end of this notebook, you’ll learn how to:

- **Build a News Aggregator with RAG**  
  Ingest real-time news from RSS feeds, index it in a vector database, and surface relevant articles for a portfolio of stocks.

- **Embed and Query Financial News**  
  Use OpenAI embeddings and vector search to find relevant news stories per ticker, regardless of where the news is published.

- **Summarize with GPT**  
  Use generative models to condense multiple articles into a readable daily brief, organized by ticker.

- **Automate the Workflow**  
  Schedule and deploy the pipeline via GitHub Actions to deliver daily emails with your portfolio’s news.

## Contribute to Our RSS Feed Library

This repo is also a central hub for the community-curated list of financial-news RSS feeds. Want to see a source added? Just:

1. Fork this repository.  
2. Open and update `news_rss.json` with your favorite finance or market news RSS URL(s).  
3. Submit a pull request with a brief description of the source and why it’s valuable.