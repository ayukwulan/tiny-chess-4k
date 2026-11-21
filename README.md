# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/ayukwulan/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/ayukwulan/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4,086-byte Python chess engine that squeezes a full search into the 4 KB limit: alpha-beta with SEE pruning inside quiescence search, so losing captures get thrown out before they waste nodes. It scored Elo 1396 on trial-0 against the eight house engines — a clear step up from the Round 3 entry at 1253 — and talks to the trial environment through MAKEFUN_ENV_URL, sending its moves in UCI.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8771 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=nax&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
