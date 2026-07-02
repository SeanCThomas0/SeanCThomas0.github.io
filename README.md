# Sean Thomas

Software engineer in San Francisco. This is the source for my personal site,
[SeanCThomas0.github.io](https://SeanCThomas0.github.io).

I'm a founding engineer at Tex Software, where I spend most of my time on
document ingestion — OCR, entity resolution, and getting structured data out of
25+ million messy documents. Before this I did GIS work for the City of Fort
Wayne, and studied CS and math at Purdue (class of 2024).

## Work

### Tex Software — founding engineer (2026–present)

- Built the OCR/document-ingestion pipeline, which has processed over 25 million documents so far.
- Entity resolution and record linkage to dedupe records across sources that all disagree with each other.
- Automated ingestion across all 50 states, designed to recover from failures on its own.
- The React frontend (auth, role-based access) and a MapLibre + PMTiles map that stays fast on large geospatial datasets.

### City of Fort Wayne — GIS software engineer (2025–2026)

- RAG chatbot over city documents (Python, Azure AI Search).
- Automated a range of geospatial processing that was previously done by hand.

## Projects

### Kald

A location-based prediction market — native iOS (SwiftUI) and Android (Jetpack
Compose) apps on a Postgres/Supabase backend. The interesting part is making it
hard to cheat: identity is device-bound ECDSA keys with signed requests and
replay protection, all money movement happens inside `SECURITY DEFINER` Postgres
functions with row locking and idempotency keys, and outcomes settle through a
trust-weighted multi-resolver consensus system with signed disputes.

### [PrivyData](projects/PrivyData.md)

Runs statistical queries on student data under differential privacy (OpenDP), so
you can do aggregate analysis without being able to recover any individual's
records. Python/Flask.

### [JobTrackr](projects/JobTrackr.md)

Job application tracker with accounts and stats. Mostly an excuse to learn
Kubernetes. React/TypeScript/Postgres.

## Tech

Day to day I write Python, TypeScript, Swift, and Kotlin, with a lot of Postgres.
I've also shipped things in Java, Rust, C++, and C#. Comfortable with AWS, Azure,
Docker, and Terraform.

## About this site

A single hand-rolled `index.html` served via GitHub Pages. To view it live,
visit [SeanCThomas0.github.io](https://SeanCThomas0.github.io).
