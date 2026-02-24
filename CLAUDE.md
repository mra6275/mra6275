# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Repository Overview

This is a **GitHub profile repository** (`mra6275/mra6275`). Its sole purpose is to display a personal profile on [github.com/mra6275](https://github.com/mra6275). GitHub treats the `README.md` in a same-name repository as special — it renders on the user's public profile page.

## Repository Contents

| File | Purpose |
|------|---------|
| `README.md` | GitHub profile page shown on the user's public profile |

There is no source code, build system, test suite, or package configuration. The entire repository is a single Markdown file.

## Owner Profile

- **Name**: Mark (mra6275)
- **Interests**: Python programming
- **Contact**: mra6275@gmail.com
- **Focus**: Learning and collaborating on Python projects

## Development Conventions

### README.md Edits

- Keep the tone friendly and personal — this is a public-facing profile.
- The file uses GitHub Flavored Markdown (GFM) with emoji bullets (`-`).
- The HTML comment block at the bottom (`<!--...-->`) is a GitHub-generated note; do not remove it.
- Avoid adding technical jargon or boilerplate unrelated to the owner's interests.

### Commit Messages

- Use plain, descriptive messages (e.g., `Update README.md`, `Add skills section`).
- No ticket numbers or scope prefixes are needed for this simple repo.

### Branch Strategy

- The default branch is `master` (mirrored from `main` on the remote).
- Work happens on `claude/` prefixed branches when changes are made via AI assistants.
- Merge to `master`/`main` after review.

## Common Tasks

### Update the profile bio

Edit `README.md` directly. The visible content starts at line 1. Preserve the closing HTML comment block.

### Add new sections

Use standard Markdown lists or sections. GitHub renders emoji in Markdown natively, so `:emoji_name:` syntax works.

## What This Repository Does NOT Have

- No build or compilation step
- No test suite
- No CI/CD pipeline
- No dependencies or package manager files
- No source code directories
