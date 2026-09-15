# Agent skills

Skills teach coding agents *how* to design, not just which file to copy.

## Taste and anti-slop

| Repo | Why it is here |
| --- | --- |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | High-agency frontend taste. Forces a register (editorial / soft / brutalist) instead of generic UI. |
| [uxjoseph/supanova-design-skill](https://github.com/uxjoseph/supanova-design-skill) | Taste-skill derivative aimed at standalone HTML landing pages. |
| [nexu-io/open-design](https://github.com/nexu-io/open-design) | Design skills with `SKILL.md` + `example.html` pairs, including taste-derived web prototypes. |

## HTML artifacts and magazine pages

| Repo | Why it is here |
| --- | --- |
| [GoDiao/show-html](https://github.com/GoDiao/show-html) | 24 magazine-quality self-contained HTML examples + skill workflow. |
| [neethanwu/visuals](https://github.com/neethanwu/visuals) | Single-file HTML presentations; many styles and curated font trios. |
| [zarazhangrui/beautiful-html-templates](https://github.com/zarazhangrui/beautiful-html-templates) | Agent-indexed visual systems (`index.json` + `AGENTS.md`). Built for decks; excellent type/color reference. |
| [plannotator/effective-html](https://github.com/plannotator/effective-html) | Skills for HTML, wireframes, prototypes, plans, design-artifact process. |
| [prdai-archive/design-agent-skills](https://github.com/prdai-archive/design-agent-skills) | Polished HTML design artifacts: decks, prototypes, explorations. |

## Sites, scroll, landing-page craft

| Repo | Why it is here |
| --- | --- |
| [nateherkai/scroll-craft](https://github.com/nateherkai/scroll-craft) | Premium scroll-driven sites with an approved ten-site standard. Codex / Claude Code skill + plugin. |
| [MustBeSimo/web-design-studio](https://github.com/MustBeSimo/web-design-studio) | Art direction, motion, interactive 3D, 28 live examples. Formerly Cinematic Scroll. |
| [MengTo/Skills](https://github.com/MengTo/Skills) | Large skill library: landing pages, Awwwards-quality sites, GSAP, scroll storytelling. |
| [divyanshu-iitian/agent-website-design-skills](https://github.com/divyanshu-iitian/agent-website-design-skills) | Visual direction, landing-page craft, responsive QA, accessibility. |

## Email-specific skills

| Repo | Why it is here |
| --- | --- |
| [resend/react-email](https://github.com/resend/react-email/tree/canary/skills/react-email) | Official React Email skill. `npx skills add resend/react-email` |
| Resend email skills | Also see `npx skills add resend/resend-skills` and `npx skills add resend/email-best-practices` |

## Local companion

| Repo | Why it is here |
| --- | --- |
| [critfusion/claude-md](https://github.com/critfusion/claude-md) | Your portable UI design / implementation framework for coding agents. |

## Install hints

Many of these follow the emerging agent-skills layout (`SKILL.md`). Typical install:

```bash
npx skills add Leonxlnx/taste-skill
npx skills add nateherkai/scroll-craft
npx skills add GoDiao/show-html
npx skills add resend/react-email
npx skills add plannotator/effective-html
```

If the agent cannot install skills, clone or browse the repo and follow its `SKILL.md` / `AGENTS.md` by hand.
