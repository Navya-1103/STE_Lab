# IBM Bob IDE — Tutorial Lab Guide

A GitHub Pages site that guides workshop participants through the IBM Bob IDE tutorial series using the **Galaxium Travels** demo application.

## Tutorials covered

| # | Tutorial | Description |
|---|----------|-------------|
| 0 | Introduction | Overview, prerequisites, and app architecture |
| 1 | Start a project with `/init` and `AGENTS.md` | Give Bob persistent project context |
| 2 | Create a commit and pull request with Bob | Use Bob's built-in Git integration |
| 3 | Use literate coding to generate code from comments | Write code with AI in-editor |
| 4 | Standardize Bob's behavior | Team-wide rules files |
| 5 | Add a custom mode | Build a product manager persona |
| 6 | Create a new context window | Manage tokens and memory |

## Running locally

```bash
gem install bundler jekyll
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Deploying to GitHub Pages

Push this repository to GitHub and enable **GitHub Pages** in Settings → Pages (source: `main` branch, `/ (root)`).
