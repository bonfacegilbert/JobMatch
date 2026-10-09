# JobMatch

A job-matching app that connects job seekers with newly hiring firms and cooperatives based on their preferences.

- **On-site jobs:** USA
- **Remote jobs:** worldwide

This repo currently holds a working front-end prototype (single HTML file, no build step, sample data).

## Features (prototype)

- Preference profile: skills, work type, US state, sector, employer type (company, cooperative, nonprofit), minimum pay, experience level
- Skill-based match score with a short "why it matched" note
- "Newly hiring" badge and filter (postings from the last 14 days)
- Employer and cooperative job posting form
- Saved jobs (browser localStorage) and a demo alert form (email, SMS, WhatsApp; sends nothing yet)
- Light and dark theme, responsive layout

## Run it

Open `index.html` in any browser. No install needed.

## Roadmap

1. User accounts and saved preference profiles
2. CV upload with skill extraction
3. Real backend: Node.js or Python API with PostgreSQL
4. Job data sources: direct employer and co-op postings, licensed job APIs (e.g. Adzuna, Jooble), public ATS feeds (Greenhouse, Lever)
5. Search upgrade: Postgres full-text search, then Meilisearch or Elasticsearch
6. Real notifications: email, SMS, WhatsApp
7. Employer verification and auto-expiring listings
8. AI-assisted matching that explains why a job fits

## Data and privacy notes

- Do not scrape sites whose terms forbid it (e.g. LinkedIn, Indeed); use licensed APIs and public feeds.
- Treat CVs and contact details as personal data: collect only what is needed and let users delete it.

## License

MIT
