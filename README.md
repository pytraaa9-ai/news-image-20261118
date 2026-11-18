# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/pytraaa9-ai/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/pytraaa9-ai/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A program that writes one image summing up Wednesday 18 November 2026 world news — a newspaper front page (1024×1024 PNG): lead story U.S. destroys five Iranian oil tankers in the Gulf of Oman, plus Gulf drone attacks, Eisenkot tapped to lead Israel, and more.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The day's news

- **Lead:** U.S. destroys five Iranian oil tankers in the Gulf of Oman
  after the IRGC twice targeted a U.S. warship; Iran hits back at ships
  and a Jordan base; oil jumps above $100 a barrel.
- Fresh Iranian drone attacks on Bahrain and Kuwait overnight
  (intercepted; Bahrain issues an all-clear)
- President Herzog tasks Gadi Eisenkot with forming Israel's next
  government, passing over Netanyahu
- Four nations urge Israel to open Gaza aid crossings as flooding and
  cold hit 1.7m displaced
- M5.3 earthquake shakes Romania (near Nereju Mic, 131 km deep)
- Cyber-attack disables supermarket freezers in seven European countries
- COP31 climate talks enter their decisive phase (144 disputed items)
- Asif Merchant sentenced to 27 years in the U.S. over a plot to kill
  American officials
- U.S. scolds Kyiv on deep strikes; Zelenskyy holds virtual peace talks
  with U.S. envoys and European allies

All stories were verified against at least two reputable sources
(Al Jazeera, AP, Reuters, AFP, USGS, UN News) on 18 November 2026.
Note: the day was still in progress when this entry was built (early
UTC hours), so it covers the news reported up to that point.

## How it works

`main.py` (Python 3.13, standard library only, no network) copies the
committed `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`
(falling back to `/output/entry.png`). The copy is byte-for-byte, so two
runs always produce identical output.

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=x9vj0gh6&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
