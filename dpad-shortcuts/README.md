# ![DPad](doc/dpad.png?raw=true "DPad") Ship of Harkinian DPad Shortcuts Mod

![Screenshot](doc/screenshot.png?raw=true "Screenshot")

This mod adds the ability to toggle boots and use the Ocarina from the DPad, originally seen in the Ocarina of Time Randomizer and Ocarina of Time Redux.

**❗This mod requires compiling Ship of Harkinian from the source.❗**

## Installation

- Clone the [Shipwright](https://github.com/HarbourMasters/Shipwright) repo from `develop`, the latest tested commit is [ac2127094b0ba1d2c99850a32eb8fe1cd5003055](https://github.com/HarbourMasters/Shipwright/tree/ac2127094b0ba1d2c99850a32eb8fe1cd5003055)
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
