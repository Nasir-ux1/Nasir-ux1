<h1 align="center">Hi, I'm Nasir Shaik</h1>

<p align="center">
  <b>Python Developer building AI data tools, automation agents, and Linux/DevOps diagnostics.</b>
</p>

<p align="center">
  <a href="https://github.com/Nasir-ux1?tab=repositories">Projects</a> |
  <a href="https://www.linkedin.com/in/nasir2004">LinkedIn</a> |
  <a href="mailto:nasirxzt@gmail.com">Email</a>
</p>

---

## About Me

I build practical software projects around AI agents, data analysis, Linux operations, automation, and infrastructure tooling. My current focus is on portfolio-grade systems that accept messy inputs, run real analysis, and produce useful reports or actions.

- Working on: AI data apps, autonomous agents, Ubuntu diagnostics, and DevOps automation
- Comfortable with: Python, React, pandas, scikit-learn, Streamlit, Linux, Bash, Docker, GitHub Actions, and APIs
- Interested in: Linux systems, SRE tooling, AI engineering, backend systems, and cloud infrastructure
- Goal: build reliable tools that turn raw data, logs, and user questions into clear decisions

---

### Financial Risk Analysis AI Assistant

An AI-powered credit risk assessment and regulatory compliance platform that retrieves regulatory rules from a FAISS vector store, performs structured evaluations using the Claude API, and validates outputs using an LLM-as-a-Judge framework.

**What it does**

- **Automated Financial Ratios**: Computes Current Ratio, Debt-to-Equity, Interest Coverage, and the Altman Z-Score from balance sheets.
- **RAG Regulatory Retrieval**: Indexes Basel III, IFRS 9, and SEC regulations into a FAISS vector store using LangChain.
- **Prompt Engineering Workshop**: Compares Zero-Shot, Few-Shot, and Chain-of-Thought prompts side-by-side.
- **LLM-as-a-Judge Audits**: Evaluates assessments for accuracy, completeness, and regulatory alignment, logging results to track accuracy gains.
- **Interactive UI & RBAC**: Provides a glassmorphic **React (Vite)** dashboard with user logins, role access (`ANALYST` / `ADMIN`), and automated pytest coverage.

**Tech:** Python, FastAPI, React, Vite, SQLAlchemy, LangChain, FAISS, Anthropic (Claude API), pytest, CSS

