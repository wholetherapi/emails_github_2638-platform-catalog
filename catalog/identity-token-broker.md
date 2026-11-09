---
component_id: identity-token-broker
name: Identity Token Broker
owner: Identity and Access
status: ga
implementation_url: https://github.com/wholetherapi/emails_github_2638-artifact-registry/tree/main/artifacts/identity-token-broker
support_tier: 1
review_cycle: quarterly
description: Issues and rotates short-lived OIDC tokens for internal service-to-service calls.
---
# Identity Token Broker

Brokers client-credentials and workload-identity tokens for internal services.
Handles key rotation, token introspection and per-caller rate limiting, and is a
hard dependency for every control-plane service.

Maintainer: Identity and Access team. Escalation: iam-oncall.
