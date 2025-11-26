# Data Folder

This folder contains all datasets used for the Agentic FB Ads Analyst project.

## Files

### 1. sample_fb_ads.csv
A lightweight version used for development.  
Columns expected:
- date
- campaign_name
- adset_name
- impressions
- clicks
- ctr
- spend
- purchases
- revenue
- roas
- creative_type
- creative_message
- audience_type
- platform
- country

### 2. full_fb_ads.csv
Full dataset (not included in repo).

## Notes
- Controlled via `config/config.yaml`
- Never commit full datasets.
