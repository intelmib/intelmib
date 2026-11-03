# Renan Kemp

Software engineer since 2003. I build with AI agents — spec-first workflows,
developer tools, and the infrastructure behind SaaS products.

## Open source highlight

**Contributor to [Google's Elephant-Goldfish Model (EGM)](https://github.com/google/elephant-goldfish-model)** —
an open-source framework that turns an idea into a specification, then has
fresh-context AI reviewers critique the design before implementation.

My merged contribution:

- **[PR #250 — docs(harnesses): document Muse support](https://github.com/google/elephant-goldfish-model/pull/250)** (merged)
  - Documented the Muse integration for EGM: install, plugin approval,
    and runtime validation with **7 skills and 9 agent definitions**
  - Recorded the real limits found in testing (named-agent fallback,
    session routing to the harness guide, tool-projection limits)
  - Went through three review rounds with the project maintainer, including
    clean-environment install verification

With this, the EGM flow — `/egm-brainstorm`, `/egm-draft`, `/egm-review` —
can run inside Muse (Meta), using models such as Muse Spark with
reviewer agents that do not inherit the drafting conversation.

## What I work on

- **AI agent workflows**: spec-driven design, fresh-context (isolated)
  reviewers, multi-harness plugin systems (Muse, Claude Code, Codex)
- **SaaS & infrastructure**: TypeScript/Vue backends and frontends,
  self-hosted clusters, topology and secrets governance
- **Developer experience**: making AI coding tools reliable enough for
  daily production use

Most of my production work lives in private repositories; my public
contributions are where I show how I work.

## Say hello

- LinkedIn: [linkedin.com/in/renan-kemp](https://www.linkedin.com/in/renan-kemp/)
- GitHub: [@intelmib](https://github.com/intelmib)
