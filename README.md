# research-runner

Workflow runner for a private project. Runs only on `workflow_dispatch` from its owner.

It holds no data, no skills and no logs. Every step's output goes to a private log file that is uploaded to the owner's private API, so the public run page shows only step names and pass/fail.
