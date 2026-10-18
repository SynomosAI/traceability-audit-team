# traceability-audit-team · Traceability Audit Team

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)
[![Agent Skill](https://img.shields.io/badge/Agent%20Skill-SKILL.md-blue.svg)](SKILL.md)
[![Compliance Audit](https://img.shields.io/badge/compliance-audit-brightgreen.svg)](SKILL.md)

SynomosAI four-pillar system: **Identity · Traceability · Governance · Symbiosis**.

> This repo is part of the [SynomosAI](https://github.com/SynomosAI) skill ecosystem.

**Keywords**: AI identity traceability · evidence-chain audit · three-anchor verification · digital-human identity · provenance report

A three-role audit team (lead auditor / standards officer / report writer) that audits AI subjects, digital humans, AI-generated content and claimed identities for provenance and evidence chain — answering "whose is this, where did it come from, can it be trusted". Benchmarked on the accounting-firm audit paradigm: standards → evidence-chain audit → report.

## Quick Start

Prerequisite: place this directory in your agent skills folder (e.g. `~/.workbuddy/skills/`). Verify standards online before citing clauses.

```bash
git clone https://github.com/SynomosAI/traceability-audit-team.git
cd traceability-audit-team
cat SKILL.md
cat references/audit-report-template.md
```

```text
Triggers: traceability · audit · three-anchor verification · evidence chain
AI identity · digital-human identity · claimed-identity check · provenance report
```

## The three-anchor method

1. **Memory anchor** — is the subject's history and statements internally consistent and sourced?
2. **Identity anchor** — are credentials (ID, certificates, accounts) real, issued by a traceable authority, and consistent across platforms?
3. **Behavior anchor** — do outputs and decisions match the claimed identity, without signs of impersonation?

Any broken anchor becomes an audit finding. All three consistent + complete evidence chain → trustworthy.

## Repository layout

```text
traceability-audit-team/
├── SKILL.md            # skill main file (roles / anchors / SOP)
├── LICENSE.md
└── references/
    ├── audit-report-template.md
    ├── evidence-chain-checklist.md
    └── standards-map.md
```

## License

MIT License. © 2026 注册老炮. See [LICENSE.md](LICENSE.md).

## Disclaimer

Theoretical-positioning and tooling exploration. External standards (ISO/IEC 42001, EU AI Act, W3C DID·VC, NIST AI RMF, GB/T 45081-2024) are paraphrased from public sources; verify independently before formal citation.
