# Aaron Lab

This repository used to host the `aaronagent` profile README.

The account identity has moved to `aaronlab`. For the current AI open-source
launch, use these links:

- GitHub account: https://github.com/aaronlab
- Featured project: https://github.com/aaronlab/browsertrace
- Live BrowserTrace demo: https://aaronlab.github.io/browsertrace/
- BrowserTrace launch discussion: https://github.com/aaronlab/browsertrace/discussions/6

## Featured Project: BrowserTrace

BrowserTrace is a local flight recorder for AI browser agents.

It helps Browser Use, Stagehand, Skyvern, Playwright + LLM, and custom
computer-use builders debug failed browser-agent runs with local timelines,
screenshots, URLs, actions, model input/output, errors, and public-safe HTML
exports.

Useful starting points:

- Debugging walkthrough: https://aaronlab.github.io/browsertrace/debug-browser-agent-failure.html
- Public-safe demo export: https://github.com/aaronlab/browsertrace/releases/download/v0.1.11/browsertrace-demo-public.html
- Roadmap: https://github.com/aaronlab/browsertrace/blob/main/ROADMAP.md
- Good first issue: https://github.com/aaronlab/browsertrace/issues/19

No-install local check before PyPI publishing is enabled:

```bash
uvx --from "browsertrace[ui] @ git+https://github.com/aaronlab/browsertrace@v0.1.11" browsertrace doctor
```

If you build browser agents, the most useful feedback is which failure context
your current logs do not capture.
