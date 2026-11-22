# Session 1 eight-hour work plan and first phased instruction R3

Project links: [project plan](https://github.com/deepakgupta5/Alignerr/blob/docs/claude-session-1-update/docs/PROJECT_PLAN.md) and [development roadmap](https://github.com/deepakgupta5/Alignerr/blob/docs/claude-session-1-update/docs/DEVELOPMENT_ROADMAP.md). Read the versions on branch `docs/claude-session-1-update`. Confirm actual repository access before claiming to have read them.

## Repository access and reading order

All current session inputs are in https://github.com/deepakgupta5/Alignerr on branch `docs/claude-session-1-update`. Start at docs/START_HERE.md. The repository does not automatically synchronize this saved workspace.

First record the local branch, HEAD, remotes and working tree. If network access is available, fetch the named documentation branch and inspect its files without switching, resetting or overwriting the working tree. Use `git show FETCH_HEAD:docs/START_HERE.md` and the four linked documents. Record the fetched commit. Preserve all existing uncommitted code, tests and architecture records. Do not merge these documents over existing local work during this inspection. If the branch cannot be fetched, report the precise access failure and stop dependent document review. Do not replace current guidance with an older local copy without identifying the mismatch.

I want you to bring this saved workspace up to date before writing more application code. Read docs/PROJECT_PLAN.md, docs/PRODUCT_OVERVIEW.md, docs/DEVELOPMENT_ROADMAP.md and docs/ENGINEERING_PRINCIPLES.md from the updated repository branch. Start with the project plan, then read the roadmap, overview and principles. First verify whether this saved workspace can access that branch. If access fails, report the actual command, error and available local revision. Do not claim to have read unavailable documents. These documents update the project direction. They do not certify the existing implementation or approve an exact schema or fixture baseline.

This is still Session 1, Task ID 0a50dc2d-3947-4ef9-ac00-b27c326547d0. Instruction WE-INS-CL-S001-R3. The work item is WE-WP-CL-S001, supporting the foundation checkpoint. Keep this ID through continuation or compaction. Later administrative sessions get their own IDs. The project has a minimum 14-week horizon for the engine and the first two workflows. That excludes additional industries, workflows and scenarios we have not yet defined. Those extend the roadmap. The seven technical stages are a roadmap, not seven fixed-duration sessions or the end of this project. Do not compress the project into seven sessions.

In your last response, you reported an uncommitted foundation and 27 passing tests. I want you to preserve that work. I have not yet verified the implementation or those results. Your proposed session sequence has not been adopted. Use the repository roadmap and reconcile your existing work against it.

I have selected a eight-hour work block from the session plan. It spans multiple bounded turns and may need continuation. It is not one eight-hour response. I want you to work through the phases below in order. Do not attempt all the phases in one turn. I will review the evidence at each checkpoint before issuing the next bounded instruction. Keep the same Session 1 ID during continuation. Actual supported hours remain separate from this estimate.

## Full route through this work block

| Phase | Planning allowance | Work and expected result |
| --- | ---: | --- |
| 1. Catch up and inspect | 30 minutes | Read the current documents and inspect saved state. Return the inventory first. Run baseline checks only under a separate focused follow-up after that inventory is reviewed. |
| 2. Reconcile requirements and design | 40 minutes | Review the actual starting evidence, alternatives, interfaces, exact contract/fixture scope and readiness. Return a design proposal for disposition. |
| 3. Implement the bounded change | 180 minutes | After scoped issuance, build the selected validator. Preserve usable work. Identify the candidate and unrequested choices. Respond to bounded implementation prompts rather than completing all future phases. |
| 4. Test | 60 minutes | Exercise approved normal, invalid, boundary and invariant cases under focused testing instructions. Record commands and results. |
| 5. Technical review | 50 minutes | Assess the candidate and evidence through the assigned review route. Record coverage, correctness, interfaces, maintainability and findings. |
| 6. Debug and correct | 65 minutes | Reproduce actual findings, establish root cause and apply bounded corrections. Test corrections in focused follow-ups and obtain review closure. |
| 7. QC verification | 35 minutes | Freeze the reviewed candidate. Use the qualified assessor and evidence route. Record checks, independence and limits. A self-check is not independent QC. |
| 8. Close and preserve | 20 minutes | Reconcile approval criteria, product evidence, defects and supported actual hours. Preserve saved state and next action. |
| Total planned work block | 480 minutes | Eight hours planned. No actual hours or successful outcomes are pre-recorded. |

The allowances organize the work. They are not time to manufacture or a reason to rush a failed check. Existing completed work may change the remaining allocation. If the work cannot finish in the available block, preserve a PARTIAL or BLOCKED handoff. Do not expand scope to fill time or skip verification to meet the estimate.

## Foundation scope and completion criteria

I have retained CORE-001, CORE-002, CORE-003, CORE-004 and the foundation part of CORE-016. They cover versioned definitions, validation, deterministic eligibility, explicit branch/dependency outcomes and reproducible synthetic tests. This work supports the first roadmap stage. The selected implementation increment begins with definition validation. Completing it does not complete eligibility, branching, the full first stage, or the project.

The validator must reject malformed identities, invalid schema versions, unknown references, invalid branch targets, cycles and unsupported conditions before evaluation. A valid result must preserve the definition identity and version. Error results must be complete under the approved precedence rules, deterministic, deduplicated and canonically ordered. Inputs must remain unchanged. Invalid records must not produce a runnable definition or reach downstream evaluation.

The candidate 25-case selection is a minimum after it is supplied and qualified. Do not cherry-pick cases or invent missing expectations. Relevant supplemental checks must cover accepted optional fields, type/version boundaries, nested input/output aliasing, repeated and reordered inputs, distinct versus duplicate errors, and cyclic nodes versus acyclic downstream nodes. Join validation must follow the approved boundary. Do not implement a scheduler to test the invalid-input barrier.

Before dependent coding, the reviewer and owner must dispose the exact schema/error contract, fixture expectations, architecture and applicable readiness checks. Policy approval alone does not qualify the complete fixture baseline. Do not change a contract or expected result to obtain a pass. Preserve unrelated later decisions at their own gates.

Keep eligibility execution, persistence redesign, workers, protected actions, live integrations, business ranking, web UI, migrations and cancellation out of this validator increment. Existing persistence and audit code must be preserved and assessed. Reuse it only where the scoped design justifies the dependency. Do not delete it merely because the roadmap sequence changed.

## Checkpoints and corrections

At every phase, map the assigned work to evidence. I will record PASS, FIX or BLOCKED. An unsupported factual claim remains UNVERIFIED. For FIX, provide a reproducible failure and bounded correction. For BLOCKED, identify the exact dependency, accountable next action and impact on remaining work.

Do not move to the next phase because its estimated time has arrived. Wait for the next bounded instruction after the checkpoint review. A correction can require several turns. When the candidate changes after review or QC, identify the new saved state and rerun the affected verification. Do not reuse a verdict from an older candidate as evidence for changed code.

For any test result, record the exact command, environment, candidate identity including uncommitted work, fixture version/hash, relevant clock/seed, expected/actual behavior, exit status, failures and skips. If an independent assessor or permitted evidence route is unavailable, retain the appropriate hold. Do not relabel a model assertion as verification.

## Phase 1 assignment, do this now

Complete Phase 1 only in your next response. I will select the Phase 2 instruction from what you actually find. Do not restart completed work. Do not begin new application implementation in this response.

I want you to do the following now:

1. Inspect /home/model/Alignerr and confirm the actual path, Git HEAD, branch, status, untracked files, local instructions and available tools. Identify what exists only as uncommitted work. Preserve the repository history and original README text. Read the repository documents as inputs. Do not overwrite your local architecture notes or source files with them.
2. Inventory the source, tests, CLI and architecture records you created. Explain their interfaces and which requirements they address. Identify assumptions you made before receiving my answers. Do not redesign the implementation in this turn.
3. Identify the existing test commands, test files and CLI checks that can reproduce your reported baseline. Do not run them in this initial response. I will issue a separate focused baseline-testing instruction after reviewing the inventory.
4. Identify the crash and audit tests supporting your previous claims. State which claims require further evidence. Distinguish process termination from power-loss durability, and database controls from hash-chain and independent tail-checkpoint verification. Do not report an unobserved pass.
5. Reconcile your work with the full foundation scope: versioned definitions, validation before evaluation, deterministic eligibility, explicit dependency and branch outcomes, and reproducible synthetic tests. Delivery begins with validation. Existing persistence and audit code can remain available for later review. It does not establish completion of a foundation or durability milestone.
6. Identify existing definition and validation components and any apparent conflicts with the retained foundation scope. A 25-case validator selection is being qualified separately. Do not invent its contents or claim you have received it. Defer the design proposal and implementation to their focused instructions.

I have approved explicit ALL/ANY for joins with multiple prerequisites and a failure guard for both. A failed prerequisite must not count as completed or skipped. Bypassing it requires a separately approved recovery rule. Do not invent that exception or infer the rest of the schema from this policy.

Preserve the three-way recovery distinction in the design. Verified receiver acceptance means no resend. Authoritative non-execution permits retry under the receiver contract. An uncertain outcome blocks automatic resend and requires manual reconciliation. A receiver query returning no row is insufficient unless its contract guarantees that this proves non-execution for the relevant attempt. Action IDs alone do not establish exactly-once delivery.

For this inspection, use the existing dependencies and test framework. Offline operation does not imply a permanent standard-library-only rule. JSON remains a proposal for external workflow authoring. A fixture representation does not settle that user-facing choice. Identify any numeric/hash restrictions you introduced and their consequences. Do not promote whole-cent amounts or a blanket float prohibition into product policy without a decision.

Do not add features, change application code or test assertions, install dependencies, commit, push or export workspace artifacts in this turn. Read-only checks may use disposable synthetic databases. Identify any generated files. Stop if a check could alter the saved work. Keep restricted evidence within the permitted route.

Use these eight response sections:

1. Work item and status. Instruction/work IDs, actual context identifier if available, activity, starting/ending revision or saved state, and COMPLETE FOR REVIEW, PARTIAL or BLOCKED.
2. Work completed. Each assigned inspection, actual result and omissions. Separate observations, assumptions and proposals.
3. Changes or artifacts. Inspected paths/components and any generated files. State whether source or tests changed. Identify uncommitted work and out-of-scope changes.
4. Verification and evidence. Per check: requirement, command/procedure, environment, revision plus uncommitted-file identity, expected/actual result, exit code and permitted output reference. List failures, skips and unrun checks with reasons. A commit alone does not identify uncommitted code.
5. Acceptance coverage. Map each requested check to DEMONSTRATED, FAILED or UNVERIFIED. Do not grant acceptance.
6. Defects and uncertainties. Issue ID, expected/actual behavior, reproduction, impact, owner and blocking state. Distinguish code, specification, harness and environment issues.
7. Decisions needed. Exact question, options, recommendation, consequences and affected work. Write None where appropriate.
8. Handoff. Exact ending state, uncommitted-file identity, open findings, next owner and next safe action. Do not start unassigned implementation.
