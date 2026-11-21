# Workflow Engine: Product overview

Workflow Engine is a local-first software project for coordinating multi-step business processes. It aims to turn fragmented follow-up work into explicit next actions with responsible owners, priorities, deadlines and recorded decisions.

## Initial workflows

1. **Contractor bid coordination.** Track fictional bids, deadlines, missing responses, referenced document sections, outstanding information and proposed follow-up actions.
2. **Dental recall coordination.** Use fictional appointment, payment, insurance and eligibility information to produce an explainable recall queue.

These are the first two applications of a reusable engine. They are not its final scope. Additional workflows and industries can be introduced without embedding industry-specific logic in the core.

## Intended capabilities

- Defined workflow steps, dependencies and conditional branches.
- Validation before execution and deterministic action eligibility.
- Configurable and explainable prioritization.
- Durable state, explicit approvals and audit history.
- Safe interruption and restart behavior.
- Verification or manual reconciliation before retrying uncertain external actions.
- A lightweight local web interface.

## Scope and status

The initial stack is Python 3.12, SQLite and Linux, with an offline-capable local interface. Development uses synthetic records and simulated actions. External production integrations are not part of this public project overview.

This document describes the intended product, **not a claim that these capabilities have been implemented or verified**. Current repository implementation status is described in [PROJECT_STATUS.md](PROJECT_STATUS.md).
