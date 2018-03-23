# karabiner-windows-mode
Karabiner-Elements complex ruleset to make using Mac OS more sane by enabling common keyboard functionality used in Linux and Windows.

## Installation
Copy and paste the following URL into your browser window and Karabiner-Elements *should* ask to install the file:

    karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/rux616/karabiner-windows-mode/master/windows_shortcuts.json

## List of Shortcuts
First, a note about how these shortcuts are named in Karabiner-Elements. They follow the convention

    Key (Modifiers, if any) [Special notes, if any]

so they should be easy(ish) to understand. Contact me if you have improvement suggestions.

| Input Key | Input Modifier(s) | Output Key | Output Modifier(s) | Notes |
|-|-|-|-|-|
| Home | Ctrl+Shift | Up Arrow | Command+Shift |  |
| Home | Ctrl | Up Arrow | Command |  |
| Home | Shift | Left Arrow | Command+Shift |  |
| Home |  | Left Arrow | Command | Does not apply to Terminal/iTerm2, as they already handle the key correctly. |
| End | Ctrl+Shift | Down Arrow | Command+Shift |  |
| End | Ctrl | Down Arrow | Command |  |
| End | Shift | Right Arrow | Command+Shift |  |
| End |  | Right Arrow | Command | Does not apply to Terminal/iTerm2, as they already handle the key correctly. |
| Left Arrow | Ctrl | Left Arrow | Option |  |
| Left Arrow | Ctrl+Shift | Left Arrow | Option+Shift |  |
| Right Arrow | Ctrl | Right Arrow | Option |  |
| Right Arrow | Ctrl+Shift | Right Arrow | Option+Shift |  |
| Backspace | Ctrl | Backspace | Option |  |
| Delete | Ctrl | Delete | Option |  |
| A | Ctrl | A | Command |  |
| B | Ctrl | B | Command |  |
| C | Ctrl | C | Command | Does not apply to Terminal/iTerm2 as it is an important command sequence and shouldn't get altered. |
| C | Ctrl+Shift | C | Command | Only applies to Terminal/iTerm2. |
| F | Ctrl | F | Command |  |
| F1 |  | / | Command+Shift |  |
| F3 |  | G | Command |  |
| I | Ctrl | I | Command |  |
| N | Ctrl | N | Command |  |
| O | Ctrl | O | Command |  |
| P | Ctrl | P | Command |  |
| S | Ctrl | S | Command |  |
| / | Ctrl | / | Command |  |
| T | Ctrl | T | Command |  |
| U | Ctrl | U | Command |  |
| V | Ctrl | V | Command |  |
| V | Ctrl+Shift | V | Command | Only applies to Terminal/iTerm2. |
| X | Ctrl | X | Command |  |
| Y | Ctrl | Y | Command |  |
| Z | Ctrl | Z | Command | Does not apply to Terminal/iTerm2 as it is an important command sequence and shouldn't get altered. |

## Credits
- [@TechnicallyDifficult](https://github.com/TechnicallyDifficult) for coming up with the initial json file
- [@alvaro1728](https://github.com/alvaro1728) for creating the current json file and for [asking the question](https://github.com/tekezo/Karabiner-Elements/issues/249) that got this whole thing started
- [@tezeko](https://github.com/tekezo) for Karabiner-Elements

## Links
- Karabiner-Elements [(Homepage)](https://pqrs.org/osx/karabiner/) [(GitHub)](https://github.com/tekezo/Karabiner-Elements)