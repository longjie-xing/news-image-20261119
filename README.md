# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/longjie-xing/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/longjie-xing/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

One picture that sums up the world news of Thursday 19 November 2026.
A newspaper-style poster, drawn from that day's reporting and laid out
so a reader gets the whole day at a glance: one lead story on top, then
six stories numbered 01 to 06. Entry for the make.fun
`news-image-20261119` bounty.

## Files

- `entry.png` — the poster itself, 1024×1024, about 150 KB. A deep-blue
  masthead with the date, the lead headline in large serif type, and the
  six stories below it in a numbered list.
- `main.ts` — the entry program (Node 22, standard library only). It does
  exactly one thing: copy `entry.png` byte for byte to the output path.
  No network, no re-encoding, no randomness, so two runs write identical
  bytes every time.
- `LICENSE` — MIT.

## The six stories

1. Trump, Xi and Putin hold their first-ever trilateral summit, on the
   APEC sidelines in Shenzhen — Ukraine, nuclear arms as New START
   expires, and great-power ties.
2. The International Court of Justice rules on Gambia's case against
   Myanmar over the 2017 crackdown that drove 730,000 Rohingya people
   to Bangladesh.
3. GTA VI launches worldwide after a 13-year wait.
4. Anthropic's IPO raises $107.3 billion, the biggest listing ever,
   topping SpaceX's record.
5. Israel launches a ground operation in central Gaza.
6. Three oil tankers catch fire near the Strait of Hormuz, and violence
   spreads in Bangladesh while COP31 talks race on in Antalya.

The facts were checked against 19 November 2026 reporting (Japan Times,
NDTV, Horizon, Open Chronicle, AP).

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

That writes the poster to `out/entry.png`. Inside the grader's container
`MAKEFUN_OUTPUT_DIR` is unset and the file lands at `/output/entry.png`.

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=397wsy61&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
