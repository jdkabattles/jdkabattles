<div align="center">

# Jonathan D Battles

**Building the reliability layer for AI agents.**

Evidence-citing systems. Auditable runs. Contracts that fail closed.

[![X](https://img.shields.io/badge/X-@AITechInfluence-black?logo=x&logoColor=white)](https://x.com/AITechInfluence)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/Projects-MIT-green)](https://github.com/jdkabattles)

</div>

---

I build open-source tools that make AI agents trustworthy enough for production and regulated environments.

Agents hallucinate. Fluent answers are not proofs. My work forces every claim to cite evidence, every run to be append-only and verifiable, and every API contract to fail the build when it drifts.

Currently focused on **EvidenceForge** (framework for auditable agents) and **Verity** (append-only evidence ledger).

## Featured Work

| Project | What it does | Why it matters |
|---------|--------------|----------------|
| **[EvidenceForge](https://github.com/jdkabattles/EvidenceForge)** | Open-source framework for evidence-citing AI agents. Claims must reference a structured registry. Validator fails unsupported outputs. | The missing reliability layer between raw LLMs and agents that enterprises can actually ship. |
| **[Verity](https://github.com/jdkabattles/verity)** | Append-only evidence ledger. Every goal, tool call, and observation is hashed into a chain. Claims are rejected unless cited evidence supports them. | Makes agent runs replayable and tamper-evident. `verity verify` fails if the chain is broken. |
| **[harwatch](https://github.com/jdkabattles/harwatch)** | Freeze an API from a HAR file. Fail the build when a field disappears. | Contract testing from real traffic. Stops silent API breakage. |
| **[mimicplus-oss](https://github.com/jdkabattles/mimicplus-oss)** | Open core: HAR → OpenAPI + Python client. | Turns recorded traffic into living contracts. |

All Python. All MIT. All focused on the gap between agent demos and agent systems that survive contact with reality.

## Currently

- Shipping the EvidenceForge validator and agent instruction packs
- Exploring domain packs for legal, finance, and compliance
- Building on Termux for portable, isolated agent loops

## Stack

**Python** · FastAPI · Pydantic · JSON Schema · GitHub Actions · OpenAPI · HAR · LLM tool-calling contracts

## Find me

- X: [@AITechInfluence](https://x.com/AITechInfluence)
- Sites: [forgingstack.com](https://forgingstack.com) · [neuralmatrixvault.com](https://neuralmatrixvault.com)

---

*Agents that must be right. Claims that must cite. Builds that fail closed.*
