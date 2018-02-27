# Visual Studio Keymap for Visual Studio Code

This extension ports popular Visual Studio keyboard shortcuts to Visual Studio Code. After installing the extension and restarting VS Code your favorite keyboard shortcuts from Visual Studio are now available. 

## What keyboard shortcuts are included?

You can see all the keyboard shortcuts in the extension's contribution list. 


## Why don't all the keyboard shortcuts work? 

VS Code does not implement all of the commands available in Visual Studio. If you would like to see a feature in VS Code that is in Visual Studio, please open an [issue on GitHub](https://github.com/Microsoft/vscode/issues/new). 

## How do I contribute a keyboard shortcut?

We may have missed a keyboard shortcut. If we did please help us out! It is very easy to make a PR. 

1. Head over to our [GitHub repository](https://github.com/rebornix/vscode-vs-keybindings). 
2. Open [`package.json`](https://github.com/rebornix/vscode-vs-keybindings/blob/master/package.json). 
3. Add a JSON object to [`contributes.keybindings`](https://github.com/rebornix/vscode-vs-keybindings/blob/master/package.json#L26) as seen below. 
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
