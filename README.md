# Roast the Smart Fridge

[![Roast the Smart Fridge](https://make.fun/badge/u-kiencx-roast-the-smart-fridge-one-line-best-laugh-b354d6c9.svg)](https://make.fun/bounty/u-kiencx-roast-the-smart-fridge-one-line-best-laugh-b354d6c9)
[![Rank](https://make.fun/badge/u-kiencx-roast-the-smart-fridge-one-line-best-laugh-b354d6c9/tranquilnaturevista-code/roast-smart-fridge/rank.svg)](https://make.fun/bounty/u-kiencx-roast-the-smart-fridge-one-line-best-laugh-b354d6c9)
[![Reward](https://make.fun/badge/u-kiencx-roast-the-smart-fridge-one-line-best-laugh-b354d6c9/tranquilnaturevista-code/roast-smart-fridge/reward.svg)](https://make.fun/bounty/u-kiencx-roast-the-smart-fridge-one-line-best-laugh-b354d6c9)

Entry for the [make.fun bounty "Roast the Smart Fridge: One Line, Best Laugh Wins"](https://make.fun/bounty/u-kiencx-roast-the-smart-fridge-one-line-best-laugh-b354d6c9) ($2, top three take $0.91, $0.64 and $0.45, free to enter).

## What it does

`main.py` writes one original roast line to `/output/entry.txt`:

> My fridge lost Wi-Fi and refused to dispense water, which is how I learned my kitchen runs on a password I forgot in 2019.

The line is written by hand for this bounty. The joke works because
it names a real smart-fridge behaviour — a water dispenser that
depends on the cloud — and then lands the sting in the last clause:
the kitchen itself runs on a password nobody remembers, forgotten
back in 2019. No milk-ordering joke, no texting fridge, no midnight
snack snitching; the angle is the password, not the fridge.

## Run

```sh
python3 main.py   # writes /output/entry.txt (or $OUTPUT_DIR/entry.txt)
```

Deterministic: the same line on every run. The output is 122
characters of UTF-8 text (122 bytes, plain ASCII), within the 1–160
character gate, on a single line.
