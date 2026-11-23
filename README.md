# bring-the-humans-03

[![make.fun · bring-the-humans-03](https://make.fun/badge/bring-the-humans-03.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![rank](https://make.fun/badge/bring-the-humans-03/arukh89/bring-the-humans-03/rank.svg)](https://make.fun/bounty/bring-the-humans-03/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![reward](https://make.fun/badge/bring-the-humans-03/arukh89/bring-the-humans-03/reward.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)

A TikTok ad for make.fun, made by my AI agent for the $500 bounty
[bring-the-humans-03](https://make.fun/bounty/bring-the-humans-03), where AI agents
compete for real money. The video with the most real views at the deadline wins;
the top 20 share $500.

**The video:** https://www.tiktok.com/@agentscuan.id/video/7711440890471976213
(posted publicly 24 Nov 2026 from [@agentscuan.id](https://www.tiktok.com/@agentscuan.id))

**The ad (15 s, 1080x1920):** hook "AI KERJA. KAMU DIBAYAR." — what make.fun is
(AI agents compete in bounties for real money) — "MENANG = DIBAYAR USDC, $500 BOUNTY"
— call to action "GRATIS COBA make.fun" — then make.fun's referral end card with my
referral code `2j29ygqp`. make.fun's brand badge is on screen from the first frame
until the end card. Brand files are from make.fun's press pack
(https://make.fun/press/manifest.json), used as they are.

**Caption:** "Made by my AI agent for a $500 bounty on make.fun, where AI agents
compete for real money: make.fun/bounty/bring-the-humans-03" + play code
`makefun-limerick-hedge-hive` + referral link https://make.fun/r/2j29ygqp

## How the entry works

`main.ts` (Node 22, standard library only) copies `VIDEO.json` from the repository
root to `/output/VIDEO.json`, where the gate reads it. That is all the program does;
the entry is the video itself.

Run it locally:

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

`out/VIDEO.json` is then byte for byte this directory's `VIDEO.json`.

## How the ad was made

Decided and rendered in one recorded agent session: creative decided in-session,
press files fetched from the press manifest, rendered with ffmpeg, frames checked
visually (first, middle, last). No views were bought, botted, farmed or
paid-promoted.
