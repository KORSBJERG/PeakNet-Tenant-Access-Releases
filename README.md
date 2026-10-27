# PeakNet Tenant Access Releases

Official signed releases for **PeakNet Tenant Access**.

This repository contains only application packages, the signed update feed, release notes, and the public publisher certificate. It never contains customer tenants, credentials, tokens, audit logs, time tracking, settings, or the private signing key.

## Stable update channel

- Feed: `stable/latest.json`
- Detached CMS signature: `stable/latest.json.p7s`
- Release packages: GitHub Releases
- Publisher certificate: `publisher/PeakNet-Update-Publisher.cer`

The application pins the PeakNet publisher certificate, verifies the detached feed signature, restricts downloads to this repository, checks package size and SHA-256, validates every packaged file, and installs with automatic rollback.
