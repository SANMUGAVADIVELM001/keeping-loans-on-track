# Keeping Loans on Track  
### Proactive Digital Loan Monitoring & Risk Intelligence Platform  
**LMA EDGE Hackathon Submission**

---

## Overview

**Keeping Loans on Track** is a digital loan monitoring solution designed to help lenders move from **reactive, post-default management** to **proactive, data-driven loan oversight**.

The platform introduces **day-wise repayment visibility, explainable risk intelligence, and role-based governance** to ensure loans remain compliant, transparent, and operationally efficient throughout their lifecycle — from origination to closure.

This solution directly aligns with the **LMA EDGE Hackathon theme: _Keeping Loans on Track_** by strengthening early risk detection, accountability, and decision transparency.

---

## Problem Context

Current loan monitoring practices across banks and NBFCs face structural limitations:

- Loan health is assessed **only after EMI defaults**
- No day-level visibility into borrower repayment behaviour
- Manual follow-ups lead to delayed interventions
- Re-loan decisions rely heavily on intuition rather than data
- Limited branch-level accountability and governance visibility

These gaps increase operational risk, default rates, and compliance overhead.

---

## Proposed Solution

A **proactive, end-to-end loan performance monitoring system** that:

- Tracks borrower repayment behaviour **day by day**
- Identifies early warning signals **before EMI default**
- Provides **explainable, AI-assisted insights** for decision-makers
- Enforces **role-based governance** across branches
- Preserves existing loan workflows and regulatory controls

All enhancements are **additive**, ensuring seamless adoption without disrupting existing systems.

---

## User Roles & Governance Model

### Supervisor
- Creates and manages branches with unique branch codes
- Oversees cross-branch performance and risk exposure
- Views consolidated analytics, audit logs, and reports
- Governance-level access (read-only for financial actions)

### Manager
- Operates within an assigned branch
- Creates borrowers and loans
- Updates repayment status (Paid / Unpaid / Overdue)
- Reviews borrower analytics and AI risk insights
- Makes final re-loan approval decisions (AI-assisted, human-controlled)

### Borrower
- Read-only access to personal loan details
- Views EMI schedules, payment history, and fines
- Receives reminders and notifications
- Can raise support requests (no financial control)

---

## Core Capabilities

- Proactive, lifecycle-wide loan performance monitoring
- Day-wise borrower repayment behaviour analysis
- Early risk detection with AI-assisted indicators
- Explainable risk and re-lend scoring
- Branch-level data isolation with centralized supervision
- Manager-controlled financial actions
- Preventive alerts and actionable dashboards
- Full auditability and compliance readiness

---

## AI-Driven Intelligence & Impact

- Continuous behaviour-based monitoring beyond EMI-level tracking
- Early identification of delinquency patterns
- Explainable risk scoring to support accountable decisions
- Improved re-lending accuracy through historical behaviour insights
- Reduced defaults via timely, preventive interventions

---

## Dashboards & Analytics

### Manager View
- Active loan portfolio overview
- High-risk and overdue borrower identification
- Day-wise repayment timelines and heatmaps
- Risk tags (Green / Amber / Red)
- Re-lend score with reasoning
- Today’s priority worklist

### Supervisor View
- Branch-wise performance comparison
- Collection efficiency and overdue exposure
- Manager productivity insights
- Cross-branch risk distribution
- Compliance and audit summaries

---

## Alerts & Notifications

- Borrower reminders via SMS and email
- Manager alerts for overdue and high-risk loans
- Early-warning signals based on behaviour trends
- Full notification history for transparency

---

## Audit, Compliance & Transparency

- Immutable audit trail for all system actions
- Detailed logs capturing who, what, when, and where
- Branch-level access control and data isolation
- Alignment with RBI digital lending and governance principles
- Human-in-the-loop decision enforcement

---

## Scalability & Adoption

- Supports multi-branch and multi-manager environments
- Modular, extensible architecture
- Scales with growing loan and borrower volumes
- Suitable for NBFCs, regional banks, and large financial institutions
- Deployable as an overlay on existing loan systems

---

## Technology Stack (High Level)

- **Frontend:** React.js, JavaScript, modern UI frameworks
- **Backend:** Node.js, REST APIs, secure authentication
- **Data:** Relational databases, caching layers
- **AI/Analytics:** Python-based ML models (Logistic Regression, XGBoost)
- **Notifications:** SMS and email integrations

---

## UI Screenshots & Design Artifacts

UI screenshots, wireframes, and design flows are available in the `/screenshots` folder, including:

- Supervisor dashboard
- Branch creation and governance flow
- Manager analytics and risk views
- Borrower loan visibility screens

---

## Hackathon Alignment

**Theme:** Keeping Loans on Track  
**Focus Areas Addressed:**
- Transparency and accountability  
- Risk prevention and early intervention  
- Operational efficiency  
- Explainable AI in lending  
- Sustainable and compliant loan management  

---

## One-Line Summary

*A proactive, AI-assisted loan monitoring platform that keeps loans on track through day-wise borrower behaviour analysis and role-based governance.*

---

