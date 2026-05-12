# Aaron Lab

This repository used to host the `aaronagent` profile README.

The account identity has moved to `aaronlab`. For the current AI open-source
launch, use these links:

- GitHub account: https://github.com/aaronlab
- Featured project: https://github.com/aaronlab/browsertrace
- Live BrowserTrace demo: https://aaronlab.github.io/browsertrace/
- BrowserTrace launch discussion: https://github.com/aaronlab/browsertrace/discussions/6

## Featured Project: BrowserTrace

BrowserTrace is a local replay debugger for Browser Use failures.

It helps Browser Use builders replay failed browser-agent runs with local
timelines, screenshots, URLs, actions, model input/output, errors, and
public-safe HTML exports. Stagehand, Skyvern, Playwright + LLM, and custom
computer-use workflows are supported as secondary integrations.

Useful starting points:

- Debugging walkthrough: https://aaronlab.github.io/browsertrace/debug-browser-agent-failure.html
- Public-safe demo export: https://github.com/aaronlab/browsertrace/releases/download/v0.1.18/browsertrace-demo-public.html
- Roadmap: https://github.com/aaronlab/browsertrace/blob/main/ROADMAP.md
- Good first issue queue: https://github.com/aaronlab/browsertrace/labels/good%20first%20issue

No-install local check from PyPI:

```bash
uvx --from "browsertrace[ui]" browsertrace doctor
uvx --from "browsertrace[ui]" browsertrace demo
uvx --from "browsertrace[ui]" browsertrace
```

Persistent install:

```bash
pip install "browsertrace[ui]"
```

If you build browser agents, the most useful feedback is which failure context
your current logs do not capture.
