# Stewardship Handoff Plan for CLH Schema Hosting

This document outlines the plan for long-term stewardship of the CLH Metadata Schema (CLH-MS).

## Short-Term Steward

- Held under the domain `community-led-housing.org`
- Managed via GitHub repository `Community-Led-Housing/clh-ms-schema`
- Maintained with CI/CD for reliability and reproducibility

## Handoff Criteria

We intend to migrate stewardship once the following conditions are met:
1. A formal or federated body (e.g., cooperative housing alliance or international commons steward) is willing and able to take ownership.
2. Commitment to FOSS principles and open participation is secured.
3. Domain and DNS hosting is transitioned under that organization’s control.
4. Prior URIs are maintained via redirects or are permanently mapped to the same schema versions.

## Candidate Future Stewards

- Cooperative Housing International (CHI)
- European CLH federations or umbrella orgs
- Data Commons or Open Standards community initiatives

## Migration Plan

- URIs will remain valid through 301 redirects
- `$id` values in all schemas will continue to resolve
- Documentation and governance will be updated post-handoff
