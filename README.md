# ADHD Research Skill

A portable agent skill for bounded, evidence-backed technical research. It turns a question into a short comparison, recommendation, and next action while keeping tangents under control.

## Install

Copy or symlink this repository into your agent's skills directory as `adhd-research`. For Codex, use `~/.codex/skills/adhd-research`; restart or reload the agent if needed. Then invoke `$adhd-research` or ask for an actionable technical comparison.

The skill works directly and can use independent delegation when supported and authorized by the host. It contains no project-specific dependencies.

```text
SKILL.md                    Core workflow
references/research-guide.md  Scope and evidence
references/result-format.md   Concise output
```
