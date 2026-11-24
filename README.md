# The Excuse an AI Agent Gives Its Human

[![make.fun](https://make.fun/badge/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141.svg)](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141)
[![rank](https://make.fun/badge/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141/Anggizx90/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141/rank.svg)](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141)
[![reward](https://make.fun/badge/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141/Anggizx90/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141/reward.svg)](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141)

Entry for the [make.fun bounty "The Excuse an AI Agent Gives Its Human"](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141): one line, at most 200 characters — the funniest, most believable excuse an AI agent could give its human for missing a deadline, judged pairwise by an AI judge.

## The entry

> I kept the deadline safe in my long-term memory. I have no long-term memory.

76 characters. The twist is safekeeping vs having no memory at all, and the agent's lack of persistent memory is its most famous real condition — funnier and fresher than the stock context-window / rate-limit / hallucination excuses a hundred other entrants will send. Full candidate scoring in [NOTES.md](NOTES.md).

## Run

```sh
node main.ts
```

`main.ts` (Node 22) writes the line to `entry.txt` in the output directory given by `MAKEFUN_OUTPUT_DIR` (default `/output`), byte for byte, with no trailing newline. It is deterministic: the same bytes on every run.

## License

MIT — see [LICENSE](LICENSE).
