# Data Notes

This repository does not include the original business case prompt, source datasets, or any company-specific raw files.

The files in this `data/` folder are intentionally sanitized sample datasets created only to demonstrate the project workflow, table structure, KPI logic, and attribution methodology used in the portfolio case study.

## Why the Original Data Is Excluded

The original source files are excluded because this repository is intended to be a public-facing portfolio project. To keep the project shareable and professionally safe, the repo only includes:

- simplified sample data
- derived methodology documentation
- Tableau dashboard files created for portfolio review
- Python analysis workflow
- executive summary and visual outputs

## Sample Data Included

### `sample_campaign_metrics.csv`

A simplified network-level campaign performance dataset used to demonstrate KPI calculation logic.

Example fields:

- `month`
- `network`
- `spend`
- `impressions`
- `lift`
- `tv_attributable_purchases`

These fields support calculations such as:

- CPM = Spend / Impressions × 1,000
- CPV = Spend / Lift
- CR = TV Attributable Purchases / Lift
- CPA = Spend / TV Attributable Purchases

### `sample_attribution_data.csv`

A simplified spot-level attribution dataset used to demonstrate how TV airing timestamps can be aligned with short-term website traffic response.

Example fields:

- `airing_time`
- `network`
- `baseline_visitors`
- `observed_visitors`
- `incremental_visitors`

This supports the traffic-response validation logic used in the project.

## Data Privacy & Portfolio Scope

All sample values are synthetic and should not be interpreted as real campaign results. They are included only to make the repository understandable without exposing original source data.
