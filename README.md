# Vignesh Hariharan

Analytics engineer and data analyst based in Toronto. I build pipelines from ingestion through modeling to delivery — mostly Snowflake, dbt, Python, and SQL. Currently contracting at Instacart on platform integration; previously at StackAdapt on programmatic media analytics and data architecture.

[LinkedIn](https://www.linkedin.com/in/h-vignesh/) · [Tableau Public](https://public.tableau.com/app/profile/vignesh.hariharan4351/vizzes) · [Email](mailto:vigneshhariharan1992@gmail.com)

## Experience

**Solution Delivery Analyst (Contract)** — Instacart via Apex Systems, Feb 2026–Present

- Enterprise white-label e-commerce deployments across GCP, Firebase, and AWS
- SSO / identity provider integrations and end-to-end auth validation
- Cross-system deployment coordination on Terraform-provisioned infrastructure

**Data Architecture Analyst** — StackAdapt, Jun 2022–Oct 2025

- Production ELT on Snowflake: APIs, databases, event streams
- Operational analytics platforms (API → Snowflake → Tableau / ThoughtSpot)
- Journey, audience overlap, and reach/frequency data models

**Analyst, Programmatic Media** — StackAdapt

- Automated reporting pipelines and analytical models for internal and client teams
- Python GUI for self-service data extraction by non-technical users
- Standardized dashboard frameworks in Tableau and ThoughtSpot

**Senior Catalog Specialist / Catalog Associate** — Amazon, Feb 2016–Nov 2020

## Projects

### [Salesforce Opportunity Analytics Pipeline](https://github.com/Vignesh-Hariharan/salesforce-analytics-pipeline)

Event-driven reporting for Salesforce opportunities. Kestra orchestrates batched API extraction into Snowflake, dbt builds funnel and forecast marts, matplotlib renders charts, and results go to Slack and Asana. Parameterized subflows, scheduled polling, failure handling, CI.

`Kestra` `Python` `Salesforce` `Snowflake` `dbt` `SQL`

### [Multi-Touch Attribution Analytics](https://github.com/Vignesh-Hariharan/multi-touch-attribution)

End-to-end attribution pipeline on synthetic GA4 and ad data (~28K events, 220 conversions). Four models — first touch, last touch, linear, position-based — compared in Snowflake/dbt with a Tableau consumption layer.

Last-click undervalues prospecting display by ~190% vs position-based among paid-touch conversions.

`Snowflake` `dbt` `Python` `Tableau` `GA4`

### [Fraud Detection Pipeline](https://github.com/Vignesh-Hariharan/fraud-detection-pipeline)

1.3M credit card transactions through Snowflake and dbt feature engineering (15 features), Snowflake Cortex ML classification, and Slack alerting. Four incremental experiments: the 6-feature baseline outperformed the 15-feature full model on precision/recall for this dataset.

`Snowflake` `dbt` `Python` `Cortex ML`

## Stack

Snowflake · dbt · SQL · Python · Kestra · Tableau · ThoughtSpot · Power BI
