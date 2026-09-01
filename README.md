# EU Tender Intelligence & Bid Management

A Microsoft Power Platform solution for retrieving real EU TED procurement notices, applying deterministic qualification scoring, managing Tender opportunities, and supporting human Bid / No Bid decisions with a grounded Copilot Studio agent.

![Architecture](images/architecture/eu-tender-architecture.png)

## Solution

The solution uses:

- Power Automate to synchronize recent TED procurement notices.
- Dataverse as the operational system of record.
- Power Apps for Tender review, qualification, and Bid / No Bid management.
- Copilot Studio for grounded, read-only advisory support.
- Deterministic scoring for explainable Tender qualification.

The final Bid / No Bid decision remains human-controlled.

## Technologies

- Microsoft Power Apps
- Microsoft Power Automate
- Microsoft Dataverse
- Microsoft Copilot Studio
- Power Platform Solutions

## Documentation

- [Architecture](docs/architecture.md)
- [Data Model](docs/data-model.md)
- [Deterministic Scoring](docs/scoring.md)
- [Bid / No Bid Process](docs/bid-no-bid-process.md)
- [Architecture Decisions](docs/architecture-decisions.md)
- [Testing](docs/testing.md)
- [Security, ALM and Cost](docs/security-alm-cost.md)
- [Limitations and Future Enhancements](docs/limitations-and-future.md)
