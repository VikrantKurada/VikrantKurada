# Vikrant Kurada

Senior Product Owner, Data and AI Applications, GSK, London

At GSK I own data products in the SAP ECC/BW to S/4HANA migration. Outside work I build AI analysis projects whose results can be audited.

I have led GenAI products in pharma and financial services, where audit-trail requirements limited what reached production more often than model capability did. In my analysis projects the model plans and explains while typed, versioned tools do the arithmetic. Each run is recorded in enough detail to be reproduced later, and the record includes any refused step.

## Analysis and research projects trace each result to its source

- [Econometrica](https://github.com/VikrantKurada/Econometrica) is a GenAI econometrics workbench for asset pricing and market efficiency in which agents select from 37 typed tools and never compute statistics themselves. Any result can be rerun from its manifest, which reports whether the numbers matched and names the step that diverged. In a typical pass GARCH is refused because the data shows no ARCH effects, so four of the five planned steps run. The stack is Python, FastAPI, React and Postgres with TimescaleDB and pgvector.
- [AgenticForecasting](https://github.com/VikrantKurada/AgenticForecasting) produces macroeconomic forecasts from a conversation, and every explanation states whether the forecast beat a naive baseline in backtesting. A planner composes a DAG of agents for each run; the agents pull data from FRED, the World Bank, IMF, ECB, OECD, DBnomics, EIA and other sources and fit ARIMA, VAR, dynamic-factor and gradient-boosted models. Any step can be edited and the workflow rerun.
- [AnnualReportAnalyser](https://github.com/VikrantKurada/AnnualReportAnalyser) cites the source of every number in its fundamental analysis of three years of EDGAR filings. Citations on reported numbers open the XBRL tag or table cell, and citations on derived numbers open the formula. About 80 metrics are computed in Python from the filings' XBRL facts.
- [YT_SuperSearch](https://github.com/VikrantKurada/YT_SuperSearch) treats YouTube as a research corpus and grounds its chat answers in captured transcripts. Filtered search selects the videos for bulk capture, and work is kept in saved projects.

## Tooling projects build agent skills from documents and compare model answers

- [Aptitude](https://github.com/VikrantKurada/Aptitude) turns PDFs, EPUBs, web pages and repositories into reusable agent skills with one command. It supports five model providers and five output formats. Of the public projects it is the smallest and the most reusable outside my own work.
- [the-debating-chamber](https://github.com/VikrantKurada/the-debating-chamber) is a low-cost way to find where language models disagree. Each model answers in an assigned role, then critiques the other answers with authorship hidden so brand bias cannot affect its judgement. A chairman model writes the verdict.

## Public projects run on local models first, so testing them costs nothing

Qwen and DeepSeek models run through Ollama on an RTX 5090 with 32 GB of VRAM, and quantisation is chosen per task. Claude, OpenAI, Gemini and NVIDIA are hosted alternatives.

## Private and earlier projects include Power BI report rationalisation and multi-agent teams

| Project | Function | Stack |
|---|---|---|
| Report Rationalization AI | Embeds the design documents of enterprise Power BI reports for RAG and clusters the reports by function to identify duplicates. | Azure, vector search |
| Agentforce (private, half built) | Assembles multi-agent teams dynamically with per-agent memory and telemetry. Workflows pause at human approval points. | TypeScript |
| AI Scrum Team | Runs the roles of an agile delivery team as local agents that operate unattended. | CrewAI, Ollama |
| nb-remix | Parses Jupyter notebooks in the style of NotebookLM and links them through semantic search and a knowledge graph. | Ollama, pgvector, Neo4j, CrewAI |
| LearnMax | Converts syllabus content into structured JSON and interactive concept maps. | Python, Excalidraw, Jupyter |
| Budget Scenario Planner | Models programme finances under alternative scenarios. | Python |

## GSK data products drawing on 570+ ECC tables must switch to S/4HANA by 2027

The migration runs on Azure, and I keep its vendors aligned. The data products sit on a medallion architecture, and the Power BI reports built on them are remediated in step so reporting continues through cutover.

I negotiate multi-million-pound statements of work and evaluate RFP responses from tier-1 system integrators. Milestones in each statement of work are written so slippage is visible on the due date. Delivery governance spans architecture review boards, BRDs, NFRs, risk management and executive communication.

## My career spans pharma, capital markets, retail banking, wealth management and consulting

At Lloyds Banking Group I delivered Commercial Banking Data Products. For Macmillan Cancer Support I built marketing mix models, brand equity tracking and donor lifetime value analysis, which Macmillan used to allocate spend and value each channel.

---

`Python` `TypeScript` `FastAPI` `React` `Postgres/pgvector` `Supabase` `Azure` `GCP` `Databricks` `Power BI` `Ollama` `CrewAI` `MCP` `Neo4j` `n8n` `Jupyter`

Databricks Generative AI Engineer Associate; Microsoft Azure AI Engineer Associate; Advanced Certified Scrum Product Owner; Palantir Aware; CFA Level 1 candidate; MBA, Alliance Manchester Business School; B.E. Electrical Engineering

[LinkedIn](https://www.linkedin.com/in/kuradavikrant)
