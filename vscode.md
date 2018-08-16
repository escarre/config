# vscode-settings

> You will need to install the `Fira Code` font from https://github.com/tonsky/FiraCode

> You will also have to modify the `local-history.path` and `terminal.external.osxExec` settings based on your machine/OS

## Extension List

```
Angular.ng-template
EditorConfig.EditorConfig
akamud.vscode-theme-onedark
alefragnani.Bookmarks
castwide.solargraph
christian-kohler.npm-intellisense
christian-kohler.path-intellisense
CoenraadS.bracket-pair-colorizer
dbaeumer.vscode-eslint
dzannotti.vscode-babel-coloring
eamodio.gitlens
eg2.tslint
eg2.vscode-npm-script
esbenp.prettier-vscode
felipecaputo.git-project-manager
formulahendry.auto-close-tag
formulahendry.auto-complete-tag
formulahendry.auto-rename-tag
jakethashi.vscode-angular2-emmet
johnpapa.angular-essentials
johnpapa.Angular2
johnpapa.winteriscoming
kevinmcgowan.TypeScriptImport
markis.code-coverage
mezzalab.vscode-annotations
msjsdiag.debugger-for-chrome
natewallace.angular2-inline
Orta.vscode-jest
PKief.material-icon-theme
robertohuertasm.vscode-icons
spywhere.guides
stringham.move-ts
xabikos.JasmineSnippets
```

## settings.json

```

```

// Place your settings in this file to overwrite the default settings
{
"editor.tabCompletion": true,
"editor.fontFamily": "Fira Code",
"editor.fontSize": 12,
"editor.fontLigatures": true,
"editor.formatOnSave": true,
"editor.formatOnType": true,
"editor.minimap.enabled": false,
"editor.snippetSuggestions": "top",
// Searching
"search.exclude": {
".git/**": true,
"node_modules/**": true,
"coverage/**": true,
"dist/**": true,
},
"files.exclude": {
"**/.git": true,
"**/.svn": true,
"**/.hg": true,
"**/CVS": true,
"**/.DS_Store": true,
"**/dist": true,
"**/node_modules": true,
"**/coverage": true,
// "**/\*.js": true,
"**/_.d.ts": true,
"\*\*/_.ngfactory.ts": true,
"**/\*.ngsummary.json": true,
"**/\*.metadata.json": true
},
"java.errors.incompleteClasspath.severity": "ignore",
"gitlens.keymap": "alternate",
"editor.renderIndentGuides": false,
// Formatting
"files.autoSave": "onFocusChange",
"html.format.wrapAttributes": "force-aligned",
// TSLint
"tslint.autoFixOnSave": true,
"tslint.rulesDirectory": "./node_modules/codelyzer",
// IDE
"window.restoreWindows": "none",
// Pretier Config
"prettier.singleQuote": true,
"prettier.trailingComma": "all",
"prettier.printWidth": 140,
// Custom Extensions
"auto-close-tag.activationOnLanguage": [
"xml",
"php",
"blade",
"ejs",
"jinja",
"javascriptreact",
"typescriptreact",
"plaintext",
"markdown",
"vue",
"liquid",
"erb",
"lang-cfml",
"cfml",
"HTML (Eex)"
],
"material-icon-theme.showUpdateMessage": false,
"material-icon-theme.hidesExplorerArrows": true,
"material-icon-theme.folders.theme": "specific",
"gitlens.advanced.messages": {
"suppressCommitHasNoPreviousCommitWarning": false,
"suppressCommitNotFoundWarning": false,
"suppressFileNotUnderSourceControlWarning": false,
"suppressGitVersionWarning": false,
"suppressLineUncommittedWarning": false,
"suppressNoRepositoryWarning": false,
"suppressResultsExplorerNotice": false,
"suppressShowKeyBindingsNotice": true
},
"gitlens.historyExplorer.enabled": true,
"window.zoomLevel": 0,
"typescript.updateImportsOnFileMove.enabled": "always",
"javascript.updateImportsOnFileMove.enabled": "always",
"workbench.colorTheme": "Winter is Coming (Dark)",
}

```

```
