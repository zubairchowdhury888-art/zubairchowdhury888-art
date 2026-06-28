# Setup Guide

This repository is structured like a product surface, not a single markdown file.

## Structure

- `README.md`: Public narrative and profile homepage.
- `assets/`: Visual system, cards, and media placeholders.
- `.github/workflows/`: Automation entrypoints (intentionally stubbed).
- `scripts/`: Script entrypoints for content sync and card generation.

## Local Editing

1. Edit narrative and section ordering in `README.md`.
2. Replace placeholder artwork in `assets/` while preserving file paths.
3. Implement script logic in `scripts/`.
4. Wire scripts into workflows in `.github/workflows/`.

## Automation Plan

- `scripts/update_blog.py`: Update the `BLOG` marker block in `README.md`.
- `scripts/update_publications.py`: Update the `PUBLICATIONS` marker block in `README.md`.
- `scripts/generate_cards.py`: Generate deterministic SVG cards under `assets/`.
- Workflow files orchestrate schedule and commit policy once implemented.

## Notes

Keep copy concise, research-first, and non-redundant. Every section should answer a distinct question.
