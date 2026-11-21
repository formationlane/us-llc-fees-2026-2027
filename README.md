# US LLC Fees and Deadlines by State (2026–2027)

State fees to form a domestic LLC, plus the recurring state report (annual or biennial), its fee, due date or rule, late penalty and any franchise or privilege tax, for **all 50 US states and the District of Columbia**. Each row links its official state sources.

- **Publisher:** Formation Lane, https://formationlane.com
- **Last checked against official state sources:** 30 October 2026 (`last_verified` = `2026-10-30`)
- **Rows:** 51 (50 states + DC)
- **Scope:** domestic LLC, calendar tax year. A blank cell means our data does not have that value; nothing is guessed.
- **Canonical page:** https://formationlane.com/data/ (human table: https://formationlane.com/guides/llc-fees-by-state/)
- **DOI:** [10.5281/zenodo.24424603](https://doi.org/10.5281/zenodo.24424603) (Zenodo)
- **License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Free to reuse, including commercially, with credit and a link.

## Files
| File | Format |
|---|---|
| `llc-fees-by-state-2026-2027.csv` | UTF-8 CSV, one row per state; `official_sources` is semicolon-separated |
| `llc-fees-by-state-2026-2027.json` | JSON object with dataset metadata and a `states` array (`official_sources` is an array) |

## Columns
| Column | Description |
|---|---|
| `state` | State or DC name |
| `code` | Two-letter postal code |
| `formation_filing_fee` | State fee to file a domestic LLC (with add-ons or alternatives as text) |
| `recurring_report` | Name of the recurring state report, or "No … annual report" |
| `report_fee` | Fee for that report (late fee in parentheses where published) |
| `due_date_or_rule` | Due date, or the rule that sets it |
| `franchise_or_privilege_tax` | Franchise, privilege or LLC tax named in our data |
| `late_penalty` | Late penalty for a missed report, when the state publishes one |
| `processing_time` | Official formation processing time, when the state publishes one |
| `notes` | State-specific caveats |
| `last_verified` | Date the row was last checked (YYYY-MM-DD) |
| `source` | CSV only: the Formation Lane table the row comes from |
| `official_sources` | Official state (or statute) URLs for the row |

Values are text as published by the state (for example `$60 online or paper ($25 late)`), not normalized numbers.

## Cite this dataset
> Source: Formation Lane (https://formationlane.com/data/)

Formation Lane, "LLC Fees and Deadlines by State (2026–2027)," https://formationlane.com/data/ (last verified 30 October 2026). https://doi.org/10.5281/zenodo.24424603

See `CITATION.cff` for machine-readable citation metadata.

## Also available as
- Zenodo (permanent DOI): https://doi.org/10.5281/zenodo.24424603
- Hugging Face: https://huggingface.co/datasets/formationlane/us-llc-fees-2026-2027
- Live MCP server for AI assistants: https://formationlane.com/mcp (docs: https://formationlane.com/for-agents/mcp/, code: https://github.com/formationlane/llc-fees-mcp)

## Corrections
Spot something out of date? Tell us via https://formationlane.com/contact/. The corrections log is on https://formationlane.com/data/.

## Disclaimer
State fees and due dates change. Confirm on the official state site before filing or quoting a number. This dataset is general information, not legal or tax advice.
