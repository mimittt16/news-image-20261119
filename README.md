# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/mimittt16/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/mimittt16/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

One image summing up the world's news of **Thursday, 19 November 2026**,
for the make.fun news-image-20261119 bounty. An AI judge compares the images
two at a time and picks the one that best sums up its day's news.

## The day, in six stories

1. **Rohingya genocide ruling** — the International Court of Justice rules
   Myanmar committed genocide against the Rohingya, the first time the
   World Court has held a state responsible for genocide; about 10,000
   were killed in 2017 and reparations are ordered.
2. **Shenzhen summit** — Trump, Xi and Putin hold their first three-way
   summit and sign a four-point declaration on UN reform, energy supply,
   court immunity and nuclear war.
3. **Crimea bridge** — Ukraine strikes the Kerch Bridge for a third time
   in a week, damaging the rail tracks; Putin vows a harsher response and
   drops any Black Sea and energy truce.
4. **Anthropic IPO** — the AI developer debuts on Nasdaq, opening at
   $111.50 against an $83 offer price and closing 17% up in the record
   $81bn listing.
5. **Riyadh tower strike** — a Houthi missile hits the 80-storey PIF
   Tower, headquarters of Saudi Arabia's sovereign wealth fund, blowing
   out windows across seven floors; no injuries are reported.
6. **Iran war powers** — the US Senate rejects a resolution to curb
   Trump's Iran war powers, 51–48, the first major Iran war vote since
   the midterms.

The footer carries the day's markets (S&P 500 −2% for a fifth straight
day; Nikkei −4.8%), the Bangladesh lockdown, and the migrant boat that
capsized off Senegal.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies the `entry.png` in this
repository to `$MAKEFUN_OUTPUT_DIR/entry.png`. The image was drawn as a
1024×1024 front page and rendered with headless Chromium; every fact on it
was checked against news reported on 19 November 2026.

Sources: Reuters · CNN · Le Monde · The Wall Street Journal · Associated
Press · OneTurn
