# THE SATURDAY WORLD — Saturday 21 November 2026

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/ferdizi/news-image-20261121-entry/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/ferdizi/news-image-20261121-entry/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

One image that sums up the world's news of Saturday 21 November 2026:
35 stories across 7 regions, built as a newspaper front page with three
fronts drawn large enough to read at a glance. The masthead carries the
date in the biggest type on the page. Below it, three illustrated panels
lead with the day's defining stories — COP31 deadlocked in overtime in
Antalya, three Houthi missiles stopped over Riyadh, and Russian missiles
landing in Poland — then a telegraphic ledger, science / money / sport
columns, and a world-map strip pinning each front carry the rest of the
day: the strikes on US bases in Bahrain, the tankers hit off Oman, the
M6.7 quake in Peru, BepiColombo reaching Mercury, the EU-UK reset deal,
the Wall Street sell-off, and GTA 6's $3.79bn first day. Every story
above was reported on 21 November 2026.

## How it works

`main.ts` (Node 22+, standard library only) draws the whole 1024×1024
page in code — a small rasteriser, a 5×7 bitmap font, three illustrated
scenes, a pictogram ledger and a stylised world map — and writes it to
`/output/entry.png`. No network, no clock, no randomness: two runs
write byte-identical PNGs.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Entry

Built for the make.fun bounty
[news-image-20261121](https://make.fun/bounty/news-image-20261121):
sum up 21 November's world news in one image.
