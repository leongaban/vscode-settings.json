# vscode-settings.json

```
{
  "workbench.iconTheme": "vscode-icons",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "prettier.documentSelectors": ["*.js, *.jsx", "**/*.{js,jsx,ts,css,scss,md}"],
  "notebook.formatOnSave.enabled": true,
  "workbench.settings.applyToAllProfiles": ["editor.defaultFormatter", "prettier.bracketSameLine"],
  "workbench.colorTheme": "SynthWave '84",
  "terminal.integrated.wordSeparators": " ()[]{}',\"`─‘’|-",
  "editor.wordSeparators": "`~!@#$%^&*()=+[{]}\\|;:'\",.<>/?",
  "terminal.integrated.cursorStyle": "line",
  "git.openRepositoryInParentFolders": "never",
  "editor.linkedEditing": true,
  "explorer.confirmDelete": false,
  "svelte.enable-ts-plugin": true,
  "window.zoomLevel": 2,
  "[svelte]": {
    "editor.defaultFormatter": "svelte.svelte-vscode"
  },
  "prettier.jsxSingleQuote": true,
  "prettier.singleQuote": true,
  "svelte.plugin.svelte.format.config.singleQuote": true,
  "prettier.arrowParens": "avoid",
  "prettier.printWidth": 120,
  "svelte.plugin.svelte.format.config.printWidth": 120,
  "prettier.htmlWhitespaceSensitivity": "ignore",
  "prettier.requireConfig": true,
  "prettier.bracketSameLine": true,
  "editor.autoClosingBrackets": "always",
  "emmet.includeLanguages": {
    "jsx": "jsx"
  },
  "emmet.triggerExpansionOnTab": true,
  "emmet.useInlineCompletions": true,
  "emmet.preferences": {},
  "explorer.confirmDragAndDrop": false,
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "editor.tabSize": 2,
  "typescript.updateImportsOnFileMove.enabled": "never",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.fontFamily": "Cascadia Code PL, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#FF2D00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "?",
      "color": "#3498DB",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "todo",
      "color": "#FF8C00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "*",
      "color": "#98C379",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    }
  ],
  "github.copilot.editor.enableAutoCompletions": true,
  "splitHTMLAttributes.closingBracketOnNewLine": true,
  "splitHTMLAttributes.sortOrder": ["^v-if", "^v-else", "^v-show", "^v-model", "^v-for", "^:key", "^key", "^v-", "^:", "^@click", "^@", "^id", "^class", "^.*=\""],
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "entity.name.tag.template.html.vue",
        "settings": {
          "foreground": "#FF00FF",
          "fontStyle": "italic"
        }
      },
      {
        "scope": "entity.name.tag.script.html.vue",
        "settings": {
          "foreground": "#FF00FF",
          "fontStyle": "italic"
        }
      },
      {
        "scope": "entity.name.tag.style.html.vue",
        "settings": {
          "foreground": "#FF00FF",
          "fontStyle": "italic"
        }
      }
    ]
  }
}
```
