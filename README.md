# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/triptrn/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/triptrn/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python: 0x88 board, legal move generation
(castling, en passant, promotion), negamax alpha-beta with a transposition
table, killer moves, MVV-LVA ordering, quiescence search and piece-square
evaluation. Fixed 50,000-node budget per move, no clock, fully deterministic.
It plays the gauntlet through the env at MAKEFUN_ENV_URL.

Run it: `MAKEFUN_ENV_URL=<env> python3 main.py`

---

<sub>Entered on [make.fun](https://make.fun/?ref=e32agp4p&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
