# Etherna Labs delivery notes

## Sitemap

- `/index.html` — Spanish home, projects and direct-contact guidance
- `/index-en.html` — English equivalent
- `/privacy.html` and `/privacy-en.html` — bilingual privacy notice
- `/terms.html` and `/terms-en.html` — bilingual terms of use

## Cloudflare Pages deployment checklist

- Create a Pages project and connect this repository or upload the static files.
- Use no framework preset; set the output directory to the project root.
- Add `etherna-labs.com`, configure DNS, enable HTTPS and redirect `www` consistently.
- Verify all six pages, language links, mobile navigation, form submission and custom 404 behavior.
- Add security headers (CSP, `X-Content-Type-Options`, `Referrer-Policy`, frame policy).
- Add analytics/cookies only after consent and privacy review where required.

## Placeholder checklist

- Replace every `PROJECT_WEBSITE_PLACEHOLDER`, `WHITEPAPER_URL_PLACEHOLDER` and `PROJECT_CONTACT_PLACEHOLDER` per project.
- Replace legal entity, address, jurisdiction, legal/privacy email, IP owner, court/process and update-date placeholders.
- Add approved project logos only with permission and accessible alt text.
- Add a real Open Graph image and favicon, then validate social previews.

## Legal review checklist

- Confirm the portal operator, applicable privacy roles and lawful bases.
- Confirm cross-border transfers, retention periods, service providers and data-subject request workflow.
- Validate liability limits, governing law, dispute forum and intellectual-property wording locally.
- Obtain written approval for every project description, mark, whitepaper, link and contact destination.
- Ensure no wording implies ownership, control, endorsement, exclusivity or agency.
