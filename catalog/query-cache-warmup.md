---
component_id: query-cache-warmup
name: Query Cache Warmup
owner: Data Infrastructure
status: beta
support_tier: 3
review_cycle: semi-annual
description: Pre-warms analytical query caches after nightly warehouse loads complete.
---
# Query Cache Warmup

Replays the highest-cost analytical queries against the reporting cache as soon as
the nightly warehouse load finishes, so that the morning BI dashboards are warm.
Does not serve user traffic directly.

Maintainer: Data Infrastructure team. Escalation: data-infra-oncall.
