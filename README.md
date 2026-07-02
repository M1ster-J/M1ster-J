# Jonathan Carnline
### Systems Integration • Automation • Reliability • Data Analytics


`Python` · `C#` · `PowerShell` · `JavaScript` · `PHP` · `SQL` · `Windows/Linux`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jonathan_Carnline-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jonathan-carnline-b70420262/)
[![GitHub](https://img.shields.io/badge/GitHub-M1ster--J-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/M1ster-J)

---

My current work focuses on controlled execution, explicit system boundaries, failure recovery, observability, and proving what a system actually did—not merely whether it appeared connected or running.

```text
Input → Validation → Decision → Safety Controls → Execution → Evidence
```

---

## Engineering Capabilities

### Systems Integration

Python and C# services, TCP protocols, platform bridges, event contracts, APIs, and cross-process communication.

### Reliability Engineering

Idempotency, state reconciliation, safety lockouts, recovery paths, health checks, and fail-closed behavior.

### Automation

Python utilities, PowerShell launchers, scheduled workflows, configuration validation, and repeatable operating procedures.

### Real-Time Systems

Event streams, market-data processing, feature pipelines, model runtimes, and execution lifecycle management.

### Production Diagnostics

Structured ledgers, artifact-based investigation, root-cause analysis, runtime monitoring, regression testing, and runbooks.

---

## Featured Projects

### [Market Probability Model](https://github.com/M1ster-J/market-probability-model)

A Python-based live market-data and execution-intent runtime developed around one principle:

> A model signal should not automatically become a trade.

```text
Market Data
    ↓
Feature Pipeline
    ↓
Model Signal
    ↓
Risk and Eligibility Gates
    ↓
Execution Intent
    ↓
Bridge Transport
    ↓
Logs, Ledgers, and Health Monitoring
```

The runtime receives OHLCV data, builds model features, generates probability and directional output, applies operational controls, and creates structured execution intent only when the required gates pass.

**Engineering focus:**

- Real-time market-data handling
- Feature pipelines and model scoring
- Stale-data and price validation
- Session, volatility, and probability gates
- Account-routing and execution controls
- Structured JSONL and CSV ledgers
- Runtime health monitoring
- Mock transport for safe testing
- Artifact-backed troubleshooting

---

### [Model Execution Bridge](https://github.com/M1ster-J/Model-Execution-Bridge)

A Python-to-NinjaTrader 8 execution bridge focused on reliable handoff, lifecycle tracking, risk controls, and traceability.

```text
Signal Stream
    ↓
Validation and Normalization
    ↓
Risk, Idempotency, and Safety Controls
    ↓
Execution Intent
    ↓
Python TCP Transport ↔ NinjaTrader C# Add-On
    ↓
Acknowledgements, Fills, and Position State
    ↓
Reconciliation and Durable Evidence
```

The bridge controls what happens after a system decides it wants to act. It converts signals into structured intent, protects against duplicate processing, tracks the order lifecycle, and reconciles platform state.

**Engineering focus:**

- Python and C# integration
- TCP communication
- Structured execution contracts
- Idempotency and duplicate protection
- Order and fill lifecycle tracking
- Risk controls and account validation
- Position reconciliation
- Durable runtime state
- Failure handling and recovery
- Automated lifecycle and reliability testing

**Verification:** 89 automated tests cover execution lifecycles, risk controls, idempotency, signal processing, failure recovery, and project configuration.

---

## Technical Toolkit

### Languages and Data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C%23](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=sqlite&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square&logo=yaml&logoColor=white)

`JSON` · `JSONL` · `CSV` · `SQLite` · `Time-series data`

### Systems and Operations

![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

`TCP sockets` · `CLI tooling` · `Scheduled tasks` · `systemd`  
`SSH/SFTP` · `Environment configuration` · `Structured logging`

### Engineering Practices

`Event-driven systems` · `Idempotency` · `State reconciliation`  
`Health checks` · `Fail-closed design` · `Regression testing`  
`Root-cause analysis` · `Runbooks` · `Rollback planning`

---

## Data Analytics

My systems work also involves analyzing time-series and operational data to understand behavior, validate decisions, and identify failure patterns.

I work with Python, SQL, pandas, NumPy, XGBoost, SQLite, CSV, and JSONL across tasks such as:

- Cleaning and normalizing time-series data
- Building and validating model features
- Evaluating probability and directional output
- Checking schema integrity, freshness, and data quality
- Comparing live, replay, and backfill behavior
- Reconstructing trade lifecycles and realized PnL from event records
- Investigating anomalies through structured logs and runtime artifacts
- Turning raw system evidence into traceable technical findings
