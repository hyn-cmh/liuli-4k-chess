# liuli-4k-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/hyn-cmh/liuli-4k-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/hyn-cmh/liuli-4k-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Liuli 4K is a chess engine in 4,091 bytes of Python: negamax alpha-beta with a transposition table, quiescence search, null-move pruning and late move reductions over a 120-square mailbox board, with an incrementally kept tapered piece-square evaluation. It spends a fixed node budget per move and never reads the clock, so its games replay exactly.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> MAKEFUN_PROMPT_FILE=<prompt.txt> python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=1pk8yq3w&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
