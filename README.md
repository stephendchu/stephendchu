### Stephen Chu
**I build evaluation & governance systems that make AI safe to ship in high-consequence, regulated environments.**

Most people building AI agents ask *"does it work?"* My focus is the harder
question regulated industries actually need answered: *"can you prove it — and
would you stake an audit on it?"* I design the **evaluation, grounding, and
governance layer** around agentic/LLM systems, and run it like an SRE:
deterministic, gated, auditable, and human-approved.

That comes from 14 years in **financial-markets infrastructure** — exchange
systems, SRE/reliability, and SOX-audited billing & clearing — where "mostly
right" was never an option. Most AI-eval engineers come from ML research; I come
from **production correctness enforcement in regulated systems**, which is exactly
what makes AI trustworthy enough to deploy in them.

#### A deliberate three-part arc — measuring & governing AI in regulated domains
> *"I measure, validate, and govern AI systems in high-consequence regulated environments."*

Each repo is one move in the progression:

- **🔎 Validate — [agentic-test-eval](https://github.com/stephendchu/agentic-test-eval)** ✅
  A controlled, contamination-aware study of *when* repo-aware agent tooling beats a
  strong baseline at writing tests — honest nulls, a falsifiable mechanism.
  → **[Read the study](https://stephendchu.github.io/agentic-test-eval/)**
- **📊 Measure — [filing-event-eval](https://github.com/stephendchu/filing-event-eval)** ✅
  Grounded event extraction from SEC filings with faithfulness / hallucination evals,
  anti-fabrication, and Arize Phoenix / OpenTelemetry tracing.
  → **[Read the page](https://stephendchu.github.io/filing-event-eval/)**
- **🛡 Govern — [assay](https://github.com/stephendchu/assay)** ← *capstone*
  An audit-first evaluation + governance **control plane**: grounding & anti-fabrication
  gates, a deterministic checkpointed run loop, maker-checker approval, and a
  tamper-evident audit log — demonstrated on a **SOX ITGC change-management** workflow.

#### Areas
AI evaluation & governance · grounding / hallucination detection · LLM
observability (Phoenix / OpenTelemetry) · eval control planes & gating · RAG &
agents · reliability / SRE for AI systems · SOX & auditable controls · Python

#### Background
14 years building and leading engineering teams in capital-markets / exchange
infrastructure — real-time market data, trading and reference-data systems,
SRE/reliability, and SOX-audited billing & clearing. Now focused on measuring and
governing AI in high-consequence environments.
