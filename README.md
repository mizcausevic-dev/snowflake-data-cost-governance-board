# snowflake-data-cost-governance-board

Board-readable Kinetic Gain proof repo for **Snowflake** platform and company signal coverage.

## Product thesis

Warehouse cost and trust degrade when credit burn, query ownership, sharing contracts, and model lineage are separated.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** Data platform leaders, analytics engineering, FinOps, and finance operators
- **Signal domain:** Data Engineering
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product links warehouse spend, query variance, data sharing, lineage risk, and remediation ownership in one board-ready view.
- **Value architecture:** Leaders can identify waste, protect trusted data products, and decide which workloads deserve optimization investment.

## What this repo proves

- **Normalize:** messy Snowflake operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: Snowflake query history, credits, warehouses, shares, tags, dbt models, and owner metadata.

This is synthetic proof only. It does not connect to live Snowflake tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- Snowflake
- warehouse cost
- data governance
- credit burn
- lineage
