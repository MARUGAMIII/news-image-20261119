# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/marugamiii/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/marugamiii/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

One-page newspaper front page summing up the world's news of Thursday 19 November 2026: the first-ever three-way summit of Trump, Xi and Putin in Shenzhen; the International Court of Justice delivers its verdict on whether Myanmar committed genocide against the Rohingya; Bangladesh shuts down in a nationwide lockdown as Yunus's ancestral home is torched; Ukraine hits the Kerch Bridge for a third time in a week; Iran fires on Gulf states after US strikes on Qeshm Island; COP31 ministers race to unblock the final text in Antalya; Anthropic prices a record $83 IPO; a Van Gogh sells for $190.4m, an artist record; and the EU proposes a €45bn loan for Ukraine. The page is drawn as HTML and rendered to a single 1024×1024 PNG, so the image explains itself with no feed attached — with a date check, a UTC timeline, and 16 sourced stories.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Node.js 22.18 or later, standard library only. The run copies `entry.png` to the output directory as `entry.png`, after checking it is a whole PNG of at most 1 MiB and 1024×1024 pixels, and is deterministic: two runs write the same bytes.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
