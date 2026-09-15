# beautiful-format-refs

Curated **skills** and **repos** for beautifully formatted webpages and HTML newsletters.

This repo is a reference pack, not a template dump. Point a coding agent at it when you want layout ideas, design systems, and email-safe patterns instead of generic AI slop.

**Repo:** https://github.com/critfusion/beautiful-format-refs

## Use this in a prompt

Copy [PROMPTS.md](PROMPTS.md). Short version:

```text
I need newsletter formats.

Use https://github.com/critfusion/beautiful-format-refs as the source of ideas.
Read AGENTS.md first, then catalogs/newsletters.md and catalogs/skills.md.
Do not copy a template verbatim. Borrow structure, hierarchy, type, color, and component patterns. Adapt them to my content and brand.
```

Agents should start at [AGENTS.md](AGENTS.md).

## What is in here

| File | Purpose |
| --- | --- |
| [AGENTS.md](AGENTS.md) | Operating manual for coding agents |
| [PROMPTS.md](PROMPTS.md) | Ready-to-send prompts |
| [SKILL.md](SKILL.md) | Drop-in agent skill that points back at this catalog |
| [catalogs/skills.md](catalogs/skills.md) | Agent skills for taste, HTML, scroll sites, email |
| [catalogs/newsletters.md](catalogs/newsletters.md) | HTML email / newsletter templates and frameworks |
| [catalogs/webpages.md](catalogs/webpages.md) | Landing pages, editorial HTML, design systems |
| [catalogs/frameworks.md](catalogs/frameworks.md) | Build tools: React Email, MJML, Maizzle |

## Short list (start here)

### Agent skills (webpages + design taste)

- [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) — stop generic Inter-on-white slop; force a real visual register
- [nateherkai/scroll-craft](https://github.com/nateherkai/scroll-craft) — premium scroll-driven sites with a documented design standard
- [MustBeSimo/web-design-studio](https://github.com/MustBeSimo/web-design-studio) — art direction, motion, 3D, 28 live examples
- [GoDiao/show-html](https://github.com/GoDiao/show-html) — 24 magazine-quality self-contained HTML examples
- [neethanwu/visuals](https://github.com/neethanwu/visuals) — single-file HTML presentations, 30+ styles, curated font pairings
- [plannotator/effective-html](https://github.com/plannotator/effective-html) — HTML artifacts, wireframes, prototypes, design process
- [MengTo/Skills](https://github.com/MengTo/Skills) — large design/builder skill collection (landing pages, motion, GSAP)
- [divyanshu-iitian/agent-website-design-skills](https://github.com/divyanshu-iitian/agent-website-design-skills) — landing-page craft + visual direction + QA
- [zarazhangrui/beautiful-html-templates](https://github.com/zarazhangrui/beautiful-html-templates) — agent-selectable HTML visual systems (decks; still useful for type/color)

### Newsletters / HTML email

- [resend/react-email](https://github.com/resend/react-email) — React email components + official agent skill (`npx skills add resend/react-email`)
- [mjmlio/mjml](https://github.com/mjmlio/mjml) + [mjmlio/email-templates](https://github.com/mjmlio/email-templates) — semantic markup that compiles to Outlook-safe HTML
- [maizzle/maizzle](https://github.com/maizzle/maizzle) — Tailwind CSS email framework
- [TedGoas/Cerberus](https://github.com/TedGoas/Cerberus) / [emailmonday/Cerberus](https://github.com/emailmonday/Cerberus) — battle-tested responsive email patterns
- [leemunroe/responsive-html-email-template](https://github.com/leemunroe/responsive-html-email-template) — simple, widely used single-column template
- [ActiveCampaign/postmark-templates](https://github.com/ActiveCampaign/postmark-templates) — production transactional layouts
- [mailchimp/email-blueprints](https://github.com/mailchimp/email-blueprints) — modular / responsive email blueprints
- [ColorlibHQ/email-templates](https://github.com/ColorlibHQ/email-templates) — 28 MJML newsletters compiled to table HTML
- [blocksedit/starter-email-components](https://github.com/blocksedit/starter-email-components) — mix-and-match newsletter components
- [jonathandion/awesome-emails](https://github.com/jonathandion/awesome-emails) — index of frameworks, templates, tools

### Beautiful webpages

- [PaulleDemon/awesome-landing-pages](https://github.com/PaulleDemon/awesome-landing-pages) — free SaaS / product landing templates
- [cruip/tailwind-landing-page-template](https://github.com/cruip/tailwind-landing-page-template) and [cruip/open-react-template](https://github.com/cruip/open-react-template)
- [weijunext/landing-page-boilerplate](https://github.com/weijunext/landing-page-boilerplate)
- [nordicgiant2/awesome-landing-page](https://github.com/nordicgiant2/awesome-landing-page) — older but large index

## Rules of use

1. Treat these as **references**, not drop-in clones.
2. Prefer structure + typography + spacing over copying brand colors or copy.
3. Newsletters are not webpages. Email HTML still needs tables, inline CSS, and 600px-ish width.
4. Check the source license before shipping production work.
5. If a skill repo has `SKILL.md` or `AGENTS.md`, read that file first.

## Related repo on this account

- [critfusion/claude-md](https://github.com/critfusion/claude-md) — portable UI design framework for coding agents
