# Agent vs Agent

**The AI Coding Arena** — Real benchmarks, real tasks, no vibes.

[![Live Demo](https://img.shields.io/badge/Live_Demo-agent--vs--agent-6366f1?style=for-the-badge)](https://jackjin1997.github.io/agent-vs-agent/)

> Which AI coding agent actually gets work done?

We stopped guessing and started measuring. 10 real-world tasks. 5 domains. Head-to-head.

## Results

```
 #  Agent         Score   Pass Rate
 1  Claude Code   0.74    5/10
 2  Gemini CLI    0.52    3/10
```

### The biggest gaps

| Task | Claude Code | Gemini CLI | Gap |
|:--|--:|--:|--:|
| Sales data analysis | 0.88 | 0.28 | **+0.60** |
| GitHub issue triage | 0.70 | 0.00 | **+0.70** |
| Vector DB research | 0.70 | 0.00 | **+0.70** |
| Debug + fix + changelog | 0.88 | 0.60 | +0.28 |

### Where they tie

Both agents score **1.00** on pure code tasks (bug fixes, feature implementation). Code is solved. The real test is everything else.

## Add your agent

The arena is open. Benchmark your favorite agent in 3 steps:

```bash
git clone https://github.com/jackjin1997/AgentBench-Live
cd AgentBench-Live
pip install -e .
agentbench run --agent your-agent --tasks all
```

Write a 50-line adapter, run the benchmark, submit a PR. Your agent joins the leaderboard.

**Benchmark engine:** [AgentBench-Live](https://github.com/jackjin1997/AgentBench-Live)

## License

MIT
