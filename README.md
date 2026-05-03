# NSE-Emerging-Markets-FX-Equity-Stress-Testing-
This project builds a reproducible equity panel dataset for the Nairobi Securities Exchange (NSE) spanning 2007–2025 and implements a framework for emerging market stress testing using Extreme Value Theory (EVT).

Emerging market financial datasets are often fragmented, inconsistent, and not structured for direct quantitative analysis. This project addresses that gap by constructing a clean, research-ready panel dataset from raw historical NSE equity records spanning 19 years.

The pipeline supports:

time-series return construction

cross-sectional equity analysis

portfolio risk aggregation

extreme value (tail risk) modelling

stress testing under market shock scenarios


Key Features
Multi-year NSE dataset harmonisation (2007–2025)

Stock-level panel construction (code × date structure)

Return computation and cleaning

Missing data handling in EM environments

Ready integration for EVT / GPD modelling

Portfolio stress testing framework (in development)


Research Motivation

Unlike developed market datasets (e.g. CRSP, Bloomberg), emerging market datasets require significant preprocessing before being usable for quantitative modelling. This project treats data construction as part of the research problem rather than a preprocessing step.

Current Stage
Data pipeline: complete

Feature engineering: in progress

EVT modelling: upcoming

Portfolio stress testing: upcoming

## Author
## Maina Silvia
