# Ozan Atmar

Operations and supply chain manager in Varna, Bulgaria. I run operations and supply chains, and I build the systems that make them faster.

Before this: 8 years running three-shift production for 150 people, 5 years running my own import and e-commerce companies, a software rollout with a team of about 15, and supply chain for a supplements startup. I understand the business before I write the code, and I work AI-first, every day.

Most of my code is private. Here is what it is.

## Supply chain systems

Since 2025 I build and run the systems the supply chain team of a consumer-goods company works with every day (the company stays anonymous):

- Each morning, stock, sales and incoming goods from a retailer portal and several warehouse platforms are written into the planning sheets automatically.
- Supplier spreadsheets in different formats are cleaned into a weekly report. 10 hours a week became 10 minutes.
- Order emails update the sheets and calculate next week's purchases.
- The demand forecast the team plans its purchases with, still in use.
- AI extracts and translates ingredients from product labels.

Google Apps Script, Make.com, a TypeScript API and AI.

## Shipped

| Product | What it does | Stack |
|---|---|---|
| [Truvex](https://truvex.app) | Fills restaurant shifts in one tap. One post notifies every qualified off-duty worker by push and SMS. Live on the App Store and Google Play. | React Native (Expo), Supabase, Twilio, Stripe, Next.js on Vercel |
| [Namedrop](https://namedrop.cc) | AI business name generator with live domain, X/TikTok handle and USPTO trademark checks. Customers in 40+ countries. | Next.js, Supabase, OpenAI, RDAP/DNS, Stripe |
| [Atmar Horeca](https://atmarhoreca.com) | B2B store for professional horeca equipment. Per-country EU VAT, VIES validation, auto-generated proforma invoices, 16-page admin panel. | Next.js, Supabase, Stripe |
| [SuppliMatch](https://supplimatch.com) | B2B sourcing with no signup. One request goes to matched co-packers, quotes come back by email. | Make.com, OpenAI, Notion |

## Also built

**AI email client** (private): aggregates Gmail, Zoho and IMAP/SMTP mailboxes into one inbox. An LLM classifies incoming mail and turns action items into tasks linked back to their source email, sending only metadata to the model, never message bodies. Incremental per-provider sync (Gmail history cursors, IMAP UIDVALIDITY), cross-provider threading, AES-256-GCM credential storage. TypeScript, Next.js, Supabase Postgres with RLS, Vercel Cron.

**Narrapixi**: automated short-video publisher. Extracts how books actually describe characters, places and objects, generates visual collages, and posts to YouTube, TikTok, X and Facebook on schedule.

**Client automation**: Make.com, n8n, Zapier and Google Apps Script wired into HubSpot, Slack, Airtable, Notion and Google Workspace. About 30 hours a week of manual supplier outreach replaced by one workflow. A lead-generation agency gets every sales call scored, graded and summarised into its CRM automatically.

**Earth Optional**: a space station supply chain game in Unreal Engine, in progress.

## Public here

- Make.com blueprints: [Notion bulk relations](https://github.com/ozanatmar/make-notion-add-multiple-relations), [Google Sheets chart to Slack](https://github.com/ozanatmar/make-post-sheet-data-as-chart-to-slack), [X posting with OAuth 1.0a](https://github.com/ozanatmar/make-post-to-x-oauth), [Transfermarkt values to X](https://github.com/ozanatmar/make-transfermarkt-to-x-post-market-value)
- [Notion templates](https://github.com/ozanatmar/notion-templates) for inventory and production, vendor contracts, project dashboards and finance

## Stack

- **Operations**: supply chain, purchasing, inventory, demand forecasting, production planning, process improvement
- **Automation**: Make.com · n8n · Zapier · Google Apps Script · Notion · Airtable
- **AI**: OpenAI and Claude APIs · Claude Code · agent workflows · prompt and context engineering
- **Code**: TypeScript · JavaScript · Python · PHP · React · React Native (Expo) · Next.js · Node.js · Tailwind
- **Data**: Postgres · Supabase · MySQL · MongoDB · Drizzle ORM
- **Infra and services**: Vercel · Stripe · Twilio · HubSpot · REST APIs and webhooks

## Elsewhere

[ozan.at/mar](https://ozan.at/mar) · [LinkedIn](https://www.linkedin.com/in/ozanatmar) · [Upwork](https://www.upwork.com/freelancers/ozanatmar) · [X](https://x.com/ozanatmar) · [Bluesky](https://bsky.app/profile/ozanatmar.bsky.social) · ozan@ozan.at

Turkish native, English and Bulgarian fluent, learning German, French and Italian. Open to operations, supply chain and project management roles across the EU, remote or with relocation.
