# Agent operating manual

You are using **beautiful-format-refs** as a design reference pack.

Repo: https://github.com/critfusion/beautiful-format-refs

## Goal

Produce a *specific* webpage or newsletter. Do not invent a generic Inter / purple-gradient / three-card SaaS layout unless the brief asks for that.

## Read order

1. This file.
2. `catalogs/skills.md` if the user wants an agent skill or visual register.
3. `catalogs/newsletters.md` if the deliverable is email / newsletter HTML.
4. `catalogs/webpages.md` if the deliverable is a site, landing page, or editorial webpage.
5. `catalogs/frameworks.md` if they want React Email, MJML, or Maizzle output.
6. Open 1–3 source repos from the matching catalog. Read their README / SKILL.md / AGENTS.md and at least one example file.

## Decide the medium first

| User said | Medium | Constraints |
| --- | --- | --- |
| newsletter, digest, campaign email, welcome email | HTML email | ~600px canvas, tables or MJML/React Email components, inline CSS, system or web-safe fonts, no JS |
| landing page, marketing site, scroll site | Webpage | Real CSS, custom fonts OK, motion only if it serves the story |
| one-pager, lookbook, report, magazine HTML | Self-contained HTML | Single file preferred, distinctive type + color |

Never treat a scroll-driven marketing site as a valid newsletter pattern.

## How to borrow from references

Steal these:

- Section order (kicker → masthead → lead → feature grid → quote → links → footer)
- Typographic pairing and scale
- Spacing rhythm and column widths
- Component shapes (hairline rules, masthead bars, issue numbers, TOC strips)
- Dark-mode strategy *if the source actually has one*

Do not steal:

- Their logo, product name, or marketing copy
- Pixel-identical color tokens unless the user wants that brand
- Placeholder lorem or fake social proof

## Newsletter format palette

When the user asks for newsletter formats, propose 2–4 distinct formats, then implement the one they pick (or implement all if they asked for a set).

Suggested formats to offer:

1. **Editorial digest** — serif masthead, issue number, 3–5 story blocks with bylines, thin rules, quiet footer. Look at MJML newsletter templates, Colorlib winter/stories packs, Cerberus fluid.
2. **Product / SaaS update** — logo bar, one hero announcement, changelog bullets, single CTA. Look at Postmark + Mailpace transactional sets, React Email examples.
3. **Lookbook / lifestyle** — large image, short caption, two-column product or story tiles. Look at EmailOctopus Wayfair/Karakol packs, konsav promotional template.
4. **Plain-text-forward** — almost no chrome, strong type hierarchy, links as the only color. Look at Cerberus hybrid / Postmark plain variation.
5. **Modular block newsletter** — reusable intro, feature, quote, event, product, and footer blocks. Look at blocksedit starter components and Mailchimp modular patterns.

## Webpage format palette

1. **Editorial / magazine** — paper canvas, serif display, numbered sections. See show-html, taste-skill editorial, beautiful-html-templates Soft Editorial.
2. **Soft product / Apple-Linear** — silver canvas, large type, restrained motion. See taste-skill soft / Vanguard-like skills.
3. **Brutalist / Swiss print** — oversized numerals, hairline grids, high contrast. See taste-skill brutalist.
4. **Cinematic scroll** — pinned chapters, one memorable interaction. See scroll-craft and web-design-studio. Only use when the brief wants a site, not an email.

## Quality bar

- Real content hierarchy. A kicker is not a heading is not a button label.
- One accent color plus neutrals, unless the brief is maximalist.
- Mobile: newsletter stacks to one column; webpage does not trap text under 320px.
- Accessibility: real heading order, button contrast, `alt` on images, `role="presentation"` on email spacer tables.
- No stock AI aesthetic: no purple mesh + Inter + rounded cards + three feature icons unless that *is* the requested register.

## Output

Unless the user specifies otherwise:

- Newsletters: one HTML file per format (or React Email / MJML source + compiled HTML).
- Webpages: one self-contained HTML file or a small folder with `index.html` + assets.
- Include a short `NOTES.md` listing which catalog entries you used and what you changed.
