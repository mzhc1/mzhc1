### Python data pipelines with checked output

I build scrapers and data pipelines where every run ends with a count that has to add up: rows in = rows kept + rows removed, each removal with a reason.

**Client work (Upwork, ★5.0)**
- **10,000 unique collectibles** — layered artwork → 141 traits, weighted rarity, DNA hash per item, 0 duplicates, reproducible from one seed
- **Watch specifications** — 770 SKUs scraped into one clean spec table
- **Brand review datasets** — 16,414 reviews from 7 sites, de-duplicated into one Excel file

**Public projects**
| Repo | What it shows |
|---|---|
| [building-permit-scraper](https://github.com/mzhc1/building-permit-scraper) | Municipal portal with no API, 1,479 permits, output checked against the portal's own totals |
| [dubai-open-data-collector](https://github.com/mzhc1/dubai-open-data-collector) | Fetch → validate → Postgres → check report over two public data sources |
| [creator-contact-research](https://github.com/mzhc1/creator-contact-research) | Channel → verified business email, with a human review queue for anything uncertain |
| [round-sheet-demo](https://github.com/mzhc1/round-sheet-demo) | Offline Tkinter tool: confirm-before-commit entry, append-only journal, PDF print |

**Stack:** Python · pandas · Playwright · requests · PostgreSQL · Google Sheets / Apps Script · Excel

Based in Germany (CET). Open to freelance work.
