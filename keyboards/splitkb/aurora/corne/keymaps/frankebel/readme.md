# Custom keymap.

My custom keymap which is heavily inspired by [Miryoku](https://github.com/manna-harbour/miryoku).
Some differences are:

- Number, Symbol, and Function layer are right-hand layers
- arrows are above `WASD`
- modifier order is `Alt`, `Ctrl`, `Shift`, `Super`

## Features

- [Miryoku](https://github.com/manna-harbour/miryoku) based
- [home row mods](https://precondition.github.io/home-row-mods)
- [mod-tap](https://docs.qmk.fm/#/mod_tap)
- [caps word](https://docs.qmk.fm/#/feature_caps_word)
- multiple layers with Colemak as base
- RALT layer for Umlaute, ß, €

## LAYERS

### Colemak

Base layer is Colemak with homerow mods.
`'` replaces `;` at the top right.
As I use a [tiling Wayland Compositor](https://hyprland.org),
my most used modifiers (`Shift`, `Super`) are on my strongest fingers.
`Ralt` is below the home row to be able to hold `hjkl` in vim.

![Colemak](https://user-images.githubusercontent.com/40893015/260296772-14d46a9f-8ef5-41b3-9aef-a1b6cc9f5179.png)

### Number

Numbers are arranged like a numpad with symbols in the remaining positions.

![Number](https://user-images.githubusercontent.com/40893015/266827310-1d118f2d-b973-44d7-8470-ccecb7fb05ee.png)

### Symbol

Symbols are in the same location as shifted numbers.

![SYMBOL](https://user-images.githubusercontent.com/40893015/266827373-7017edab-c424-40ea-9ff7-d8ef0e1c20f6.png)

### Function

`F1` to `F9` are arranged as the number layer with `F10` to `F12` to the left and system keys on the right.

![FUNCTION](https://user-images.githubusercontent.com/40893015/260296856-bcac5296-398a-4f3e-8ca2-611e5cc966d8.png)

### Navigation

Arrow keys at the same location as `WASD` with navigation keys below.

![NAVIGATION](https://user-images.githubusercontent.com/40893015/260296994-501e5fd0-f086-431d-8f82-a9e426593dba.png)

### Media

This layer includes brightness and volume control.
The `micmute` key sends `Super` + `/` which is configured to toggle the microphone
in my Wayland Compositor.

![MEDIA](https://user-images.githubusercontent.com/40893015/260296975-b6a6955c-1592-4393-8189-db0076a1632e.png)

### Layer

Switch default layer to the selected.
Locations are mnemonic:

- `A` for `Arrow`
- `C` for `Colemak`
- `Q` for `QWERTY`

![LAYER](https://user-images.githubusercontent.com/40893015/266827250-dc209596-2263-4d02-b9dc-f9c9ede1e5c3.png)

### Ralt

Custom Right-Alt layer for german letters and €-Symbol. Assumes US-International keyboard.

![RALT](https://user-images.githubusercontent.com/40893015/260297048-dab805b8-101e-491c-a41e-1ca0576491b4.png)

### Arrow

Dedicated arrow layer above `WASD`.

![ARROW](https://user-images.githubusercontent.com/40893015/266825006-6c9e75cb-020f-4d6c-b20c-0f3b1db3e885.png)
