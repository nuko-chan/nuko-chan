# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a **GitHub profile README repository** (`nuko-chan/nuko-chan`). It contains a single `README.md` that renders as the GitHub profile page, plus a GitHub Actions workflow for generating profile summary cards.

There is no application code, build system, or test suite.

## Structure

- `README.md` — GitHub profile page (written in HTML + Markdown, content is in Japanese)
- `.github/workflows/profile-summary-cards.yml` — Daily cron job that generates profile summary cards using `vn7n24fzkq/github-profile-summary-cards`

## Working with This Repo

- Edits to `README.md` are the primary activity. Changes are visible immediately on the GitHub profile after push.
- The README uses a mix of raw HTML (for layout/alignment) and Markdown (for tables, lists, code blocks). Maintain this hybrid style when editing.
- All prose content is in Japanese. Keep new content in Japanese unless instructed otherwise.
