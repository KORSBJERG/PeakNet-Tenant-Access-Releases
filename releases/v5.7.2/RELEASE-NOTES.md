# PeakNet Tenant Access 5.7.2

- Replaces the non-ASCII ESPM unavailable marker with the Windows PowerShell-safe text `N/A`.
- Fixes the `â€”` text visible in the ESPM column.
- Applies the safe marker consistently to the dashboard, DSData totals, billing snapshots and CSV exports.
- Adds an automated regression check and confirms that Huntress-Integration.ps1 contains no non-ASCII characters.