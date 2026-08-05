# MarketTracker

A-share market daily tracking notebooks maintained as a private GitHub project.

## Current Mainline

- `market_daily_tracker_local_v1_26.ipynb`
- Runtime version inside the notebook: `v1.28`
- Purpose: daily A-share broad-index, sector-index, and sector-ETF tracking with K-line technical charts, fish-bowl model snapshots, Excel outputs, and PDF summaries.

## Historical Versions

The repository keeps the main historical notebooks found under `/Users/liam/Documents/Python/MarketTracker/`:

| File | Parsed Tracker Version | Analysis Cache | Raw Cache | Notebook Outputs |
| --- | --- | --- | --- | --- |
| `market_daily_tracker.ipynb` |  |  |  | 1 |
| `market_daily_tracker_local.ipynb` |  |  |  | 1 |
| `market_daily_tracker_local_optimized.ipynb` |  |  |  | 1 |
| `market_daily_tracker_local_v1_11.ipynb` |  |  |  | 1 |
| `market_daily_tracker_local_v1_12.ipynb` |  |  |  | 1 |
| `market_daily_tracker_local_v1_13.ipynb` |  |  |  | 1 |
| `market_daily_tracker_local_v1_14.ipynb` |  | `v114` |  | 1 |
| `market_daily_tracker_local_v1_15.ipynb` |  | `v115` |  | 1 |
| `market_daily_tracker_local_v1_16.ipynb` |  | `v116` |  | 1 |
| `market_daily_tracker_local_v1_17.ipynb` |  | `v117` |  | 1 |
| `market_daily_tracker_local_v1_18.ipynb` |  | `v118` |  | 1 |
| `market_daily_tracker_local_v1_19.ipynb` |  | `v119` | `raw_v119` | 2 |
| `market_daily_tracker_local_v1_20.ipynb` |  | `v120` | `raw_v120` | 1 |
| `market_daily_tracker_local_v1_21.ipynb` |  | `v121` | `raw_v121` | 1 |
| `market_daily_tracker_local_v1_22.ipynb` |  | `v122` | `raw_v122` | 1 |
| `market_daily_tracker_local_v1_23.ipynb` | `v1.23` | `v123` | `raw_v123` | 2 |
| `market_daily_tracker_local_v1_24.ipynb` | `v1.24` | `v123` | `raw_v123` | 5 |
| `market_daily_tracker_local_v1_25.ipynb` | `v1.25` | `v125` | `raw_v125` | 1 |
| `market_daily_tracker_local_v1_26.ipynb` | `v1.28` | `v128` | `raw_v127` | 1 |

`archived_checkpoints/` keeps orphaned Jupyter checkpoint files that were not present as mainline files in the top-level directory. They are separated from the mainline list because checkpoint contents can differ from their filenames.

## Repository Policy

- Keep source notebooks and maintenance notes in git.
- Do not commit generated Excel/PDF/PNG outputs or local market-data caches.
- Use `output_daily_tracker/` and `data_cache_daily_tracker/` locally for runs; both are ignored by git.
