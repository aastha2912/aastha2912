# Aastha Mahajan

Software engineer. Built production systems processing 10B transactions a day, closed a $3.2B regulatory capital gap, and now building agents that find and fix vulnerabilities in real-world open source CVEs.

MEng Cybersecurity @ University of Maryland &nbsp;·&nbsp; Prev: Goldman Sachs &nbsp;·&nbsp; Google (Intrinsic)

[LinkedIn](https://linkedin.com/in/yourhandle) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2510.13859)

---

## Research & Publications

**Agentic LLM Pipeline for Automated Vulnerability Detection and Repair** *(forthcoming, June 2026)*

End-to-end agentic pipeline for vulnerability detection and patch synthesis across real-world open source CVEs. Agent orchestration, context capture instrumentation, eval against real bug corpora. 78% success rate at under $0.10 per CVE.

**MT-Sec: Benchmarking Correctness and Security in Multi-Turn Code Generation** *(2025)* &nbsp;[arXiv](https://arxiv.org/abs/2510.13859)

Built the benchmark, eval pipeline, and agentic detection layer across 2,376 tasks and 27 CWEs. Key finding: even state-of-the-art models show a 20-27% drop in correct and secure outputs from single-turn to multi-turn, and agents make it worse, not better.

**ARVO Patching Agent Evals · DARPA AIxCC Environment** &nbsp;[GitHub](https://github.com/aastha2912/aixcc-afc-archive/tree/main/crs/arvo-patching-agent)

Integrated the Theori patching agent with the ARVO dataset using the DARPA AIxCC AFC evaluation environment as part of ongoing UMD security research and ran structured evals: detection accuracy, patch quality, and how much of the performance is reasoning vs memorization.

**CVE Vulnerability Reproduction Agent** &nbsp;[GitHub](https://github.com/aastha2912/cve-vuln-reproduction)

Agent that takes a CVE description and generates a runnable Docker reproduction environment: Dockerfile, startup scripts, validation commands. GPT-4 drives environment generation; a second pass confirms the exploit is live inside the container.

---

## Experience

**University of Maryland** — Research Assistant

`2025 - 2026 · MEng Cybersecurity`

- Agentic LLM pipelines for vulnerability detection and repair, benchmark engineering, arXiv publication.

**Intrinsic (Google)** — Software Security Engineer Intern

`2025 - 2025 · Google · Robotics`

- Built a Python + PostgreSQL pipeline syncing 70K+ vulnerability findings weekly from GCP SCC and GitHub Actions CI into DefectDojo; cut analyst triage time by 63%.
- Zero-trust GCP environment (IAP, Workload Identity, Terraform-deployed alerting); drove median triage from 3 days to under 6 hours.

**Goldman Sachs** — Software Engineer II

`2021 - 2024 · Fed-regulated financial infrastructure`

- Built LCR/NSFR reporting pipelines processing ~10B records/day across the entire capital reporting stack.
- Redesigned the capital allocation engine (linear programming, $93B derivatives portfolio), closing a $3.2B regulatory gap.
- Shipped a shift-left validation framework, pub/sub tiered data classification, and group-based RBAC platform-wide.

Public filings: [LCR](https://www.goldmansachs.com/investor-relations/financials/other-information/2025/3q-2025-liquidity-coverage-ratio.pdf) &nbsp;·&nbsp; [NSFR](https://www.goldmansachs.com/investor-relations/financials/other-information/2025/3q-4q-nsfr-2025.pdf)

---

## Stack

Python · Java · C/C++ · GCP · Kubernetes · Docker · Kafka · PostgreSQL · Terraform · Semgrep · CodeQL · LangChain
