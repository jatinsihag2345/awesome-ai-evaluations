# Sandboxed Evaluation Architecture

```
[Agent] ---> [Orchestrator] ---> [Docker Host]
                                      │
                         ┌────────────┴────────────┐
                         ▼                         ▼
                  [Task Sandbox A]          [Task Sandbox B]
                  (Network Isolated)        (Resource Capped)
```
