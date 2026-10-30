# PeakNet Tenant Access 5.9.0

## PeakNet and DSData revenue views

- Adds a dedicated **PeakNet** tab for every Huntress organization that is not assigned to DSData.
- Keeps the dedicated **DSData** tab for Huntress organizations or matched local customers whose name begins with `DS`.
- Shows customer count, monthly revenue, monthly cost and monthly margin separately for PeakNet and DSData.
- Shows separate EDR, ITDR, SIEM, ESPM and ISPM quantities under each tab.
- Adds detailed customer-level usage, incident, financial and matching information beneath each set of totals.
- Uses the shared DKK sales and cost prices, so both computers calculate from the same price basis.

This release also corrects the publisher so its Windows cryptography dependency is loaded before signing the online update feed.

