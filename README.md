# Hi, I'm Naga Hema Ramishetty

**Data Analyst | SQL, Python, BigQuery, Tableau, dbt, Airflow, PySpark | Turning messy, real world data into decisions leadership can act on.**

I build end to end analytics workflows, not isolated scripts. From raw ingestion and pipeline orchestration through transformation, testing, and executive facing dashboards, each project below reflects the full analyst lifecycle a business actually runs on.

---

## 🧠 About Me

I recently completed my Master's in Computational Science and Data Science at UNC Charlotte. I'm a data analyst with a background spanning SQL and Python driven analysis, workflow orchestration, and stakeholder reporting. My projects are built the way production analytics work actually happens: messy source data, real infrastructure decisions, documented failures and fixes, and a final deliverable meant for someone outside the project to read and trust.

---

## 🚀 Projects

| Project                                                                                                                    | Description                                                                                                                                                                                                                         | Tools                                                     |
| -------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [GA4 Storefront Analytics](https://github.com/nagahemaramishetty/ga4-storefront-analytics) | Funnel, cohort retention, lifetime value, and multi-model attribution on 4.3M nested GA4 events in BigQuery; found and corrected four tracking issues (including a 5.9% revenue overstatement and self-referrals inflating 32% of revenue), validated every number in pandas, and built an interactive Data Studio dashboard | BigQuery, SQL, Python, pandas, Data Studio, Google Sheets |
| [Unified Commerce Data Pipeline](https://github.com/nagahemaramishetty/unified-commerce-data-pipeline)                     | End to end e-commerce analytics pipeline: synthetic data with injected real world messiness, idempotent Postgres loads, dbt layered transformations, Airflow orchestrated DAG, PySpark trend analysis, and a live Tableau dashboard | Python, PostgreSQL, dbt, Airflow, PySpark, Tableau, Excel |
| [Large-Scale Log Analysis & Anomaly Detection](https://github.com/nagahemaramishetty/log-analysis-anomaly-detection)       | Hybrid anomaly detection pipeline on 1.88M NASA HTTP server logs, combining Isolation Forest for point anomalies and ARIMA for temporal deviations, cutting false alert rate 39% versus threshold based alerting                    | Python, PySpark, Scikit-learn, Statsmodels, Matplotlib    |
| [Product Experimentation Analytics Engine](https://github.com/nagahemaramishetty/product-experimentation-analytics-engine) | A/B testing framework combining frequentist and Bayesian approaches with power analysis and cohort segmentation to support product decision making                                                                                  | Python, Statistical Testing, Cohort Analysis              |
| [End-to-End Supply Chain Analysis](https://github.com/nagahemaramishetty/end-to-end-supply-chain-analysis)                 | Supply chain analytics on a real world dataset using DuckDB for transformation, an automated PDF executive report, and Tableau visualization                                                                                        | DuckDB, Python, reportlab, Tableau                        |
| [NovaMart Supply Chain Intelligence Platform](https://github.com/nagahemaramishetty/NovaMart-supply-chain-analysis)        | Star schema supply chain model with SQL window function analysis, Random Forest demand forecasting, and Power BI dashboards                                                                                                         | SQLite, SQL, Random Forest, Power BI                      |

---

## 📍 Featured Projects

### [GA4 Storefront Analytics](https://github.com/nagahemaramishetty/ga4-storefront-analytics)

A product analytics project on Google's real GA4 export for the Google Merchandise Store, built the way a business intelligence team would approach it: data trusted only after it was profiled, corrected, and reconciled.

- Profiled 4.3M nested GA4 events in BigQuery and found four tracking issues before any analysis: double-fired purchases overstating revenue by 5.9%, an under-tracked add_to_cart step, self-referrals inflating 32% of revenue, and a late-January revenue gap
- Modeled reusable session and order tables, each reconciled exactly to independent counts (360,129 sessions, 5,372 orders)
- Answered five business questions with advanced SQL: funnel drop-off by segment, weekly cohort retention, observed lifetime value, multi-model attribution, and week-over-week trends
- Validated every headline number independently in pandas and added confidence intervals, including a bootstrap test that overturned an apparent channel advantage
- Live Data Studio dashboard with device, channel, and country filters, built on count-only sources so every rate stays correctly weighted

**[View Live Dashboard](https://datastudio.google.com/reporting/6deef37f-62c3-4ca2-bd4e-3f422d52f974)**

### [Unified Commerce Data Pipeline](https://github.com/nagahemaramishetty/unified-commerce-data-pipeline)

A full stack analytics pipeline built to mirror what a commerce analytics team actually runs in production.

- Synthetic e-commerce data with deliberately injected messiness: duplicate records, inconsistent date formats, orphaned foreign keys, late arriving records
- Idempotent Postgres loads via Python and psycopg2
- dbt staging, intermediate, and marts layers with automated tests
- Dockerized Airflow DAG orchestrating load, transform, test, and PySpark rolling revenue trend calculation
- Live Tableau Public dashboard and an Excel executive summary workbook

**[View Live Dashboard](https://public.tableau.com/views/UnifiedCommerceRevenueMarginAnalysis/UnifiedCommerceRevenueMarginAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 👩‍💻 Tech Stack

| Category                       | Tools                                                             |
| ------------------------------ | ----------------------------------------------------------------- |
| Languages                      | Python, SQL, R.                                                   |
| Databases                      | BigQuery, PostgreSQL, SQLite, DuckDB, MySQL                       |
| Transformation & Orchestration | dbt, Apache Airflow, PySpark.                                     |
| Visualization & Reporting      | Tableau, Power BI, Data Studio (Looker Studio), Excel, reportlab  |
| Analysis                       | A/B Testing, Funnel & Cohort Analysis, Attribution, Statistical Modeling, Time Series, Anomaly Detection |

---

## 📬 Connect

- 📧 [nagahemaramishetty2@gmail.com](mailto:nagahemaramishetty2@gmail.com)
- 🔗 **LinkedIn:** [https://www.linkedin.com/in/nagaramishetty/](https://www.linkedin.com/in/nagaramishetty/)
- 🔗 **GitHub:** [https://github.com/nagahemaramishetty](https://github.com/nagahemaramishetty)
