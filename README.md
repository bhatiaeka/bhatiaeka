# Ekam Bhatia

**Mathematical thinking applied to products.**

I'm a junior studying data science and mathematics at Northeastern University, currently interning at Amazon in Seattle. Outside of coursework I build things end to end, and I love building tools that reach and genuinely impact users.

## Currently

- Incoming Software Development Engineer Intern, Amazon, Seattle, Aug to Dec 2026, working on data pipelines that evaluate generative AI media output in the Stores org
- Undergraduate researcher, Northeastern Bouvé College of Health Sciences, since May 2025
- B.S. Data Science and Mathematics, Northeastern University, expected May 2028, GPA 3.92, Dean's List Spring 2025 and Fall 2025
- Open to product management, software engineering, data science internships for 2027

## Previously

| Role | Company | Where | When |
|---|---|---|---|
| Quantum Data Operations Intern | IBM Quantum | Yorktown Heights, NY | May to Aug 2026 |
| Backend Engineering Intern | AIR Health | Boston, MA | Oct to Dec 2025 |
| Data Science Intern | Kaliber Technologies | Boston, MA | Oct to Dec 2025 |
| Software Engineering Intern | Ricovr Healthcare | Princeton, NJ | May to Aug 2025 |

## What I'm building

**Milja** is a full stack music discovery platform I designed, built, and maintain solo. It scores recommendations from 52 dimensional pgvector taste embeddings computed fresh per request, using a content based engine I settled on after testing collaborative filtering and watching it degrade on a small catalog with cold start users.

Some of what that's taken so far. I cut recommendation query latency 6x by replacing a full row scan with two stage retrieval over a trigger synced column projection, then traced a window sort tuple projection bottleneck to passing full rows instead of bare IDs and picked up another 3.5x. Perceived launch latency dropped 23x through a disk backed deck cache, audio pre priming, and artwork cache warming. I rebuilt the acoustic feature extractor to weight frame level features by an empirical listen survival curve instead of flat averaging 25 seconds of a preview users actually hear about 3 seconds of, shipped through a shadow column so a bad run couldn't touch the live model. I'm planning now to deploy this app to the app store as well.

## Research

At Bouvé, I work on SuperLearner ensemble models over more than 25 million insurance claims records, building the Python and SQL ETL pipelines that feed them, which cut processing time by about 30%. I do feature engineering across heterogeneous datasets and run sensitivity analysis across demographic cohorts, and the findings are heading toward a paper with the senior researchers I present to.

## Side projects

| Project | What it does | Stack |
|---|---|---|
| Bayesian Optimized Cointegration Trading | Statistical arbitrage strategy using the Johansen test to find mean reverting asset pairs, tuning basket weights, entry and exit thresholds, and lookback window with Optuna to beat the Johansen baseline out of sample on Sharpe, validated on spread stationarity, half life, and drawdown across market regimes under realistic transaction costs | Python, NumPy, pandas, statsmodels, Optuna |
| QShell (🏆 Best Blockchain Award, FinHacks, 33 teams) | Quantum resilient transaction platform pairing a simplified Kyber KEM lattice based key exchange with AES over a real time WebSocket interface, logging encrypted transactions immutably via Ethereum smart contracts and simulating a Grover's speedup brute force attack to quantify security margins | Python, Solidity, Node.js, Web3.py |
| Cloud Vision Inference | Serverless CV inference pipeline with a C optimized preprocessing core wired in through Python FFI, cutting preprocessing latency about 60%, with a modular architecture for adding new models | Python, C, AWS Lambda, S3, IAM |

## Stack

| Area | Tools |
|---|---|
| Languages | Python, TypeScript, JavaScript, SQL, C++, C, Java, R, Solidity |
| Frontend | React, Next.js |
| Backend | FastAPI, Node.js, REST APIs |
| Data and ML | PyTorch, LangChain, LangGraph, pandas, NumPy, statsmodels, Optuna, SuperLearner ensembles, Google ML Kit, watsonx Granite |
| Databases | PostgreSQL, pgvector |
| Big data | Apache Spark |
| Cloud and infra | AWS (Lambda, S3, IAM), Vercel, Linux, Git |
| Visualization | Tableau, Power BI |
| Web3 | Web3.py, Ethereum smart contracts |
| Methods | Recommender systems, RAG and agentic pipelines, ETL pipeline design, statistical arbitrage and backtesting, time series analysis, Bayesian optimization, A/B testing, Markov chain journey analysis, sensitivity analysis across subgroups |

Most days it's Python and TypeScript with Next.js, FastAPI, and PostgreSQL plus pgvector.

## Beyond the terminal

I chair Northeastern ACM and captain the club fencing team as a national medalist. I speak English, Hindi, and German. Recent coursework includes databases, advanced programming with data, discrete structures, matrix methods in machine learning, advanced probability and statistics, and information visualization.

## Reach me

| | |
|---|---|
| Email | [ekamhbhatia@gmail.com](mailto:ekamhbhatia@gmail.com) |
| LinkedIn | [linkedin.com/in/ekam-bhatia](https://linkedin.com/in/ekam-bhatia) |
| Portfolio | [ekam-portfolio.vercel.app](https://ekam-portfolio.vercel.app) |
| Location | Seattle, WA |
