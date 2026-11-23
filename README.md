# Snowflake ecosystem 2026: one map, a new deep dive every Tuesday

> **Disclaimer.** Personal project, opinions are my own, not an official Snowflake resource. Verified against public docs on 2026-10-28.

Self-contained, offline HTML pages of the Snowflake AI Data Cloud, plus PNG exports. Every page is a single HTML file with embedded data, styles and scripts: no build step is needed to use it, and it makes no network requests at runtime. Open [`index.html`](index.html) to start: it links the ecosystem map and one topic guide per published topic, with Decide, Build, Learn and Connect tabs on one page.

## Views

| View | What it does |
|---|---|
| [Ecosystem map](ecosystem-map/snowflake-ecosystem-2026.html) | One picture of the platform: 16 groups, 108 capabilities, with Data Engineering, AI & Agents and Data Science & ML persona views (`?view=de\|ai\|ds`). |
| [Open Lakehouse / Iceberg](topics/snowflake-topic-2026-iceberg.html) | Topic guide: decide, build, learn and connect on one page. |

## How it was verified, and its limits

- Content was checked against **public** Snowflake documentation and Snowflake Developers guides (labs) only, on **2026-10-28**. It will be refreshed after Snowflake Expedition (November 2026); product names and release status may change.
- Lab and tutorial code was **not executed**. Links were checked to resolve, not to work end to end.
- Availability varies by edition, cloud, region, account and release status. Preview status is called out in the text where it was found in the docs; it is not a systematic badge on every tile, so confirm status in the docs before you plan on a feature.
- "No guide mapped" means no guide is mapped here, **not** that no guide exists.
- Workloads, graphs and paths are representative patterns, not complete architectures, recommendations or feature-availability guarantees.

## Rebuild and test

The Python builders and browser tests that generate these views are published with the final week of the series.

## License

- Content (text, diagrams, PNG images): [CC BY 4.0](LICENSE-CONTENT).
- Code (builders, tests, embedded scripts): [MIT](LICENSE).
- Icons: [Lucide](https://lucide.dev) (ISC License), version 1.72.0. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
- Snowflake names and logos are trademarks of Snowflake Inc. and are not covered by these licenses.

Author: Bart Wrobel.
