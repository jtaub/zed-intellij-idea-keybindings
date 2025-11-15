# IntelliJ IDEA Keybindings for Zed

<img src="https://zed.dev/_next/static/media/stable-app-logo.9b5f959f.png" height="32" style="vertical-align: middle;"> + 
<img src="https://resources.jetbrains.com/storage/products/company/brand/logos/IntelliJ_IDEA_icon.png" height="32" style="vertical-align: middle;"> = <span style="font-size: 32px; vertical-align: middle;">❤️</span>

This project contains a `keymap.json` file that you can copy-paste into Zed to enable the Intellij IDEA Linux keymap.

Zed technically already has a keymap for Intellij IDEA, but it's missing a huge amount of important keyboard shortcuts. This keymap aims to fill those gaps and provide a more complete experience for Zed users who are coming from a background in Jetbrains editors.

## How to Use

tl;dr: Copy-paste the contents of `keymap.json` into Zed.

1. In Zed, execute `zed: open keymap file` 
    1. (On my system, where I installed Zed using flatpak, this is opens `~/.var/app/dev.zed.Zed/config/zed/keymap.json`)
1. Copy-paste the contents of the `keymap.json` file in this repository into Zed.
1. Save.

## Known Limitations

### Missing Features
Generally speaking, this is missing a lot of useful shortcuts that rely on how good IntelliJ really is. Zed, is great, but the following are not and can not be supported:
- `ctrl-alt-m` is not mapped to "extract method"
- `ctrl-alt-v` is not mapped to "extract variable"
- `alt-delete` is not mapped to "safe delete"
- etc.

### Not yet supported

There are some features that are not yet supported in Zed but are possible to implement in the future:
- `alt-shift-insert` to toggle block selection mode is not supported, because Zed currently does not support block selection mode.


## See also

- [Zed Keybindings documentation](https://zed.dev/docs/key-bindings)
- [Jetbrains Mastering Keyboard shortcuts](https://www.jetbrains.com/help/idea/mastering-keyboard-shortcuts.html)
- Inspired by the [Intellij IDEA keybindings for VSCode plugin](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings)
