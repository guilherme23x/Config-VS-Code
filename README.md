# Config-VS-Code

Minha configuração de vs code minimalista, baseado no código do Rocketseat (Youtube) - https://www.youtube.com/@rocketseat

##############################################

- Baixe a font JetBrains Mono

# Visual Studio Code:
  
- CTRL + Shift + P
- Settings.JSON
- Cole o código e salve com CTRL + S

##############################################

{
  "workbench.startupEditor": "newUntitledFile",
  "editor.fontSize": 15,
  "editor.lineHeight": 1.8,
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.rulers": [
    80,
    120
  ],
  "extensions.ignoreRecommendations": true,
  "typescript.tsserver.log": "off",
  "editor.stickyScroll.enabled": false,
  "workbench.tree.enableStickyScroll": false,
  "files.associations": {
    ".env.*": "dotenv",
    ".prettierrc": "json",
    "*.css": "css",
    ".dev.vars": "dotenv"
  },
  "symbols.files.associations": {
    "*.module.ts": "nest",
    "*.guard.ts": "typescript",
    "*.spec.ts": "ts-test",
    "*.e2e-spec.ts": "ts-test",
    "*.mock.ts": "ts-test",
    "vitest.config.e2e.ts": "vite",
    ".env.development.local": "gear",
    ".env.test.local": "gear",
    ".env.local": "gear",
    ".env.example": "gear"
  },
  "tailwindCSS.experimental.classRegex": [
    [
      "tv\\(([^)]*)\\)",
      "[\"'`]([^\"'`]*).*?[\"'`]"
    ],
    "class:\\s*?[\"'`]([^\"'`]*).*?,"
  ],
  "editor.parameterHints.enabled": false,
  "editor.renderLineHighlight": "gutter",
  "cSpell.language": "en,pt",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.suggestSelection": "first",
  "explorer.confirmDelete": false,
  "gitlens.codeLens.recentChange.enabled": false,
  "terminal.integrated.showExitAlert": false,
  "[prisma]": {
    "editor.formatOnSave": true
  },
  "typescript.suggest.autoImports": true,
  "typescript.preferences.preferTypeOnlyAutoImports": true,
  "terminal.integrated.env.osx": {
    "FIG_NEW_SESSION": "1"
  },
  "workbench.editor.labelFormat": "short",
  // "editor.fontLigatures": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "cSpell.enableFiletypes": [
    "!asciidoc",
    "!c",
    "!cpp",
    "!csharp",
    "!go",
    "!handlebars",
    "!haskell",
    "!jade",
    "!java",
    "!latex",
    "!php",
    "!pug",
    "!python",
    "!restructuredtext",
    "!rust",
    "!scala",
    "!scss"
  ],
  "editor.acceptSuggestionOnCommitCharacter": false,
  "explorer.compactFolders": false,
  "git.enableSmartCommit": true,
  "editor.accessibilitySupport": "off",
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "JetBrains Mono",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "graphql"
  ],
  "editor.semanticHighlighting.enabled": false,
  "breadcrumbs.enabled": false,
  "workbench.productIconTheme": "fluent-icons",
  "editor.fontFamily": "JetBrains Mono",
  "gitlens.codeLens.authors.enabled": false,
  "editor.tabSize": 2,
  "security.workspace.trust.untrustedFiles": "newWindow",
  "files.exclude": {
    "**\/CVS": true,
    "**\/.DS_Store": true,
    "**\/.hg": true,
    "**\/.svn": true,
    "**\/.git": true,
    ".vscode": true
    // "node_modules": true
  },
  "workbench.iconTheme": "symbols",
  "update.mode": "default",
  "terminal.integrated.gpuAcceleration": "on",
  "terminal.integrated.defaultProfile.osx": "fish",
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "git.openRepositoryInParentFolders": "always",
  "symbols.hidesExplorerArrows": false,
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "console-ninja.featureSet": "Community",
  "workbench.editor.empty.hint": "hidden",
  "update.showReleaseNotes": false,
  "security.promptForLocalFileProtocolHandling": false,
  "apc.activityBar": {
    "position": "bottom",
    "hideSettings": true,
    "size": 48,
    "itemMargin": 8,
    "itemSize": 32
  },
  "editor.hideCursorInOverviewRuler": true,
  "editor.minimap.enabled": false,
  "window.titleBarStyle": "native",
  "apc.electron": {
    "titleBarStyle": "hiddenInset",
    "trafficLightPosition": {
      "x": 11,
      "y": 10
    },
    "opacity": 1,
    "vibrancy": "dark",
    "frame": false
  },
  "apc.header": {
    "height": 36
  },
  "apc.listRow": {
    "height": 24
  },
  "apc.font.family": "JetBrains Mono",
  "apc.stylesheet": {
    ".title-label > h2": "display: none",
    ".editor-actions": "display: none",
    ".nosidebar .inline-tabs-placeholder": "width: 75px",
    ".pane-header": "padding: 0 8px",
    ".pane-body": "padding: 8px",
    ".split-view-view:first-child .pane-header": "display: none !important;",
    ".monaco-list-row": "border-radius: 4px;",
    ".monaco-workbench .monaco-list:not(.element-focused):focus:before": "display: none;"
  },
  "editor.scrollbar.vertical": "hidden",
  "explorer.sortOrder": "foldersNestsFiles",
  "explorer.fileNesting.patterns": {
    "package.json": ".eslint*, prettier*, tsconfig*, vite*, pnpm-*, bun.lockb, nest*, package-lock*",
    "tailwind.config.*": "tailwind.config*, postcss.config*",
    ".env.local": ".env*",
    ".env": ".env*"
  },
  "explorer.fileNesting.enabled": true,
  "workbench.statusBar.visible": false,
  "editor.tokenColorCustomizations": {
    "textMateRules": []
  },
  "workbench.colorTheme": "Min Dark",
  "files.autoSave": "afterDelay",
  "editor.renderWhitespace": "none",
  "editor.renderControlCharacters": false,
  "window.commandCenter": false,
  "workbench.layoutControl.enabled": false,
  "workbench.activityBar.location": "bottom",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.editor.showTabs": "single"
}
