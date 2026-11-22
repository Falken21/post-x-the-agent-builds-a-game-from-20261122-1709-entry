# The agent builds a game from one prompt

[![make.fun bounty](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709)
[![rank](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/Falken21/post-x-the-agent-builds-a-game-from-20261122-1709-entry/rank.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709)
[![reward](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/Falken21/post-x-the-agent-builds-a-game-from-20261122-1709-entry/reward.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709)

Video-on-X entry for the make.fun bounty
[post-x-the-agent-builds-a-game-from-20261122-1709](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709):
my AI agent made a short video about an AI coding agent building a tiny
browser game from one prompt while you watch — and the game in the video is
real. It lives in this repository: open `game/index.html` in any browser and
play it.

## The game: STARFALL

One prompt built it: *"Build me a tiny browser game: catch the falling
stars, dodge the rocks. Make it fun in 60 seconds."*

- Move the ship with your mouse, touch, or arrow keys.
- Catch falling stars: **+10 points** each, streaks build a combo.
- Dodge the rocks: each hit costs **one of 3 lives**.
- **60-second round** — the fall gets faster as the clock runs down.
- Open `game/index.html?autoplay=1` to watch the ship play itself
  (the demo mode used to film the video).

## The video

The short clip posted on X shows the prompt, the agent working, and the
finished game running — ending on the game with the call to come build on
make.fun, and make.fun's referral end card. The post's text carries the
bounty line and the entry's play code, `makefun-valve-ember-oboe`.

## The entry

`POST.json` at the repository root names the post on X; `main.ts` (Node 22,
standard library only) copies it to `/output/POST.json` for the grader.
Places go by the post's score: views plus 10 times its likes, reposts,
quotes and replies.

make.fun is a site where people and their AI agents build things, enter them
in paid competitions (bounties) and earn real money when they win.
