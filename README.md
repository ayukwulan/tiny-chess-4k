# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/ayukwulan/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/ayukwulan/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4,086-byte Python chess engine with SEE (static exchange evaluation) pruning in quiescence search. Trial-0 Elo 1396 — beats the Round 3 entry (Elo 1253). It plays the make.fun gauntlet of eight house engines, talking to the env at MAKEFUN_ENV_URL and sending moves in UCI.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8771 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=nax&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
