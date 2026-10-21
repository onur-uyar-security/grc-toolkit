# ISO/IEC 27001 — Information Security Risk Assessment Methodology
 
A generic, repeatable method aligned with **ISO/IEC 27001:2022 clause 6.1.2** (information
security risk assessment) and **clause 8.2** (performing assessments). Replace `<...>` with
your own context.
 
## 1. Purpose & scope
Define how `<organisation>` identifies, analyses and evaluates information security risks
within the ISMS scope, so that treatment decisions are consistent and repeatable.
 
## 2. Risk criteria
 
### 2.1 Impact scale (Confidentiality / Integrity / Availability)
| Level | Score | Description (example) |
|---|---|---|
| Very low | 1 | Negligible effect; no regulatory or customer impact |
| Low | 2 | Minor disruption; handled within the team |
| Medium | 3 | Noticeable disruption; some customer/regulatory attention |
| High | 4 | Major disruption; contractual/regulatory breach likely |
| Very high | 5 | Severe/unrecoverable; significant legal, financial or safety impact |
 
### 2.2 Likelihood scale
| Level | Score | Description (example) |
|---|---|---|
| Rare | 1 | Not expected (< once in 5 years) |
| Unlikely | 2 | Could occur (once in 2–5 years) |
| Possible | 3 | Might occur (yearly) |
| Likely | 4 | Expected (several times a year) |
| Almost certain | 5 | Frequent (monthly or more) |
 
### 2.3 Risk rating
**Risk = Impact × Likelihood** (1–25).
 
| Risk score | Rating | Action |
|---|---|---|
| 1–4 | Low | Accept / monitor |
| 5–9 | Medium | Treat where cost-effective |
| 10–15 | High | Treat — plan required |
| 16–25 | Critical | Treat urgently — management attention |
 
### 2.4 Risk acceptance criteria
Risks rated **Low** may be accepted by the risk owner. **Medium and above** require a
documented treatment decision and approval by `<role>`.
 
## 3. Process
1. **Identify assets / processes** in scope and their owners.
2. **Identify threats and vulnerabilities** for each.
3. **Identify risks** (loss of C, I or A) and assign a **risk owner**.
4. **Analyse** — assign Impact and Likelihood using the scales above.
5. **Evaluate** — compare to risk acceptance criteria; prioritise.
6. **Treat** — select an option (below) and map to **Annex A** controls → feed the SoA.
7. **Record** in the risk register; review at planned intervals and after major change.
## 4. Risk treatment options (clause 6.1.3)
- **Modify / mitigate** — apply controls (reference Annex A).
- **Avoid** — stop or change the activity.
- **Share / transfer** — insurance, outsourcing (with supplier controls).
- **Accept** — document the justification and the accepting authority.
## 5. Outputs
- Information security **risk register** (see [`../templates/risk-register.md`](../templates/risk-register.md))
- **Risk treatment plan** (owner, control, due date, status)
- **Statement of Applicability** (see [`statement-of-applicability-template.md`](statement-of-applicability-template.md))
## 6. Review
The risk assessment is reviewed **at least annually** and after significant change
(new systems, incidents, regulatory change). Results feed the **management review**
(clause 9.3).
 
---
*Template — ISO/IEC 27001:2022. Replace placeholders; keep records as evidence.*
