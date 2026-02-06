---
description: What This Accomplishes
---

# Viewing AI Audit Logs

Viewing AI audit logs allows users to **review exactly how artificial intelligence was used** within TRACE.

AI audit logs provide visibility into:

* When AI was used
* Why it was used
* What information was provided
* What output was generated
* Which model was used
* Who initiated the action

This enables oversight, audit review, and internal governance without relying on assumptions or reconstructions.

### When to Review AI Audit Logs

Users typically review AI audit logs when:

* Preparing for audits or regulatory reviews
* Investigating how content was generated
* Validating AI usage against internal policy
* Reviewing high-impact decisions
* Responding to internal or external inquiries

AI audit logs are available regardless of whether AI usage is frequent or rare.

### Who Can Access AI Audit Logs

Access to AI audit logs is role-based.

Depending on permissions:

* Administrators and designated reviewers can view detailed audit entries
* Other users may see limited metadata or summaries
* Sensitive prompt details may be restricted

All access to AI audit logs is itself logged.

### How to View AI Audit Logs

#### Step 1: Navigate to the AI Audit Log

From the TRACE navigation, go to **AI Audit Logs** or the **Audit / Oversight** area, depending on your configuration.

<figure><img src="../../.gitbook/assets/AI Log.png" alt=""><figcaption></figcaption></figure>

#### Step 2: Review the Log Overview

The AI audit log displays a list of AI-assisted actions, typically showing:

* Date and time
* User who initiated the action
* Associated assessment or section
* AI action type (e.g., drafting, summarization)
* AI provider and model

This view provides a high-level summary of AI usage activity. Clicking Show Audit Details in the upper right hand corner surfaces more detailed log information. After clicking show audit details, uncheck group by assessment.

<figure><img src="../../.gitbook/assets/AI Audit Log.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Grup by assessment.png" alt=""><figcaption></figcaption></figure>

#### Step 4: View a Detailed Audit Entry

Selecting an individual log entry reveals detailed information, such as:

* Purpose of the AI action
* Summary of input data provided
* Output preview
* AI provider and model version
* User attribution
* Timestamps and duration
* Integrity or verification metadata

This detail allows reviewers to understand **exactly what occurred**.

<figure><img src="../../.gitbook/assets/Full ai audit log (1).png" alt=""><figcaption></figcaption></figure>

### How AI Audit Logs Are Used in Practice

AI audit logs are commonly used to:

* Validate compliance with AI governance policies
* Support audit evidence requests
* Explain AI involvement in specific decisions
* Investigate unexpected or disputed outputs

They provide context without requiring technical expertise.

### What TRACE Records

For every AI-assisted action, TRACE records:

* The initiating user
* The purpose of AI usage
* The model and provider used
* A summary of inputs and outputs
* Time and duration of the action
* Integrity metadata

These records are immutable and time-stamped.
