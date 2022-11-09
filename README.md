# Settings
```json
{
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "debug.javascript.autoAttachFilter": "disabled",
  "diffEditor.ignoreTrimWhitespace": true,
  "editor.colorDecorators": false,
  "editor.fontFamily": "Roboto Mono, monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 15,
  "editor.fontWeight": "500",
  "editor.formatOnPaste": false,
  "editor.formatOnSave": true,
  "editor.guides.bracketPairs": "active",
  "editor.guides.bracketPairsHorizontal": false,
  "editor.inlineSuggest.enabled": true,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.showSlider": "always",
  "editor.renderWhitespace": "none",
  "editor.scrollBeyondLastLine": false,
  "editor.wordWrap": "on",
  "emmet.includeLanguages": { "javascript": "javascriptreact" },
  "emmet.triggerExpansionOnTab": true,
  "explorer.autoReveal": false,
  "explorer.confirmDelete": false,
  "githubPullRequests.fileListLayout": "flat",
  "githubPullRequests.pullBranch": "never",
  "material-icon-theme.folders.associations": {
    "__codegen__": "graphql",
    "__graphql__": "graphql",
    "domain": "shared",
    "framework": "components",
    "ui": "components"
  },
  "material-icon-theme.folders.color": "#42a5f5",
  "terminal.integrated.fontFamily": "RobotoMono Nerd Font Mono",
  "workbench.activityBar.visible": true,
  "workbench.colorTheme": "One Dark Pro",
  "workbench.editor.showTabs": true,
  "workbench.editorAssociations": { "git-rebase-todo": "default" },
  "workbench.iconTheme": "material-icon-theme",
  "workbench.sideBar.location": "left",
  "workbench.statusBar.visible": true,
  "explorer.compactFolders": false
}
```

# Keybindings
```json
[
  {
    "key": "ctrl+shift+cmd+c",
    "command": "workbench.action.terminal.openNativeConsole",
    "when": "!terminalFocus"
  },
  {
    "key": "shift+cmd+c",
    "command": "-workbench.action.terminal.openNativeConsole",
    "when": "!terminalFocus"
  },
  {
    "key": "alt+cmd+r",
    "command": "workbench.files.action.showActiveFileInExplorer"
  },
  {
    "key": "alt+cmd+r",
    "command": "-revealFileInOS",
    "when": "!editorFocus"
  },
  { "key": "cmd+1", "command": "workbench.action.openEditorAtIndex1" },
  { "key": "cmd+2", "command": "workbench.action.openEditorAtIndex2" },
  { "key": "cmd+3", "command": "workbench.action.openEditorAtIndex3" },
  { "key": "cmd+4", "command": "workbench.action.openEditorAtIndex4" },
  { "key": "cmd+5", "command": "workbench.action.openEditorAtIndex5" },
  { "key": "cmd+6", "command": "workbench.action.openEditorAtIndex6" },
  { "key": "cmd+7", "command": "workbench.action.openEditorAtIndex7" },
  { "key": "cmd+8", "command": "workbench.action.openEditorAtIndex8" },
  { "key": "cmd+9", "command": "workbench.action.openEditorAtIndex9" }
]

```

# Extensions
- Apollo GraphQL
- EditorConfiq for VS Code
- ESlint
- File Utils
- GitLens
- Material Icon Theme
- Material Theme
- One Dark Pro
- Prettier
- VS Live Share
- vscode-styled-components
- Sort Lines
