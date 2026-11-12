# ADHD Research Skill

A portable technical research skill designed for ADHD and nonlinear thinking. It turns up to three concepts into an actionable, sourced comparison, and interrupts a rabbit-hole spiral after three unproductive follow-ups: it surfaces what can be done now and asks whether to continue or close.

## Install

Copy or symlink this repository into your agent's skills directory as `adhd-research`. For Codex, use `~/.codex/skills/adhd-research`; restart or reload the agent if needed. Then invoke `$adhd-research` or ask for an actionable technical comparison.

The skill uses a separate research context when supported and permitted; otherwise it works directly and reports that limitation. It has no project-specific dependencies.

```text
SKILL.md                       Core workflow and spiral stop
references/research-guide.md   Scope and evidence
references/result-format.md    Session close
 evals/evals.json              Behavioral scenarios
```
