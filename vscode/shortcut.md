<!-- Adapt depending on Mac or linux/windows with ctrl or cmd -->

🐧 Linux User
```json
// Place your key bindings in this file to override the defaultsauto[]
[
    {
        "key": "ctrl+p",
        "command": "workbench.action.quickOpen"
    },
    {
        "key": "ctrl+e",
        "command": "-workbench.action.quickOpen"
    },
    {
        "key": "ctrl+e",
        "command": "editor.action.deleteLines",
        "when": "textInputFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+k",
        "command": "-editor.action.deleteLines",
        "when": "textInputFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+down",
        "command": "editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+alt+down",
        "command": "-editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+up",
        "command": "editor.action.copyLinesUpAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+alt+up",
        "command": "-editor.action.copyLinesUpAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+meta+w",
        "command": "workbench.action.closeOtherEditors"
    },
    {
        "key": "tab",
        "command": "editor.action.indentLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+f2",
        "command": "editor.action.rename",
        "when": "editorHasRenameProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "f2",
        "command": "-editor.action.rename",
        "when": "editorHasRenameProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+f2",
        "command": "editor.action.changeAll",
        "when": "editorTextFocus && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+f2",
        "command": "-editor.action.changeAll",
        "when": "editorTextFocus && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+meta+s",
        "command": "workbench.action.files.saveAll"
	},
	{
		"key": "f1",
		"command": "workbench.action.navigateBack"
	},
	{
		"key": "ctrl+alt+-",
		"command": "-workbench.action.navigateBack"
	},
	{
		"key": "f2",
		"command": "workbench.action.navigateForward"
	},
	{
		"key": "ctrl+shift+-",
		"command": "-workbench.action.navigateForward"
	},
	{
		"key": "f3",
		"command": "workbench.action.navigateToLastEditLocation"
	},
	{
		"key": "ctrl+k ctrl+q",
		"command": "-workbench.action.navigateToLastEditLocation"
    },
    {
        "key": "alt+right",
        "command": "editor.action.insertCursorAtEndOfEachLineSelected",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+i",
        "command": "-editor.action.insertCursorAtEndOfEachLineSelected",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+left",
        "command": "cursorLineStart"
    },
    {
        "key": "alt+right",
        "command": "cursorLineEnd"
    }
]
```

🍎 MAC User

```json
// Place your key bindings in this file to override the defaults
[
    {
        "key": "cmd+e",
        "command": "editor.action.deleteLines",
        "when": "textInputFocus && !editorReadonly"
    },
    {
        "key": "shift+cmd+k",
        "command": "-editor.action.deleteLines",
        "when": "textInputFocus && !editorReadonly"
    },
    {
        "key": "alt+cmd+w",
        "command": "workbench.action.closeOtherEditors"
    },
    {
        "key": "alt+cmd+t",
        "command": "-workbench.action.closeOtherEditors"
    },
    {
        "key": "tab",
        "command": "editor.action.indentLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "cmd+]",
        "command": "-editor.action.indentLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+f2",
        "command": "editor.action.rename",
        "when": "editorHasRenameProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "f2",
        "command": "-editor.action.rename",
        "when": "editorHasRenameProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+f2",
        "command": "editor.action.changeAll",
        "when": "editorTextFocus && editorTextFocus && !editorReadonly"
    },
    {
        "key": "cmd+f2",
        "command": "-editor.action.changeAll",
        "when": "editorTextFocus && editorTextFocus && !editorReadonly"
    },
    {
        "key": "f1",
        "command": "workbench.action.navigateForward"
    },
    {
        "key": "ctrl+shift+-",
        "command": "-workbench.action.navigateForward"
    },
    {
        "key": "f2",
        "command": "workbench.action.navigateBack"
    },
    {
        "key": "ctrl+-",
        "command": "-workbench.action.navigateBack"
    },
    {
        "key": "f3",
        "command": "workbench.action.navigateToLastEditLocation"
    },
    {
        "key": "cmd+k cmd+q",
        "command": "-workbench.action.navigateToLastEditLocation"
    },
    {
        "key": "alt+right",
        "command": "editor.action.insertCursorAtEndOfEachLineSelected",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+i",
        "command": "-editor.action.insertCursorAtEndOfEachLineSelected",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+left",
        "command": "cursorLineStart",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+a",
        "command": "-cursorLineStart",
        "when": "textInputFocus"
    }
]
```
