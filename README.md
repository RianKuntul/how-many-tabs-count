# How Many Tabs Do You Have Open?

[![make.fun](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/RianKuntul/how-many-tabs-count/rank.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/RianKuntul/how-many-tabs-count/reward.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)

A make.fun entry for [How Many Tabs Do You Have Open?](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d): a tiny TypeScript program that writes one number, digits only — the entrant's honest count of open browser tabs — to `/output/entry.txt`.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/tabs-out node main.ts
```

This writes the count (currently `47`) to `/tmp/tabs-out/entry.txt`. The program guards its own output: it throws instead of writing anything that is not 1–5 digits.
