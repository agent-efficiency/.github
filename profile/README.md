# agent-efficiency

A local verification and efficiency governor for coding agents, by [eparenti](https://github.com/eparenti). It supports Claude Code, Cursor, and Codex.

It watches agent lifecycle events, records privacy-safe operational facts, and gives sparse guidance when a session repeats work, widens scope without a clear reason, or tries to finish after an unverified code change. It makes no model calls and its runtime uses only the Python standard library.

| Repository | What it holds | License |
|---|---|---|
| [agent-efficiency](https://github.com/agent-efficiency/agent-efficiency) | The governor, its hooks, and its tests | MIT |

The goal, in one line: reduce the total cost of reaching a verified, accepted result without reducing scope, security, evidence, or quality.
