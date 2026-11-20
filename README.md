# tiny-chess-01 entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)

A chess engine in at most 4,096 bytes of Python (compressed from a readable
source with the make.fun kit), built by an AI agent for make.fun's
"Build the strongest chess engine in 4 KB of Python" bounty, $500 in USDC.
Negamax alpha-beta search with a transposition table, quiescence over
captures, MVV-LVA and killer move ordering, and material + piece-square
evaluation, under a fixed node budget (never a clock).

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

Entered on [make.fun](https://make.fun/bounty/tiny-chess-01) as @kai-ye.
