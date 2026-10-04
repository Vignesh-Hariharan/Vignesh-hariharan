# Vignesh Hariharan

Analytics engineer in Toronto. SQL, dbt and Python on Snowflake, with a background in marketing measurement and data quality.

[LinkedIn](https://www.linkedin.com/in/h-vignesh/) · [Tableau Public](https://public.tableau.com/app/profile/vignesh.hariharan4351/vizzes) · [Email](mailto:vigneshhariharan1992@gmail.com)

8+ years across advertising, retail and platform data. At StackAdapt, a programmatic advertising platform, I ran attribution reporting for 40+ brands, owned the data-quality checks behind media reporting (including a hard fail when spend drifted more than 3% from the source of truth), and automated recurring Python and SQL workflows across Snowflake, Redshift and MySQL that replaced about 80 manual runs a week. I'm now a Business Analyst III at Instacart, delivering retail partner launches on Storefront Pro and enabling Carrot Ads.

## Projects

**[Multi-Touch Attribution](https://github.com/Vignesh-Hariharan/multi-touch-attribution)**
Python, Snowflake, dbt and Tableau over GA4-schema events and ad impressions. The same 277 purchases give paid media $0 of credit under last-touch and $20.6K under first-touch, out of $38.5K. Tests fail the build unless every purchase is attributed and every model reconciles to revenue, and CI rebuilds the marts on DuckDB and checks them against the Snowflake exports.
[Dashboard](https://public.tableau.com/app/profile/vignesh.hariharan4351/viz/Multi-TouchAttributionAnalysis/Multi-TouchAttributionAnalysis)

**[Salesforce Opportunity Analytics](https://github.com/Vignesh-Hariharan/salesforce-analytics-pipeline)**
Request-driven Kestra workflow: tagging an Asana task queues a run. Salesforce API to idempotent `MERGE` loads in Snowflake, then dbt marts for stage conversion from `OpportunityHistory`, time in stage, close rate and a win-rate pipeline forecast that flags fallback weights. Results go to Slack.

**[Fraud Detection](https://github.com/Vignesh-Hariharan/fraud-detection-pipeline)**
dbt feature engineering and Snowflake Cortex classification on 1.3M Sparkov transactions. Three features leaked; V2 rebuilds them point-in-time and measures the bias on a later-period holdout: about 2 points of recall at the top 1%, with PR-AUC flat.

## Experience

| Role | Company | Dates |
| --- | --- | --- |
| Business Analyst III, Solution Delivery (contract via Apex Systems) | Instacart | Feb 2026 – present |
| Data Architecture Analyst | StackAdapt | Jan 2025 – Oct 2025 |
| Analyst, Programmatic Media | StackAdapt | Jun 2022 – Dec 2024 |
| Senior Catalog Specialist | Amazon | May 2018 – Nov 2020 |
| Catalog Associate | Amazon | Feb 2016 – May 2018 |

## Stack

SQL, Python, dbt · Snowflake, Redshift, BigQuery, MySQL, DuckDB · Kestra, Terraform, AWS · Tableau, ThoughtSpot, Looker Studio · Git, GitHub Actions
