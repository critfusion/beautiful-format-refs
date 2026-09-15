# Newsletters and HTML email templates

Use these when the deliverable has to render in Gmail, Outlook, Apple Mail, and phone mail apps.

## Production frameworks (prefer these for new work)

| Repo | Notes |
| --- | --- |
| [resend/react-email](https://github.com/resend/react-email) | ~20k stars. React/TS components, preview server, official agent skill, templates for auth and commerce. |
| [mjmlio/mjml](https://github.com/mjmlio/mjml) | Industry-standard markup. Compiles to table HTML. |
| [mjmlio/email-templates](https://github.com/mjmlio/email-templates) | Official MJML template set, including a newsletter layout. |
| [maizzle/maizzle](https://github.com/maizzle/maizzle) | Tailwind + Vue email framework with inlining and Outlook helpers. |
| [Mailteorite/mjml-email-templates](https://github.com/Mailteorite/mjml-email-templates) | 40+ free MJML + compiled HTML flows (welcome, promo, cart, invoices). |

## Battle-tested HTML patterns

| Repo | Notes |
| --- | --- |
| [TedGoas/Cerberus](https://github.com/TedGoas/Cerberus) / [emailmonday/Cerberus](https://github.com/emailmonday/Cerberus) | Fluid, responsive, and hybrid patterns that survive Outlook + Gmail. Best anatomy lesson. |
| [leemunroe/responsive-html-email-template](https://github.com/leemunroe/responsive-html-email-template) | ~14k stars. Minimal single-column + CTA. Good skeleton. |
| [seanpowell/Email-Boilerplate](https://github.com/seanpowell/Email-Boilerplate) | Classic client-quirk boilerplate. Use as a checklist, not a look. |
| [ActiveCampaign/postmark-templates](https://github.com/ActiveCampaign/postmark-templates) | Welcome, reset, invoice, comment, etc. Three layout densities. |
| [mailchimp/email-blueprints](https://github.com/mailchimp/email-blueprints) | Modular patterns + responsive + fixed-width sets. Strip merge tags if you are not on Mailchimp. |
| [dcondrey/html-email](https://github.com/dcondrey/html-email) | Hand-authored framework with documented client quirks and several designed templates. |

## Designed newsletter packs

| Repo | Notes |
| --- | --- |
| [ColorlibHQ/email-templates](https://github.com/ColorlibHQ/email-templates) | 28 MJML newsletters (stories, travel, shopping, winter, agency…). |
| [threeheartsdigital/emailoctopus-templates](https://github.com/threeheartsdigital/emailoctopus-templates) | Karakol / Abacus / Wayfair packs: newsletter + announcement + transactional. Inlined CSS. |
| [mailpace/templates](https://github.com/mailpace/templates) | Tailwind + Maizzle transactional set, dark mode. |
| [konsav/email-templates](https://github.com/konsav/email-templates) | General / promotional / explorational. CodePen previews. |
| [nirajrajgor/email-templates](https://github.com/nirajrajgor/email-templates) | Mix of ecommerce, promo, and an "AI Newsletter" layout. Browser customizer. |
| [blocksedit/starter-email-components](https://github.com/blocksedit/starter-email-components) | Component kit derived from real newsletters: hero, listings, events, receipts. |
| [sendwithus/templates](https://github.com/sendwithus/templates) | Older open-source template set; still useful for structure. |

## Indexes

| Repo | Notes |
| --- | --- |
| [jonathandion/awesome-emails](https://github.com/jonathandion/awesome-emails) | Frameworks, templates, tools, testing, inspiration. |
| [wallies/awesome-newsletters](https://github.com/wallies/awesome-newsletters) | Curated *content* newsletters to read, not templates. Use for editorial structure inspiration. |

## Email-specific constraints to keep

- Width: design at 600–640px, fluid down to ~320px.
- CSS: inline for body styles; keep `@media` in `<style>` for clients that honor it.
- Layout: tables or a compiler that emits tables. CSS Grid will fail in Outlook.
- Fonts: web fonts are optional and often stripped. Always set a system stack fallback.
- Images: host absolutely; always provide `alt` and dimensions.
- Footer: physical address / why they got this / unsubscribe if it is marketing.
