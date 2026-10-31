# Awesome-Conversational-Business-Intelligence-AI

# Awesome-Conversational-Business-Intelligence-AI

**Top Conversational Business Intelligence AI (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Natural Language Query, Semantic Layers, AI-Generated Insights & Self-Hosted Analytics Agents*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Conversational Business Intelligence & AI**. These tools enable users to ask questions of their data in plain language and receive governed answers, automated insights, and visualizations—from fully managed platforms with semantic models and agentic analytics to self-hosted frameworks that give organizations control over their LLM provider, data residency, and query logic.



**Examples** include Snowflake Cortex Analyst, ThoughtSpot Sage, Tableau Pulse, Power BI Copilot, Sisense Fusion AI, Qlik Answers, Veezoo, Domo AI, AskData, and Luzmo AI (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted conversational BI, text-to-SQL agents, and open analytics infrastructure. **Critical note**: The open-source landscape is nascent but functional—**Orion** is the most complete text-to-SQL agent with BigQuery integration, statistical analysis, and visualization , while **RAGFrame** offers a privacy-first, offline analytics agent for sensitive data . No open-source project matches the semantic-layer depth of Cortex Analyst or the enterprise governance of ThoughtSpot Sage, but for teams prioritizing data sovereignty, the building blocks exist.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global conversational AI and business intelligence market represents an estimated addressable sector size of ~$30B to $41B in 2026, projected to surpass $62B+ by 2031 at a ~10-14% CAGR as enterprises shift from static dashboards to natural-language analytics agents. The sector exhibits a moderately concentrated, barbell-fragmented structure where hyperscaler BI platforms (Microsoft, Salesforce/Tableau) and major cloud data warehouses (Snowflake, SAP) capture incumbent market share, while focused pure-play vendors (ThoughtSpot, Sisense, Veezoo, Luzmo) compete on specialized agentic orchestration, semantic layer precision, and embedded integrations.

## SaaS/Hosted Platforms

| Company / Product | Company Size (Valuation / Revenue) | Starting Pricing Tier | Free Tier / Trial Limits | Key Focus & Notes |
| :--- | :--- | :--- | :--- | :--- |
| **[Power BI Copilot](https://powerbi.microsoft.com/)** (Microsoft) | **Valuation: ~$3.1T+**<br>*(FY25 Rev: $245B+)* | **$262.80/month** (Fabric F2 PAYG capacity) + **$14/user/month** (Power BI Pro seat below F64) | **60-day free trial** of Fabric capacity (F64 equivalent, 1 TB OneLake storage); **Note**: Copilot features require dedicated paid F2+ capacity and are excluded on trial SKUs. | Governed conversational BI deeply embedded in Microsoft Fabric / Office 365. Sustained organizational usage typically requires F64 (~$8,410/mo PAYG). |
| **[Tableau Pulse / Tableau Agent](https://www.tableau.com/)** (Salesforce) | **Valuation: ~$280B+**<br>*(FY25 Rev: $38B+)* | **$15/user/month** (Viewer, Standard) / **$115/user/month** (Creator, Enterprise); Tableau+ bundle is custom-quoted | **60-day free trial** of Tableau Agent in Pulse on existing Tableau Cloud sites (unlimited questions during the 60-day window; cannot be extended or paused). | Conversational metric exploration and autonomous digest generation natively embedded in Tableau Cloud / Salesforce Data Cloud. |
| **[Snowflake Cortex Analyst](https://www.snowflake.com/)** | **Valuation: ~$110B+**<br>*(FY26 Rev: $4.68B)* | **$3.00/credit** (Enterprise Edition PAYG compute) + AI credit/message metering (~6.7 credits/100 requests) | **30-day free trial** with **$400 in platform credits**; **Note**: Cortex AI / LLM features are disabled on self-service trial accounts and require pay-as-you-go conversion. | Governed natural language to SQL executing over Snowflake warehouse tables via audited YAML semantic models. |
| **[Qlik Answers](https://www.qlik.com/)** (Qlik / Thoma Bravo) | **Valuation: ~$10B**<br>*(Est. ARR: $1B+)* | **$300/month** (Starter tier, billed annually at $3,600/yr for 10 users & 10 GB) or **$825/month** (Standard tier, 25 GB) | **30-day free trial** (access to full Qlik Cloud Analytics environment with standard connector limits). | Conversational analytics, unstructured content Q&A, and associative engine analysis within Qlik Cloud. |
| **[ThoughtSpot Sage](https://www.thoughtspot.com/)** | **Valuation: ~$4.2B**<br>*(Est. ARR: ~$170M-$200M+)* | **$95/user/month** (Enterprise base seat estimate) or usage-based tiering starting ~$2,500/yr | **14-day free trial** (full access to search data, AI agents like Spotter, and warehouse connections; max 10 CSV uploads per user). | Search-driven analytics and natural language insights over cloud data warehouses using semantic search indexing. |
| **[Sisense Fusion AI](https://www.sisense.com/)** | **Valuation: ~$1.1B**<br>*(Est. ARR: ~$140M-$150M)* | **~$2,083/month** (Billed annually starting ~$25,000-$40,000/year base deployment package) | **14-day free trial** (cloud sandbox environment with preloaded demo datasets and Compose SDK embedding access; no credit card required). | API-first embedded conversational analytics with AI insights, ElastiCube data modeling, and custom front-end SDKs. |
| **[Domo AI](https://www.domo.com/)** | **Valuation: ~$150M**<br>*(FY26 Rev: $318M)* | **~$2,500/month** (Billed annually starting ~$30,000/year consumption credit pool; credit charges apply to AI chat requests) | **30-day free trial** (unlimited trial credits for core BI; strictly excludes AutoML, Jupyter Workspaces, and advanced governance). | Full-stack cloud BI with conversational chat interfaces, Magic ETL pipelines, and embedded agentic workflows. |
| **[Luzmo AI](https://www.luzmo.com/)** | **Valuation: ~$75M**<br>*(Est. ARR: ~$5M-$10M)* | **$1,995/month** ("Embedded Everywhere" plan, billed annually; unlimited end-users, 100M Warp rows, 500 AI conversations/mo) | **10-day free trial** (full access to embedding SDKs, white-labeling, and Luzmo IQ conversational analytics; no permanent free tier). | Purpose-built embedded conversational analytics and self-service dashboards designed specifically for B2B SaaS software vendors. |
| **[AskData](https://askdata.com/)** (SAP) | **Valuation: Undisclosed**<br>*(Parent SAP Cap: ~$260B+)* | **$4/month** (Historical standalone entry plan); integrated via SAP BTP / SAP Analytics Cloud subscription tiers | **Free-forever plan** for public datasets / SAP BTP Free Tier (evaluation access with strict capacity & service limits; 90-day integration trials). | Acquired by SAP in July 2022; conversational SQL and search-driven analytics interface embedded across SAP BTP. |
| **[Veezoo](https://www.veezoo.com/)** | **Valuation: Undisclosed**<br>*(Total Funding: ~$7.3M, Est. Rev: ~$1.2M)* | **$49/user/month** (Professional tier starting base) or Predictable/Flexible annual team packages (hosted LLM token costs included) | **14-day free trial** (test knowledge graph generation, root-cause analysis, and natural language queries; no permanent free tier). | AI-native conversational BI powered by dynamic knowledge graphs with all LLM token inference costs bundled into the base subscription. |

## Open-Source GitHub Projects



- **[Orion](https://github.com/gavrielhan/orion-data-analyst)**

  **AI-powered data analysis agent** (PyPI package) — **the most complete open-source text-to-SQL agent** found in this research, with BigQuery integration and autonomous analysis . **Features**: **Natural language to SQL** using Google Gemini; **statistical analysis** (ranking, trends, segmentation, RFM, anomaly detection); **self-healing** with error feedback loops (max 3 retries); **visualizations** (bar, line, pie, scatter, box, candle) auto-saved; **conversation memory** for follow-ups; **safety**—blocks DROP/DELETE, cost estimation before execution, human-in-the-loop approval for expensive queries; query and schema caching . **Tech stack**: Python, LangGraph, Google BigQuery, Gemini API. **Deploy**: `pip install orion-data-analyst`; requires Google Cloud project, service account, and Gemini API key . **Trade-off**: **BigQuery and Gemini only**—not multi-warehouse or multi-LLM; requires Google Cloud setup. **Best for**: developers and analysts on BigQuery wanting a self-hosted agent that generates SQL, analyzes results, and creates charts from natural language—without a commercial BI platform.



- **[RAGFrame](https://github.com/ragframe/ragframe)**

  **Privacy-first, offline analytics agent** (license per repo) — **the most sovereignty-focused open-source conversational BI tool**, designed for sensitive data that cannot leave the environment. **Features**: **Fully offline**—runs entirely on local models (Ollama, LM Studio); no data leaves your infrastructure; **natural language query** over local databases; designed for regulated industries and air-gapped environments. **Tech stack**: Python, local LLM integration. **Deploy**: Self-hosted (local or air-gapped). **Trade-off**: **Requires local LLM setup**—performance depends on hardware; smaller community than Orion. **Best for**: organizations with strict data residency requirements (healthcare, government, finance) wanting conversational BI without cloud LLM dependency.



### Additional Strong Open-Source Options



- **Vanna.AI** — Open-source Python RAG framework for SQL generation (MIT). Trains on your schema and queries to improve text-to-SQL accuracy; supports multiple LLMs and databases. **Note**: Library for building custom NL2SQL, not a complete BI interface. **Best for**: developers wanting to add natural language query to their own analytics application.

- **SQLCoder** — Open-source LLM for text-to-SQL (Defog). Fine-tuned model specifically for SQL generation; can run locally. **Note**: Model only—requires integration with a database and UI. **Best for**: teams wanting a purpose-built text-to-SQL model to self-host.



**Frameworks for building custom systems**: Combine **Orion** for BigQuery-based text-to-SQL and analysis with **RAGFrame** for air-gapped environments and **Vanna.AI** for custom NL2SQL integration—creating a self-hosted conversational BI stack. **None of these match Cortex Analyst's semantic model governance or ThoughtSpot's enterprise search**, but for teams prioritizing data sovereignty and LLM choice, the building blocks are available.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Conversational BI platforms handling enterprise data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for sensitive metrics and queries.

- **The "governed semantic layer" vs. "search-driven analytics" vs. "agentic text-to-SQL" vs. "offline privacy-first" distinction is critical.** **Snowflake Cortex Analyst** uses **semantic models** for governed NL2SQL—accuracy depends on model quality but answers are auditable . **ThoughtSpot Sage** is **search-driven**—natural language over a search index. **Power BI Copilot** and **Tableau Pulse** are **embedded in their BI platforms**—they require the parent platform's capacity or license tier . **Orion** is an **agentic text-to-SQL tool**—it generates SQL, analyzes results, and visualizes, but without a governed semantic layer . **RAGFrame** is **offline privacy-first**—it runs local models for air-gapped environments . **Choose based on whether you need governance, search, embedded BI, or sovereignty.**

- **Snowflake Cortex Analyst cannot be evaluated on trial accounts.** Cortex AI features are deliberately disabled on self-service trials—no role grants or region settings will enable them . **You must convert to pay-as-you-go or attend a Snowflake-sponsored workshop that provides an enabled trial account** .

- **Power BI Copilot requires capacity, not just a license.** A Pro or PPU license alone is insufficient—you need paid Fabric F2+ or Premium P1+ capacity; **trial SKUs are not supported** . **F2 is exhausted after ~20 questions/day**; realistic sustained use requires F64 (~$100K/year) . **Model your question volume before committing.**

- **Tableau Agent in Pulse is trial-only for 60 days.** There is no way to pause or extend the trial; users lose access after 60 days unless **Tableau+** is purchased . **Plan evaluation accordingly.**

- **Veezoo includes LLM token costs** in its hosted pricing—no separate token bill . **This is unusual**—most platforms meter AI consumption separately. **For teams burned by unpredictable token costs, it is worth evaluating.**

- **Domo AI consumes credits for every AI chat request** since January 2025, and added AI Pro Documents/Agent Knowledge credits in August 2026 . **The 30-day trial has no credit cap but excludes AutoML and Jupyter** .

- **Orion is the most complete open-source text-to-SQL agent**—BigQuery, Gemini, statistical analysis, visualizations, and safety guardrails . **The trade-off**: Google Cloud lock-in (BigQuery + Gemini); requires setup. **For teams already on GCP, it is the pragmatic open-source choice.**

- **Pricing opacity is universal across commercial vendors.** Cortex Analyst, ThoughtSpot, Tableau+, Sisense, Qlik, Veezoo (Enterprise), and Domo all require sales contact or capacity commitment. AskData publishes $4/month entry with free tier; Luzmo offers free start. **Validate with direct vendor conversations against your query volume and data platform.**

- Self-hosted open-source solutions require proper infrastructure (Google Cloud for Orion, local LLM for RAGFrame), security hardening for database credentials, and ongoing maintenance. **Conversational BI tools execute queries against production data**—ensure your deployment includes cost controls and query validation before connecting live warehouses.



---



**Made for data analysts, BI teams, and organizations building transparent conversational analytics solutions.**

Let's make Conversational Business Intelligence more open, data-driven, and question-friendly.
