# NSE-Emerging-Markets-FX-Equity-Stress-Testing-

# Status: Research in Progress  
# Focus: Emerging Markets | Risk Modelling | Data Construction  

## Overview

This repository develops a reproducible pipeline for constructing a research-ready equity panel dataset from Nairobi Securities Exchange (NSE) historical data (2007–2025) and applying quantitative risk modelling techniques, including Extreme Value Theory (EVT), for portfolio stress testing.

Emerging market datasets are often fragmented and inconsistent, limiting their direct use in financial modelling. This project addresses that gap by integrating data engineering and financial econometrics into a unified workflow.

## Research Objectives

- Construct a consistent stock-level panel dataset from raw NSE files

- Enable return computation and cross-sectional analysis

- Develop a framework for portfolio construction

- Apply EVT methods for tail risk estimation

- Evaluate stress scenarios in an emerging market context


## Raw Dataset Description
Coverage: 2007–2025

Observations: ~300,000+

Structure: Panel (date × stock code)


## Core variables:
date

code

day_price

return

volume (partial coverage)


## Methodology Pipeline

Raw NSE Files
    ↓
    
Data Cleaning & Harmonisation
    ↓
    
Panel Dataset Construction
    ↓
    
Return Computation
    ↓
    
Portfolio Construction
    ↓
    
EVT Tail Risk Modelling

## Key Challenges (Emerging Market Context)

- Inconsistent schema across years
  
- Missing observations in price and volume
  
- Sparse liquidity for certain assets
  
- Structural breaks in time series

These characteristics are explicitly accounted for in the data pipeline and modelling approach.

## Repository Structure
src/ → core pipeline and modelling code

notebooks/ → exploratory and validation analysis

data/processed/ → clean dataset (parquet)

outputs/ → figures and results

docs/ → methodology and dataset notes

## Current Status

 Data pipeline: complete

 Return computation: complete

 Portfolio construction: in progress

 EVT modelling: upcoming


## Reproducibility
To run the pipeline:

pip install -r requirements.txt

python src/data_pipeline.py

python src/feature_engineering.py

## Research Contribution

This project demonstrates how data construction forms a critical component of financial modelling in emerging markets, where standardized datasets are limited. It provides a foundation for systematic risk analysis and stress testing within frontier equity markets.

## Author
## Maina Silvia
