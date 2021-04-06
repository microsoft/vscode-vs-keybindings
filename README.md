# Visual Studio Keymap for Visual Studio Code

This extension ports popular Visual Studio keyboard shortcuts to Visual Studio Code. After installing the extension and restarting VS Code your favorite keyboard shortcuts from Visual Studio are now available. 

## What keyboard shortcuts are included?

| Command | macOS | Windows | Linux |
| :------ | :---- | :------ | :---- |
| `workbench.action.tasks.build` | `ctrl+shift+b`  | `ctrl+shift+b` | `ctrl+shift+b` ||
| `workbench.debug.viewlet.action.addFunctionBreakpointAction` | `ctrl+b`  | `ctrl+b` | `ctrl+b` ||
| `workbench.debug.viewlet.action.removeAllBreakpoints` | `ctrl+shift+f9`  | `ctrl+shift+f9` | `ctrl+shift+f9` |
| `workbench.action.debug.restart` | `ctrl+shift+f5`  | `ctrl+shift+f5` | `ctrl+shift+f5` |
| `editor.debug.action.runToCursor` | `ctrl+f10`  | `ctrl+f10` | `ctrl+f10` |
| `editor.action.formatDocument` | `ctrl+k ctrl+d`  | `ctrl+k ctrl+d` | `ctrl+k ctrl+d` |
| `insertSnippet` | `ctrl+k ctrl+x`  | `ctrl+k ctrl+x` | `ctrl+k ctrl+x` |
| `editor.action.deleteLines` | `ctrl+shift+l`  | `ctrl+shift+l` | `ctrl+shift+l` |
| `editor.action.clipboardCutAction` | `ctrl+l`  | `ctrl+l` | `ctrl+l` |
| `workbench.action.files.openFileFolder` | `ctrl+shift+g`  | `ctrl+shift+g` | `ctrl+shift+g` |
| `editor.action.referenceSearch.trigger` | `alt+f12`  | `alt+f12` | `alt+f12` |
| `redo` | `ctrl+y`  | `ctrl+y` | `ctrl+y` |
| `editor.action.smartSelect.expand` | `ctrl+w`  | `ctrl+w` | `ctrl+w` |
| `editor.action.addSelectionToNextFindMatch` | `shift+alt+.`  | `shift+alt+.` | `shift+alt+.` |
| `editor.action.triggerSuggest` | `ctrl+alt+space`  | `ctrl+alt+space` | `ctrl+alt+space` |
| `undo` | `alt+space`  | `alt+space` | `alt+space` |
| `deleteWordEndRight` | `ctrl+delete`  | `ctrl+delete` | `ctrl+delete` |
| `deleteWordStartLeft` | `ctrl+backspace`  | `ctrl+backspace` | `ctrl+backspace` |
| `workbench.action.files.saveAll` | `ctrl+shift+s`  | `ctrl+shift+s` | `ctrl+shift+s` |
| `workbench.action.output.toggleOutput` | `ctrl+alt+o`  | `ctrl+alt+o` | `ctrl+alt+o` |
| `workbench.view.explorer` | `ctrl+alt+l`  | `ctrl+alt+l` | `ctrl+alt+l` |
| `editor.action.rename` | `ctrl+r ctrl+r`  | `ctrl+r ctrl+r` | `ctrl+r ctrl+r` |
| `editor.action.toggleRenderWhitespace` | `ctrl+r ctrl+w`  | `ctrl+r ctrl+w` | `ctrl+r ctrl+w` |
| `editor.foldAll` | `ctrl+k ctrl+m`  | `ctrl+k ctrl+m` | `ctrl+k ctrl+m` |
| `workbench.action.navigateBack` | `ctrl+-`  | `ctrl+-` | `ctrl+-` |
| `workbench.action.navigateForward` | `ctrl+shift+-`  | `ctrl+shift+-` | `ctrl+shift+-` |
| `workbench.action.quickOpen` | `ctrl+,`  | `ctrl+,` | `ctrl+,` |
| `cursorColumnSelectDown` | `shift+alt+down`  | `shift+alt+down` | `shift+alt+down` |
| `cursorColumnSelectLeft` | `shift+alt+left`  | `shift+alt+left` | `shift+alt+left` |
| `cursorColumnSelectPageDown` | `shift+alt+pagedown`  | `shift+alt+pagedown` | `shift+alt+pagedown` |
| `cursorColumnSelectPageUp` | `shift+alt+pageup`  | `shift+alt+pageup` | `shift+alt+pageup` |
| `cursorColumnSelectRight` | `shift+alt+right`  | `shift+alt+right` | `shift+alt+right` |
| `cursorColumnSelectUp` | `shift+alt+up`  | `shift+alt+up` | `shift+alt+up` |
| `workbench.action.toggleZenMode` | `shift+alt+enter`  | `shift+alt+enter` | `shift+alt+enter` |
| `workbench.action.closeActiveEditor` | `ctrl+f4`  | `ctrl+f4` | `ctrl+f4` |
| `editor.action.copyLinesDownAction` | `ctrl+d`  | `ctrl+d` | `ctrl+d` |
| `cursorWordStartRight` | `ctrl+right`  | `ctrl+right` | `ctrl+right` |
| `cursorWordStartRightSelect` | `ctrl+shift+right`  | `ctrl+shift+right` | `ctrl+shift+right` |
| `editor.action.insertLineBefore` | `ctrl+enter`  | `ctrl+enter` | `ctrl+enter` |
| `editor.action.insertLineAfter` | `shift+enter`  | `shift+enter` | `shift+enter` |
| `editor.action.wordHighlight.next` | `ctrl+shift+down`  | `ctrl+shift+down` | `ctrl+shift+down` |
| `editor.action.wordHighlight.prev` | `ctrl+shift+up`  | `ctrl+shift+up` | `ctrl+shift+up` |
| `editor.action.replaceAll` | `alt+a`  | `alt+a` | `alt+a` |
| `search.action.replaceAll` | `alt+a`  | `alt+a` | `alt+a` |
| `search.action.replaceAllInFile` | `alt+a`  | `alt+a` | `alt+a` |
| `search.action.replaceAllInFolder` | `alt+a`  | `alt+a` | `alt+a` |
| `editor.action.replaceOne` | `alt+r`  | `alt+r` | `alt+r` |
| `search.action.replace` | `alt+r`  | `alt+r` | `alt+r` |
| `toggleSearchRegex` | `alt+e`  | `alt+e` | `alt+e` |
| `toggleFindRegex` | `alt+e`  | `alt+e` | `alt+e` |
| `deleteWordStartRight` | `ctrl+delete`  | `ctrl+delete` | `ctrl+delete` |

