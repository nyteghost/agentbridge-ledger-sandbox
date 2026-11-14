# agentbridge-ledger-sandbox

**Sandbox only.** Private dispatch ledger used to test [AgentBridge](https://github.com/nyteghost/AgentBridge)
against real GitHub (live test plan L1–L4). Not used by any real project.

- Ledger data lives on branch `agentbridge-dispatch-ledger`, written only by AgentBridge's
  ledger token through compare-and-swap commits. Do not edit it by hand.
- That branch is protected by a ruleset: no deletion, no force pushes.
- Contains no application code, no workflows and no secrets.

See `docs/LEDGER.md` and `docs/qa/LIVE-TEST-PLAN.md` in the AgentBridge repository.
