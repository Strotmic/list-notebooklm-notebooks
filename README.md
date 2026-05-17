# 📓 NotebookLM Tabs

A community-curated collection of public NotebookLM notebooks — browse what others are exploring, and share your own.

## What is this?

[NotebookLM](https://notebooklm.google.com) lets you build AI-powered notebooks from your sources. This repo is a place to share public notebooks with the world — whether it's a research deep-dive, a learning resource, or a creative project.

## Browse the collection

👉 **[View the gallery](https://strotmic.github.io/list-notebooklm-notebooks/)**

## Submit your notebook

**Easy way:** Just [open an issue](https://github.com/Strotmic/list-notebooklm-notebooks/issues/new) or a Pull Request with your public notebook URL — I'll take care of filling in the details and adding it to the collection.

**Manual way (if you want full control):**

1. Fork this repo
2. Copy `tabs/example-tab.json` and rename it to something descriptive (e.g. `tabs/my-ai-research.json`)
3. Fill in the fields (see schema below)
4. Open a Pull Request

Submissions are reviewed and merged within a few days.

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
| `category` | ✅ | One of: `Research`, `Science`, `Learning`, `News`, `Creative`, `Business`, `Other` |
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
| 🧪 Science | Neuroscience, physics, biology, computing |
| 📚 Learning | Tutorials, explainers, study guides |
| 📰 News | Current events, analysis |
| 🎨 Creative | Writing, worldbuilding, fiction |
| 💼 Business | Industry reports, strategy, finance |
| 🗂️ Other | Anything that doesn't fit above |

## What this project is / is not

Public NotebookLM notebooks are otherwise hard to discover. This project exists to fix that — a community directory where notebooks can be found and shared.

**This project is:**
- A community directory of public NotebookLM notebooks
- A discovery tool for notebooks others have shared
- An open-source gallery anyone can contribute to

**This project is not (currently):**
- A curated editorial library with gatekeeping beyond basic quality guidelines
- A marketplace, promotional channel, or paid placement platform
- A source of affiliate links or ad-supported content

**What may come later (see Roadmap):**
- A hosted submission form with user accounts, saved notebooks, and lists
- Moderation tooling for reviewing submissions without touching code
- Sponsorship or ads — only if hosting costs make it necessary, and not as a primary direction

**Policy positions:**
- No paid placement or promoted listings
- No affiliate links
- Analytics/tracking: only what GitHub Pages provides by default (no third-party tracking added)
- Submitted notebook metadata is CC0 (see License); notebook content belongs to its authors
- Moderation criteria: public link required, genuine educational or informational value, no spam
- The project does not take responsibility for the content of linked notebooks — authors own their work

If you have questions or concerns about direction, open an issue.

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
