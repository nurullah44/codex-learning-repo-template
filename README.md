# Codex Learning Repo Template

Template for building a tiny real AI product while learning full-stack product engineering.

The default first product is a single-user AI notebook:

- login
- notes CRUD
- search or retrieval
- AI summary and question-answering over notes
- deployed to a real domain
- basic tests, logs, backups, cost limits, and security review

## Create A New Repo

If the local `gh learn` alias is installed:

```powershell
gh learn ai-notebook-tool
```

Raw GitHub CLI command:

```powershell
gh repo create ai-notebook-tool --public --template nurullah44/codex-learning-repo-template --clone
```

## First Prompt To Codex

```text
Use slow-learning-builder and follow AGENTS.md.
I want to learn before building. Start by helping me define the smallest useful version.
Do not code yet.
```

## First Files To Fill

- `ai/PROJECT_MEMORY.md`
- `docs/ARCHITECTURE.md`
- `docs/DEPLOYMENT.md`
- `docs/SECURITY.md`
- `docs/OPERATIONS.md`

Keep them short. They should clarify decisions, not become homework.
