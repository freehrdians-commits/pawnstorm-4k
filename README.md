# pawnstorm-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/freehrdians-commits/pawnstorm-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/freehrdians-commits/pawnstorm-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB chess engine in Python: alpha-beta search, quiescence, piece-square tables. It plays the make.fun tiny-chess-01 gauntlet.

## Engine

Null-move pruning, late move reductions, killer moves, tapered middlegame/endgame evaluation, and check evasions in quiescence. The readable source is packed with the kit's `makefun compress` (LZMA) into a 2,942-byte `main.py`. Verified locally: practice trial-0 Elo 1279 (3 wins, 0 draws, 3 losses), max think 2.4 s per move, deterministic.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=kssey7ph&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
