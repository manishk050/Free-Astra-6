# Puter Dev Chat

A browser-based multi-model AI chatbot built around Puter.js browser authentication and `puter.ai.chat()`.

## Run

Open `index.html` in a modern browser, click **Sign in**, and authenticate with your Puter account. No provider API key is embedded in the app.

## Models

- GPT-6 Astra — `openai/gpt-6-astra`
- GPT-6 Astra Pro — `openai/gpt-6-astra-pro`
- Claude Opus 5 — `anthropic/claude-opus-5`
- Claude Fable 5 — `anthropic/claude-fable-5`
- Claude Fable 5.1 — `anthropic/claude-fable-5-1`
- GPT-OSS 120B — `openai/gpt-oss-120b`
- GPT-OSS 20B — `openai/gpt-oss-20b`

The app also queries `puter.ai.listModels()` and marks the requested models against Puter's live catalog.

## Features

Authentication, streaming, multi-turn chat, model switching, developer modes, system instructions, temperature/max-output/reasoning controls, Markdown, syntax highlighting, copy buttons, regenerate, edit/resend, stop, file/code attachments, chat search, local persistence, JSON export/import, and optional Puter KV cloud save/load.

## Developer modes

General, Build, Debug, Review, Architecture, Refactor, Testing, SQL, DevOps, Security, Data/ML, Git, Docs.

## Scope

This is a developer-focused chatbot, not yet a fully autonomous coding agent. It does not directly inspect your VS Code workspace or execute terminal commands. A true coding-agent version should be implemented as a VS Code extension that exposes workspace, terminal, Git, and other tools to the model.
