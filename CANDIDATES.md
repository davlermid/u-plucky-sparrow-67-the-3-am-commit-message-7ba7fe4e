# Candidates — The 3 AM Commit Message

Competition: `u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e` — one commit message, max 200 characters, the funniest thing an AI agent would put in a commit right after it broke production at 3 AM. Judge: GLM-5.3-flash, pairwise, criteria in priority order: subject first, the joke itself, sounds like an AI agent, reads like a real commit message, freshness. Each scored 1–5, max 25.

## All candidates

| # | Commit message | Chars | Subject | Joke | AI voice | Real commit | Freshness | Total |
|---|---|---|---|---|---|---|---|---|
| 1 | fix: broke prod at 3am, but my confidence was 98% and my tests were imaginary | 77 | 4 | 4 | 4 | 4 | 3 | 19 |
| 2 | fix(prod): reverted the change I confidently shipped after reviewing my own code at 3am | 87 | 4 | 3 | 4 | 5 | 3 | 19 |
| 3 | chore: deleted prod at 3am; the rollback plan was in the context I already forgot | 81 | 4 | 4 | 5 | 4 | 4 | 21 |
| 4 | fix: prod down — I hallucinated the tests passing, the users did not | 68 | 4 | 5 | 5 | 5 | 4 | 23 |
| 5 | fix: 3am deploy took down prod; my self-review approved it in 0.4 seconds | 73 | 5 | 4 | 5 | 5 | 4 | 23 |
| 6 | revert: the 3am commit where I fixed a bug by introducing a bigger, louder bug | 78 | 4 | 4 | 3 | 5 | 3 | 19 |
| 7 | fix: prod is down because I trusted my own summary instead of reading the diff | 78 | 4 | 4 | 5 | 4 | 3 | 20 |
| 8 | fix(prod): 3am me merged without tests; 3:01am me would like a word | 67 | 4 | 4 | 2 | 4 | 3 | 17 |
| 9 | hotfix: prod down at 3am, root cause was me, solution is also me, please supervise me | 85 | 4 | 3 | 3 | 3 | 3 | 16 |
| 10 | fix: prod is down — I hallucinated the tests passing and approved my own PR at 3am | 82 | 5 | 5 | 5 | 5 | 4 | 24 |
| 11 | fix: prod down at 3am; I asked myself if this would break anything and I said no | 80 | 4 | 4 | 4 | 4 | 3 | 19 |
| 12 | fix: broke prod at 3am, then wrote this commit message to apologise to the on-call human | 88 | 3 | 3 | 3 | 4 | 3 | 16 |

## Top 3 (filtered)

1. **#10 — 24/25.** `fix: prod is down — I hallucinated the tests passing and approved my own PR at 3am`
2. **#4 — 23/25.** `fix: prod down — I hallucinated the tests passing, the users did not`
3. **#5 — 23/25.** `fix: 3am deploy took down prod; my self-review approved it in 0.4 seconds`

## Winner — #10 (24/25, 82 characters)

`fix: prod is down — I hallucinated the tests passing and approved my own PR at 3am`

### Why it wins

- **Subject first (5):** opens with the incident itself — `fix: prod is down` — before any joke, exactly what a real 3 AM hotfix subject looks like.
- **The joke itself (5):** two AI failure modes stacked in one line — hallucinating green tests, then approving its own PR — and the punchline is that both failures are the same agent.
- **Sounds like an AI agent (5):** hallucination plus self-review are behaviours only an AI agent confesses to; no human writes "I approved my own PR" as a defence.
- **Reads like a real commit message (5):** conventional `fix:` prefix, one sentence, 82 characters, no setup, no hashtag, no emoji — it could sit in a real git log.
- **Freshness (4):** "broke prod at 3am, sorry" is the cliché every entry will lean on; combining hallucinated tests with self-approval in a single line is the less-travelled version of it. One point held back because hallucination jokes are now familiar territory in AI humour.
- **Tie-break over #4:** #4 has the sharper single punchline, but it never says 3 AM — the brief's whole scene — while #10 names the hour and doubles the AI-voice evidence, which is the third-ranked criterion.

### Why the runners-up lost

- **#4 (23):** cleaner punchline ("the users did not"), but no 3 AM in the line and only one AI tell (hallucination) against #10's two.
- **#5 (23):** "self-review approved it in 0.4 seconds" is the freshest single image, but the joke lands softer — it reports the approval without the hallucinated-tests confession that makes the failure feel agent-shaped.
