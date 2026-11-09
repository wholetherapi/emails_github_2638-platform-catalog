---
component_id: payments-gateway-adapter
name: Payments Gateway Adapter
owner: Payments Platform
status: beta
support_tier: 2
review_cycle: quarterly
description: Normalises payment-provider APIs behind a single internal charge and refund contract.
---
# Payments Gateway Adapter

Wraps the card, wallet and bank-transfer provider SDKs and exposes one idempotent
interface to internal services. Replaces three legacy integration shims and emits
structured settlement events to the ledger pipeline.

Maintainer: Payments Platform team. Escalation: payments-oncall.
