# vscode-settings
Collection of useful tweaks to VSCode settings.

## Settings
Settings are stored in `File > Preferences > Keyboard Shortcuts`
* `editor.copyWithSyntaxHighlighting`:`false` - disable rich text copying. This causes different behaviour in different programs. Some copy plain text some HTML formatted. For example Google Sheets now pastes without text formatting (color, font, fontsize). 
* `workbench.tree.indent`: 12 - sane file tree explorer indentation size [link](https://stackoverflow.com/questions/55310734/how-to-add-more-indentation-in-the-visual-studio-code-explorer-file-tree-structu).

## Keybinds
Keybinding are stored in `File > Preferences > Settings`.

Rebind these:
* `copyLinesDownAction` rebind to `ctrl+d` - simple selected lines duplication keybind
* `editor.action.startFindReplaceAction` rebind to `ctrl+r` - simple replace kebind
* `workbench.action.findInFiles`, `actions.find` - unbind them and bind these instead `workbench.action.replaceInFiles` to `ctrl+shift+f` and `editor.action.startFindReplaceAction` to `ctrl+f`. Finding is just a subset of replacing.

## Tips
Default keybindings cheat sheet from [VSCode get started](https://code.visualstudio.com/docs/getstarted/tips-and-tricks#vscode):
![KeyboardReferenceSheet](https://user-images.githubusercontent.com/72770213/176055799-c3b4c7d1-0746-4f9d-8f47-91a6f7ee8721.png)
