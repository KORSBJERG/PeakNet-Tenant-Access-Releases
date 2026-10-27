# PeakNet Tenant Access 5.3.0

- Adds secure online updates through GitHub Releases.
- Verifies a detached CMS signature against the pinned PeakNet publisher certificate.
- Restricts update downloads to this official repository.
- Verifies package size, SHA-256, and every file in the release manifest.
- Stages and validates updates before installation.
- Automatically backs up and rolls back program files on failure.
- Refuses installation while tenant sessions are active.
- Keeps tenant data, time records, logs, tokens, and settings outside release packages.