The full list of keyboard shortcuts including the `when` clause (e.g. while debugging) can be found in the extension's [contribution list](https://github.com/microsoft/vscode-vs-keybindings/blob/bf87aaa88a7e50e4c316ce3f4fe703c4443366ce/package.json#L26). 

## Why don't all the keyboard shortcuts work? 

VS Code does not implement all of the commands available in Visual Studio. If you would like to see a feature in VS Code that is in Visual Studio, please open an [issue on GitHub](https://github.com/Microsoft/vscode/issues/new). 

## How do I contribute a keyboard shortcut?

We may have missed a keyboard shortcut. If we did please help us out! It is very easy to make a PR. 

1. Head over to our [GitHub repository](https://github.com/Microsoft/vscode-vs-keybindings). 
2. Open [`package.json`](https://github.com/Microsoft/vscode-vs-keybindings/blob/main/package.json). 
3. Add a JSON object to [`contributes.keybindings`](https://github.com/Microsoft/vscode-vs-keybindings/blob/main/package.json#L26) as seen below. 
4. Open a pull request. 

```json
{
    "mac": "<keyboard shortcut for mac>",
    "linux": "<keyboard shortcut for linux",
    "win": "<keyboard shortcut for windows",
    "key": "<default keyboard shortcut>",
    "command": "<name of the command in VS Code"
}
```

You can read more about how to contribute keybindings in extensions in the [official documentation](http://code.visualstudio.com/docs/extensionAPI/extension-points#_contributeskeybindings). 
