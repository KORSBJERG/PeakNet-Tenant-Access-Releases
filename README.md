# PeakNet Tenant Access Releases

Official signed releases for **PeakNet Tenant Access**.

This repository contains only application packages, the signed update feed, release notes, and the public publisher certificate. It never contains customer tenants, credentials, tokens, audit logs, time tracking, settings, or the private signing key.

## Stable update channel

- Atomic signed feed: `stable/latest.p7m`
- Human-readable feed: `stable/latest.json`
- Optional detached signature for auditing: `stable/latest.json.p7s`
- Release packages: GitHub Releases
- Publisher certificate: `publisher/PeakNet-Update-Publisher.cer`

The application validates the CMS envelope against its pinned PeakNet publisher certificate, restricts downloads to this repository, checks package size and SHA-256, validates every packaged file, and installs with automatic rollback.
