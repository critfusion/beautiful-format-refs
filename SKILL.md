---
name: beautiful-format-refs
description: Use when designing newsletters, HTML emails, landing pages, or editorial webpages and the user wants distinctive formats instead of generic templates. Points at the critfusion/beautiful-format-refs catalog of skills and repos.
---

# Beautiful format refs

Reference pack: https://github.com/critfusion/beautiful-format-refs

## When to use

- User asks for newsletter formats, campaign HTML, or transactional email layouts
- User wants a webpage that does not look like default AI SaaS
- User says "use the format-refs repo" or pastes this repo URL

## Workflow

1. Read `AGENTS.md` in the repo.
2. Choose medium: email vs webpage. Do not mix constraints.
3. Open the matching catalog file (`catalogs/newsletters.md` or `catalogs/webpages.md`) plus `catalogs/skills.md`.
4. Pull 1–3 upstream repos. Read their README / SKILL.md and one example.
5. Propose a format (or three), then implement.
6. Write a short note of which references informed the result.

## Hard rules

- Email: no JavaScript, prefer 600px container, inline CSS or a compiler (MJML / React Email / Maizzle).
- Webpage: commit to one visual register; ban default purple-gradient + Inter + three feature cards unless requested.
- References are for ideas. Do not copy copyrighted copy, logos, or unique illustrations.
