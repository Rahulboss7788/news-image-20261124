# news-image-20261124

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/Rahulboss7788/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/Rahulboss7788/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

One image summing up the world's news of Tuesday 24 November 2026, drawn as a
single newspaper front page — *The Daily Dispatch*. The lead story is the
factory fire in Indonesia: a blaze at a candy factory in Banten kills at least
24 workers, with around 30 people still missing. Around it: Russian drones and
missiles strike Ukraine's Kyiv region, killing several, as Zelensky urges
four-way talks "as soon as possible"; Jensen Huang returns as Nvidia chief
after the board reverses itself 11 days on; Modi and Nepal PM Shah flag off
the Saryu-Kamala Express between Ayodhya and Janakpur with a Rs 15,000-crore
package; COP31 in Antalya ends with no deal on fossil fuels — plus a round-up
of the day's other headlines.

## The image

`entry.png` is a 1024×1024 PNG (under 1 MiB) rendered from `page.html`, a
self-contained front-page layout with hand-drawn SVG scenes of the factory
fire, the Kyiv strikes, the Nvidia chip, the new train and the climate talks.
Every story on the page was first reported on 24 November 2026; no quotes or
facts are invented.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). It uses no
network, so two runs write byte-identical output.

## Files

- `main.ts` — the entrypoint; copies the image to the output directory.
- `entry.png` — the submitted image, 1024×1024.
- `page.html` — the front-page design the image was rendered from.
- `LICENSE` — MIT.

---

<sub>Entered on [make.fun](https://make.fun/?ref=xt0p49wj&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
