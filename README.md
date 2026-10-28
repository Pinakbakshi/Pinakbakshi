# Hi, I'm Pinakpani Bakshi

**Software developer building data-intensive systems, AI developer tools, and automation products.**

I work at the intersection of **healthcare data engineering, backend development, applied AI, and developer productivity**. My day-to-day experience includes data integration and migration workflows, SQL/PL/SQL, ETL modernization, and automation. Outside that work, I build practical tools that explore how AI agents can be made safer and how software behaviour can be tested and understood more effectively.

- **Professional role:** Programmer Analyst at Cognizant, working in healthcare technology and data integration.
- **Education:** B.Tech in Computer Science and Business Systems, SRM Institute of Science and Technology.
- **Core interests:** Python, SQL, data engineering, backend APIs, agentic AI, Model Context Protocol (MCP), LLM applications, testing automation, and MLOps.
- **Currently building:** privacy and security tooling for AI coding workflows, autonomous application-impact testing, and personal productivity automation.

## Current builds

### [PrivateGuard](https://github.com/Pinakbakshi/PrivateGuard)
**A local-first privacy gateway for AI coding agents.**

Explores scanning project files for likely secrets and personal information, producing sanitized copies, encrypting artifacts with AES-256-GCM, and exposing narrowly scoped tools through MCP. It also includes an optional audit-commitment registry concept.

*Status and security note:* This is a security-sensitive portfolio MVP, not an independently audited production security boundary. Detection is heuristic; it can miss sensitive data. Do not rely on it as the sole control for secrets, PHI, or regulated information.

### [TracePlay](https://github.com/Pinakbakshi/traceplay)
**UI-to-backend impact testing, regression analysis, and REST API contract checks.**

A testing platform built around Playwright and FastAPI. It supports browser-driven crawling, network/trace capture, database-state diffs, latency observations, and regression reports. A REST API contract CLI now checks authenticated endpoints, expected HTTP statuses, required nested JSON fields, and latency, with sensitive query values redacted. Its six focused contract-validator tests pass in GitHub Actions. Live-target testing still requires a reachable service and locally configured credentials.

### [Crypto Analyzer GPT](https://github.com/Pinakbakshi/crypto-analyzer-get)
An API-oriented crypto market-analysis project. Its merged `/analysis/technical-signal` endpoint returns an explainable weighted technical-bias score using moving-average trend, RSI, MACD, and price versus SMA20, along with component explanations and indicator context. Seven CI tests pass, including authenticated route tests with mocked candles. Live exchange connectivity and predictive performance remain unverified; this is not a guaranteed forecast or financial advice.

### [Daily Digest Automation](https://github.com/Pinakbakshi/Daily_digest_automation)
A personal automation project for consolidating developer news, learning resources, media, and selected daily updates into one digest.

### [Reel Generator](https://github.com/Pinakbakshi/reel_generator)
An AI-assisted short-form video-generation application exploring a workflow for creating social video content.

## Recent engineering updates (2026-10-29)

- **Crypto Analyzer GPT:** merged the explainable technical-signal API, tests, and implementation documentation.
- **TracePlay:** merged authenticated REST API contract probing, response assertions, latency reporting, and credential redaction.
- Both projects' GitHub Actions checks passed. These results verify the tested code paths, not live-service availability or financial predictive accuracy.

## Other projects and experiments

- [Algorithmic Trading](https://github.com/Pinakbakshi/Algo-trading) — ML/DL experimentation and strategy backtesting.
- [Stock Market Analysis](https://github.com/Pinakbakshi/Stock-Market-Analysis-) — market-data analysis and visualization.
- [Air Canvas](https://github.com/Pinakbakshi/Aircanvas--computer-vision-project-) — gesture-driven drawing using computer vision.
- [Face Detection with Flask and OpenCV](https://github.com/Pinakbakshi/flask-realtime-face-detection-opencv-python) — an earlier computer-vision web demo.
- [Loan Prediction](https://github.com/Pinakbakshi/Loan-Prediction) and [Red Wine Quality Prediction](https://github.com/Pinakbakshi/Red-Wine-Quailty-prediction) — educational machine-learning projects.

## Technical toolkit

**Data & integration:** Python, SQL, Oracle PL/SQL, SQL Server/T-SQL, Informatica PowerCenter, XML/XSD, ETL workflows  
**Backend & APIs:** FastAPI, Flask, Django, REST APIs, PostgreSQL, SQLite  
**AI & developer tooling:** LLM applications, MCP, agent workflows, prompt/tool integration, TensorFlow, Keras, scikit-learn  
**Automation & quality:** Playwright, browser automation, regression testing, Python scripting, scheduled jobs  
**Computer vision & apps:** OpenCV, MediaPipe, Streamlit, JavaScript/Node.js  
**Engineering practices:** Git, Docker, dependency management, environment-based configuration, testable design

## How I like to build

- Solve a specific workflow problem and make the result easy to run.
- Keep sensitive data local where possible and make security assumptions explicit.
- Use reproducible setup instructions, meaningful tests, and observable failure modes.
- Separate prototypes from production-ready systems; document limitations rather than overstate capabilities.
- Explore how AI agents can help build, test, and maintain useful products.

## Connect

- [GitHub](https://github.com/Pinakbakshi)
- [LinkedIn](https://linkedin.com/in/pinakbakshi)

*Project maturity varies: some repositories are active experiments or portfolio MVPs. Check each project README for implementation details, setup requirements, and known limitations.*
