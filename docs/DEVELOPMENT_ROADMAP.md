# Workflow Engine: Initial development roadmap

The initial development direction has seven technical stages:

1. **Workflow definitions and execution.** Represent steps, dependencies and branches; validate definitions and demonstrate basic execution.
2. **Bid intake and prioritisation.** Model fictional contractor bids, outstanding information, deadlines and explainable follow-up priorities.
3. **Durable state and recovery.** Persist workflow state and support safe resumption after interruption.
4. **Human approval and simulated sending.** Require authorization before relevant actions and exercise simulated side effects.
5. **Dashboard, API and audit trail.** Provide local operator visibility, controls and execution history.
6. **Failure testing.** Exercise interruption, retry, duplicate-prevention and uncertain-outcome scenarios.
7. **Second workflow and isolation.** Demonstrate the fictional dental recall workflow using the same reusable engine, with isolated records and state.

These stages describe technical direction. They are **not fixed-duration sessions**, and the project does not end after the seventh stage. Additional workflows and industries are intended after the first two are demonstrated.

Development and acceptance depend on working software and verified evidence. This roadmap does not certify that any stage is complete.

## Current foundation delivery direction

Retain the full foundation scope: versioned definitions, validation, deterministic eligibility, explicit branch/dependency outcomes and reproducible synthetic tests. Deliver it incrementally, beginning with validation. Inspect and reconcile existing saved work before selecting the next implementation change. Exact contracts, fixture expectations and architecture need review before dependent implementation is issued. An existing implementation is not accepted solely because it was reported complete.

## Project horizon and later industries

The project has a minimum 14-week planning horizon for the engine and first two workflows. Future industries and undefined scenarios extend that horizon. The seven stages are not seven sessions or an upper limit on the project. See [PROJECT_PLAN.md](PROJECT_PLAN.md) for scope, evidence and expansion controls.
