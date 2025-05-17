# My Personal VSCode Settings

```json
{
    // Editor settings
    "editor.formatOnSave": true,
    "editor.detectIndentation": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2,
    "editor.linkedEditing": true,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "on",
    "editor.inlineSuggest.enabled": true,
    "editor.wordWrap": "on",
    // Workbench settings
    "workbench.colorTheme": "Cursor Dark Midnight",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorCustomizations": {
        "editorWarning.foreground": "#757575",
        "editorError.foreground": "#f66",
        "list.warningForeground": "#757575",
        "list.errorForeground": "#f66",
        "gitDecoration.modifiedResourceForeground": "#dda24e",
        "gitDecoration.untrackedResourceForeground": "#00ffb3"
    },
    // Git settings
    "git.enableSmartCommit": true,
    "git.confirmSync": false,
    "git.autofetch": true,
    // Language settings
    "javascript.updateImportsOnFileMove.enabled": "always",
    "typescript.updateImportsOnFileMove.enabled": "always",
    "prettier.singleQuote": true,
    // Security settings
    "security.workspace.trust.untrustedFiles": "open",
    "explorer.confirmDelete": true,
    // Language-specific settings
    "[html]": {
        "editor.suggest.insertMode": "replace",
        "editor.defaultFormatter": "mohd-akram.vscode-html-format"
    },
    "[jsonc]": {
        "editor.tabSize": 2
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[xml]": {
        "editor.defaultFormatter": "j69.ejs-beautify"
    },
    "[css]": {
        "editor.defaultFormatter": "michelemelluso.code-beautifier"
    },
    "[csharp]": {
        "editor.defaultFormatter": "csharpier.csharpier-vscode"
    },
    "[python]": {
        "editor.tabSize": 4
    },
    "[prisma]": {
        "editor.defaultFormatter": "Prisma.prisma"
    },
    "[astro]": {
        "editor.defaultFormatter": "astro-build.astro-vscode"
    },
    "[java]": {
        "editor.defaultFormatter": "mwpb.java-prettier-formatter"
    }
}
