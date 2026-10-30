# PeakNet Tenant Access 5.8.1

## Huntress contract pricing

- Adds the supplied contract costs: EDR EUR 2.26, ITDR EUR 1.28 and ISPM EUR 0.61 per unit/month.
- Converts prices with the ECB reference rate for 2026-10-29: EUR 1 = DKK 7.4736.
- Stores rounded DKK costs: EDR 16.89, ITDR 9.57 and ISPM 4.56.
- Sets sales prices to exactly twice the rounded DKK cost: EDR 33.78, ITDR 19.14 and ISPM 9.12.
- Leaves SIEM and ESPM at zero until their contract prices are provided.
- Adds visible Cost EUR, EUR/DKK rate, Cost DKK and Sales DKK fields plus a one-click recalculation button.
- Saves prices in the shared Huntress settings so both computers use the same billing basis.