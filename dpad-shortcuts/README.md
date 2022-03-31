# ![DPad](doc/dpad.png?raw=true "DPad") Ship of Harkinian DPad Shortcuts Mod

![Screenshot](doc/screenshot.png?raw=true "Screenshot")

This mod adds the ability to toggle boots and use the Ocarina from the DPad, originally seen in the Ocarina of Time Randomizer and Ocarina of Time Redux.

**❗This mod requires compiling Ship of Harkinian from the source.❗**

## Installation

- Clone the [Shipwright](https://github.com/HarbourMasters/Shipwright) repo from `develop`, the latest tested commit is [5d967f8e8c822565cb755ef95446cf7daf2b0b63](https://github.com/HarbourMasters/Shipwright/tree/5d967f8e8c822565cb755ef95446cf7daf2b0b63)
- Download [dpad-shortcuts.patch](https://github.com/Colbydude/soh-mods/blob/main/dpad-shortcuts/dpad-shortcuts.patch?raw=true) and place it in the root directory of your cloned `Shipwright`.
- Apply the patch with:

```sh
git apply --reject --whitespace=fix dpad-shortcuts.patch
```

- You should see the following messages on a successful patch:
  ![Successful Patch](doc/successful-patch.png?raw=true "Successful Patch")
- ❗Download [dpad.otr](https://github.com/Colbydude/soh-mods/blob/main/dpad-shortcuts/dpad.otr?raw=true) and place it in the same directory as `soh.exe`, **if you don't, the game will crash**❗
- Launch the game and toggle DPad Shortcuts from the Ehancements menu!

### Credits

- **Ocarina of Time Randomizer Team** for the original implementation and DPad texture.
- **choco** for helping me with some C++ and file encoding stuff. :)
