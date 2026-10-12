# Awesome-Marketing-Analytics-BI

## Top Marketing Analytics & BI Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Marketing Data Integration, Unified Reporting & Business Intelligence*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Marketing Analytics & BI Tools**. These tools connect marketing channels, ad platforms, CRMs, and analytics sources into unified reporting layers — enabling attribution analysis, campaign performance tracking, and self-service business intelligence without manual CSV exports.

**Examples** include Salesforce Marketing Cloud Intelligence, Supermetrics, Funnel.io, Improvado, Adverity, Singular, Looker Studio, Triple Whale, Polar Analytics, and DashThis (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom marketing data pipelines, and transparent BI — ideal for growth teams, data analysts, and developers building data-sovereign marketing analytics.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Marketing Cloud Intelligence](https://www.salesforce.com/)**  
  Enterprise marketing analytics and BI platform unifying cross-channel data for attribution, reporting, and optimization.

- **[Supermetrics](https://supermetrics.com/)**  
  Marketing data connector and reporting platform pulling data from 100+ sources into Google Sheets, Looker Studio, and data warehouses [citation:11].

- **[Funnel.io](https://funnel.io/)**  
  Marketing data hub that collects, normalizes, and unifies data from ad platforms, analytics, and CRMs for BI tools.

- **[Improvado](https://improvado.io/)**  
  Marketing analytics platform with ETL pipelines, data warehousing, and customizable dashboards for enterprise teams.

- **[Adverity](https://www.adverity.com/)**  
  Marketing data integration and analytics platform with governance, transformation, and multi-client management [citation:12].

- **[Singular](https://www.singular.net/)**  
  Marketing analytics platform with unified attribution, cost aggregation, and ROI reporting across mobile, web, and CTV.

- **[Looker Studio](https://lookerstudio.google.com/)**  
  Google's free BI and reporting tool with native connectors for marketing platforms and data warehouses.

- **[Triple Whale](https://www.triplewhale.com/)**  
  E-commerce analytics platform with profit tracking, attribution, and marketing intelligence for Shopify brands.

- **[Polar Analytics](https://www.polaranalytics.com/)**  
  E-commerce BI platform unifying marketing, sales, and product data for D2C brands [citation:19].

- **[DashThis](https://dashthis.com/)**  
  Marketing reporting platform with automated dashboards, 30+ integrations, and client-ready templates.

## Open-Source GitHub Projects

- **[OWOX Data Marts](https://github.com/OWOX/owox-data-marts)**  
  Open-source self-service analytics platform that automates marketing reporting without semantic layers. Analysts build SQL data marts; business users browse and filter in Google Sheets, Looker Studio, Slack, or email. Connectors for Facebook Ads, Google Ads, TikTok, Shopify, and more. JavaScript-based, MIT licensed [citation:11].

- **[marketing-data-hub](https://pypi.org/project/marketing-data-hub/)**  
  Open-source Windsor.ai alternative that pulls Google Analytics 4, Search Console, Google Ads, Meta Ads, and YouTube into a local database. Queryable via REST API, scheduled CSV exports, and AI assistants (MCP). No hosted service, no subscription — tokens never leave your machine. Python-based [citation:2].

- **[Matomo](https://github.com/matomo-org/matomo)**  
  Leading open-source web analytics platform (Google Analytics alternative) with 70+ plugins including SEO dashboards, funnel analysis, heatmaps, and eCommerce tracking. Self-hosted with full data ownership, GDPR compliance, and embeddable widgets. PHP/MySQL stack [citation:6].

- **[Jitsu](https://github.com/jitsucom/jitsu)**  
  100% open-source event data collection platform streaming website, app, email, and CRM data to data warehouses (Snowflake, BigQuery, Redshift, Postgres, ClickHouse). Simple tag deployment like Segment. MIT licensed, self-hosted with free tier for 200K events [citation:8][citation:18].

- **[Insights](https://github.com/mariusandra/insights)**  
  Open-source self-hosted BI platform (Looker Studio alternative) for visually exploring PostgreSQL databases. Auto-detects schema, creates time-based graphs, filters, and saved views. MIT-licensed Sponsorware. Node.js-based [citation:4].

- **[Lightdash](https://github.com/lightdash/lightdash)**  
  Open-source Looker alternative that integrates directly with dbt projects. Define metrics and dimensions in dbt YAML; business users self-serve through familiar interfaces. Self-hosted free or cloud option. Typescript/React stack [citation:9][citation:14].

- **[OverSeek](https://github.com/MerlinStacks/overseek)**  
  Self-hosted WooCommerce operations dashboard unifying analytics, marketing, inventory, and customer intelligence. Features revenue attribution, cohorts, CLV, email marketing, inbox, and PWA mobile support. PostgreSQL + Elasticsearch + Redis stack [citation:1].

- **[OpenPanel](https://github.com/Openpanel-dev/openpanel)**  
  Open-source Mixpanel alternative combining product analytics with Plausible-like simplicity. Features funnels, cohorts, session replay, A/B testing, revenue tracking, and MCP server for AI queries. Next.js + ClickHouse + PostgreSQL + Redis stack. No usage limits [citation:16].

- **[Multiwoven](https://github.com/Multiwoven/multiwoven)**  
  Open-source Reverse ETL platform (HighTouch/Census alternative) syncing warehouse data to marketing tools (Salesforce, HubSpot, Klaviyo, Braze, Google Ads, Facebook Ads). Sources: Redshift, BigQuery, Snowflake, Databricks. AGPL-3.0 licensed [citation:7][citation:17].

- **[Talivia](https://github.com/talivia-group/talivia)**  
  Open-source revenue-first analytics platform with web analytics, session replay, and customer revenue from Stripe, LemonSqueezy, and Polar. Features first/last-touch attribution and subscription lifecycle tracking. MIT licensed, self-hosted [citation:10].

- **[OpenMetrics Analytics](https://github.com/blueorbitware/openmetrics-analytics)**  
  Self-hosted product analytics platform with event ingestion, funnels, dashboards, and multi-tenant workspaces. Collector → Redis Streams → ClickHouse pipeline for high-throughput analytics. Go + Next.js stack [citation:5].

### Additional Strong Open-Source Options

- **[Airbyte](https://github.com/airbytehq/airbyte)** — Open-source ELT platform with 300+ connectors for marketing data integration into warehouses. Self-hosted free or cloud from $10/month [citation:12][citation:13].
- **[Metabase](https://github.com/metabase/metabase)** — Open-source BI tool for exploring marketing data with visual query builder and dashboards.
- **[Apache Superset](https://github.com/apache/superset)** — Enterprise-grade open-source BI with rich visualization and SQL Lab.
- **[Grafana](https://github.com/grafana/grafana)** — Open-source observability and analytics dashboards for marketing metrics.
- **[PostHog](https://github.com/PostHog/posthog)** — Open-source product analytics with funnels, session replay, and feature flags.
- **[Plausible](https://github.com/plausible/analytics)** — Lightweight, privacy-focused open-source web analytics.
- **[Umami](https://github.com/umami-software/umami)** — Simple, self-hosted open-source analytics alternative.
- **[Listmonk](https://github.com/knadh/listmonk)** — Open-source newsletter and mailing list manager for marketing communications.
- **Data Transformation** — dbt Core, SQLMesh, and Dataform for marketing data modeling.
- **Orchestration** — Apache Airflow, Dagster, Prefect for marketing pipeline scheduling.

**Frameworks for building custom systems**: Combine **OWOX Data Marts** or **marketing-data-hub** for data ingestion, **Lightdash** or **Insights** for BI, **Jitsu** for event collection, **Airbyte** for ELT, and **Metabase + ClickHouse** for dashboards to build a complete self-hosted marketing analytics stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Marketing analytics tools must comply with data protection regulations (GDPR, CCPA), platform API terms, and consent requirements.
- Self-hosted open-source solutions require proper security hardening, data governance, and pipeline maintenance.

---

**Made for growth analysts, marketing data engineers, BI developers, and teams building transparent marketing analytics platforms.**  
Let's make marketing analytics and BI more open, data-sovereign, and developer-friendly.
