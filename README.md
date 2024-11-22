# keymapper
Simple python script using [keyboard](https://github.com/boppreh/keyboard/) python library, that creates layers of key maps to keyboard using a modifier hotkey.

See this [article](https://dreymar.colemak.org/layers-extend.html) and [this one](https://getreuer.info/posts/keyboards/symbol-layer/index.html) for more explanation and showcase of common layer presets (Which I plan to add in the future).

## Modifier hotkey types
**Note**: a hotkey can be composed of one or more keys

Modifier hotkeys can activate a layer using one of three types: switch, lock or latch.

### Switch
Acts like shift or ctrl keys, where you hold down to open an extension layer.

### Lock
Acts like the caps lock key, lock and unlock the extend layer.

### Latch
(Currently I don't plan to implement this type)
Press and release the modifier hotkey so the next mapped key press' is a part of the extend layer.