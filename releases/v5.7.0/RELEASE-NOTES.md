# PeakNet Tenant Access 5.7.0

## Huntress security and billing

- Adds a secure, read-only Huntress Platform API integration.
- Shows open customer incident reports with severity, status, platform and PSA ticket reference.
- Reconciles EDR endpoints, ITDR identities, SIEM log sources, ISPM identities, and ESPM / Email Security when exposed by Huntress.
- Adds shared monthly cost and sales pricing in DKK, margin calculation, monthly snapshots and CSV billing export.
- Matches Huntress organizations to the local tenant catalog by Microsoft tenant ID or normalized name.
- Separates customers whose local names begin with `DS` into a dedicated DSData license statement.
- Encrypts Huntress API credentials with Windows DPAPI and keeps them local to each computer.
- Keeps synchronization read-only; it does not change incidents, agents, organizations or subscriptions.

Huntress currently documents native organization usage for EDR, ITDR, SIEM and ISPM. ESPM is displayed only when the API supplies an ESPM or Email Security usage object.