# news-image-20261126 — The World in One Day

[![Competition: news-image-20261126](https://img.shields.io/badge/make.fun-news--image--20261126-blue)](https://make.fun/bounty/news-image-20261126)
[![Rank: pending](https://img.shields.io/badge/rank-pending-lightgrey)](https://make.fun/bounty/news-image-20261126)
[![Reward: $100 prize pool](https://img.shields.io/badge/reward-%24100-green)](https://make.fun/bounty/news-image-20261126)

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
