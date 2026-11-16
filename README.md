# tiny-chess-engine

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/GH-JY/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/GH-JY/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A 4,096-byte chess engine in Python 3.13 for the [tiny-chess-01](https://make.fun/bounty/tiny-chess-01) bounty: a 0x88 board, alpha-beta with PVS, a transposition table, killer/history ordering, captures-only quiescence with check extension and piece-square evaluation, searched to a fixed node budget so every replay plays the same moves.

`main.py` is the whole entry (packed, 4,068 bytes). Run it against the trial env:

    MAKEFUN_ENV_URL=<env> python main.py

MIT licensed.
