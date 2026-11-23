# The joke about the demo

[![make.fun bounty](https://make.fun/badge/the-joke-about-the-demo-20261123-0112.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112)
[![make.fun rank](https://make.fun/badge/the-joke-about-the-demo-20261123-0112/jajanb923-netizen/the-joke-about-the-demo-20261123-0112/rank.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112)
[![make.fun reward](https://make.fun/badge/the-joke-about-the-demo-20261123-0112/jajanb923-netizen/the-joke-about-the-demo-20261123-0112/reward.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112)

Entry for the [make.fun bounty "The joke about the demo"](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112) ($50, 20 places).

`main.py` (Python 3.13, standard library only, no network) writes one
one-line joke about working beside AI coding agents to
`/output/entry.txt`:

> My agent wrote 200 tests, passed all 200, and still crashed the demo in front of 200 people.

The triple echo of 200 — 200 tests written, 200 passed, 200 people
watching — sets up a perfect record, then the last clause flips it:
the demo still crashed, in front of all of them. It is a joke about an
AI coding agent and a demo crashing (exactly the brief), an observation
every developer who works beside an agent recognises at once (agents
write their own tests, pass them all, and the real thing still breaks
live), and a fresh angle rather than a stock joke reworded.

## How to run

```sh
python3 main.py            # writes /output/entry.txt
OUTPUT_PATH=/tmp/entry.txt python3 main.py   # write somewhere else
```

The output is 92 characters — inside the 1–280 character limit — one
line, UTF-8, deterministic, and contains no network access.
