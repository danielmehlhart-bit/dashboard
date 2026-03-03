# Data Rules — Dashboard

## JSON Files
- Data files live in `data/`
- Updated by cron jobs (nightly) or manually
- Format: standard JSON, UTF-8

## Current Data Sources
- `data/support-dashboard.json` — Zoho Desk analytics (tickets, agents, CSAT, FRT/RT)

## Adding New Data
- Place JSON in `data/`
- Document the source and update frequency
- Commit and push so GitHub Pages serves it
