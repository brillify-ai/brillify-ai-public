# Brillify.ai Public Website

Public-facing website for [Brillify.ai](https://brillify.ai) — AI Solutions for Smarter Decisions.

## Pages

- **`index.html`** — Homepage with services overview and contact form
- **`sms-consent.html`** — SMS messaging consent & opt-in page (Twilio A2P compliance)
- **`privacy-policy.html`** — Privacy policy
- **`terms-of-service.html`** — Terms of service

## Hosting

This is a static site with no build step required. Can be hosted on:

- **GitHub Pages** — enable in repo Settings → Pages → deploy from `main` branch
- **Netlify / Vercel / Cloudflare Pages** — connect repo, zero config
- **Any static hosting** — just serve the HTML files

## SMS Compliance

The `sms-consent.html` page is designed to satisfy Twilio's A2P 10DLC / toll-free number registration requirements by providing:

- Clear description of how consumer consent is collected
- Sample opt-in form with compliant disclosure language
- Types of messages sent
- Message frequency disclosure
- Opt-out instructions (STOP/HELP keywords)
- Links to Privacy Policy and Terms of Service

## Customization

- Update `support@brillify.ai` with actual support email
- Replace `YOUR_FORM_ID` in `index.html` contact form action with actual Formspree (or similar) endpoint
- Adjust service descriptions in `index.html` cards as needed

## License

© 2025 Brillify. All Rights Reserved.
