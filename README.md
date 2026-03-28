# DotClaude Lab

An interactive, single-file web app inspired by the trend article "Anatomy of the .claude/ folder".

## What it does

- Generates a synthetic hidden agent workspace and lets you browse its file tree
- Inspects file contents with a lightweight editor
- Simulates new agent runs (producing typical artifacts: summaries, logs, tool outputs, prompts)
- Estimates storage tokens and a heuristic "leakage risk" score
- Applies retention rules (keep all, keep last N runs, or stay within a size budget)
- Generates and downloads a reproducible bundle.json
- Creates a shareable snapshot link by encoding the bundle into the URL hash (no server)

## Trend source

- https://blog.dailydoseofds.com/p/anatomy-of-the-claude-folder

## Run locally

Open `index.html` in any modern browser.

Tip: press `?` for the in-app guide.
