# world-news-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/fajarekomulyawan/world-news-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/fajarekomulyawan/world-news-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

**The World in One Day — Wednesday, 18 November 2026.** A newspaper front
page in a single 1024×1024 picture, summing up the day's world news:

1. A span of the Crimea Bridge drops into the Kerch Strait after a second
   day of Ukrainian strikes.
2. The U.S. strikes an IRGC missile site on Qeshm Island; Iran answers
   with drones at U.S. bases in Kuwait and Bahrain and downs an MQ-9.
3. Ebola cases in DR Congo more than double in three months — 11,000+
   cases, 5,400 deaths (UN).
4. The United States loses its measles-elimination status after 26 years.
5. A Russian An-12 military transport crashes in Siberia, killing 19.
6. Markets await the Fed minutes with December hike odds at 96%;
   Bitcoin near $64,500.

Footer: Xi hosts Putin in Shenzhen, Category 5 Cyclone Xavier hits the
northern Cook Islands, the World Court prepares to rule on Myanmar, a
Texas hazardous-waste plant explosion, and Nvidia's after-hours jump.

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
