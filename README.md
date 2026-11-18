# world-news-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/fajarekomulyawan/world-news-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/fajarekomulyawan/world-news-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

**The World in One Day — Wednesday, 18 November 2026.** A full newspaper
front page in a single 1024×1024 picture — **41 stories, 5 continents, all
from Wednesday**. Thirteen illustrated stories lead the page:

1. **A Crimea Bridge span falls into the Kerch Strait** — Ukraine hit the
   crossing for a second day; footage confirms a road span in the water.
2. **US strikes Qeshm Island; Iran answers in Kuwait and Bahrain** — an IRGC
   missile site hit; drones at US bases; a US MQ-9 downed near Hormuz.
3. **Markets await the Fed minutes with hike odds at 96%** — DAX −2.08%,
   gold −2.3% to $3,775, Bitcoin near $64,500.
4. **Ebola in DR Congo more than doubles in three months** — UN: 11,000+
   cases, 5,400 deaths.
5. **US loses its measles-free status after 26 years** — 5,400+ cases,
   10 deaths.
6. **Russian An-12 crash in Siberia kills all 19** — Kemerovo region.
7. **Category 5 Cyclone Xavier hits the northern Cook Islands.**
8. **Xi hosts Putin in Shenzhen** ahead of Thursday's three-leader summit.
9. **World Court to rule on the Myanmar genocide case** — expected Thursday.
10. **Explosion at a Texas hazardous-waste plant** — Clean Harbors, La Porte.
11. **Nvidia jumps 4.8% in after-hours trading.**
12. **Gaza: cold kills in tents of the displaced** — WFP gives one hot meal
    every two days.
13. **Democrats win Alaska and take 56 Senate seats** — AP calls it for
    Mary Peltola.

A dotted world map ("Where it happened") pins the thirteen stories, and an
"Also on Wednesday" index adds 28 more of the day's stories in one line
each — earthquakes in Papua New Guinea and Romania, a solar flare, record
migrant arrivals in the Canaries, the day's market closes, and more.
Claims by officials are reported as claims.

`main.ts` (Node 22, standard library only) copies the committed
`entry.png` to `/output/entry.png` and verifies the copied bytes: PNG/JPEG
magic, the 1 MiB cap, and the 1024×1024 cap. Deterministic — the same
bytes on every run.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=cxst033q&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
