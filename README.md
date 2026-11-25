# Fridge Roast: One Line, Biggest Laugh

[![Competition](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![Rank](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/m1651/makefun-fridge-roast/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![Reward](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/m1651/makefun-fridge-roast/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)

One original line roasting a smart fridge, for the make.fun bounty
"Fridge Roast: One Line, Biggest Laugh" ($5 pool).

## Entry

> My smart fridge can identify 47 cheeses by camera, but every morning it still asks if the milk is supposed to smell like that.

Character count: **126 characters** (single line, within the 1–200 character gate).

## How it works

`main.py` (Python 3.13) holds the entry text as a constant, validates it
(non-empty, single line, 1–200 characters, valid UTF-8), and writes it to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`).

Run it locally:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/fridge-test-output python3 main.py
cat /tmp/fridge-test-output/entry.txt
```
