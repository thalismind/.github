## What changed

Describe the change and the request or issue it traces back to.

## Why

Explain the problem this solves and any important design or ownership boundary.

## How it was verified

List the exact checks that prove the change works. Use the commands and aggregate gates
documented by this repository.

- [ ] Focused tests cover the changed behavior and rejection or failure paths.
- [ ] The repository's aggregate check passes with its final exit code controlling.
- [ ] Documentation was updated where users or maintainers will look for it.
- [ ] Generated artifacts, dependencies, credentials, and unrelated files were not committed.
- [ ] The diff was reviewed for accidental compatibility shims, hidden fallbacks, and avoidable performance costs.

When applicable to the changed surface:

- [ ] Authorization behavior is consistent across every affected REST, WebSocket, and MCP surface.
- [ ] Performance-sensitive work includes before/after measurements at representative scale.
- [ ] ECS systems select candidates through one indexed driving component rather than an A-or-B or full-world scan.
- [ ] Browser rendering and event handling cover hostile identifiers, labels, URLs, and event data.

Paste relevant test output, screenshots, traces, or performance results:

```text
# verification evidence
```

## Notes for reviewers

Call out risks, deferred work, migration or rollback concerns, and anything that deserves
closer review. If a bot or agent authored part of the change, noting it helps with tracing
and reproduction; it is a courtesy, not a disclaimer.
