# PeakNet Tenant Access 6.0.0

## Microsoft 365 licensing and billing through Crayon

- Adds **Microsoft 365 licensing & billing** below Huntress in the left menu.
- Connects read-only to the Crayon Cloud-iQ API.
- Reads Microsoft customer tenants, subscriptions, quantities, billing cycles, terms, automatic renewal and renewal dates.
- Reads current Crayon subscription unit prices and applicable reseller sales-price rules.
- Calculates monthly-equivalent cost, known revenue and known profit.
- Separates PeakNet and DSData customers into dedicated tabs.
- Adds an upcoming-renewals view and CSV export.
- Encrypts Crayon Client ID, Client Secret, API username and API password locally with Windows DPAPI.
- Stores only cached reports and exports in the shared Clients folder; credentials are never synchronized.

Revenue and profit are shown only when Crayon returns a usable reseller sales-price rule. Missing sales pricing is clearly marked rather than estimated.