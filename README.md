# Workflow Engine

Local-first workflow engine in Python and SQLite, built from scratch. MIT licensed.

## What it is

In most companies' processes today, revenue is missed when nobody owns the next step. A dentist's receptionist has 10 to 30 patients to call a day. Now she should be able to rank them by history, payment record and insurance, most revenue first. But she calls them randomly with no focus on revenue. A contractor with bids out needs to know which team mate has so far has not replied and which pages of a 20-page attachment matter which will prevent him from submitting the RFP on time. The data sits in email, spreadsheets, Google Drive and people's heads. My engine will own the deadline and the order. People will make the decision. I am going to build a workflow engine in Python and SQLite that will turn follow-ups into a ranked action list, then runs the approved ones. Each morning for every task owner it will show what is due, who has not replied and the next action, drafted for a person to approve. Processes pause for approval and resume after a crash without losing progress. It will run offline on Linux, with a local web interface showing what is running, what failed and what needs a decision. The hard part is a crash mid-step. If a send succeeds but the engine stops before recording it, a retry duplicates it and a skip loses it. I will interrupt workflows at each step, restart them, and show that nothing ran twice and no approval was skipped. Today Autonomy Bridge is my solo business and I am the sole owner; no client commissioned, funded or owns this idea of mine and no engagement restricts it; all the data is fictional; running the module on a client's system will be delivery, not transfer of ownership because I own the product and the code.

## Stack

Python, SQLite, and a lightweight local web interface on Linux. Local fixtures in place of email, spreadsheets, and Drive integrations. No internet, cloud services, Docker, or GPU.

## Licence

MIT — see LICENSE.
