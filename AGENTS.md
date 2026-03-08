# Larm docs

Public documentation for [Larm](https://larm.dev), built on [Mintlify](https://mintlify.com).

## Project structure

- `docs.json` — Mintlify configuration (navigation, theme, logos)
- `index.mdx` — Docs homepage
- `quickstart.mdx` — Getting started guide
- `development.mdx` — Local development guide for docs contributors
- `api-reference/` — API documentation
- `logo/` — Light and dark mode logos
- `favicon.svg` — Browser favicon

## Terminology

Use Larm product terms consistently:

| Use | Don't use |
|---|---|
| monitor | check, test |
| alert channel | notification, notification channel |
| status page | status site |
| heartbeat monitor | cron monitor, ping monitor |
| organization | workspace, team, account |

## Style

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

This is the **public product documentation**. Document:

- Product features and how to use them
- API reference for customer-facing endpoints
- Getting started guides

Do not document:

- Internal architecture (probe protocol, evaluator, buffer flusher)
- Infrastructure or deployment details
- Internal API endpoints (probe API, ingestion, admin)

## Commands

- `mint dev` — preview locally at `http://localhost:3000`
- `mint broken-links` — check for broken links
