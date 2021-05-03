# Settings
```json
{
  "editor.formatOnSave": false,
  "editor.fontSize": 18,
  "editor.fontFamily": "Roboto Mono, monospace",
  "files.exclude": {
    "**/tmp": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/_DS_Store": true
  },
  "workbench.startupEditor": "none",
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "editor.colorDecorators": false,
  "editor.formatOnPaste": false,
  "editor.minimap.showSlider": "always",
  "editor.minimap.renderCharacters": false,
  "workbench.statusBar.visible": true,
  "files.associations": {
    "*.html": "html"
  },
  "explorer.autoReveal": false,
  "editor.renderWhitespace": "none",
  "editor.wordWrap": "on",
  "workbench.sideBar.location": "left",
  "workbench.activityBar.visible": true,
  "explorer.confirmDelete": false,
  "javascript.validate.enable": false,
  "editor.fontLigatures": true,
  "editor.scrollBeyondLastLine": false,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "editor.fontWeight": "500",
  "workbench.colorTheme": "One Dark Pro",
  "typescript.suggest.autoImports": false,
  "javascript.suggest.autoImports": false,
  "breadcrumbs.filePath": "off",
  "emmet.triggerExpansionOnTab": true,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.editor.enablePreview": true,
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "material-icon-theme.folders.color": "#42a5f5",
  "material-icon-theme.folders.associations": {
    "domain": "shared",
    "ui": "components",
    "__graphql__": "graphql",
    "__codegen__": "graphql",
    "framework": "components"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
  },
  "[graphql]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
  },
  "terminal.integrated.fontFamily": "RobotoMono Nerd Font Mono",
  "terminal.integrated.rendererType": "canvas",
  "explorer.compactFolders": false,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "zenMode.hideTabs": false,
  "zenMode.hideLineNumbers": false,
  "zenMode.hideStatusBar": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "zenMode.hideActivityBar": false,
  "workbench.editor.showTabs": true,
  "githubPullRequests.fileListLayout": "flat",
  "liveshare.authenticationProvider": "GitHub",
  "debug.javascript.autoAttachFilter": "disabled"
}
```

# Keybindings
```json
// Place your key bindings in this file to override the defaultsauto[]
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
- TSLint
- VS Live Share
- vscode-styled-components
- Sort Lines
