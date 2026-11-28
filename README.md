# DATA CULT

Cynthia's Gauntlet — final submission (V12).

## Files

- `team.json` — six Pokémon and their legal moves (40/40 points).
- `policy.py` — custom battle policy.

## Website practice benchmarks

| Configuration | Battles | Wins | Losses | Win rate |
| --- | ---: | ---: | ---: | ---: |
| Custom policy, run 1 | 1,000 | 985 | 15 | 98.5% |
| Custom policy, run 2 | 1,000 | 987 | 13 | 98.7% |
| **Custom policy, combined** | **2,000** | **1,972** | **28** | **98.6%** |
| Organizer's default policy | 250 | 139 | 111 | 55.6% |

The two modes may use different opponent lineups and seeds, so this is not a controlled comparison of policy strength. Hidden-variant tournament results are unverified.

[Official simulator](https://cynthias-gauntlet.onrender.com/)
