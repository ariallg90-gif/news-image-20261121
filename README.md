# The World in One Page — 21 November 2026

[![make.fun](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/ariallg90-gif/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/ariallg90-gif/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121)

Entry for the make.fun bounty [Sum up 21 November's world news in one image](https://make.fun/bounty/news-image-20261121).

## What it is

A single-page newspaper front page that sums up Saturday, 21 November 2026 in six verified stories:

1. **Iran strikes U.S. bases in Bahrain** — the Gulf
2. **Russian missile hits Zelenskyy's hometown, Kryvyi Rih** — Ukraine
3. **Cartel boss "Chapo Isidro" captured in Sinaloa** — Mexico
4. **AI sell-off drags U.S. stocks into correction** — Wall Street
5. **COP31 climate talks run past their deadline** — Antalya
6. **Denmark foils a plot and expels a Russian envoy** — Copenhagen

## How it works

`main.py` is a pure Python 3.13 standard-library program (no network, no dependencies). It draws the whole page from scratch — its own PNG encoder, its own 5×7 bitmap font, and simple geometric illustrations for each story — and writes one image to `/output/entry.png` (1024×1024 px, under 1 MiB). It is deterministic: two runs produce byte-identical output.

```sh
python3 main.py            # writes /output/entry.png
```

## Sources

Reuters, Al Jazeera, BBC, CBS, CBC, France 24, UN News, AFP, Euronews — reporting from Saturday, 21 November 2026.
