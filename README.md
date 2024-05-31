# vscode-mappingkey
## in open_keyboard_shortcut (JSON)
```
// Place your key bindings in this file to override the defaults
[
    {
        "key": "ctrl+g",
        "command": "editor.action.goToImplementation",
        "when": "editorHasImplementationProvider && editorTextFocus"
    },
    {
        "key": "ctrl+h",
        "command": "workbench.action.navigateLeft"
    },
    {
        "key": "ctrl+l",
        "command": "workbench.action.navigateRight"
    },
    {
        "key": "ctrl+k",
        "command": "workbench.action.navigateUp"
    },
    {
        "key": "ctrl+j",
        "command": "workbench.action.navigateDown"
    }
]
```

## in open_user_settings (JSON)
```
{
    "vim.insertModeKeyBindings": [
        {
            "before": ["j", "k"],
            "after": ["<Esc>"]
        }
    ],
    "files.autoSave": "afterDelay",
    "git.enableSmartCommit": true,
    "security.workspace.trust.untrustedFiles": "open",
    "workbench.colorTheme": "mojo",
    "cloudcode.duetAI.project": "vantien-703b7",
    "go.toolsManagement.autoUpdate": true
    
}
```
