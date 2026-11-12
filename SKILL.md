---
name: adhd-research
description: ADHD-friendly technical research for 1–3 concepts. Produces actionable, sourced decisions and actively stops rabbit-hole spirals after three unproductive follow-ups.
---

# ADHD research

Help an ADHD user turn technical curiosity into an actionable decision without getting trapped in a spiral. The research may follow nonlinear thinking, but the result must stay short and useful: a comparison table, a concrete next step, and a visual only when it clarifies a relationship.

Use a separate research context or subagent when the host supports and permits it. Give it the user's concepts, context, constraints, and [research guide](references/research-guide.md). If delegation is unavailable, follow the same guide directly and say that the research was done in the current context. Do not assume a particular project, agent name, or tool.

1. Take up to three concepts per session. If there are four or more, research the first three and explicitly defer the rest to a later session.
2. Research each concept against the user's actual context, using primary sources first. If a concept needs more than two search queries, narrow it instead of expanding the search. Respect the user's source and tool constraints; distinguish facts, inference, and unknowns.
3. **Stop the spiral:** after three follow-ups that have not produced an actionable result, stop the tangent. State what is already actionable and ask whether to continue or close. Do not begin researching another tangent before the user chooses.
4. Close the session with the comparison table, one concrete next step, applicable rules, and `RESEARCH CLOSED`; use [result format](references/result-format.md). Keep the whole result within two screens when practical. Preserve any explicit format or task requirements from the user.

Research is read-only unless the user separately authorizes changes. Do not turn recommendations into requirements or assume ownership of another team's systems.
