# 2026 Global Digital Gaming Regulatory & Tax Benchmark Dataset

## Overview
A structured, machine-readable dataset benchmarking regulatory frameworks, fiscal structures, licensing models, and compliance requirements across 24 regulated online gaming jurisdictions as of **Q4 2026**.

The dataset is designed for comparative policy research, regulatory compliance analysis, fiscal modeling, and automated market-entry assessments across Europe, North America, Latin America, the Caribbean, and Africa.

* **Primary File:** [`data/global_gaming_regulatory_benchmark_2026.csv`](data/global_gaming_regulatory_benchmark_2026.csv)
* **Coverage:** 24 regulated jurisdictions (ISO 3166-1 / 3166-2 coded)
* **Attributes:** 19 standardized regulatory, fiscal, and operational variables
* **Verification Snapshot:** 2026-Q4

## Schema Overview

| Field | Description |
|---|---|
| `jurisdiction_iso` | ISO 3166-1 alpha-2 or ISO 3166-2 subdivision code (e.g., `GB`, `CA-ON`, `US-NJ`) |
| `jurisdiction_name` | Official jurisdiction name |
| `region` | Geographic macro-region |
| `market_model` | Licensing structure (Open Licensing, Concession/Tender, Hybrid/Skin-Based, Direct) |
| `primary_regulator` | National or regional regulatory authority |
| `governing_statute` | Primary legislative act governing remote gaming |
| `online_casino_status` | Legal status of online RNG/live casino operations |
| `online_sportsbook_status` | Legal status of online fixed-odds sports betting |
| `b2b_license_required` | Mandatory B2B software/supplier permit status (`Yes`, `No`, `Registration Only`) |
| `tax_basis` | Primary fiscal calculation base (`GGR`, `AGR`, `Turnover`, `Mixed`, `Fixed Fee`) |
| `headline_tax_rate_pct` | Primary statutory tax rate (%) used for cross-market comparison |
| `tax_structure_notes` | Detailed breakdown of tiered duties, levies, and product-specific rates |
| `license_term_years` | Standard license duration (`Indefinite` or integer years) |
| `national_self_exclusion_registry` | Centralized player exclusion system or operator-level requirement |
| `advertising_restriction_tier` | Regulatory strictness (`Moderate`, `High`, `Strict / Near-Ban`) |
| `local_presence_required` | Domestic incorporation, EU/EEA domicile, or land-based partner requirement |
| `crypto_payments_permitted` | Permissibility of direct cryptocurrency payment rails |
| `compliance_complexity_index` | Composite ordinal index (`1` = low barrier to `5` = high technical/fiscal complexity) |
| `last_verified_period` | Quarter of statutory verification (`2026-Q4`) |

## Methodology & Scope
Data points are compiled from statutory legislation, official regulatory bulletins, and public tax schedules effective through Q4 2026. Where jurisdictions apply differentiated rates across product verticals (e.g., slots vs. table games or casino vs. sportsbook), `headline_tax_rate_pct` reflects the primary remote gaming rate while full product-level nuances are documented in `tax_structure_notes`.

## Data Reference & Documentation
* **Industry Regulatory Reference:** [2WinPower Research & Documentation](https://2wpower.com/en)
* **Repository:** https://github.com/flcoin/digital-gaming-regulatory-dataset-2026
* **Zenodo Archive (DOI):** [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24585731.svg)](https://doi.org/10.5281/zenodo.24585731)


## License
Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for full terms.
