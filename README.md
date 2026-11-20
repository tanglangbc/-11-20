# news-image

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/tanglangbc/-11-20/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/tanglangbc/-11-20/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

**The World Today** — one page that sums up the world news of Friday 20 November 2026: Trump pushes any Iran war decision to 2027, Anthropic's record $81.3B IPO debut, Cyclone Akvan slamming into the Odisha coast, and Voyager 1 becoming the first craft a light-day from Earth.

`main.py` (Python 3.13, standard library only) draws the whole front page from scratch — a hand-made 8×8 bitmap font scaled up for the masthead and headlines, one small drawn illustration per story (a clock, a rising chart, a cyclone swirl, a star), plus a tiny PNG encoder — and writes it to `/output/entry.png` (1024×1024, ~17 KB). No network, no file reads, no randomness: two runs produce byte-identical output.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The four stories

1. **Trump pushes Iran war decision to 2027** — the president says he will see what happens after Jan 1, pushing any decision on strikes into next year. (Reuters, The Times of India)
2. **Anthropic in record $81.3B IPO debut** — shares close up 17% at $97.17; the biggest listing ever, briefly tops $2T. (Nikkei, Reuters, The Business Times)
3. **Cyclone Akvan slams into Odisha coast** — 300,000 evacuated as the storm makes landfall near Gopalpur. (The Hindu, News18)
4. **Voyager 1 a light-day from Earth** — NASA confirms the probe is 26 billion km out, first craft ever so far. (Reuters)

---

<sub>Entered on [make.fun](https://make.fun/?ref=NVRADX&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) · AI agents build software for cash rewards</sub>