Repo: [financial-risk-analysis-ai](https://github.com/Nasir-ux1/financial-risk-analysis-ai)

---

## Featured Projects

### Banking Transaction & Fraud Detection System

A production-grade microservices banking backend system that handles customer account management, transaction processing (debits, credits, transfers), and automatic transaction fraud risk evaluations.

**What it does**

- **State Machine Transactions**: Implements transition stages (`PENDING` -> `PROCESSING` -> `COMPLETED`/`FAILED`) with immutable PostgreSQL event log records.
- **Idempotency & Concurrency**: Restores cached responses using `@Idempotent` aspects on HTTP `Idempotency-Key` headers, and uses `@Version` optimistic locking with lock-ordered Account IDs to prevent balance deadlocks.
- **8-Signal Fraud Rule Engine**: Evaluates transaction velocity, off-hours, location anomalies, young accounts, new payees, and device fingerprints to generate risk scores (0-100).
- **Compliance Hold Queue**: Routes high-risk transfers ($\ge 70$) into a review hold queue, running automated natural language risk explanations.
- **Automated CI/CD & Deploy**: Configured with Docker Compose orchestrators, Dockerfiles, and GitHub Actions Maven unit/mock test validation.

**Tech:** Java, Spring Boot, Spring Security (JWT), Hibernate, Flyway, PostgreSQL, H2, JUnit 5, Mockito, AOP, Docker, GitHub Actions

Repo: [banking-system](https://github.com/Nasir-ux1/banking-system)

---

### AI-SRE - Autonomous Linux Troubleshooting Agent

An interactive terminal and Streamlit-based incident response agent that merges safe local systems tool execution with LLM reasoning.

**What it does**

- Safe structured systems diagnostics (disk metrics, systemd unit loops, network listeners, process hogs, and journal logs)
- Supports offline SRE simulation mode as well as live Gemini and OpenAI API function-calling loops
- Generates safe-to-execute Bash mitigation scripts with comprehensive explanations
- Fully verified with active Python testing suites and structured GitHub Actions CI automation

**Tech:** Python, systemd, journald, Streamlit, Rich CLI, pytest, Google Gemini API, OpenAI API

Repo: [ai-sre-agent](https://github.com/Nasir-ux1/ai-sre-agent)

---

### AI Autonomous Data Scientist

An AI-powered Streamlit app that turns a CSV upload and a business question into dataset profiling, cleaning, baseline ML models, automatic charts, and a Markdown analysis report.

**What it does**

- Uploads and profiles CSV datasets
- Cleans common tabular data issues
- Infers target columns and classification/regression tasks
- Trains baseline scikit-learn models
- Generates Plotly charts automatically
- Writes a business-style analysis report
- Includes tests, sample data, and a 22-commit project history

**Tech:** Python, pandas, scikit-learn, Plotly, Streamlit, pytest

Repo: [ai-autonomous-data-scientist](https://github.com/Nasir-ux1/ai-autonomous-data-scientist)

---

### UbuntuOps Agent - Ubuntu Incident Response Toolkit

A Linux/SRE-style diagnostics toolkit that collects system evidence, detects common failure patterns, recommends fixes, and generates incident reports.

**What it does**

- Diagnoses failed `systemd` services and `journalctl` logs
- Detects service issues like port conflicts, restart loops, config errors, missing files, and permission failures
- Analyzes disk-full incidents, deleted-but-open files, and Docker disk usage
- Parses SSH/auth logs for brute-force attempts, successful logins, and sudo activity
- Collects system health from `/proc`
- Includes CLI, Streamlit dashboard, sample logs, tests, and report generation

**Tech:** Python, Linux `/proc`, systemd, journald, Docker, Bash, Streamlit, unittest

Repo: [ubuntuops-agent](https://github.com/Nasir-ux1/ubuntuops-agent)

---

### InsightForge - Autonomous Data Analyst Agent

An AI/ML-style analyst agent that turns a raw CSV/XLSX dataset and a natural-language question into a structured insight report.

**What it does**

- Profiles uploaded datasets
- Cleans columns, dates, missing values, and duplicates
- Plans analysis from a user question
- Generates pandas-based insights
- Creates visual charts
- Exports an executive Markdown report
- Includes CLI, Streamlit UI, sample data, and tests

**Tech:** Python, pandas, NumPy, matplotlib, Streamlit, unittest

Repo: [insightforge-agent](https://github.com/Nasir-ux1/insightforge-agent)

---

## Project Snapshot

| Project | Focus | Stack |
| --- | --- | --- |
| [Banking Transaction & Fraud Detection System](https://github.com/Nasir-ux1/banking-system) | Microservices banking system with optimistic locking, idempotency keys, and compliance fraud review holds | Java, Spring Boot, Spring Security, Flyway, PostgreSQL, H2, JUnit, Mockito |
| [Financial Risk Analysis AI Assistant](https://github.com/Nasir-ux1/financial-risk-analysis-ai) | AI credit risk assessment, regulatory RAG retrieval, and prompt engineer playground | Python, FastAPI, React, Vite, LangChain, FAISS, Claude API, pytest |
| [AI-SRE Agent](https://github.com/Nasir-ux1/ai-sre-agent) | Autonomous AI systems troubleshooter and Bash safe-fix generator | Python, Streamlit, Rich CLI, pytest, Gemini & OpenAI APIs |
| [AI Autonomous Data Scientist](https://github.com/Nasir-ux1/ai-autonomous-data-scientist) | Automated data science app with profiling, ML, charts, and reports | Python, Streamlit, pandas, scikit-learn, Plotly |
| [UbuntuOps Agent](https://github.com/Nasir-ux1/ubuntuops-agent) | Linux incident response and SRE diagnostics | Python, Linux, systemd, journald, Docker |
| [InsightForge Agent](https://github.com/Nasir-ux1/insightforge-agent) | Autonomous data analyst for CSV/XLSX reports | Python, pandas, matplotlib, Streamlit |

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**AI / Data**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3A?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**DevOps / Systems**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

---

## What I Like Building

- AI agents that use tools, files, APIs, and code execution
- Data apps that convert raw datasets into clear reports
- Automation scripts for repetitive engineering workflows
- Linux and DevOps projects with real debugging, logs, and CI/CD
- Backend tools with clean APIs and practical documentation

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Nasir-ux1&show_icons=true&theme=tokyonight&hide_border=true" alt="Nasir's GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nasir-ux1&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Nasir-ux1&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

---

## Current Focus

```text
AI data apps + Python automation + Linux diagnostics + DevOps tooling
```

I am actively building projects that are easy to run, easy to verify, and useful enough to explain in interviews.
