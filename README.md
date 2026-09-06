# Ticket Creation & Decomposition Process

> **Parent Initiative:** [Epic ID]
> **Source Request:** [Original Request ID]
> **Goal:** Transform a large, multi-topic request into clear, actionable sub-tickets across logical work packages.
> **Outcome:** Better planning, clearer ownership, and faster implementation.

---

## Overview

This document explains the process used to break down a complex support or platform redesign request into smaller, manageable delivery items.

### Why this process works
- **Clarity:** Large requests are easier to understand when separated into focused stories.
- **Predictability:** Smaller tickets are easier to estimate, test, and review.
- **Ownership:** Roles and responsibilities become much clearer.
- **Traceability:** Every delivery item can be mapped back to a specific need or gap.

---

## Step-by-Step Process

### 1. Review the original request
Start by reading the source ticket, brief, or intake request in full.

Focus on:
- business goal
- user pain points
- systems involved
- forms, workflows, or automations affected
- dependencies and risks

### 2. Identify major themes
Group the request into a small number of logical work packages.

Typical examples:
- portal or navigation changes
- ticket type cleanup
- form redesign
- automation and routing
- data migration
- onboarding and documentation

### 3. Split each theme into user stories
Break each work package into small delivery items.

A good sub-ticket should:
- solve one clear problem
- have one main outcome
- be reviewable on its own
- be small enough to estimate confidently

### 4. Define ticket metadata
For each sub-ticket, capture:
- title
- short description
- current state
- target state
- owner
- reviewer
- expected deliverable
- acceptance criteria

### 5. Clarify roles early
Separate implementation responsibilities from review responsibilities.

Example:
- **Implementer:** configuration, workflow setup, form logic, automation, migration
- **Reviewer:** process validation, UX review, business approval, documentation review

### 6. Validate before bulk creation
Before creating all child tickets, verify:
- active forms and workflows
- naming conventions
- ownership model
- affected systems
- dependencies between work packages

---

## Suggested Work Package Structure

Example structure for a medium-sized request:

1. **Portal Restructuring**
2. **Ticket Type Consolidation**
3. **Support Area Setup**
4. **Form Field and Logic Updates**
5. **Automation and Routing**
6. **Data Migration**
7. **User Onboarding and Dashboarding**

Each package can then be split into 2-4 sub-tickets depending on scope.

---

## Example Story Mapping Template

| Work Package / Story | Current State | Target State | Owner / Reviewer | Deliverable |
|---|---|---|---|---|
| 1.1 Navigation Overview | Entry points are inconsistent | Users see a clear route to the right request type | [Implementer] / [Reviewer] | Updated navigation structure |
| 1.2 Support Structure | Categories overlap | Topics are grouped logically | [Implementer] / [Reviewer] | Category mapping |
| 2.1 Ticket Type Cleanup | Duplicate request types exist | Redundant request types are merged or retired | [Implementer] / [Reviewer] | Rationalization list |
| 3.1 Access Request Form | Information is incomplete | Form captures all required data up front | [Implementer] / [Reviewer] | Field definition |
| 4.1 Mandatory Field Review | Too many required fields | Only essential fields remain mandatory | [Implementer] / [Reviewer] | Field audit |
| 5.1 Intake Automation | Requests are routed manually | Rules assign tickets automatically | [Implementer] / [Reviewer] | Routing rules |
| 6.1 Data Migration | Data lives in spreadsheets | Data is stored in a maintained system | [Implementer] / [Reviewer] | Migration log |
| 7.1 User Guidance | Users submit low-quality requests | Help content improves request quality | [Reviewer] / [Implementer] | Guides and FAQs |

---

## Role Model

| Role | Responsibility |
|---|---|
| Product or Process Reviewer | Validates business fit, process design, user experience, and final acceptance |
| Technical Implementer | Configures systems, updates forms, builds automations, migrates data, and tests delivery |

---

## Recommended Repository Structure

\`\`\`text
project-delivery-docs/
├── README.md
├── docs/
│   ├── work-packages.md
│   ├── current-vs-target.md
│   ├── acceptance-criteria.md
│   └── verification-checklist.md
└── exports/
    └── child-tickets.csv
\`\`\`

---

## Definition of Done

- [x] Parent initiative identified
- [x] Scope grouped into logical work packages
- [x] Each work package broken into smaller tickets
- [x] Ownership and review roles defined
- [x] Current state and target state documented
- [ ] Existing workflows and forms verified
- [ ] Child tickets created in the tracking system
- [ ] Acceptance criteria reviewed with stakeholders

---

## Best Practices

- Keep ticket titles short and outcome-focused.
- Avoid mixing technical work and approval work in one ticket.
- Write target states in plain language.
- Capture assumptions early.
- Retire obsolete request types carefully to avoid breaking history.
- Add documentation tasks if users need guidance after rollout.

---

## Common Pitfalls

- Creating tickets that are still too large
- Leaving ownership unclear
- Skipping validation of existing workflows
- Renaming request types without documenting impact
- Missing dependencies between automation, forms, and data

---

## Reuse Guidance

You can reuse this process for:
- support portal redesigns
- service desk restructuring
- workflow standardization
- form optimization projects
- request type consolidation
- onboarding and support experience improvements# ticketreconstruction
Ticket reconstruction into user friendly form
