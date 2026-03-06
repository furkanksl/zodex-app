# Zodex

Zodex is a model agnostic AI engineering development environment. Built with Rust to ensure performance and security.

## This Repo Is For

- Downloading official app builds from **Releases**
- Reporting bugs and feature requests in **Issues**

## Download

- Releases page: `https://github.com/furkanksl/zodex-app/releases`
- Latest release shortcut: `https://github.com/furkanksl/zodex-app/releases/latest`

Current public artifacts in this channel are macOS builds (Apple Silicon + Intel).

## What Zodex Includes

- Project/session sidebar with search
- Multi-model chat with streaming output
- Providers (Anthropic, OpenAI, Google, Groq and ChatGPT OAuth)
- Local model support (LM Studio, Ollama, OpenAI-compatible endpoints)
- Built-in tool execution (terminal, file editing, patching, web fetch/search)
- Interactive stdin for long-running terminal commands
- Permission modes per session: `Prompt`, `Auto-edit`, `Full access`
- Git panel: diff, stage/unstage, discard, commit, stash, pull/push, merge/rebase
- Integrated multi-session terminal panel with splits
- Message actions: edit, rollback, regenerate
- Attachments support (`pdf`, `md`, `txt`, `log`, `json`, `csv`, `tsv`, `yaml`, `yml`, `xml`, images)
- Slash commands: `/compact`, `/info`, `/export`
- Session export to Markdown and text logs
- Automatic update checks + in-app updater
- Local database backup/restore tools

## Reporting Issues

- Create issue: `https://github.com/furkanksl/zodex-app/issues/new`
- Please search existing issues before opening a new one.

Include these details in every report:

- App version
- OS version and CPU architecture
- Provider/model used
- Reproduction steps
- Expected behavior
- Actual behavior
- Screenshot or screen recording
- Exported session logs if possible (`Session context menu -> Export Logs`)

## Important Notes

- Provider credentials are stored locally by the app.
- This repo does not accept source-code contributions or PRs.
