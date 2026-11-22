# Workflow Engine project plan

Owner direction updated 22 November 2026.

## Product and planning horizon

I want a reusable local-first workflow engine. It must coordinate responsibilities, deadlines, dependencies, priorities, approved actions and execution history. Contractor bid coordination and dental recall coordination are the first two workflows. Industry-specific rules must remain outside the engine core.

This is a project of at least 14 weeks. That is a minimum planning horizon, not a fixed delivery promise or an upper limit. It covers development and verification of the engine and these first two workflows. Future industries, additional workflows and scenarios that have not yet been defined extend the roadmap. Do not claim that unidentified scenarios have been specified or tested.

The seven technical stages in [DEVELOPMENT_ROADMAP.md](DEVELOPMENT_ROADMAP.md) do not mean seven administrative sessions. Each stage can require several design, implementation, testing, debugging, review and verification sessions. The work continues until the applicable requirements and acceptance criteria are demonstrated.

## Governing inputs

Read [PRODUCT_OVERVIEW.md](PRODUCT_OVERVIEW.md) for the product purpose, [ENGINEERING_PRINCIPLES.md](ENGINEERING_PRINCIPLES.md) for the engineering constraints and [DEVELOPMENT_ROADMAP.md](DEVELOPMENT_ROADMAP.md) for the stage sequence. Read the current owner instruction for the selected session objective. These documents describe direction. Exact schema, fixture expectations and architecture need their own disposition before dependent implementation.

Use Python 3.12, SQLite, Linux, a lightweight local web interface, synthetic records and simulated effects. Offline operation does not automatically prohibit packaged dependencies. Propose a dependency when needed and explain offline availability. Do not silently settle external authoring formats or business policy.

## Delivery sequence

1. Establish and verify the foundation. Retain versioned definitions, validation before evaluation, deterministic eligibility, explicit dependency/branch outcomes and reproducible tests. Deliver incrementally, beginning with validation. Preserve and reconcile existing work.
2. Demonstrate contractor bid coordination using the shared engine. Define its specific inputs, prioritization rules, missing-data handling and acceptance oracles before claiming business correctness.
3. Establish durable state and recovery. Distinguish process termination, storage failures and the stated power-loss guarantees.
4. Demonstrate current human authorization and simulated effects. Exercise crashes before and after receiver acceptance. An uncertain outcome blocks automatic resend.
5. Provide local operator visibility through dashboard, interfaces and audit history.
6. Exercise relevant failure, restart, race and recovery paths. Review actual evidence and correct failures.
7. Demonstrate dental recalls and workflow isolation using the same core. Verify eligibility, exclusions, explainable ranking and separation of records and business rules.

These are dependency-led technical stages. They are not dated weekly commitments. Review discoveries may change internal sequencing while preserving owner-approved scope.

## Working cadence and evidence

[TASK_APPROVAL_CRITERIA.md](TASK_APPROVAL_CRITERIA.md) is the benchmark for every Claude session. It requires eight hours of supported real work, a starting plan, a measurable one-line definition of done, owner-led decisions, focused prompts, direct checking after responses and visible review/correction throughout. Completion of the engineering objective within eight hours is not required.

Select bounded work from the current roadmap and actual saved state. A planned eight-hour work block spans multiple bounded prompts, implementation results, reviews and corrections. One response must not claim the whole block is complete.

Each substantial milestone needs requirement coverage, an actual candidate identity, relevant normal/invalid/boundary/failure results, technical review, appropriately qualified QC verification, defect disposition and owner acceptance. Keep planned time separate from supported actual hours.

At each handoff record PASS, FIX or BLOCKED with evidence. Unsupported claims remain UNVERIFIED. Preserve the exact saved state, uncommitted work, unresolved findings and next safe action. Follow the governing platform rules for saving, accounting and permitted evidence. Do not mark the whole project Complete because a session or stage has ended.

## Expansion after the first two workflows

The engine should expose clear boundaries so new workflow definitions and business rules can be added. Demonstrate extension through working contracts and the two initial workflows. Do not build speculative industry features into the core.

For each later industry, first define the business outcome, workflow, data, actors, authority, failure risks and acceptance scenarios. Estimate and select that work separately. New scenarios can also reveal shared engine defects. Assess their applicability and regression impact before changing the core.
