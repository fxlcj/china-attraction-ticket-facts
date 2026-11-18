# Changelog

Each entry records what changed and the date the official source was re-checked.
A figure never changes without its `checked_on` date changing with it.

## 2026-11-19 — DB backfill

- 1 entries appended from the site's curated `verified_facts` (source URLs already re-checked at DB ingest). Append-only, deduped by claim+source.


## 2026-11-19 — DB value sync (drift corrected)

- #8 `ticket`: Huangshan charges CNY 190 full fare (CNY 95 half fare) in regular seas… → Huangshan charges CNY 190 full fare (CNY 95 half fare) in regular seas… (DB checked 2026-11-19 06:30:00)
- Direction: DB `verified_facts` re-checked later than the repo row; DB is authoritative. Figures were silently stale here until now.

## 2026-11-14 — initial release

- 30 entries from the site's curated `verified_facts` (each source URL re-checked against its official page at DB ingest). CC BY 4.0.
