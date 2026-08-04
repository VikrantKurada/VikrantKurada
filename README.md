# Vikrant Kurada

Senior Product Owner, Data and AI Applications. London.

I own data products at GSK, inside an SAP ECC/BW to S/4HANA migration on Azure with a hard 2026 deadline and several vendors to keep pointed the same way. Before this, pharma, capital markets, retail banking, wealth management and consulting.

Outside work I build software. Mostly the same idea, approached from different angles.

## What I build, and why

The interesting problem in applied AI is no longer whether a model can produce an answer. It is whether anyone can tell where the answer came from. A forecast or a financial metric is worth nothing if you cannot trace it back to the series, the filing, or the formula that produced it.

So the projects below tend to do two things. The model plans and explains; typed, versioned tools do the arithmetic. And every run records enough to be reproduced later, including the refusals.

They also all run locally first, on Ollama, with Claude, OpenAI, Gemini and NVIDIA as options. Not out of principle. It is that you learn far more about a system when running it costs nothing.

## Projects

**[Econometrica](https://github.com/VikrantKurada/Econometrica)**
A GenAI econometrics workbench for asset pricing and market efficiency. Agents choose from 37 typed econometric tools and never compute statistics themselves. Any result can be re-run from its manifest, which reports whether the numbers came back the same and names the step if they did not. A typical end-to-end pass plans five steps, runs four, and refuses GARCH because the data has no ARCH effects to model. Python, FastAPI, React, Postgres with TimescaleDB and pgvector.

**[AgenticForecasting](https://github.com/VikrantKurada/AgenticForecasting)**
Macroeconomic forecasting by conversation. A planner composes a run-specific DAG of agents that pull real data from FRED, the World Bank, IMF, ECB, OECD, DBnomics, EIA and others, fit ARIMA, VAR, dynamic-factor and gradient-boosted models, and backtest against a naive baseline so the explanation stays honest. Any step can be edited and the workflow rerun.

**[AnnualReportAnalyser](https://github.com/VikrantKurada/AnnualReportAnalyser)**
Fundamental analysis from primary sources. Three years of filings from EDGAR with their XBRL facts, roughly 80 metrics derived in Python rather than by the model, and a citation chip on every number. Click one and you see the XBRL tag, table cell or formula it came from.

**[Aptitude](https://github.com/VikrantKurada/Aptitude)**
Turns PDFs, EPUBs, web pages and repositories into reusable agent skills. Five providers, five output formats, one command. The smallest of these, and the most likely to be useful to someone else.

**[YT_SuperSearch](https://github.com/VikrantKurada/YT_SuperSearch)**
Treats YouTube as a research corpus. Precise filtered search, saved projects, bulk transcript capture, then grounded chat over the transcripts.

**[the-debating-chamber](https://github.com/VikrantKurada/the-debating-chamber)**
Several models answer the same question in assigned roles, critique each other anonymously so brand bias cannot leak in, and a chairman writes the verdict. A cheap way to find out where models actually disagree.

**Agentforce** (private)
Dynamic multi-agent teams in TypeScript, with per-agent memory, telemetry and human approval gates. Roughly half built.

### Earlier work, not public

**Report Rationalization AI.** A RAG platform over an enterprise Power BI portfolio. It ingests the design documents, embeds them, and clusters reports by what they actually do, which is how you find out how many of them are the same report. Azure, vector search.

**nb-remix.** A NotebookLM-style parser for Jupyter notebooks, with semantic search and a knowledge graph across them. Ollama, pgvector, Neo4j, CrewAI.

**AI Scrum Team.** A local multi-agent system that plays an agile delivery team. CrewAI and Ollama.

**LearnMax.** Turns syllabus content into structured JSON and interactive concept maps. I built it because I needed it. Python, Excalidraw, Jupyter.

**Budget Scenario Planner.** Programme financial modelling and scenario analysis. Python.

## Product management

- **Data products at scale.** 13 enterprise data products drawing on 570+ ECC tables, a medallion architecture beneath them, and a Power BI estate remediated in step.
- **Commercial and vendor management.** Multi-million-pound SOW negotiation, milestone structuring, RFP evaluation across tier-1 system integrators. The hard part is not the number. It is writing milestones that make it obvious when something is late.
- **Delivery governance.** Architecture review boards, BRDs, NFRs, risk management, executive communication.
- **Agile leadership.** Advanced Certified Scrum Product Owner.

## AI applications

- **Agentic systems.** Multi-agent workflows in CrewAI, including a local delivery team that runs without anyone attending it.
- **Retrieval and knowledge graphs.** RAG on Supabase and pgvector, Neo4j where the structure matters, MCP to give models real tools instead of descriptions of tools.
- **Local LLM engineering.** Ollama on an RTX 5090 with 32 GB of VRAM. Qwen and DeepSeek families, quantisation picked per task rather than by habit.
- **Workflow automation.** n8n, Python pipelines, structured output design.

## Commercial AI and forecasting

- **Gen AI in regulated industries.** Product leadership across pharma, banking and wealth management, where the constraint is rarely the model and usually the audit trail.
- **Credit risk.** Real-time credit-risk monitoring and forecasting products at Lloyds Banking Group.
- **Commercial forecasting.** Marketing mix modelling, brand equity tracking and donor lifetime value at Macmillan Cancer Support, which decided where the spend went and what each channel was worth.

## Tools

`Python` `TypeScript` `FastAPI` `React` `Postgres/pgvector` `Azure` `GCP` `Databricks` `Power BI` `Ollama` `CrewAI` `MCP` `Neo4j` `n8n` `Jupyter`

## Credentials

Databricks Generative AI Engineer Associate. Microsoft Azure AI Engineer Associate. Advanced Certified Scrum Product Owner. Palantir Aware. CFA Level 1 candidate. MBA, Alliance Manchester Business School. B.E. Electrical Engineering.

## Now

- Shipping data products against the 2026 migration deadline
- Making agentic analysis reproducible, not merely plausible
- CFA Level 1, with tooling I wrote for it

[LinkedIn](https://www.linkedin.com/in/kuradavikrant)
