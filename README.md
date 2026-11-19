# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/pytraaa9-ai/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/pytraaa9-ai/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A program that writes one image summing up Wednesday 18 November 2026 world news — a newspaper front page (1024×1024 PNG): lead story Iran strikes U.S. bases in Kuwait and Bahrain as the Gulf war widens, plus the U.S. sinking five Iranian tankers, Trump, Xi and Putin gathering in Shenzhen, and more.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The day's news

- **Lead:** Iran strikes U.S. bases in Kuwait and Bahrain after U.S. jets
  hit a missile site on Qeshm Island; Gulf defences intercept the attacks;
  an ADNOC vessel is hit in the Strait of Hormuz, one crewman missing;
  oil eases to about $92 a barrel.
- U.S. sinks five Iranian tankers in the Gulf of Oman after two missile
  attacks on a U.S. warship; Iran hits back
- Trump, Xi and Putin gather in Shenzhen; Xi greets Trump at the airport;
  a first trilateral summit is set for Thursday at APEC
- COP31 deadlock persists: 21 issues unresolved in Antalya as a stocktake
  launches; new drafts due Thursday
- Eisenkot ally Matan Kahana wins the Knesset speakership 66–52, taking
  the gavel from Netanyahu's Likud
- Trump's Board of Peace says Israel and Hamas both failed Gaza pledges;
  the ceasefire may collapse
- Mary Peltola wins the Alaska Senate seat, beating Dan Sullivan in the
  last midterm race called; Democrats lead 56–44
- Nvidia revenue doubles to $115.8bn, up 103% on AI demand; guides to
  $130bn next quarter
- Voyager 1 reaches one light-day from Earth, the first human-made object
  16bn miles out; signals now take a day

All stories were verified against at least two reputable sources
(Reuters, AP, AFP, Al Jazeera, UN News, NASA) on 18 November 2026.
Note: this v2 entry covers the full day of 18 November 2026, including
afternoon and evening developments the morning version missed.

## How it works

`main.py` (Python 3.13, standard library only, no network) copies the
committed `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`
(falling back to `/output/entry.png`). The copy is byte-for-byte, so two
runs always produce identical output.

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=x9vj0gh6&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
