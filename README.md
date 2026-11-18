# E-commerce Sales & Customer Behavior

**Maksym Voronenko | Data Analyst**

An analysis of e-commerce sales estimates, website sessions, customer profiles, and acquisition channels using SQL, Python, statistical methods, and Tableau.

**Tools:** SQL, Google BigQuery, Python, pandas, SciPy, statsmodels, Matplotlib, Seaborn, Tableau.

[View the notebook](ecommerce_sales_customer_behavior.ipynb) · [Open in Google Colab](https://colab.research.google.com/drive/1PPy0e0EvnxNOGWxIISLjSYBjdRls41VF)

## Analysis

- Extract and join session, account, order, and product data with SQL in BigQuery.
- Identify leading continents, countries, product categories, devices, and traffic sources.
- Analyze registered accounts, email verification, and newsletter subscription status.
- Explore daily sales estimates, weekday patterns, and differences across segments.
- Examine correlations with time-dependence diagnostics, HAC standard errors, and Bonferroni correction.
- Compare groups using paired t-tests, chi-square tests, two-proportion z-tests, and Mann–Whitney U tests.

## Dataset Snapshot

Figures below are taken from the notebook's saved output for the Tableau extract.

| Metric | Value |
| --- | ---: |
| Sessions | 336,076 |
| Registered accounts | 27,945 |
| Revenue estimate | 31,971,731.10 |
| Primary purchase-analysis window | November 1, 2020–January 27, 2021 |

Revenue is estimated from the sum of recorded product prices; quantities and transaction totals are unavailable. The notebook documents the analysis windows and interpretation of its statistical results.

## Tableau Dashboards

### Sales Overview

Revenue estimates, sessions, purchasing sessions, purchase rates, trends, and leading countries and product categories. Controls include date, continent, device, Top N, and time level.

[Open Sales Overview](https://public.tableau.com/app/profile/maxim.voronenko2142/viz/Project1_17939128738000/SalesOverview)

![Sales Overview dashboard](https://public.tableau.com/static/images/Pr/Project1_17939128738000/SalesOverview/1.png)

### Audience and Acquisition

Registered-user, email-verification, unsubscribe, and organic-traffic KPIs; sessions by channel and device; leading countries by registered users; and recorded purchase rates by device.

[Open Audience and Acquisition](https://public.tableau.com/app/profile/maxim.voronenko2142/viz/Project1_17939128738000/AudienceandAcquisition)

![Audience and Acquisition dashboard](https://public.tableau.com/static/images/Pr/Project1_17939128738000/AudienceandAcquisition/1.png)

## Repository Contents

| File | Contents |
| --- | --- |
| `ecommerce_sales_customer_behavior.ipynb` | Original notebook with its code, analysis, saved tables, and charts |
| `README.md` | Project overview, notebook link, and Tableau links and previews |

## Run the Notebook

Open the notebook in Google Colab, run the dependency-installation cell, authenticate with a Google account that has access to the `data-analytics-mate` BigQuery project and its referenced `DA` tables, and run the cells in order.

The repository includes the notebook's saved outputs. Access to the BigQuery source data is required to recompute them.
