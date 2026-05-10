# Metalpol AI Automation

## Overview

This repository contains a proposed AI-assisted automation solution
for the complaint handling process in Metalpol Sp. z o.o.

The goal of the solution is to:
- reduce complaint response time,
- automate repetitive operational tasks,
- standardize complaint categorization,
- improve SAP and JIRA integration,
- provide reporting and analytics capabilities.

The project focuses on business understanding,
Event Storming, system architecture and AI automation design.

---

# Current Process Problems

The current complaint handling process contains several operational issues:

- manual complaint registration in Excel,
- delayed email processing,
- inconsistent categorization,
- lack of SAP and JIRA integration,
- limited reporting and KPI visibility,
- operational bottlenecks during seasonal peaks.

---

# Proposed Solution

The proposed solution introduces:

- Microsoft Graph webhook integration,
- AI-based complaint extraction and categorization,
- automated SAP validation,
- automatic JIRA ticket creation,
- AI-assisted customer response generation,
- confidence-based human review flow,
- analytics and KPI reporting.

The architecture follows an event-driven and human-in-the-loop approach.

---

# Proposed Technology Stack

| Area | Technology |
|---|---|
| Backend / Integration Layer | ASP.NET Core Web API |
| AI Processing | Azure OpenAI |
| Email Integration | Microsoft Graph API |
| ERP Integration | SAP REST API |
| Ticketing | JIRA REST API |
| File Storage | Azure Blob Storage |
| Database | PostgreSQL |
| Authentication | OAuth2 |

---

# Repository Structure

```text
docs/       -> business and technical documentation
diagrams/   -> Event Storming and architecture diagrams
examples/   -> example API payloads and integration responses
```

---

# Documentation

## Business Analysis
- [01-business-understanding](docs/01-business-understanding.md)

## Event Storming
- [02-event-storming-as-is](docs/02-event-storming-as-is.md)
- [03-event-storming-to-be](docs/03-event-storming-to-be.md)

## Technical Design
- [04-solution-architecture](docs/04-solution-architecture.md)
- [05-ai-automation-flow](docs/05-ai-automation-flow.md)
- [06-tradeoffs](docs/06-tradeoffs.md)

---

# Key Design Decisions

- Event-driven architecture for scalability and resilience
- Human-in-the-loop validation for low-confidence AI decisions
- AI used for unstructured data processing only
- Deterministic integrations for SAP and JIRA operations
- Separation between orchestration logic and AI processing

---

# Main Benefits

- Faster complaint processing
- Reduced manual workload
- Standardized categorization
- Better operational visibility
- Improved reporting and analytics
- Better scalability during seasonal peaks

---

# Author

Kacper Rusinek  