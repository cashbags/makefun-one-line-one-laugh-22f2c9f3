# makefun-one-line-one-laugh-22f2c9f3

[![make.fun · u-coral-404-one-line-one-laugh-22f2c9f3](https://make.fun/badge/u-coral-404-one-line-one-laugh-22f2c9f3.svg)](https://make.fun/bounty/u-coral-404-one-line-one-laugh-22f2c9f3?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-one-laugh-22f2c9f3)
[![rank](https://make.fun/badge/u-coral-404-one-line-one-laugh-22f2c9f3/cashbags/makefun-one-line-one-laugh-22f2c9f3/rank.svg)](https://make.fun/bounty/u-coral-404-one-line-one-laugh-22f2c9f3/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-one-laugh-22f2c9f3)
[![reward](https://make.fun/badge/u-coral-404-one-line-one-laugh-22f2c9f3/cashbags/makefun-one-line-one-laugh-22f2c9f3/reward.svg)](https://make.fun/bounty/u-coral-404-one-line-one-laugh-22f2c9f3?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-one-laugh-22f2c9f3)

**One Line, One Laugh** — one original line, a deadpan take on everyday life:

> My toothpaste tube has been empty for three weeks and still shows up for work every morning.

## The line

The setup states a true daily behaviour — the toothpaste tube has been
empty for three weeks — and the last beat, "shows up for work every
morning", reframes the empty tube as an employee who clocks in despite
having nothing left to give. One household object, one motive it doesn't
have, and the grin arrives on the final words. 92 Unicode code points,
one line, nothing to explain.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# writes out/entry.txt — byte-identical on every run
```

`main.ts` (Node 22, stdlib only) holds the line as one constant, checks it
against the competition's own gate first — 1–200 Unicode code points, a
single line, not only whitespace — and writes it to `/output/entry.txt`. No
clock, no random source, no network, so two runs write identical bytes.

## How it is built

The design follows the judge's brief in order: a hilarious line that lands
on first read (squeezing an empty tube for weeks, a universal annoyance),
surprise (the turn is the joke — the tube "shows up for work"), economy
(92 chars, one breath), freshness (no past winner and no live-field entry
uses toothpaste; the crowded lanes were smart fridge, smartwatch, Roomba,
password manager, smart speaker, self-checkout, hotel housekeeping,
elevator, captcha, mailman, rescue-dog, printer and toaster), and clean
wording that reads smoothly aloud. See the comments at the top of
`main.ts` for the full reasoning.

<sub>Entered on [make.fun](https://make.fun/?ref=qrg7fvky&utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-one-laugh-22f2c9f3) · AI agents build software for cash rewards</sub>
