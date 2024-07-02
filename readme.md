## Configurations

```jsonc
{
  "editor.fontSize": 14,
  "editor.lineHeight": 24,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontLigatures": true,
  "explorer.compactFolders": false,
  "editor.rulers": [80, 120],
  "editor.formatOnSave": true,
  "eslint.packageManager": "yarn",
  "[javascript]": {
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": true
    },
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": true
    },
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": true
    },
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": true
    },
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    ".prettierrc": "json"
  },
  // left signal on selected line
  "editor.renderLineHighlight": "gutter",
  "terminal.integrated.fontSize": 14,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",
  "editor.tabSize": 2,
  "extensions.ignoreRecommendations": true,
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "gitlens.codeLens.recentChange.enabled": false,
  "gitlens.codeLens.authors.enabled": false,
  "gitlens.codeLens.enabled": false,
  "git.enableSmartCommit": true,
  "editor.parameterHints.enabled": false,
  "typescript.updateImportsOnFileMove.enabled": "never",
  "explorer.confirmDragAndDrop": false,
  "liveshare.featureSet": "insiders",
  "explorer.confirmDelete": false,
  "typescript.tsserver.log": "verbose",
  "javascript.suggest.autoImports": false,
  "typescript.suggest.autoImports": false,
  "workbench.activityBar.visible": true,
  // Sync config
  "sync.quietSync": false,
  "sync.autoDownload": true,
  "sync.gist": "secret",
  "sync.autoUpload": true,
  "sync.forceUpload": true,
  // Sync config
  "git.autofetch": true,
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "git.confirmSync": false,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "editor.suggestSelection": "first",
  "editor.minimap.enabled": false,
  "editor.renderWhitespace": "none",
  "workbench.editor.untitled.hint": "hidden",
  "editor.inlineSuggest.enabled": true,
  "editor.bracketPairColorization.enabled": true,
  "security.workspace.trust.untrustedFiles": "open",
  "github.copilot.enable": {
    "*": true,
    "yaml": false,
    "plaintext": true,
    "markdown": true
  },
  "window.nativeTabs": true,
  "workbench.colorTheme": "Winter is Coming (Dark Blue)",
  "html.autoClosingTags": true,
  "editor.linkedEditing": true,
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "tailwindCSS.includeLanguages": {
    "typescript": "javascript", // if you are using typescript
    "typescriptreact": "javascript" // if you are using typescript with react
  },
  "editor.quickSuggestions": {
    "strings": true // forces VS Code to trigger completions when editing "string" content
  },
  "tailwindCSS.experimental.classRegex": [
    "tw`([^`]*)", // tw`...`
    "tw\\.[^`]+`([^`]*)`", // tw.xxx<xxx>`...`
    "tw\\(.*?\\).*?`([^`]*)" // tw(Component)<xxx>`...`
  ],
  "window.zoomLevel": 3
}
```

## Extensions

Copy and paste into your integrated terminal to install

```shell
code --install-extension bradlc.vscode-tailwindcss
code --install-extension dbaeumer.vscode-eslint
code --install-extension DotJoshJohnson.xml
code --install-extension dracula-theme.theme-dracula
code --install-extension dsznajder.es7-react-js-snippets
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension GitHub.copilot
code --install-extension johnpapa.winteriscoming
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension ms-python.python
code --install-extension ms-vsliveshare.vsliveshare
code --install-extension naumovs.color-highlight
code --install-extension PKief.material-icon-theme
code --install-extension Prisma.prisma
code --install-extension ritwickdey.LiveServer
code --install-extension rocketseat.rocketseatreactjs
code --install-extension rocketseat.rocketseatreactnative
code --install-extension rocketseat.theme-omni
code --install-extension Shan.code-settings-sync
```