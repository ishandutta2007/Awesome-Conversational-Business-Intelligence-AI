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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Snowflake Cortex Analyst](https://www.snowflake.com/)**

  **Natural language to governed SQL** over Snowflake tables using semantic models. **Pricing**: Bundled at no extra cost for Enterprise Edition customers; moved to **decoupled AI-credit billing in April 2026** . **Free tier**: **No permanent free tier**—only a **30-day credit trial**; **Cortex AI features are deliberately disabled on self-service trial accounts** . **Best for**: Snowflake Enterprise customers wanting governed NL2SQL within the warehouse perimeter—**trade-off**: trial accounts cannot evaluate Cortex features; requires pay-as-you-go conversion or workshop-provided accounts .



- **[ThoughtSpot Sage](https://www.thoughtspot.com/)**

  **AI-powered analytics** with natural language search and automated insights. **Pricing**: Public price list exists (2 plans); third-party listings suggest **Enterprise from ~$95/user/month** . **Free tier**: **No free tier**; **14-day free trial** . **Best for**: teams wanting search-driven analytics with AI-generated insights—**trade-off**: enterprise pricing; no free tier for evaluation beyond trial.



- **[Tableau Pulse / Tableau Agent](https://www.tableau.com/)**

  **Conversational metrics exploration** within Tableau Pulse. **Pricing**: **Tableau Agent in Pulse requires Tableau+ license edition** after trial; Tableau+ pricing is quote-only. **Free tier**: **60-day trial** of Tableau Agent in Pulse for existing Tableau Cloud sites—**unlimited questions during trial**; trial cannot be paused; users lose access after 60 days unless Tableau+ is purchased . **Best for**: existing Tableau Cloud customers wanting conversational metric exploration—**trade-off**: requires Tableau+ for production; trial is time-boxed and cannot be extended.



- **[Power BI Copilot](https://powerbi.microsoft.com/)**

  **Copilot for Power BI** requiring **paid Fabric capacity (F2 or higher) or Premium P1+**—a Pro/PPU license alone is **not sufficient**; **trial SKUs are not supported** . **Pricing**: **F2 capacity from $262.80/month pay-as-you-go** (~$156/month reserved 1-year) plus **Pro seats at $14/user/month below F64**; **F64 at $8,409.60/month PAYG** removes viewer Pro license requirement; token-metered consumption on top (100 CU-seconds per 1,000 input tokens; 400 per 1,000 output tokens) . **Free tier**: **No free tier**; **trial capacities are explicitly not supported** . **Best for**: Microsoft Fabric customers with existing capacity commitments—**trade-off**: F2 is exhausted after ~20 questions/day per community measurement; realistic sustained use requires F64 (~$100K/year) .



- **[Sisense Fusion AI](https://www.sisense.com/)**

  **Embedded analytics** with AI-powered insights. **Pricing**: **Enterprise-only pricing, no published tiers**—all pricing negotiated through sales . **Free tier**: **No free tier**; **14-day free trial** available . **Best for**: enterprises wanting embedded analytics with AI insights—**trade-off**: inaccessible for small teams; no self-service pricing.



- **[Qlik Answers](https://www.qlik.com/)**

  **Conversational analytics** within Qlik Cloud. **Pricing**: Quote-only; Qlik Cloud Analytics pricing available on request. **Free tier**: **30-day free trial** . **Best for**: Qlik customers wanting natural language Q&A on their data—**trade-off**: tied to Qlik ecosystem.



- **[Veezoo](https://www.veezoo.com/)**

  **Agentic analytics** with knowledge graph and natural language query. **Pricing**: **Pro and Enterprise plans**; **Predictable** (fixed annual for licensed users) or **Flexible** (active-user pricing); **LLM token costs included** in hosted version—no separate token bill . **Free tier**: **Try free** available for Pro; no permanent free tier specified . **Best for**: teams wanting AI analytics without surprise LLM token costs—**trade-off**: knowledge graph setup required for governed answers.



- **[Domo AI](https://www.domo.com/)**

  **AI chat and agentic analytics** within Domo's platform. **Pricing**: **No list price**—credit-based consumption model; **AI chat requests consume credits since January 1, 2025**; **Domo AI Pro Documents and Agent Knowledge consume credits since August 1, 2026** . **Free tier**: **30-day trial** with **no credit cap**, but **excludes AutoML, Jupyter Workspaces, and some governance functions** . **Best for**: Domo customers wanting AI analytics within their existing platform—**trade-off**: credit consumption model makes costs unpredictable; trial excludes key AI-adjacent features.



- **[AskData](https://askdata.com/)**

  **Conversational analytics** platform. **Pricing**: **Free tier available**; paid from **$4/month** across 2 tiers; self-serve checkout . **Free tier**: **Yes, free-forever plan** with no credit card required . **Best for**: small teams wanting low-cost conversational BI—**trade-off**: limited enterprise features at entry pricing.



- **[Luzmo AI](https://www.luzmo.com/)**

  **Embedded analytics with AI** for SaaS products. **Pricing**: **Free to start**; upgrade when scaling; no credit card required . **Free tier**: **Yes, free workspace** to start . **Best for**: SaaS companies embedding analytics with AI into their product—**trade-off**: embedded/white-label focus, not internal BI.



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
