# ⚙️ Automate Your Daily News Brief with GitHub Actions

This repository contains everything you need to set up a fully automated daily portfolio news briefing—no local installs required beyond initially forking. It is recommended that you go through the News Updater Jupyter Notebook before attempting this automated workflow.

## 1️⃣ Fork the Repo

Click **Fork** in the top-right corner to create your own copy under your GitHub account.

## 2️⃣ Add Your Secrets

In **Settings → Secrets and variables → Actions**, add the following repository secrets:

* **OPENAI\_API\_KEY**: Your OpenAI API key.
* **YAHOO\_EMAIL**: Your Yahoo email address for sending.
* **YAHOO\_APP\_PASSWORD**: App password for your email provider.
* **TO\_EMAIL**: Recipient address for the daily brief.
* **PORTFOLIO**: Comma-separated list of tickers (e.g. `AAPL,MSFT,NVDA`).

## 3️⃣ Configure RSS Feeds (Optional)

Edit `news_rss.json` in your fork if you want to customize which news sources are pulled in.

## 4️⃣ Review the Workflow

Open `.github/workflows/daily_brief.yml` in the root directory to see the schedule (runs daily at 07:00 UTC) and the steps it performs:

1. Install dependencies (`Retrieval Augmented Generation/Portfolio News Updater/automation_scripts/requirements.txt`).
2. Run `Retrieval Augmented Generation/Portfolio News Updater/automation_scripts/daily_news_brief.py` to fetch, summarize, and email the briefing.

## 5️⃣ Push & Automate

Any push to your fork’s default branch will trigger the workflow on schedule. No further action required—your inbox will receive a markdown-formatted news brief each morning.

### ⚡ Manual Trigger

You can also run the job on demand via **Actions → Daily Brief → Run workflow**.

---

> **Note:** If you'd like to test locally, you can clone your fork and run:
>
> ```bash
> pip install -r Retrieval Augmented Generation/Portfolio News Updater/automation_scripts/requirements.txt
> cp .env.example .env
> # fill in your credentials in .env
> python Retrieval Augmented Generation/Portfolio News Updater/automation_scripts/daily_news_brief.py
> ```
>
> But for pure automation, steps 1–5 above are all you need.

## 📝 License

This project is MIT-licensed. See [LICENSE](LICENSE).
