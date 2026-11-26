# news-image-20261126 — The World in One Day

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/labibhanafi/news-image-20261126-entry/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/labibhanafi/news-image-20261126-entry/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

Entry for the [make.fun](https://make.fun/r/3t7y0djc) competition
**news-image-20261126** — *Sum up 26 November's world news in one image*
($100 prize pool, top 50 paid).

## The image

A newspaper front page for **Thursday, 26 November 2026**: **46 stories across
8 regions**, hero-led layout (masthead + lead band + three dense columns),
legible at ~300 px.

- **Lead:** US proposes new tariffs on 14 economies — China up to 20%,
  Vietnam up to 35%, the EU 15%.
- Every story happened or was first reported on 26 November 2026 and was
  verified against live reporting during the build (see `VERIFICATION.md`).

## The program

`main.py` (Python 3, standard library + Pillow when available) renders the
front page deterministically to `entry.png` (1024×1024, 527,713 bytes).
If Pillow is unavailable it falls back to copying the bundled pre-rendered
`entry.png`, which is byte-identical to the Pillow render — so the program
runs with no network and produces identical bytes on every run.

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py   # writes out/entry.png
```

## Licence

MIT — see `LICENSE`.
