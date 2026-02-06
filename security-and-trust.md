---
description: >-
  TRACE is designed to support organizations operating in regulated, high-risk
  environments where security, confidentiality, and auditability are mandatory.
---

# Security and Trust

This page describes **how** TRACE **protects customer data, controls access, and supports secure, auditable governance workflows**. It does not replace an organization’s own security program, but is intended to clearly explain TRACE’s security posture and design principles.

### Security by Design

Security is built into TRACE’s core architecture rather than added as an afterthought.

Key principles include:

* Strong tenant isolation
* Role-based access controls
* Explicit human approvals for governance actions
* Comprehensive logging and auditability
* Defense against unauthorized access and tampering

All sensitive actions are designed to be **intentional, reviewable, and attributable**.

### Data Protection

TRACE is designed to protect customer data throughout its lifecycle.

#### Data Handling Principles

* Customer data is used only to provide the TRACE service
* Data is logically isolated by tenant
* Data minimization is applied wherever possible
* Customer data is not used to train AI models

#### Encryption

* Data is encrypted in transit using industry-standard protocols
* Data is encrypted at rest using modern encryption mechanisms

### Access Controls and Authorization

Access to TRACE is governed through role-based access controls.

This includes:

* Separation of duties between contributors, reviewers, and approvers
* Restricted access to sensitive areas (e.g., AI audit logs, approval workflows)
* Explicit permissions required for approving assessments, risks, and mitigations

All access to sensitive data and administrative functions is logged for audit and review.

### Human-in-the-Loop Controls

TRACE is designed to preserve human accountability at all times.

In TRACE:

* AI actions are always initiated by a human
* AI outputs are clearly labeled
* AI outputs are never finalized automatically
* Human review and approval are required before decisions are recorded

This ensures that governance outcomes remain **human-directed and explainable**, even when AI is used to assist drafting or analysis.

### AI Data Handling and Model Controls

TRACE integrates with AI providers through enterprise-grade APIs.

AI-related controls include:

* No customer data is used to train AI models
* Only necessary information is provided to AI systems
* AI model selection can be configured by the organization
* All AI usage is logged and auditable

Details of AI activity are captured in **AI Audit Logs**, enabling traceability of AI-assisted actions without relying on assumptions or reconstruction.

### Auditability and Logging

TRACE maintains comprehensive audit logs across governance workflows.

This includes:

* Assessment creation and approval
* Risk identification and decision-making
* Mitigation actions
* AI-assisted activity
* Access to sensitive records

Audit logs are designed to be:

* Tamper-evident
* Chronologically ordered
* Attributable to specific users and actions

These records support regulatory inquiries, audits, and internal investigations.

### Customer Responsibility

TRACE provides tooling to support secure, auditable governance workflows.\
Customers remain responsible for:

* Determining how TRACE is used within their organization
* Reviewing and approving outputs
* Making final governance decisions
* Ensuring compliance with applicable laws and regulations

TRACE does not replace professional judgment or regulatory accountability.
