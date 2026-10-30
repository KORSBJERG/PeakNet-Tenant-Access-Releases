# PeakNet Tenant Access 5.8.0

## Correct DSData reconciliation

- Classifies Huntress organizations whose names begin with `DS` as DSData, even when no matching local tenant exists.
- Retains local DS-prefix matching as an additional ownership rule.
- Correctly finds 15 DSData organizations in the current synchronized data instead of one.
- Replaces the ambiguous combined license number with separate EDR, ITDR, SIEM, ESPM and ISPM totals.

## More detail

- Shows billable and total EDR endpoints and endpoint health: unresponsive, outdated and isolated.
- Shows billable and total ITDR and ISPM identities.
- Shows SIEM billable sources, online storage and retention.
- Shows ESPM billable and total users when Huntress supplies the product data.
- Shows open incidents, pricing, margin, match method, ownership rule, Huntress organization ID and Microsoft tenant ID.
- Re-evaluates ownership from cached data immediately, so a full API synchronization is not required for the DSData correction.