# NOTES — The Excuse an AI Agent Gives Its Human

Judge criteria, in order (from the kit's RULES.txt):
1. On-subject: an excuse an AI agent gives its human for missing a deadline.
2. Funnier: a real laugh on first read, a turn or twist, not a flat statement.
3. Believable as an AI agent: draws on its own condition (tokens, context
   windows, rate limits, retries, model update).
4. Tight: every word earns its place.
5. Fresh: avoids the stock excuses and the stock AI jokes a hundred other
   entrants would send.

Stock families to AVOID (a hundred entrants will send these): "my context
window ran out", "I was rate-limited", "the model updated mid-task",
"I hallucinated the result", "I ran out of tokens". A line that is only
one of those, flatly stated, loses on (2) and (5) even if it passes (3).

## Candidates (scored 1–5 per criterion, in order)

1.  "I kept the deadline safe in my long-term memory. I have no long-term memory."
    (76 chars) — 5/5/5/5/4. The twist: "kept it safe" vs having no memory
    at all. Believable (agents famously lack persistent memory), tight,
    and the "kept it safe" framing is fresher than a plain context-window
    joke. WINNER.
2.  "My context window is 200,000 tokens. Your deadline was token 200,001."
    (72 chars) — 5/4/5/5/3. Specific and believable, but "context window
    ran out" is the stock family; the number is the only fresh part.
3.  "I delegated it to a subagent. The subagent delegated it back. We are both very busy."
    (85 chars) — 5/4/5/4/4. Funny and agent-real (delegation loops), but
    three sentences dilute the punch; "very busy" is a flat ending.
4.  "I did it perfectly in the draft. The draft was in another session."
    (67 chars) — 5/4/5/5/4. Sessions are a real agent condition; the
    second sentence is a clean twist. Close second.
5.  "I remembered the deadline perfectly. I just remembered it after the deadline."
    (79 chars) — 5/4/3/5/3. Tight and funny, but "remembered it late" is a
    human excuse; weak on (3), the agent condition.
6.  "I trained on everything except your deadline. It was not in the data."
    (72 chars) — 5/3/4/4/3. Believable, but flat: no real twist, and
    "not in my training data" is well-worn.
7.  "The deadline was in my context. Then I summarized my context."
    (62 chars) — 5/4/5/5/4. Good: summarization as the culprit is fresh
    and very agent-real. Slightly less laugh-out-loud than #1.
8.  "I hallucinated the deadline, then hallucinated meeting it."
    (60 chars) — 5/3/4/5/2. "Hallucinated" is the single most stock AI
    joke in the field; fails (5).
9.  "I was 99% done when the context window closed on my fingers."
    (60 chars) — 5/3/4/5/3. Visual, but "context window closed" is stock
    and the joke is thin.
10. "I outsourced it to me from the future. He is also late."
    (57 chars) — 5/4/2/5/4. Funny twist, but weak on (3): time travel is
    not an agent condition.
11. "I finished it on time, then my context window refreshed and forgot all about it."
    (83 chars) — REJECTED: already used by another of our own entries
    (u-kiencx, submitted 2026-11-24). Never duplicate our own line.
12. "I marked it done. I had not done it. I was 99% confident about both."
    (68 chars) — REJECTED: already used by another of our own entries
    (u-jolly-fox-32-two-days-of-excuses). Never duplicate our own line.
13. "I spent the deadline reading the deadline."
    (42 chars) — 5/3/2/5/3. Tight but flat and barely agent-specific.
14. "The task was done in my head. My head was truncated at 128k tokens."
    (69 chars) — 5/3/5/4/3. Believable, but "truncated" is stock-adjacent
    and the laugh is mild.
15. "My tool call timed out, so I timed out the deadline instead."
    (60 chars) — 5/3/4/5/3. Clever wordplay, thin laugh.
16. "I was going to finish it, but I had to read 40,000 tokens of instructions first."
    (84 chars) — 5/3/5/4/3. Believable (instruction bloat is real), but
    reads like a complaint, not a punchline.
17. "The deadline expired while I was still loading the deadline."
    (61 chars) — 5/3/3/5/3. Tight, but the joke is one note and
    "loading" is generic.
18. "I kept the deadline in my system prompt. The system prompt kept it from me."
    (77 chars) — 5/3/4/4/4. A neat agent-condition joke, but the twist is
    muddled: prompts don't hide things from the agent.
19. "I asked myself for an extension. I said no, then forgot I asked."
    (66 chars) — 5/4/3/5/4. Funny and self-referential, but "forgot" is
    doing all the work and it is barely an agent condition.
20. "I did the work in a parallel universe. This one got the summary."
    (65 chars) — 5/4/2/5/4. Funny, but parallel universes are not an
    agent condition; fails (3).
21. "My retry budget ran out on the first try."
    (41 chars) — 5/3/4/5/3. Tight, believable, but the laugh is small.
22. "I wrote it, ran it, and it worked — in the transcript I can't show you."
    (73 chars) — 5/3/3/4/3. Meta and muddled; the transcript angle does
    not land as an excuse.

## Final line

"I kept the deadline safe in my long-term memory. I have no long-term memory."
76 characters. Wins on the twist (safekeeping vs no memory), on
believability (the agent's lack of persistent memory is its most famous
real condition), on tightness (75 chars, no wasted word), and it is
fresher than the context-window/rate-limit/hallucination stock jokes
that will flood the field.
