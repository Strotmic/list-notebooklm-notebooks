# 📓 NotebookLM Tabs

A community-curated collection of public NotebookLM notebooks — browse what others are exploring, and share your own.

## What is this?

[NotebookLM](https://notebooklm.google.com) lets you build AI-powered notebooks from your sources. This repo is a place to share public notebooks with the world — whether it's a research deep-dive, a learning resource, or a creative project.

## Browse the collection

👉 **[View the gallery](https://strotmic.github.io/list-notebooklm-notebooks/)**

## Submit your notebook

1. Fork this repo
2. Copy `tabs/example-tab.json` and rename it to something descriptive (e.g. `tabs/my-ai-research.json`)
3. Fill in the fields (see schema below)
4. Open a Pull Request

Your submission will be reviewed and merged within a few days.

### Schema

```json
{
  "title": "Your notebook title",
  "description": "A short description of what this notebook is about",
  "link": "https://notebooklm.google.com/notebook/...",
  "category": "Research",
  "tags": ["AI", "papers"],
  "author": "your_github_username",
  "date": "2026-05-06"
}
```

| Field | Required | Description |
|---|---|---|
| `title` | ✅ | Name of your notebook |
| `description` | ✅ | Short summary (1–2 sentences) |
| `link` | ✅ | Public NotebookLM share link |
| `category` | ✅ | One of: `Research`, `Learning`, `News`, `Creative`, `Business`, `Other` |
| `tags` | ✅ | 1–5 tags describing the content |
| `author` | ✅ | Your GitHub username |
| `date` | ✅ | Date added (YYYY-MM-DD) |

## Guidelines

- **Public links only** — make sure your notebook is set to public sharing before submitting
- **No spam or self-promotion** — notebooks should have genuine educational or informational value
- **Keep descriptions honest** — describe what the notebook actually contains
- **One file per notebook** — don't bundle multiple notebooks into one entry

## Categories

| Category | Examples |
|---|---|
| 🔬 Research | Academic papers, scientific topics |
| 📚 Learning | Tutorials, explainers, study guides |
| 📰 News | Current events, analysis |
| 🎨 Creative | Writing, worldbuilding, fiction |
| 💼 Business | Industry reports, strategy, finance |
| 🗂️ Other | Anything that doesn't fit above |

## Contributing (beyond notebooks)

Found a bug in the site or want to improve the gallery UI? PRs are welcome on `index.html` as well. Open an issue first if it's a bigger change.

## License

All notebook metadata submitted to this repo is released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/) — the content of the notebooks themselves belongs to their respective authors.

---

## Roadmap

The current submission flow requires a GitHub account and a pull request. That's a bit technical for a general audience, so a proper deployment is in progress.

**Planned:**
- A hosted web app with a database backend
- A simple submission form — no GitHub account or pull request needed
- Moderation tools so submissions can be reviewed without touching code
- The gallery will stay open-source; only the backend infra will move off GitHub Pages

Until then, the PR-based flow is the way to submit. Thanks for bearing with it.
