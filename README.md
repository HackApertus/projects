---
created: 2026-10-31
---

# Hack Apertus project data

Public, read-only JSON for the Hack Apertus project pages. JSON contract: schema_version 1;
manifest, projects, stats, participants_stats. Technical reports: reports/<slug>.pdf next to
the JSON of each stage, as submitted by the teams (links.report is this path).

- hackapertus/v1/next/ and current/: submitted projects (only consented, public fields; participant numbers aggregated, groups under 5 folded).
- hackapertus/test/v1/next/ and current/: synthetic test data (fictional submissions and aggregate registrations). Not production data.

Report problems: https://github.com/HackApertus/projects/issues
