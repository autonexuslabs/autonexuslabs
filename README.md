### Hi, I'm Emil. I build AI automation for small businesses.

I run **[AutoNexus Labs](https://autonexuslabs.com)**, a one-person automation studio. Most of my work is the plumbing behind "the lead got an answer in a minute and nobody forgot to follow up":

- **Scraping & data pipelines** that collect business data from the web, dedupe it and score it, then push it into a spreadsheet or CRM
- **Lead & outreach automation**: tracker sync, sequencing, reply detection, suppression lists
- **Alerting & watchdogs** on Telegram and email, so a broken job gets noticed the same hour
- **LLM workflows** on the Claude API: drafting, classification, extraction, chat assistants
- **Small internal dashboards** that give one owner a single place to see everything

### Live samples

All of them run on invented businesses, so you can click around freely.

- [Home services demo](https://demo.autonexuslabs.com/hvac-sample): an AI front desk for a heating and cooling company
- [Real estate demo](https://demo.autonexuslabs.com/sample-demo): an agent's listing assistant that answers after hours
- [Owner dashboard](https://autonexuslabs.github.io/owner-dashboard-pwa/): an installable phone app for leads, replies and automation health
- [Personalized landing pages](https://autonexuslabs.github.io/personalized-landing-pages/): one page per lead, generated from a spreadsheet

### Open-source projects

Each one is a small, tested, documented example of work I do for clients. The data is synthetic and the demos run offline.

| | Project | What it shows |
|---|---|---|
| 🧲 | [business-lead-scraper](https://github.com/autonexuslabs/business-lead-scraper) | Google Places (official API) → dedupe → website enrichment (emails, chat widget, booking platform) → CSV |
| 🎯 | [lead-scoring-engine](https://github.com/autonexuslabs/lead-scoring-engine) | Dedupe, exclude, gate and score leads from a JSON config, with a reason behind every point |
| 🤖 | [ai-chat-widget](https://github.com/autonexuslabs/ai-chat-widget) | One-tag Claude chat for a business site: answers from your facts, books visits, captures leads |
| ✍️ | [ai-reply-drafter](https://github.com/autonexuslabs/ai-reply-drafter) | Claude drafts customer email replies; a person reviews and approves each one |
| 📧 | [email-sequence-sender](https://github.com/autonexuslabs/email-sequence-sender) | Sequences that stop on reply: classification, suppression, CAN-SPAM checks, recipient time zones |
| 📩 | [gmail-reply-tracker](https://github.com/autonexuslabs/gmail-reply-tracker) | Incremental Gmail sync: find lead replies, star them, alert on Telegram |
| 📊 | [sheets-crm-sync](https://github.com/autonexuslabs/sheets-crm-sync) | Google Sheets as a CRM without overwriting what your team typed |
| 🚨 | [telegram-watchdog](https://github.com/autonexuslabs/telegram-watchdog) | Uptime and dead-man's-switch monitoring that alerts on change, not on every probe |
| 🔗 | [personalized-landing-pages](https://github.com/autonexuslabs/personalized-landing-pages) | Static page per lead: stable slugs, expiry, XSS-safe templates, GitHub Pages deploy |
| 📱 | [owner-dashboard-pwa](https://github.com/autonexuslabs/owner-dashboard-pwa) | React + Vite PWA: installable, offline, light and dark |
| 🕵️ | [link-scanner-detector](https://github.com/autonexuslabs/link-scanner-detector) | Tell real email clicks from Safe Links / Proofpoint scanners |
| 🔀 | [n8n-automation-workflows](https://github.com/autonexuslabs/n8n-automation-workflows) | Five importable n8n workflows with the Code-node logic unit-tested |

### Stack

`Node.js` · `JavaScript` · `Python` · `React` · `Vite` · `Vercel` · `Google Cloud Run` · `Redis` · `n8n` · `Claude API` · `Gmail API` · `Telegram Bot API` · `Google Sheets / Drive`

### Credentials

- n8n Foundations: [N8N101](https://badges.n8n.io/d2be139c-0938-49cc-bb5f-c8b48d42b583) · [N8N102](https://badges.n8n.io/55f72afe-d9e2-4398-9a9f-2c457888d8e3) · [N8N103](https://badges.n8n.io/44df8277-2ede-4932-8ce0-82513143e062)

### Work with me

I take freelance projects: fixed-scope builds, fixes to automations you already have, and ongoing maintenance.
Email **contact@autonexuslabs.com**, or find me on Upwork.
