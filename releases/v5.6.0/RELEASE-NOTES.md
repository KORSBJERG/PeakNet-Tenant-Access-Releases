# PeakNet Tenant Access 5.6.0

This release improves the external email forwarding workflow and makes existing forwarding visible before changes are made.

- Lists mailbox-level external and internal forwarding.
- Lists Inbox Rules that forward, redirect, or forward messages as attachments.
- Shows rule name, destination, enabled state, and whether the original message is kept.
- Keeps the existing forwarding inventory read-only.
- Refuses to replace or clear an existing internal forwarding address when applying external forwarding.
- Disabling external forwarding preserves internal forwarding and every Inbox Rule.
- Verifies mailbox forwarding again after every change.
