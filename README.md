# Audit.md

**The structured audit framework for every ML pipeline.**

A model hit 11.5% weighted MAPE. The team celebrated. A feature audit then found three variables were leaking the target. After removing them, error jumped to 71.3%. The model had never been forecasting — it had been reading the answer sheet.

`Audit.md` exists so that never happens to you.

---

## What's inside

- 14 pipeline stages — from problem definition to post-deployment monitoring
- 5 leakage types with detection patterns and code examples
- 100+ audit checks with severity tiers
- Feature Audit Log, Model Card, and Post-Mortem templates
- Walk-forward validation and drift monitoring code
- Pre-training and post-training master checklists

## How to use it

Drop `Audit.md` into every ML project repo alongside your `README.md`. Run it at every stage. No exceptions.

---

→ **[Open Audit.md](./Audit.md)**

---

*Domain-agnostic — works for classification, regression, forecasting, ranking, and anomaly detection.*
*License: Use freely. Star the repo. Audit relentlessly.*