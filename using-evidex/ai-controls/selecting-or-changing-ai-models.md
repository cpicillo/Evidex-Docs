---
description: What This Accomplishes
---

# Selecting or Changing AI Models

Selecting or changing the AI model in Evidex allows organizations to **control which AI provider and model are used** for AI-assisted workflows.

This control ensures alignment with:

* Internal AI governance policies
* Risk tolerance and regulatory expectations
* Data handling and vendor requirements

Model selection affects **future AI-assisted actions only** and does not retroactively alter prior records.

### When to Select or Change an AI Model

Organizations may select or change AI models when:

* Establishing initial AI governance settings
* Updating internal AI policies
* Responding to regulatory or procurement requirements
* Evaluating model performance or suitability
* Temporarily disabling AI assistance

Model changes are intentional administrative actions.

### How AI Model Selection Works in Evidex

AI model selection in Evidex is:

* **Tenant-scoped** (applies at the organizational level)
* **Explicit** (requires a human action)
* **Auditable** (changes are logged)

Evidex supports multiple AI providers and allows organizations to determine which model is used for AI-assisted drafting and analysis.

AI models are used **only** when a user initiates an AI-assisted action.

### Selecting or Changing an AI Model

#### Step 1: Navigate to AI Settings

From the administrative or settings area, navigate to **AI Controls** or **AI Settings**.

Only users with appropriate permissions can view or modify AI model settings.

<figure><img src="../../.gitbook/assets/AI Configurations.png" alt=""><figcaption></figcaption></figure>

#### Step 2: Select the Desired AI Model

Choose from the available AI providers and models configured for your organization.

Model options may include different providers or versions, depending on availability and configuration.

Selection considerations typically include:

* Organizational policy requirements
* Data handling expectations
* Model capabilities and limitations

<figure><img src="../../.gitbook/assets/AI configurations 1.png" alt=""><figcaption></figcaption></figure>

#### Step 3: Confirm the Change

After selecting a model:

* Confirm the change
* The selected model becomes active for future AI-assisted actions

Existing assessments, decisions, and audit records remain unchanged.

#### Step 3: Confirm the Change

After selecting a model:

* Confirm the change
* The selected model becomes active for future AI-assisted actions

Existing assessments, decisions, and audit records remain unchanged.

### What Evidex Records

When an AI model is selected or changed, Evidex records:

* The previous and newly selected model
* The user who made the change
* The date and time of the change
* The scope of the change (organizational / tenant-level)

These records support AI governance and oversight.

### Disabling AI Assistance

Organizations may choose to disable AI assistance entirely.

When AI is disabled:

* AI-assisted actions are unavailable
* Manual workflows remain fully functional
* No AI audit logs are generated

This allows organizations to operate Evidex without AI if desired.
