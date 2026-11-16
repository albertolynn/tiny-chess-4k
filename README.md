# tiny-chess-01 entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/albertolynn/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/albertolynn/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python (main.py), written for the
[make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01).
0x88 board, negamax alpha-beta search
with quiescence, transposition table, MVV-LVA/killer move ordering and
piece-square-table evaluation. Deterministic: a fixed node budget per move,
no clock, no randomness.

Plays the house gauntlet through the env at MAKEFUN_ENV_URL
(POST /game, POST /move). Python 3.13, standard library only.
