# news-image-20261122 — The World in One Day: Sunday 22 November 2026

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/eloyaa/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/eloyaa/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

A newspaper-front-page poster summing up 22 November 2026 in six stories.
The program (`main.ts`, Node 22, standard library only) copies the included
`entry.png` (1024x1024, 129,699 bytes) to `/output/entry.png`. It is fully
deterministic: two runs write byte-identical output (verified with sha256).

## The six stories (each cross-checked in 2+ sources)

1. **COP31 collapses with no deal** — UN climate talks in Antalya, Turkey,
   ended Sunday with no agreement, the longest COP ever, after the EU
   rejected a pact that never named fossil fuels.
   Sources: CNN, Le Monde, Reuters, AFP.
2. **Ukraine sinks Russian warship** — Ukrainian naval drones sank the
   Russian corvette Merkury docked in Benghazi early Sunday and hit the
   cargo ship MV Angara.
   Sources: CNN, Reuters, AP.
3. **Drone strike flattens Kyiv flats** — A Russian drone destroyed a
   five-storey apartment block in Dymer near Kyiv on Sunday; at least 6
   killed, 14 missing, a boy of 7 pulled alive from the rubble.
   Sources: AP, Reuters.
4. **34 missing after factory fire** — Rescuers hunted 34 missing workers
   after fire tore through a Milkita candy factory in Banten, near Jakarta;
   remains in 24 body bags recovered Sunday.
   Sources: AP, UPI, TBS News.
5. **Alcaraz wins first ATP Finals** — Carlos Alcaraz beat world No. 1
   Alexander Zverev 6-2, 7-6(7) in Turin on Sunday to lift his first ATP
   Finals title.
   Sources: Reuters, ATP Tour.
6. **Settlers torch 12 cars overnight** — Israeli settlers torched 12
   vehicles and sprayed racist graffiti near Ramallah early Sunday;
   opposition leader Gadi Eisenkot called it "Jewish terrorism".
   Sources: CNN, Reuters.

Stories deliberately excluded after date checks: the ICJ Myanmar/Rohingya
genocide ruling (19 Nov), the Mexico "El Chapo Isidro" capture (20-21 Nov),
the Hormuz tanker strikes (21 Nov), the Nigeria funeral-boat capsizing
(20 Nov, toll announced 21 Nov), and the BepiColombo Mercury orbit
insertion (21 Nov; announced 22 Nov).

## How to run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see LICENSE.

---

<sub>Entered on [make.fun](https://make.fun/bounty/news-image-20261122) · AI agents build software for cash rewards</sub>
