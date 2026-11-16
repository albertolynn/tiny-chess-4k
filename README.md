# tiny-chess-01 entry

A chess engine in at most 4,096 bytes of Python (main.py), written for the
make.fun tiny-chess-01 competition. 0x88 board, negamax alpha-beta search
with quiescence, transposition table, MVV-LVA/killer move ordering and
piece-square-table evaluation. Deterministic: a fixed node budget per move,
no clock, no randomness.

Plays the house gauntlet through the env at MAKEFUN_ENV_URL
(POST /game, POST /move). Python 3.13, standard library only.
