# IT General Controls Assessment & Improvement Plan  
**Project for NovaCore Microfinance Bank**

---

## 🏢 Organization Overview

- **Name:** NovaCore Microfinance Bank  
- **Industry:** Financial Services  
- **Size:** ~350 employees  
- **Locations:** Head Office + 5 branches nationwide  
- **Core Systems:**  
  - Core Banking System (CBS)  
  - Human Resource Management System (HRMS)  
  - Document Management System (DMS)  
  - Cloud-hosted Email & Productivity Tools (O365)  

---

## 📌 Business Situation

NovaCore recently failed a preliminary audit by a potential investor and was flagged by the central bank due to IT control weaknesses. There is an urgent need to improve IT General Controls (ITGC) across:

- Access Management  
- Change Management  
- Backup & Recovery  
- System Logging & Monitoring  

The Board has approved an ITGC remediation project with a 3-month timeline. As the Internal IT Risk Consultant, the task is to conduct a full ITGC assessment and develop an actionable improvement plan.

---

## 🔍 Key Problems Identified (Scenario Input)

| Area              | Sample Control Gaps                              |
|-------------------|-------------------------------------------------|
| **Access Management** | No formal user access review; orphaned accounts active |
| **Change Management** | Changes made directly in production; no documentation or testing |
| **Backup & Recovery** | No documented recovery procedures; backups not encrypted |
| **Logging & Monitoring** | No SIEM or centralized log repository; logs deleted after 7 days |
| **Policy & Governance** | Security policies outdated; no formal ITGC framework |

---

## 🚀 Project Scope & Objectives

### Scope  
Assess effectiveness and compliance of ITGCs across:

- Access Management  
- Change Management  
- Backup & Recovery  
- Logging & Monitoring  
- Privacy & Data Protection  
- IT Policy & Governance  

Evaluate against regulatory frameworks and standards such as ISO/IEC 27001, SOX, and COBIT 2019.

### Objectives  
- Assess maturity of ITGCs in NovaCore’s IT environment  
- Identify and document control weaknesses and risks  
- Assign remediation responsibilities  
- Ensure all critical ITGC deficiencies are addressed within 3 months  

### Timeline  
3 months (assessment and remediation planning)

### Stakeholders

| Stakeholder         | Role                                      |
|---------------------|-------------------------------------------|
| IT Department       | Provide system access and technical input |
| HR Department       | Collaborate on user lifecycle controls    |
| Chief Information Security Officer (CISO) | Oversee security strategy and remediation |
| Risk & Compliance Unit | Ensure regulatory alignment              |
| Executive Management | Approve roadmap and receive risk summaries|

---

## STEP 2: Current State Assessment & Gap Analysis

| Domain             | Control Weakness Summary                           | Risk Level |
|--------------------|--------------------------------------------------|------------|
| Access Management   | Orphan accounts active; no formal access reviews | High       |
| Change Management   | Direct production changes; no testing/documentation | High     |
| Backup & Recovery   | Unencrypted backups; no disaster recovery plan   | High       |
| Logging & Monitoring| Short log retention; no centralized logging      | High       |
| Governance & Policy | Outdated security policies                        | Medium     |

### Detailed Weaknesses and Impact

| Domain           | Identified Weakness                              | Risk Level | Potential Impact                                        |
|------------------|-------------------------------------------------|------------|---------------------------------------------------------|
| Access Management | Orphaned user accounts not disabled              | High       | Unauthorized access leading to potential fraud          |
|                  | No formal access reviews                          | High       | Over-privileged accounts and compliance violations      |
| Change Management | Direct changes in production without testing     | High       | System outages, financial loss, reputational damage     |
|                  | No documentation of changes                       | Medium     | Poor audit trail and incident response                   |
| Backup & Recovery | Backups not encrypted                             | High       | Data breach risk                                        |
|                  | No disaster recovery plan or testing              | High       | Prolonged outages, data loss                             |
| Logging & Monitoring | Logs deleted after 7 days                      | High       | Impaired forensic investigations                        |
|                  | No centralized logging or SIEM                    | High       | Reduced threat visibility and response                   |
| Policy & Governance | Outdated security policies                       | Medium     | Regulatory non-compliance                               |
|                  | No formal ITGC framework                           | Medium     | Lack of standardization, audit failures                  |

---

## Deliverable 4: Mapping Gaps to ISO 27001 Controls

| ITGC Domain         | Gap Identified                                | ISO 27001 Control Reference         |
|---------------------|-----------------------------------------------|------------------------------------|
| Access Control      | Inactive/offboarding user accounts not disabled | A.9.2.6 – Removal of Access Rights  |
| Access Control      | No formal access reviews                        | A.9.2.1 – User Access Management    |
| Change Management   | No sandbox/testing before production changes   | A.12.1.2 – Change Management        |
| Change Management   | No documentation or approvals                   | A.12.1.2 – Change Management        |
| Backup & Recovery   | Unencrypted backups, no DR plan                  | A.12.3.1 – Information Backup       |
| Logging & Monitoring| Logs deleted after 7 days; no centralized logging | A.12.4.1 – Event Logging            |
| Logging & Monitoring| No SIEM or endpoint integration                   | A.12.4.3 – Administrator Logs      |
| Information Security Policy | Outdated policies, no reviews               | A.5.1.1 – Policies for Information Security |
| Governance & Awareness | No ITGC framework or training                   | A.7.2.2 – Information Security Awareness, Education and Training |

---

## Deliverable 5: ITGC Improvement Plan – Summary

### Access Management  
- Enforce strict onboarding/offboarding processes  
- Conduct periodic user access reviews  
- Auto-disable accounts inactive for 30 days  

### Change Management  
- Formalize change management policies with documented approvals  
- Test all changes in sandbox/staging environments before production  
- Maintain vulnerability scanning and patch management records  

### Backup & Recovery  
- Encrypt all backups (at rest and in transit)  
- Develop and regularly test a Disaster Recovery plan  

### Logging & Monitoring  
- Deploy a SIEM system (e.g., Splunk, Microsoft Sentinel)  
- Extend log retention to 30+ days  
- Use logs proactively for incident detection and resolution  

### Governance & Policy  
- Conduct annual policy reviews and updates  
- Adopt formal ITGC frameworks aligned with industry standards  

---

## Deliverable 6: Monitoring & Reporting Framework

### Performance Tracking  
- Define clear timelines for remediation tasks (e.g., 2–3 weeks for access control fixes)  
- Track progress via completion rate, task status, bottlenecks  

### Regular Review Meetings  
- Biweekly meetings (or more frequent early on) via Zoom/Teams  
- Record minutes and assign action items  
- Use shared dashboard (Excel, Power BI, Jira) for status updates  

### Stakeholder Responsibility Matrix  

| Stakeholder        | Responsibilities                                  |
|--------------------|--------------------------------------------------|
| IT Department      | Implement technical controls (access, logs, backup) |
| HR Department      | Review onboarding/offboarding procedures          |
| CISO               | Strategic oversight and risk prioritization       |
| Audit & Compliance | Ensure regulatory compliance and internal audits  |

---

# Contact  
For questions or contributions, please reach out to the project lead or submit issues via GitHub.

---

*This README documents the assessment and improvement project for NovaCore Microfinance Bank’s IT General Controls.*

