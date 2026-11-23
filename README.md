# Hi, I'm Tarifur 👋

**Senior Analytics Engineer.** I build the data foundations teams can trust (clean pipelines, well-tested models, dashboards people actually use) and then use that foundation to answer the harder question: *what actually moves the outcome?*

## What I work on

- 🏗️ **Data modeling:** layered dbt projects (staging → intermediate → marts), one model per grain
- ✅ **Data quality:** tests, documentation and lineage so every number is defensible
- 📊 **Causal analysis & experimentation:** separating what correlates from what drives results
- 🤝 **Stakeholder partnership:** turning vague business questions into scoped, answerable ones

## Tech stack

**SQL** · **dbt** · **Python** (pandas, statsmodels, pytest) · **BigQuery** · **DuckDB** · **GitHub Actions** · **sqlfluff** · **[Snowflake / Postgres]** · **[Airflow / Dagster]** · **[Tableau / Looker]** · **Git**

## Featured project

### [Analytics Engineering Portfolio](https://github.com/tarifurrah/analytics-engineering-portfolio)
A multi-domain analytics platform built like a production team would build it: messy raw data in, tested and governed data products out, deployed by CI/CD.

- **Messy data cleanup:** four timestamp formats, synonyms, null placeholders and duplicates normalised by reusable macros; bad rows quarantined with a reason, never silently dropped
- **Private vs public tables:** dbt groups and access levels keep each domain's internals private; consumers get contract-enforced, PII-free public tables
- **Tests:** 8 dbt unit tests, 68 data tests and 35 Python tests, plus SQL and Python linting
- **CI/CD:** every pull request is linted, tested and built; merging to main deploys production, docs and public data to GitHub Pages
- **First domain, customer experience:** a naive analysis says fast support replies cut churn by 2.3 pts; three causal methods, checked against ground truth, show it's ~4 pts

## Get in touch

[LinkedIn](https://linkedin.com/in/tarifur) · [Email](mailto:tarifurrahman@yahoo.com)
