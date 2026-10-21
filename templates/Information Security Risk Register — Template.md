# Information Security Risk Register — Template
 
One row per risk. Scores use the scales in
[`../iso27001/risk-assessment-methodology.md`](../iso27001/risk-assessment-methodology.md)
(Impact 1–5 × Likelihood 1–5 = Risk 1–25).
 
| ID | Asset / process | Threat | Vulnerability | Risk (loss of C/I/A) | Owner | Impact | Likelihood | Score | Rating | Treatment | Annex A control(s) | Target date | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R-001 | Customer database | Unauthorised access | Weak access control | Confidentiality breach | IT Lead | 4 | 3 | 12 | High | Modify | A.5.15, A.8.5 | `<date>` | In progress |
| R-002 | Email | Phishing | Limited user awareness | Credential theft | SecOps | 4 | 4 | 16 | Critical | Modify | A.6.3, A.8.23 | `<date>` | Planned |
| R-003 | Backups | Ransomware | No offline backup | Availability loss | IT Lead | 5 | 3 | 15 | High | Modify | A.8.13, A.5.29 | `<date>` | In progress |
| R-004 | Supplier access | Third-party compromise | Weak supplier controls | Integrity / confidentiality | Procurement | 3 | 3 | 9 | Medium | Share/Modify | A.5.19–A.5.22 | `<date>` | Open |
| R-xxx | `<asset>` | `<threat>` | `<vulnerability>` | `<C/I/A>` | `<owner>` | `<1-5>` | `<1-5>` | `<calc>` | `<rating>` | `<option>` | `<A.x.x>` | `<date>` | `<status>` |
 
**Rating bands:** 1–4 Low · 5–9 Medium · 10–15 High · 16–25 Critical
**Treatment options:** Modify · Avoid · Share/Transfer · Accept (document justification + approver)
 
> Tip: keep this as a spreadsheet in practice (filter/sort by Score). This Markdown version
> is for the repo; the columns are the same.
 
