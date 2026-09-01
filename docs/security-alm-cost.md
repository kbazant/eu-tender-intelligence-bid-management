# Security, ALM and Cost

## Security

- Microsoft authentication is used for the Copilot Studio agent.
- Structured Dataverse retrieval is read-only.
- Copilot cannot update the Human Bid / No Bid decision.
- Multi-user role and column-security testing is deferred to a future multi-user environment.

## ALM

The solution is developed as an unmanaged Power Platform solution.

Both unmanaged and managed solution packages were exported.

The unmanaged package represents the development/source artifact.

The managed package represents the deployment artifact for a future target environment.

## Cost

The solution minimizes additional operating cost by using:

- Dataverse as the existing operational datastore
- one scheduled synchronization flow
- Copilot Studio pay-as-you-go
- no additional Azure compute
- no Fabric
- no Power BI
- no secondary database
