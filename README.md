# skill-explainers

Interactive HTML explainers of Claude Code skills worth learning from. Open `index.html` in a browser.

Each explainer has three parts:

- **A · Organisation**: the file tree and who reads each file (agent, tool or browser), the anatomy of `SKILL.md`, the agent's loop step by step, and lessons for writing your own complex skills.
- **B · Runtime**: how the skill's code works, with live demos ported from its source.
- **C · Domain knowledge**: the technical ideas underneath (rendering, UI, animation, audio, …).

## Explainers

| # | Skill | Source | Topics |
|---|---|---|---|
| 001 | [teardown](explainers/teardown/index.html) | [elvarofficial/teardown](https://github.com/elvarofficial/teardown) @ e7e668c | skill structure, `render(t)` contract, review loop, three.js post-processing, stencil cutaways, PBR lighting, easing, perf tiers, procedural audio |

## Adding an explainer

1. Create `explainers/<skill>/index.html`: one self-contained file. Inline CSS and JS; CDN libraries only when needed, pinned to an exact version.
2. Add a card to `index.html` and a row to the table above.
3. Pin the analysed commit in the explainer header so it stays accurate if the source changes.
