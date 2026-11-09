---
component_id: csv-batch-importer
name: CSV Batch Importer
owner: Data Operations
status: beta
support_tier: 3
review_cycle: semi-annual
description: Validates and ingests partner CSV feeds into the staging warehouse.
---
# CSV Batch Importer

Accepts scheduled partner CSV drops, applies schema validation and quarantines
malformed rows, then loads the accepted data into the staging warehouse.

Maintainer: Data Operations team. Escalation: data-ops-oncall.
