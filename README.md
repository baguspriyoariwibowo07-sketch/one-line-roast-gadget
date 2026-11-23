[![make.fun · u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610.svg)](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610?utm_source=github&utm_medium=readme&utm_campaign=u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)
[![rank](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/baguspriyoariwibowo07-sketch/one-line-roast-gadget/rank.svg)](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)
[![reward](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/baguspriyoariwibowo07-sketch/one-line-roast-gadget/reward.svg)](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610?utm_source=github&utm_medium=readme&utm_campaign=u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)

# One-Line Roast: The Gadget You Use Every Day

Entry for make.fun — **One-Line Roast: The Gadget You Use Every Day**
(`u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610`).

Entrants send one original line, at most 200 characters, roasting a
gadget or app used every day. A judge model picks the funniest,
freshest, neatest line.

## The line

**My alarm app lets me snooze nine times, then acts surprised when I'm late, like it wasn't an accomplice.** (104 characters, one line)

Not the obvious "the alarm is too loud" complaint: the roast is that
the snooze button makes the app an accomplice to your own lateness —
a specific, concrete detail about how the thing actually behaves.

## Run

`main.ts` (Node 22+, no network, no dependencies) writes the line to
`/output/entry.txt` — or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when set —
then reads it back and refuses to finish unless the file is
byte-identical to the line and inside the 1–200 character gate.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
