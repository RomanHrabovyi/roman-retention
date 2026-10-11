# Roman Hrabovyi — Klaviyo & Retention Landing

Bilingual (EN/UA) landing page for Roman Hrabovyi — Klaviyo & email-retention specialist for DTC brands.

## Stack
Single self-contained `index.html` (HTML + CSS + vanilla JS, no build step). Dark theme, brand colors (emerald + silver), animated hero dashboard, EN/UA language switch, lead form.

## Run
Open `index.html` in a browser, or host it on any static host (GitHub Pages, Netlify, Vercel).

## Files
- `index.html` — the page
- `roman-about.png` — portrait used in the About section

## Lead form
The form has no backend by default — it builds a ready-to-send request and shows contacts. To receive submissions, set `FORM_ENDPOINT` near the top of the `<script>` in `index.html` (Formspree / your backend), or replace the form block with a Klaviyo embed form.

## Contacts configured
- Email: roman.ret.mark@gmail.com
- Telegram: set via `TELEGRAM_URL`
- LinkedIn: add your URL to `LINKEDIN_URL` to show the link
