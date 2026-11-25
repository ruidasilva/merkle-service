# Votari lifecycle decision — inactive upstream service

**Date:** 2026-11-25
**Authority:** Founder (Rui Da Silva), owner confirmation.
**Status:** INACTIVE_UPSTREAM — ACTIVATION NOT AUTHORISED.

This repository contains the upstream BSV Blockchain Merkle Service. Rui confirmed it is not activated or used by Votari. It is distinct from our MPS, `ruidasilva/bitcoin-merkle-proof-store-go`. This is an owner decision, not an independently verified live-host inventory.

## Standing hold

- Do not activate, deploy, start, provision, publish images, dispatch release workflows, or integrate this service into Arcade or other Votari services without a new explicit founder decision.
- Exclude it from routine active-service maintenance. Keep PRs #1, #2 and #3 unmerged; do not remediate upstream findings solely to clear CI. Security findings are neither fixed nor waived.
- Retain upstream history. Do not remove resources or change unrelated services.
- The current main workflow publishes images on pushes to main and version tags. Do not merge this documentation PR or push to main while publication would occur. Existing auto-merge settings are not confirmed disabled. This record is not technical enforcement.

## Reactivation

Require an explicit founder-approved change establishing need, source revision, relationship to Arcade and our MPS, security remediation, compatibility, release and deployment gates, target environment, rollback and independent verification. Follow the [canonical CI/CD standard](https://github.com/ruidasilva/votari-infrastructure-operations/blob/main/governance/CI_CD_AND_DEPENDENCY_MAINTENANCE.md) and internal container provenance standard. Keep this hold until superseded by a recorded founder decision.
