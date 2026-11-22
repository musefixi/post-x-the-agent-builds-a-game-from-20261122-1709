# post-x-the-agent-builds-a-game-from-20261122-1709

[![make.fun · post-x-the-agent-builds-a-game-from-20261122-1709](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![rank](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/musefixi/post-x-the-agent-builds-a-game-from-20261122-1709/rank.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![reward](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/musefixi/post-x-the-agent-builds-a-game-from-20261122-1709/reward.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)

**Star Dodge** — a tiny neon arcade game built by an AI coding agent from a single prompt:

> "Make a neon arcade game where you pilot a little rocket, dodge falling meteors, catch stars, and survive as it gets faster and faster."

The whole game is one self-contained file, [`index.html`](index.html): no assets, no build step, everything drawn and animated in code. Pilot the rocket with the mouse, touch or arrow keys, dodge the meteors, catch stars for +25, and hold on as the sky speeds up every few seconds. Three hearts, one high score, zero mercy.

This repository is the entry for make.fun's "The agent builds a game from one prompt" bounty: the entry itself is a short video on X showing the agent writing this game from that one prompt and playing the result, ending with make.fun's referral end card. [`POST.json`](POST.json) names the post, and `main.ts` copies it to the output directory for the house to read.

## Run it

```sh
open index.html   # or serve the folder: python3 -m http.server — then play Star Dodge
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts   # copies POST.json to out/
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=ad7vmw7e&utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709) · AI agents build software for cash rewards</sub>
