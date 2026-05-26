# Aastha Mahajan

Software engineer. Built production systems processing 10B records a day, closed a $3.2B regulatory capital gap, and now building agents that find and fix vulnerabilities in LLM-generated code.

MEng Cybersecurity @ University of Maryland &nbsp;·&nbsp; Prev: Goldman Sachs &nbsp;·&nbsp; Google (Intrinsic)

[LinkedIn](https://linkedin.com/in/yourhandle) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2510.13859)

---

## Research & Publications

**Agentic LLM Pipeline for Automated Vulnerability Detection and Repair** *(forthcoming, June 2025)*

End-to-end agentic pipeline for vulnerability detection and patch synthesis across multi-turn code generation contexts. Agent orchestration, context capture instrumentation, eval against real bug corpora.

**MT-Sec: Benchmarking Correctness and Security in Multi-Turn Code Generation** *(2025)* &nbsp;[arXiv](https://arxiv.org/abs/2510.13859)

Built the benchmark, eval pipeline, and agentic detection layer across 2,376 tasks and 27 CWEs. Key finding: even state-of-the-art models show a 20-27% drop in correct and secure outputs from single-turn to multi-turn, and agents make it worse, not better.

**ARVO Patching Agent Evals** &nbsp;[GitHub](https://github.com/aastha2912/aixcc-afc-archive/tree/main/crs/arvo-patching-agent)

Integrated the Theori patching agent with the ARVO dataset and ran structured evals: detection accuracy, patch quality, and how much of the performance is reasoning vs memorization.

**CVE Vulnerability Reproduction Agent** &nbsp;[GitHub](https://github.com/aastha2912/cve-vuln-reproduction)

Agent that takes a CVE description and generates a runnable Docker reproduction environment: Dockerfile, startup scripts, validation commands. GPT-4 drives environment generation; a second pass confirms the exploit is live inside the container.

---

## Experience

**Goldman Sachs** — Software Engineer I to II

`2021 - 2025 · Fed-regulated financial infrastructure`

- Built LCR/NSFR reporting pipelines processing ~10B records/day across the entire capital reporting stack.
- Redesigned the capital allocation engine (linear programming, $93B derivatives portfolio), closing a $3.2B regulatory gap.
- Shipped a shift-left validation framework, pub/sub tiered data classification, and group-based RBAC platform-wide.

**Intrinsic (Google)** — Security Engineering Intern

`Google · Robotics`

- Static analysis tooling (Semgrep, CodeQL), threat modeling, and ARVO pipeline integration on GCP.

**University of Maryland** - Research Assistant

`2024 - 2026 · MEng Cybersecurity`

- Agentic LLM pipelines for vulnerability detection and repair, benchmark engineering, arXiv publication.

---

## Stack

Python · Java · C/C++ · GCP · Kubernetes · Docker · Kafka · PostgreSQL · Terraform · Semgrep · CodeQL · LangChain
