# Information Security Risk Register
**Framework:** ISO/IEC 27001:2022 — Clause 6.1.2  
**Scenario:** Fictional eCommerce Company — SecureShop LLC  
**Prepared by:** Sruti Susan Shaji | ISO/IEC 27001:2022 Certified Lead Auditor  
**Version:** 1.0  
**Date:** June 2026  

---

## Purpose
This risk register identifies and evaluates information security risks 
facing a fictional eCommerce organisation, aligned with ISO/IEC 27001:2022 
risk assessment requirements.

---

## Risk Scoring Matrix

| Likelihood | Score | Impact | Score |
|------------|-------|--------|-------|
| Rare | 1 | Negligible | 1 |
| Unlikely | 2 | Minor | 2 |
| Possible | 3 | Moderate | 3 |
| Likely | 4 | Major | 4 |
| Almost Certain | 5 | Critical | 5 |

**Risk Score = Likelihood × Impact**

| Risk Score | Rating |
|------------|--------|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Critical |

---

## Risk Register

### RISK-001 — Unauthorised Access to Customer Data

| Field | Detail |
|-------|--------|
| **Asset** | Customer database (personal & payment data) |
| **Threat** | Unauthorised internal or external access |
| **Vulnerability** | Weak access controls, shared admin credentials |
| **Likelihood** | 4 — Likely |
| **Impact** | 5 — Critical |
| **Risk Score** | 20 — Critical |
| **Current Controls** | Password policy, basic user roles |
| **Treatment** | Implement Role-Based Access Control (RBAC), enforce MFA |
| **Risk Owner** | IT Manager |
| **Status** | Open |

---

### RISK-002 — Third-Party Vendor Data Breach

| Field | Detail |
|-------|--------|
| **Asset** | Customer and order data shared with logistics vendor |
| **Threat** | Vendor suffers data breach exposing shared data |
| **Vulnerability** | No formal vendor security assessment process |
| **Likelihood** | 3 — Possible |
| **Impact** | 4 — Major |
| **Risk Score** | 12 — High |
| **Current Controls** | Basic contractual agreements |
| **Treatment** | Implement vendor risk assessments, include security clauses in contracts |
| **Risk Owner** | Procurement Manager |
| **Status** | Open |

---

### RISK-003 — Phishing Attack on Employees

| Field | Detail |
|-------|--------|
| **Asset** | Employee email accounts and credentials |
| **Threat** | Employees targeted by phishing emails |
| **Vulnerability** | Lack of security awareness training |
| **Likelihood** | 4 — Likely |
| **Impact** | 3 — Moderate |
| **Risk Score** | 12 — High |
| **Current Controls** | Basic spam filters |
| **Treatment** | Conduct regular security awareness training, simulate phishing tests |
| **Risk Owner** | HR & IT Manager |
| **Status** | In Progress |

---

### RISK-004 — Payment Data Interception

| Field | Detail |
|-------|--------|
| **Asset** | Online payment transactions |
| **Threat** | Man-in-the-middle attack intercepting payment data |
| **Vulnerability** | Outdated encryption protocols on payment pages |
| **Likelihood** | 2 — Unlikely |
| **Impact** | 5 — Critical |
| **Risk Score** | 10 — High |
| **Current Controls** | SSL certificate in place |
| **Treatment** | Enforce TLS 1.2+, conduct regular vulnerability scans |
| **Risk Owner** | IT Manager |
| **Status** | Open |

---

### RISK-005 — Loss of Business Data Due to System Failure

| Field | Detail |
|-------|--------|
| **Asset** | Product catalogue, order history, customer records |
| **Threat** | Server failure or accidental data deletion |
| **Vulnerability** | No tested backup and recovery procedure |
| **Likelihood** | 3 — Possible |
| **Impact** | 4 — Major |
| **Risk Score** | 12 — High |
| **Current Controls** | Weekly manual backups |
| **Treatment** | Implement automated daily backups, test recovery procedures quarterly |
| **Risk Owner** | IT Manager |
| **Status** | Open |

---

## Risk Summary

| Risk ID | Description | Score | Rating | Status |
|---------|-------------|-------|--------|--------|
| RISK-001 | Unauthorised Access to Customer Data | 20 | Critical | Open |
| RISK-002 | Third-Party Vendor Data Breach | 12 | High | Open |
| RISK-003 | Phishing Attack on Employees | 12 | High | In Progress |
| RISK-004 | Payment Data Interception | 10 | High | Open |
| RISK-005 | Loss of Business Data | 12 | High | Open |

---

## Notes
- Risk register to be reviewed quarterly or following significant changes
- All risks to be reassessed following implementation of treatment plans
- Risk owner is responsible for monitoring and updating status

---

*Aligned with ISO/IEC 27001:2022 Clause 6.1.2 — Information Security Risk Assessment*
