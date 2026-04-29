# GRC Risk Register

A cybersecurity risk register built to document, score, and track risks across key security domains using industry-standard GRC methodology. This project was developed as a portfolio piece to demonstrate practical knowledge of cybersecurity risk management, compliance frameworks, and executive-ready reporting.

---

## Overview

This risk register provides a structured, actionable view of cybersecurity risk across seven domains. Each risk is documented using a cause → event → business impact format, scored using a likelihood × impact matrix, and tracked through mitigation plans, control owners, and remediation timelines.

---

## Risk Domains Covered

- Identity & Access Management
- Endpoint Security
- Vulnerability Management
- Logging & Monitoring
- Backup & Recovery
- Cloud Security
- Third-Party / Vendor Risk

---

## Methodology

### Risk Scoring
Risks are scored using a **5×5 likelihood × impact matrix**:

| Score | Likelihood | Impact |
|-------|------------|--------|
| 1 | Rare | Negligible |
| 2 | Unlikely | Minor |
| 3 | Possible | Moderate |
| 4 | Likely | Major |
| 5 | Almost Certain | Critical |

**Risk Rating Scale:**
| Score Range | Rating |
|-------------|--------|
| 15 – 25 | 🔴 Critical |
| 10 – 14 | 🟠 High |
| 5 – 9 | 🟡 Medium |
| 1 – 4 | 🟢 Low |

### Risk Documentation Format
Each risk is documented using the following structure:
- **Cause** — The root condition that enables the risk
- **Event** — The threat action or failure that could occur
- **Business Impact** — The consequence to the organization if the event occurs
- **Existing Controls** — Current safeguards in place
- **Control Gaps** — Where current controls fall short
- **Mitigation Plan** — Recommended remediation actions
- **Owner** — Accountable team or role
- **Due Date** — Target remediation timeline
- **Status** — Open, In Progress, Accepted, or Closed

---

## Framework Alignment

This risk register aligns with the **NIST Cybersecurity Framework (CSF)** core functions:

| NIST CSF Function | Domains Covered |
|-------------------|-----------------|
| Identify | Third-Party Risk, Vulnerability Management |
| Protect | Identity & Access, Endpoint Security, Cloud Security |
| Detect | Logging & Monitoring |
| Respond | Logging & Monitoring |
| Recover | Backup & Recovery |

---

## File Structure

```
grc-risk-register/
│
├── cybersecurity_risk_register.xlsx   # Main risk register with dashboard
└── README.md                          # Project documentation
```

### Workbook Tabs
- **Risk Register** — Full risk ledger with scoring, controls, gaps, and mitigation plans
- **Dashboard** — Executive summary with risk counts by rating, domain, and status

---

## Risk Summary

| Risk ID | Domain | Risk Title | Rating | Status |
|---------|--------|------------|--------|--------|
| R-001 | Identity & Access | MFA Not Enforced on Privileged Accounts | 🔴 Critical | In Progress |
| R-002 | Endpoint Security | Inconsistent EDR Deployment | 🟡 Medium | Closed |
| R-003 | Vulnerability Management | No Formal Patch Management Process | 🔴 Critical | Open |
| R-004 | Logging & Monitoring | Incomplete Log Coverage | 🟠 High | In Progress |
| R-005 | Backup & Recovery | Untested Backup Recovery | 🟢 Low | Accepted |
| R-006 | Cloud Security | Cloud Misconfiguration Exposure | 🟡 Medium | Closed |
| R-007 | Third-Party Risk | No Vendor Security Assessment | 🟠 High | Open |

---

## Skills Demonstrated

- Cybersecurity risk documentation and scoring
- Control gap analysis and mitigation planning
- NIST CSF framework mapping
- Executive-ready risk reporting and dashboard design
- GRC (Governance, Risk & Compliance) fundamentals
- Microsoft Excel / Google Sheets for structured risk tracking

---

## Author

**Shaunak Peri**
