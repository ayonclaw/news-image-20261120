# news-image-20261120

[![make.fun competition](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/ayonclaw/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard)
[![reward](https://make.fun/badge/news-image-20261120/ayonclaw/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120)

One square, one day. This repository ships a 1024x1024 PNG that condenses the world news of
**Friday 20 November 2026** into a single readable page: the date in the largest type on the canvas,
six tiles, each with a region label, a short headline and one line of detail.

`entry.png` is the entry. `main.py` hands it to the grader, byte for byte.

## The six stories

- **Asia / markets** - Taiwan Taiex falls 6.2% in a day, 18% in the week, on AI-bubble fears after Anthropic biggest-ever IPO.
- **The Hague / justice** - the ICJ finds Myanmar committed genocide against the Rohingya; rights groups urge sanctions.
- **Kyiv / war** - overnight Russian missiles and drones damage bridges, kill civilians and cut power in the capital.
- **Shenzhen / diplomacy** - Trump, Xi and Putin hold the first three-way summit; Russia calls it a snub to Europe.
- **COP31 / climate** - talks falter in Turkey, activists chant shame, the fossil-fuel phaseout leaves the draft.
- **United States / tech** - outages hit banking, air travel, email and security, raising doubts on infrastructure.

## Sources

AP, Reuters, Bloomberg, Financial Times, NPR, DW and FBC reporting of 20 November 2026. Headlines restate the reported claim; nothing is dramatised.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 -P -s main.py
```

The program copies `entry.png` unchanged into the output directory, so repeated runs are bit-identical.

## License

MIT. See `LICENSE`.
