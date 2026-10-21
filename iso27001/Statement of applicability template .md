# ISO/IEC 27001:2022 — Statement of Applicability (SoA) Template
 
The **Statement of Applicability (clause 6.1.3 d)** lists all **Annex A** controls and, for
each, whether it is **applicable**, the **justification**, and its **implementation status**.
 
**Annex A 2022** has **93 controls** in **4 themes**:
 
| Theme | Reference | # controls |
|---|---|---|
| Organizational | A.5.1 – A.5.37 | 37 |
| People | A.6.1 – A.6.8 | 8 |
| Physical | A.7.1 – A.7.14 | 14 |
| Technological | A.8.1 – A.8.34 | 34 |
 
> 2022 also introduced **5 attributes** per control (control type, information security
> properties — C/I/A, cybersecurity concepts, operational capabilities, security domains)
> and **11 new controls** (e.g. threat intelligence, information security for cloud,
> ICT readiness for business continuity, physical security monitoring, configuration
> management, information deletion, data masking, data leakage prevention, monitoring
> activities, web filtering, secure coding).
 
## SoA table (fill one row per Annex A control)
 
| Control | Title | Applicable (Y/N) | Justification | Status | Linked risk(s) | Evidence |
|---|---|---|---|---|---|---|
| A.5.1 | Policies for information security | Y | Required baseline | Implemented | R-001 | ISMS policy v1.2 |
| A.5.7 | Threat intelligence | Y | Supports risk-based defence | In progress | R-014 | Threat-intel procedure |
| A.5.23 | Information security for use of cloud services | Y | Cloud-hosted services in scope | Implemented | R-008 | Cloud security standard |
| A.6.3 | Information security awareness, education and training | Y | Human-risk reduction | Implemented | R-003 | Training records |
| A.7.4 | Physical security monitoring | Y | On-prem assets in scope | Implemented | R-011 | CCTV/access logs |
| A.8.8 | Management of technical vulnerabilities | Y | Vulnerability handling required | In progress | R-006 | Patch/vuln procedure |
| A.8.12 | Data leakage prevention | Y | Sensitive data in scope | Planned | R-009 | DLP standard |
| A.8.16 | Monitoring activities | Y | Detection capability | In progress | R-006 | SIEM use cases |
| A.8.23 | Web filtering | Y | Reduce malicious-site exposure | Implemented | R-012 | Proxy policy |
| A.8.28 | Secure coding | <Y/N> | `<justify based on whether you develop software>` | `<status>` | `<R-xxx>` | `<evidence>` |
| ... | *(continue for all 93 controls)* | | | | | |
 
### Status values
`Implemented` · `In progress` · `Planned` · `Not applicable`
 
### Notes
- Every **applicable** control must trace to at least one **risk** and have **evidence**.
- A control marked **Not applicable** needs a clear justification (e.g. "no software is
  developed in-house" for A.8.25–A.8.28).
- The SoA is a **living document** — update it whenever risks, controls or scope change.
---
*Template — ISO/IEC 27001:2022 Annex A. For the full control text, refer to the official standard.*
 
