# Build frameworks

Pick a toolchain after you pick a format.

## Email compilers

### React Email

- Repo: https://github.com/resend/react-email
- Skill: https://github.com/resend/react-email/tree/canary/skills/react-email
- Install skill: `npx skills add resend/react-email`
- Scaffold: `npx create-email@latest`
- Best when the rest of the stack is React/Next and you want components + preview.

### MJML

- Engine: https://github.com/mjmlio/mjml
- Templates: https://github.com/mjmlio/email-templates
- Extra packs: https://github.com/Mailteorite/mjml-email-templates
- Best when you want semantic `<mj-section>` / `<mj-column>` authoring and Outlook-safe output without React.

### Maizzle

- Starter: https://github.com/maizzle/maizzle
- Framework: https://github.com/maizzle/framework
- Docs: https://maizzle.com
- Best when you want Tailwind utilities and a production inliner.
- Related templates: https://github.com/mailpace/templates

## Hand-coded HTML email

Use Cerberus or Lee Munroe as the skeleton if you must ship a single HTML file with no build step.

## Webpage stacks that stay pretty

- Self-contained HTML + CSS (show-html / visuals style) for one-off pages and agent output.
- Tailwind + semantic HTML for landings (Cruip, PaulleDemon packs).
- Next.js only if the page needs routing, CMS, or production hosting — not because it is the default.

## Testing (email)

Before calling a newsletter done:

- Litmus / Email on Acid if available
- At least preview in Gmail (web) and a dark-mode client
- Outlook-safe buttons (VML or bulletproof `<a>` in a `<td>`)
- Real unsubscribe / preference URL placeholders if it is marketing mail
