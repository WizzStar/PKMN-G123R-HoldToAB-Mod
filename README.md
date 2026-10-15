# G123R HoldToAB Mod

Hold **A** or **B** to auto-advance text in Gen 1, Gen 2 and Gen 3.

## Features

- **Text**: hold A or B on dialogue and battle text.
- **Boot**: hold A from launch to go straight into CONTINUE (no save: NEW GAME, stops at the first choice). Hold B to skip only the intro.
- **Save**: hold A after SAVE to answer YES and save.
- **Nurse**: hold A on the Pokémon Center nurse to heal.
- **Battle** *(off by default)*: hold A to keep picking FIGHT + the highlighted move.

HOLD DELAY and REPEAT SPEED run on real time, so fast-forward never speeds the repeat up.

Turbo stops on every other YES/NO, menus, the overworld and minigames, and while START or SELECT is held (soft reset works). Prompts are only answered while YES / HEAL is highlighted.

## Options

| Option | Default |
|---|---|
| TURBO A/B · TURBO A · TURBO B | ON |
| TURBO BOOT · TURBO SAVE · TURBO NURSE | ON |
| TURBO BATTLE | OFF |
| HOLD DELAY | 16 frames |
| REPEAT SPEED | 3 (1 slow – 5 fast) |

## For mod authors

Opt a screen out with `state.noTurboAB = true`, or call `exports.denyScreen(id)` / `exports.allowScreen(id)`.
