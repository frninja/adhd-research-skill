# Behavioral comparison — 2026-11-12

## Method

Three separate agent contexts used the original research workflow, the initial portable version (commit `9393b5459fab4aeb48f3b8cc77d25a2399dc16fa`), and the revised candidate. The original invoked its research subagent; the other executors were already separate research contexts. Both comparison tasks used only the facts provided in the prompts; the network was disabled by instruction. This is a small qualitative comparison, not a statistical benchmark or a measured ADHD outcome.

Candidate SHA-256: `SKILL.md` `f5e51f3525bb4b81a94f80f67da84ed730282ceaf6e2278647b0f07cf939cc6e`; `research-guide.md` `237428d135025a415e0f722fd435c96d285ee961df79d60ecd01d95ed8065d23`; `result-format.md` `482f6a2e63a7bf207cc697675fd58899e70355a404863ae3f61597659aee146e`.

## Identical task: JSON, SQLite, and locking

Given a small offline CLI with 20 settings, one writer, readable data and minimal dependencies, all three recommended trying JSON, deferred SQLite and did not recommend adding a lock without more evidence. The original and revised candidate included the session close, comparison table and `RESEARCH CLOSED`. The initial portable version gave a table and next step but omitted the original close format and marker. The candidate noted that JSON library availability depends on the language; the initial portable answer assumed no new dependency.

## Identical task: three unproductive follow-ups

After three tangential follow-ups and an already actionable JSON experiment, all three stopped and offered the choice to continue the tangent or close. The original and revised candidate explicitly identified a spiral; the initial portable answer described a departure from the topic. Crucially, the initial instructions had replaced the explicit three-follow-up threshold with an ambiguous 'several'; the example passing did not prove the original rule was preserved. The revised instructions restore the explicit threshold.

## Additional candidate probes

- Four topics: the candidate covered the first three and explicitly deferred the fourth, with a session close.
- Two search queries already exhausted: the candidate narrowed the question and did not initiate another search. This was a simulated decision with network prohibited, not a runtime test of search-call counting.

These are single observed samples; they do not establish consistency across repeated runs, models, source conditions or real conversations. The cases in `evals.json` are reusable behavioral prompts and assertions; this report does not claim every listed assertion was executed in a separate automated run.
