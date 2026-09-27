# Data architecture project

**Portfolio context:** This repository is part of James Jennings' [Applied AI, Risk Analytics & Data Engineering portfolio](https://github.com/JJennings728/ZipSmart360/blob/main/PORTFOLIO.md).

**Status: planning repository.** This repository was created for the Yield Orbit Core data-platform concept. It does not yet contain infrastructure code or a deployed platform.

## Working architecture example

For a completed, reproducible local portfolio demonstration, see **[ZIPSmart](https://github.com/JJennings728/ZipSmart360)**:

- CSV ingestion with strict validation and duplicate detection.
- SQLite schema, constraints, index, and explicit aggregation queries.
- Reproducible CSV/JSON exports and a quality report.
- Dashboard and local read-only JSON API.
- Tests for data quality, calculations, repeatability, and HTTP responses.

[Read the architecture decisions](https://github.com/JJennings728/ZipSmart360/blob/main/docs/architecture.md) · [Review the SQL schema](https://github.com/JJennings728/ZipSmart360/blob/main/sql/schema.sql)

ZIPSmart is a synthetic-data demonstration. It is a separate project and does not establish that Yield Orbit Core has been implemented.
