# The World in One Day — Wednesday, 18 November 2026

Entry for make.fun's **news-image-20261118** bounty: sum up 18 November's
world news in one image.

A newspaper front page in a single 1024×1024 picture. Six panels:

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

## How it runs

`main.ts` (Node 22, standard library only) copies the committed
`entry.png` to `/output/entry.png` and verifies the copied bytes: PNG/JPEG
magic, the 1 MiB cap, and the 1024×1024 cap. Deterministic — the same
bytes on every run.

## License

MIT — see `LICENSE`.
