# Architecture

The solution follows a deliberately minimal Power Platform architecture.

EU TED Search API → Power Automate → Dataverse → Power Apps / Copilot Studio

Power Automate retrieves TED notices, performs create/update logic, and calculates deterministic qualification scores.

Dataverse stores Tender, Company Capability, and Qualification Assessment records and acts as the single operational source of truth.

Power Apps provides the business interface for Tender review and human Bid / No Bid decisions.

Copilot Studio uses Dataverse-grounded knowledge and read-only structured retrieval to provide advisory recommendations.

The AI agent cannot record the official Bid / No Bid decision.

![Architecture](../images/architecture/eu-tender-architecture.png)
