### Stephen Chu
**I build evaluation & governance systems that make AI safe to ship in high-consequence, regulated environments.**

I work on the **evaluation, grounding, and governance layer** around agentic and
LLM systems, and I run it like production infrastructure: outputs get checked,
gated, logged, and signed off before anyone relies on them. The aim is an AI
system whose behavior you can prove and defend in an audit, not just one that
looks good in a demo.

That background is 14 years in **financial-markets infrastructure**: exchange
systems, SRE/reliability, and SOX-audited billing and clearing. In regulated
trading systems, a wrong number is a real financial and compliance problem, so
correctness and auditability were always part of the job. Most people who do AI
evals come from ML research. I came up through production and regulation, which
is the side that matters most when you have to put AI into environments like
these.

---

#### Measuring & governing AI in regulated domains

Four repos, one progression — each one a different layer of the same problem:

- **🔎 Validate — [agentic-test-eval](https://github.com/stephendchu/agentic-test-eval)** ✅
  A controlled, contamination-aware study of *when* repo-aware agent tooling beats a
  strong baseline at writing tests — honest nulls, a falsifiable mechanism.
  → **[Read the study](https://stephendchu.github.io/agentic-test-eval/)**
- **📊 Measure — [filing-event-eval](https://github.com/stephendchu/filing-event-eval)** ✅
  Grounded event extraction from SEC filings with faithfulness / hallucination evals,
  anti-fabrication, and Arize Phoenix / OpenTelemetry tracing.
  → **[Read the page](https://stephendchu.github.io/filing-event-eval/)**
- **🛡 Govern — [assay](https://github.com/stephendchu/assay)** ✅
  An audit-first governance **control plane**: grounding & anti-fabrication gates,
  deterministic rule checks, maker-checker approval, and a tamper-evident audit log —
  on **SOX change-management** and **PAD trade surveillance**. Control-F1 0.87 [0.73, 1.00], 35 tests all offline.
  → **[Read the page](https://stephendchu.github.io/assay/)**
- **⚖️ Certify — [hr-fidelity](https://github.com/stephendchu/hr-fidelity)** ✅
  A bias-audit and certification layer for AI résumé screeners — EEOC four-fifths
  disparate impact, counterfactual drift, and recruiter–AI agreement (Cohen's κ) —
  CERTIFIED or BLOCKED before the screener touches a live application.
  → **[Live demo](https://hr-fidelity-schu.fly.dev)**
