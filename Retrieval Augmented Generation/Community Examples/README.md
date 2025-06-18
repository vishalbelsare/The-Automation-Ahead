# Community-Created RAG Examples for Finance

This space is dedicated to sharing **Retrieval-Augmented Generation (RAG)** use cases specifically within the world of **finance and investment**.

Whether you're building tools to summarize earnings calls, monitor regulatory filings, power investment research, or generate portfolio briefs—we'd love for you to contribute.

## Purpose

This folder exists to:

* Highlight practical, finance-focused RAG workflows
* Help others get inspired by concrete implementations
* Foster community learning, experimentation, and collaboration

## What Makes a Good Finance Example?

Each contribution should aim to be:

* **Finance/Investment-Relevant**: Tied to an actual finance workflow (e.g., analyzing 10-Ks, generating macroeconomic summaries, querying fund documents, etc.)
* **Clear**: Well-documented so others can understand and replicate it
* **Self-contained**: Includes example inputs or links to publicly available data
* **Google Colab-Based**: Each submission should consist of a `README.md` file that links to an Google Colab Notebook
* **Readable**: The linked notebook should contain markdown cells that clearly explain your objective, setup, workflow, and results
* **Reproducible**: All required dependencies should be installable from within a notebook cell (e.g. using `!pip install ...`)

## 📂 Suggested Folder Structure

Each contribution should be added in a subfolder with the following format:

```
community_examples/
└── your_project_name/
    └── README.md              # Describes your example and links to the notebook
```

## 🧑‍💻 How to Contribute

1. **Fork this repository**
   Click the “Fork” button on GitHub.

2. **Clone your fork**

   ```bash
   git clone https://github.com/<your-username>/The-Automation-Ahead.git
   cd The-Automation-Ahead/Retrieval Augmented Generation/community_examples
   ```

3. **Add your example**
   Create a new folder and include a `README.md` file that describes your use case and provides a link to your Shared Google Colab Notebook.

4. **Push your changes**

   ```bash
   git checkout -b add-my-finance-example
   git add .
   git commit -m "Add RAG example: <brief title>"
   git push origin add-my-finance-example
   ```

5. **Open a pull request**
   Submit your contribution and include a brief summary of your use case.

---

## Example README Structure

```markdown
# Earnings Call Summarizer (RAG Pipeline)

This example shows how to index earnings call transcripts and answer questions using RAG.

## Notebook
Access the notebook here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/your-notebook-link)

## Notes
This pipeline uses OpenAI embeddings and FAISS. Replace any module to fit your stack.

Data sourced from: https://example.com/earnings-calls
```

---

## Thanks for contributing!
