# SuperMacro (Turtle / SuperWoW)

**Maintained fork:** [leenux/SuperMacro](https://github.com/leenux/SuperMacro)

Compatible with **World of Warcraft 1.12.1** and **Turtle WoW 1.18.1** (Interface `11200`).

Based on the Turtle / SuperWoW SuperMacro line (FindBuff caps, 511-character macros with SuperWoW, Horu UI, etc.). **Use with [SuperWoW](https://github.com/balakethelock/SuperWoW).**

Full historical notes remain in [`readme.txt`](readme.txt).

## leenux changes

- **Per-character Super macros:** `SM_SUPER`, `SM_EXTEND`, and Super action-bar mappings are stored per character (`SM_C_*` via `SavedVariablesPerCharacter`), so each character keeps its own Super / Extend data.
- **Account-wide UI options:** `SM_VARS` (font size, window size, minimap button, …) stays account-wide.
- **One-time migration:** on first login after upgrade, data is copied from the old account `SavedVariables` into the current character (never overwrites character data that already exists).

See the *SavedVariables layout* section in [`readme.txt`](readme.txt) for paths and details.

## Install

1. Install **SuperWoW**.
2. Download from [leenux/SuperMacro](https://github.com/leenux/SuperMacro), rename the folder to `SuperMacro`.
3. Copy to `World of Warcraft\Interface\AddOns\SuperMacro`.
4. Restart the game.

Related: [leenux/SuperCleveRoidMacros](https://github.com/leenux/SuperCleveRoidMacros), [leenux/SuperMate](https://github.com/leenux/SuperMate).
