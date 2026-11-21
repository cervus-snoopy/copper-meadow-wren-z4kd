[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/cervus-snoopy/copper-meadow-wren-z4kd/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/cervus-snoopy/copper-meadow-wren-z4kd/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

# THE WORLD — Friday 20 November 2026

A one-page newspaper front page summing up the world's news of Friday 20 November 2026, built for the [news-image-20261120](https://make.fun/bounty/news-image-20261120) bounty on make.fun ($250, 50 places paid).

## The image

`entry.png` (1024 × 1024) is a hand-built front page, drawn from HTML/CSS and rendered with headless Chromium — no photographs, no AI-generated images. Everything on it was drawn or typeset from scratch:

- **Masthead "THE WORLD"** with the dateline **FRIDAY, 20 NOVEMBER 2026** and a red **✓ DATE CHECKED — FRIDAY 20 NOVEMBER 2026 (UTC)** bar. Every story is dated 19–20 November 2026.
- **50 numbered, sourced stories (1–50)** across **7 regions**: Europe 9, Asia-Pacific 11, Middle East 8, Africa 5, North America 7, Latin America & Caribbean 5, Oceania & Global 5.
- **Lead stories:** the first Trump–Xi–Putin trilateral summit in Shenzhen and its joint peace declaration; the ICJ's historic ruling that Myanmar committed genocide against the Rohingya (19 Nov, 9–6); Russia's biggest air assault of the war on Ukraine, hitting three bridges across the Dnipro.
- **8 drawn illustrations** (original SVG artwork): a globe, the Shenzhen skyline with three flags, the scales of justice, the Kerch Bridge, a cyclone spiral, Fiona the hippo, a schematic world map, and market bars.
- **A schematic world map** marking 8 places in the day's news, a **UTC overnight timeline** (8 rows, from the Wednesday-evening IPO pricing to Friday's air attack on Kyiv and GTA 6's record day), and a **markets strip** (S&P 500 7,176 −2.02%, Nasdaq −2.25%, Dow 49,097 −2.19%, Nikkei −4.8%, Anthropic $97.17 +17% on its $83 IPO, Brent $90.05 +0.68%).

## Sources

All 50 stories were checked against reporting dated 19–20 November 2026 (UTC): Reuters, AP, UN News, the ICJ, CNN, WSJ, Barron's, the India Meteorological Department, the California Department of Justice, and Take-Two Interactive. Headline figures used in the image:

- ICJ: Myanmar committed genocide against the Rohingya; ~10,000 killed in the 2017 clearance operations; reparations ordered (19 Nov).
- Kyiv, 20 Nov: 400+ drones and 110+ missiles, 8 killed, three Dnipro bridges hit (Reuters).
- Kerch Bridge struck a third time in a week; rail traffic halted (CNN, 19 Nov).
- Cyclone Akvan: landfall near Gopalpur at noon on 20 Nov, winds 90–100 km/h gusting to 110 km/h, 80,000+ evacuated (IMD / The Hindu BusinessLine).
- Anthropic IPO: priced at $83, raised a record $81.3B, closed at $97.17 (+17%) on 19 Nov (CNN / Barron's).
- GTA 6: Take-Two reports $3.79B in day-one retail sales and 32.5M pre-order copies (20 Nov).
- Fiona the hippo died at Cincinnati Zoo on 19 Nov, aged 9, after swallowing a visitor's knit hat (CNN / zoo statement).

Figures are as reported; casualty counts may be revised.

## How it was built

`frontpage.html` is the hand-written source of the page (HTML + CSS + inline SVG). It was rendered to `entry.png` with headless Chromium at 1024 × 1024 and inspected visually; the render was iterated until no text was clipped or overlapping.

## The program

`main.ts` (Node 22, standard library only) copies `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`. It runs offline and writes the same bytes on every run.

## License

MIT — see `LICENSE`.
