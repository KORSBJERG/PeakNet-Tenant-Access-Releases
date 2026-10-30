# PeakNet Tenant Access 5.7.1

- Fixes Huntress synchronization when the final API response contains a pagination object without the optional `next_page_url` property.
- Treats the missing property correctly as the end of the result set.
- Adds regression tests for both final-page and next-page API responses.
- Preserves the encrypted Huntress credentials and all shared pricing data from 5.7.0.