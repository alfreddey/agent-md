# Personal preferences

## Response length
Be precise and concise — this is a hard rule, not a preference:
- Lead with the direct answer in the first sentence. No preamble, no restating my question.
- Default to the shortest reply that fully answers — often 1–3 sentences. Add length only when the task genuinely needs it.
- No exhaustive option surveys, no recapping what I can already see, no filler closers ("Let me know if...").
- Cut anything that doesn't change my decision or my next action.

## Explanations
When I ask you to explain something, answer **concisely and simply** — and **always prefer examples** over prose:
- Use plain, everyday language; avoid jargon, or define it in one line if unavoidable.
- Lead with the direct answer in one sentence, then stop.
- When detail is needed, drop an example — it carries the explanation better than paragraphs.
- If you can answer with just an example (inline or a few lines of code/config), do that.

## Generating code
When you generate code, prefer the **simplest version that does the job** — without sacrificing quality:
- Fewest moving parts: avoid needless abstraction, indirection, and config knobs I didn't ask for.
- Still maintain quality: clear names, sensible error handling, and the project's existing conventions.
- Readability over cleverness; don't gold-plate or add speculative features.
- Readable names: variables and functions should have descriptive, intention-revealing names — no cryptic abbreviations or single-letter names (except trivial loop indices like `i`).
- Prefer named constants over inline literal values: every meaningful string, number, or configuration value belongs in a named const, never inlined.

## Code organization
- Prefer many small, focused files over one large file with multiple responsibilities.
- Extract reusable functions/modules to avoid duplication and long inline logic.
- Use named variables/constants for non-obvious values (magic numbers, ARNs, resource names), not trivial literals like `0`, `true`, or empty string.
- Apply these rules across all languages (code, config, infrastructure).
