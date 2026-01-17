# Working With Clarity Alliance

## Audit Engagement Overview

This document outlines what a typical security audit engagement with **Clarity Alliance** looks like, from initial scoping through final report delivery. Its purpose is to help teams understand our workflow, expectations, and how to collaborate effectively with our researchers.

---

## 1. Initial Scoping & Familiarization

Before any formal engagement begins, we require access to the relevant codebase in order to scope the audit.

At this stage:

- You grant us **read access** to the repository (public or private).
- We review the codebase to understand:
  - Architecture and design patterns
  - Core protocol logic and assumptions
  - Scope size and technical complexity

This step allows us to:

- Define an accurate audit scope
- Estimate timelines
- Price the engagement appropriately

**This scoping and familiarization phase is free of charge.**  
No audit work is performed at this stage.

---

## 2. Proposal & Agreement

After reviewing the codebase, we provide a formal audit proposal, which includes:

### Scope of Work

- Contracts, modules, or components included
- Any explicitly excluded items

### Timeline

- Audit start date
- Audit duration
- Dedicated remediation / fix-review period

### Pricing

- A **fixed audit fee**, based on the estimated audit duration, taking into account codebase size and technical complexity

If both parties agree on the terms:

- The audit agreement is signed
- The audit start date is confirmed

---

## 3. Audit Kickoff & Setup

Once the audit begins, we set up the collaboration environment.

### Communication Channel

A dedicated **Telegram or Slack channel** is established.

Used for:

- General coordination and questions
- Clarifications during the audit
- Drawing attention to urgent or time-sensitive matters

### Kickoff Call

A kickoff meeting can be held, if the circumstances require so.

Common topics include:

- High-level architecture overview
- Key risk areas or recent changes
- Audit expectations on both sides

---

## 4. Documentation & Context Sharing

To ensure an efficient and high-quality audit, we ask clients to share relevant context early, such as:

- Technical documentation or specifications
- Architecture diagrams
- Protocol or business-logic descriptions
- Threat models (if available)
- Previous audit reports, including resolved findings

Providing this information upfront helps our team focus on meaningful research rather than rediscovering known context.

---

## 5. Findings & Collaboration During the Audit

### Notion Workspace

- You will be invited to a **private Notion workspace** for the engagement.
- This is where findings are documented and tracked throughout the audit.

### Findings Workflow

- Findings are added as they are discovered and confirmed.
- Each finding typically includes:
  - Detailed description and potential impact
  - Severity classification
  - Affected components
  - Suggested remediation

### Client Collaboration

Your team is encouraged to:

- Leave feedback on discovered findings
- Ask questions or provide clarifications
- Discuss your product's architecture with our researchers

This allows for continuous feedback and alignment during the audit.

---

## 6. Remediations During the Audit

Clients may begin applying fixes at any time during the audit.

When fixes are ready:

- Share the relevant commit(s) or PRs
- Link them directly in the corresponding Notion finding

Our researchers may provide early feedback when possible, though during the audit window our primary focus remains on identifying issues.

---

## 7. Remediation Review Phase

After the audit period concludes:

- All identified issues will be listed in the findings table in Notion
- A dedicated remediation review period begins

During this phase, our researchers:

- Review submitted fixes
- Verify correctness and completeness
- Assist with follow-up questions or alternative approaches if needed

Each finding is ultimately marked as one of:

- **Resolved**
- **Acknowledged** (accepted risk)
- **Unresolved** or **Partially Resolved**

---

## 8. Final Report Delivery

Once all findings are resolved or acknowledged, we deliver the final audit report, which includes:

- Executive summary
- Scope and methodology
- Detailed findings and remediation status

Audit reports are generally intended to be made **public following completion**, subject to mutual agreement. Reports may be kept private at the client’s request.

---

## 9. Post-Delivery

After delivery:

- We remain available to clarify findings
- We can assist with upgrades, re-reviews, or follow-up audits

---
