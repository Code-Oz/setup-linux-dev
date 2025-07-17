// Place your key bindings in this file to override the defaults
[
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
    "when": "editorTextFocus && !editorTabMovesFocus"
  },
  {
    "key": "cmd+]",
    "command": "-editor.action.indentLines",
    "when": "editorTextFocus && !editorTabMovesFocus"
  },
  {
    "key": "shift+tab",
    "command": "outdent",
    "when": "editorTextFocus && !editorTabMovesFocus"
  },
  {
    "key": "shift+cmd+r",
    "command": "workbench.files.action.showActiveFileInExplorer"
  },
  {
    "key": "alt+f1",
    "command": "dynoFileUtils.newItemsAtCurrentPath"
  },
  {
    "key": "alt+f3",
    "command": "dynoFileUtils.renameFile"
  },
  {
    "key": "alt+f2",
    "command": "-dynoFileUtils.renameFile"
  },
  {
    "key": "alt+f2",
    "command": "dynoFileUtils.newItems"
  },
  {
    "key": "alt+n",
    "command": "-dynoFileUtils.newItems"
  },
  {
    "key": "shift+alt+h",
    "command": "editor.action.smartSelect.shrink",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+shift+left",
    "command": "-editor.action.smartSelect.shrink",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+shift+cmd+left",
    "command": "-editor.action.smartSelect.shrink",
    "when": "editorTextFocus"
  },
  {
    "key": "shift+alt+l",
    "command": "editor.action.smartSelect.expand",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+shift+right",
    "command": "-editor.action.smartSelect.expand",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+shift+cmd+right",
    "command": "-editor.action.smartSelect.expand",
    "when": "editorTextFocus"
  },
  {
    "key": "shift+alt+j",
    "command": "editor.action.moveLinesUpAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "alt+up",
    "command": "-editor.action.moveLinesUpAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "shift+alt+k",
    "command": "editor.action.moveLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "alt+down",
    "command": "-editor.action.moveLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+cmd+f",
    "command": "-workbench.action.toggleFullScreen",
    "when": "!isIOS"
  },
  {
    "key": "ctrl+cmd+f",
    "command": "workbench.action.experimental.quickTextSearch"
  },
  {
    "key": "ctrl+`",
    "command": "workbench.action.terminal.focus"
  },
  {
    "key": "ctrl+`",
    "command": "workbench.action.focusActiveEditorGroup",
    "when": "terminalFocus"
  }
]
