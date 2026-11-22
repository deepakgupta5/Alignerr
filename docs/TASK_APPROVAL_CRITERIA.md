# Task approval criteria for Claude sessions

Owner-supplied benchmark, recorded 22 November 2026. Applies to every Claude session. Plain bullets record the criteria. They do not claim that any criterion has been met.

## Session requirements

- Eight hours of real work. Prompting, testing and model time all count.

## Before you start

- You have a plan for how to approach it. It can change along the way, but you know where you are starting.
- You have a measurable definition of done in one line. Examples include tests passing, a speed target or matching specified behavior. You do not need to reach it within eight hours.

## While you work

- You decide what happens next. If you ask the model for suggestions, choose among them and say why.
- Notice design choices the model makes that you did not ask for. Approve them deliberately or change them.
- Push back if the model misses a requirement, introduces a bug or expands the scope. Name the issue and redirect the work.
- Avoid open-ended instructions such as “optimize as much as you can” or “do whatever is best.”
- Include your reasoning in requests. Explain constraints, tradeoffs and what you are worried about.
- Keep prompts focused. Do not fold design, debugging and testing into a single request.

## After each response

- Read what came back before replying.
- Run, open or test the result yourself on your computer.
- If a choice looks odd, ask the assistant to explain it.
- Each turn follows from the last result, such as a bug you found, a test that failed or a limitation you encountered.

## When something is wrong

- Push back on code that is incomplete, buggy or heading the wrong way. Explain why.
- Narrow the scope or redirect the approach when the model is overbuilding or drifting.
- Revisit earlier decisions when new findings call for it.

## Shape of the session

- Your turns support the hours. Decisions, tests and follow-ups appear throughout the session. A few long prompts or repeated “keep going” messages cannot support an eight-hour claim.
- Most time goes to hard problems such as persistence, performance, concurrency, recovery or changes across many files, rather than renaming items or adjusting colors.
- The session includes planning, building, testing and reviewing.
- Someone reading your messages alone can see that you knew what you wanted, checked the work and disagreed when it mattered.

## Application to this project

This benchmark supersedes the earlier seven-hour session plan. Eight hours is the required real-work benchmark, not a pre-filled actual-hours entry. Record supported actual time and the evidence of prompting, model work, direct checks, decisions and follow-ups. Do not pad work, invent activity or report the estimate as actual hours.

Plan the entire work block before starting. Issue focused instructions one at a time. The full route can include design, implementation, testing, review, debugging and verification, but a single prompt must not bundle those activities into one undirected assignment. Review each result before choosing the next action.

At close, assess these criteria against observed work and identify missing evidence. A session may end with a saved partial engineering result. Completing eight hours does not establish product acceptance, and finishing an increment does not establish eight hours of work.

The project remains at least 14 weeks for the engine and initial contractor/dental workflows. Additional industries, workflows and undefined scenarios extend that horizon.
