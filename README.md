# AI Marketing Automation Platform

Automate marketing workflows using configurable AI agents.

Overview

This repository provides a small, configurable framework for running AI-driven marketing tasks (research, content generation, SEO helpers, etc.) via agents defined in `config/`.

Quick start

1. Create and activate a Python virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Run the app:

```powershell
python crew.py
```

Configuration

- Define agents in `config/agents.yaml` and tasks in `config/tasks.yaml`.
- The app reads those files at runtime to run workflows.

Contributing

- Make changes on a branch, open a PR, and include a short description.
- Keep changes small and focused; add tests when practical.

License

MIT. Change to your preferred license if needed.
