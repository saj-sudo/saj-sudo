# Hi, I'm Saj.

I started by knocking on doors for environmental justice campaigns. Now I run a national direct response data program by day and build tools by night. The arc from organizer to data practitioner to builder shapes everything I make: start with the specific person, then build the thing they actually need.

Everything below was built with Claude Code as the build tool; the architecture and data decisions are mine.

---

## What I'm building

**[CivicRadar](https://civicradar.co)** · Live
Civic action that starts from who you are. Pick every identity and issue you hold, and it ranks the state, federal, and city council bills that touch any of them, with every advocacy org's public position on the same card: 2,055 positions from 139 organizations across 48 states, DC, and Congress. Then it helps you act, with a letter or call script, testimony for a hearing, a comment to a utility commission, or a thank-you when your legislator votes your way. Matching is a deterministic scorer across 27 identity and 30 issue tags; AI drafting is opt-in and off by default. It also flags copycat bills moving across states, with a page that diffs each verified pair sentence by sentence. Every advocacy org gets its own page, and an election module hands you off to your state's official voting lookups and shows how your own legislators voted on your issues, as plain rows rather than a score. Your profile lives in your browser, and nothing about you is stored unless you sign up for alerts. Next.js, TypeScript, Upstash, Cloudflare R2, Claude Haiku, Gemini; OpenStates, LegiScan, Congress.gov, and Legistar.

**[Euphora](https://euphora.app/welcome)** · Live
Speech and voice practice across five lanes, from stuttering to confidence to gender-affirming voice work, built around one refusal: it will not score your fluency with AI. Pitch and resonance get measured on-device because they can be measured honestly; fluency does not, because the detection fails and the score rewards the wrong goal. Recordings never leave your device, and there is no backend and no account.

**[Funding Atlas](https://saj-sudo.github.io/funding-atlas/)** · Live · open source
An open registry of the public funding a town can apply for, read straight from federal and state agencies every day. Grants.gov lists direct federal awards only; money passed through state agencies shows up only on their own sites, so 26 connectors read Grants.gov, SAM.gov Assistance Listings, and state agency portals from California to New York. Every record is hashed, so each state page and its Atom and JSON feed say what is new, what moved, and what disappeared. It will not guess: a field the source never stated stays blank, an unclear status stays unknown, and the analysis lives in SQL views anyone can read. Python, SQLite, and a static site rebuilt on GitHub Actions. ([repo](https://github.com/saj-sudo/funding-atlas))

**[Livability map](https://github.com/saj-sudo/livability-map)** · Open source, not yet deployed
A global map that puts projected 2050 climate hazards next to present-day wellbeing and the things you weigh yourself: jobs, transit, rent, schools, LGBTQ+ presence. It won't tell you where to live. It shows the evidence, where it came from, and where the gaps are (missing data stays missing, never zero). Outside the countries with rich census data, it adds travel time to care and to a city, relative wealth ranked within each country, conflict nearby, and whether local water points are working. A Python pipeline over 58 open-licensed sources on H3 hexagons, from regional scale down to neighborhoods, with a Next.js and MapLibre front end.

**Untitled taste portrait** · In development
A taste portrait for movies, TV, games, and books, built from your own ratings and your own words instead of averaging you into people like you.

---

## Open source

- **[Funding Atlas](https://github.com/saj-sudo/funding-atlas)**, above. Code MIT, records under the Open Database License.
- **[Farview](https://github.com/saj-sudo/farview)** ([farview.dev](https://farview.dev)) shows your Capacities goals and projects across time, on a timeline and a set of horizons. It runs entirely in the browser and is read-only unless you opt into editing.
- **[Yesteryear](https://github.com/saj-sudo/yesteryear)** ([yesteryear.dev](https://yesteryear.dev)) brings older Capacities notes back on a cadence, with no streaks and no guilt, and keeps its history inside your own space rather than on a server.
- **[Livability map](https://github.com/saj-sudo/livability-map)**, above.

Farview and Yesteryear read your space's actual schema instead of hardcoding one, so they work on spaces they have never seen, and their builds fail on any accessibility violation in light or dark, on a phone or a desktop.

---

## Day job

Data Manager at the **Human Rights Campaign**. Every direct response pull runs through me: direct mail, email and SMS, telemarketing, and events. That means audience selection, suppression logic, and quality control across 10 million constituent records in a CRM and a data lakehouse, worked alongside a national voter file. I also build the analyses the team plans from, most recently nine years of event attendees and invitees, curated across systems that don't natively join, which changed how invite lists get built.

Self-taught SQL. Production-level now.

---

## Stack

**Languages and data:** SQL (Redshift, Oracle, PostgreSQL, SQLite), Python (pandas, geopandas, H3, httpx, pydantic), TypeScript

**Frontend:** Next.js, React, Preact, Vite, Tailwind, MapLibre, Capacitor

**Data work:** CRM at scale, cloud data warehouse, voter file, audience and suppression logic, semantic layer

**AI and infra:** Claude API, Gemini, Vercel, Cloudflare Workers and R2, GitHub Actions and Pages, OAuth with PKCE, axe-core and Playwright in CI

**APIs:** OpenStates, LegiScan, Congress.gov, Legistar, Grants.gov, SAM.gov, Capacities, TMDB, IGDB, Open Library

---

## What I'm building toward

Work at the intersection of data systems, AI governance, and technical program management. I care about how data systems get built, who they serve, and whether the people closest to the problem have a say in the tools.

---

## Contact me

[sajchandoo.com](https://sajchandoo.com) · hello@sajchandoo.com
