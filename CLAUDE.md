# Orchestration Guide

## Overview
Single-page teaching site for Claude Code orchestration patterns. GitHub Pages serves `index.html` directly.

## Structure
- `index.html` — The complete teaching document (self-contained HTML, dark theme, responsive)
- `llms.txt` — Machine-readable summary for GitMCP/AI assistant indexing
- `README.md` — Pointer to the live site

## Conventions
- index.html is a single self-contained file with embedded CSS and minimal JS
- No external dependencies except Google Fonts (gracefully degrades to system monospace)
- Content updates go in index.html; structural changes should maintain the dark theme and responsive layout
- Keep llms.txt in sync with any major content additions to index.html
