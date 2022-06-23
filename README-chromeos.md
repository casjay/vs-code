# My vscode settings for chromebook  
Download and install from https://code.visualstudio.com/download 
  
## Created using:

```shell
code --list-extensions | awk '{print $1}' | sed 's|"||g;s|,||g;s|^|code --install-extension "|g;s|$|" --force  |g'
``` 
  
# install extensions  
  
```text
bash -c "
code --install-extension "aaron-bond.better-comments" --force  
code --install-extension "bengreenier.vscode-node-readme" --force  
code --install-extension "bmalehorn.vscode-fish" --force  
code --install-extension "christian-kohler.npm-intellisense" --force  
code --install-extension "Cjay.ruby-and-rails-snippets" --force  
code --install-extension "d9705996.perl-toolbox" --force  
code --install-extension "DavidAnson.vscode-markdownlint" --force  
code --install-extension "dbaeumer.vscode-eslint" --force  
code --install-extension "dnicolson.binary-plist" --force  
code --install-extension "dotiful.dotfiles-syntax-highlighting" --force  
code --install-extension "DotJoshJohnson.xml" --force  
code --install-extension "dsznajder.es7-react-js-snippets" --force  
code --install-extension "duniul.dircolors" --force  
code --install-extension "dunstontc.viml" --force  
code --install-extension "eamodio.gitlens" --force  
code --install-extension "eiminsasete.apacheconf-snippets" --force  
code --install-extension "eliostruyf.vscode-front-matter" --force  
code --install-extension "esbenp.prettier-vscode" --force  
code --install-extension "formulahendry.auto-rename-tag" --force  
code --install-extension "foxundermoon.shell-format" --force  
code --install-extension "ginfuru.ginfuru-vscode-jekyll-syntax" --force  
code --install-extension "ginfuru.vscode-jekyll-snippets" --force  
code --install-extension "hangxingliu.vscode-nginx-conf-hint" --force  
code --install-extension "HexcodeTechnologies.vscode-prettydiff" --force  
code --install-extension "HookyQR.beautify" --force  
code --install-extension "justusadam.language-haskell" --force  
code --install-extension "keyring.Lua" --force  
code --install-extension "MariusAlchimavicius.json-to-ts" --force  
code --install-extension "mechatroner.rainbow-csv" --force  
code --install-extension "mrmlnc.vscode-apache" --force  
code --install-extension "ms-azuretools.vscode-docker" --force  
code --install-extension "ms-python.python" --force  
code --install-extension "ms-python.vscode-pylance" --force  
code --install-extension "ms-vscode-remote.remote-containers" --force  
code --install-extension "ms-vscode.powershell" --force  
code --install-extension "ms-vscode.vscode-typescript-tslint-plugin" --force  
code --install-extension "nepaul.editorconfiggenerator" --force  
code --install-extension "octref.vetur" --force  
code --install-extension "oderwat.indent-rainbow" --force  
code --install-extension "piotrpalarz.vscode-gitignore-generator" --force  
code --install-extension "quicktype.quicktype" --force  
code --install-extension "redhat.vscode-yaml" --force  
code --install-extension "ritwickdey.live-sass" --force  
code --install-extension "ritwickdey.LiveServer" --force  
code --install-extension "rohgarg.jekyll-post" --force  
code --install-extension "rpinski.shebang-snippets" --force  
code --install-extension "Shan.code-settings-sync" --force  
code --install-extension "sidneys1.gitconfig" --force  
code --install-extension "sissel.shopify-liquid" --force  
code --install-extension "streetsidesoftware.code-spell-checker" --force  
code --install-extension "syler.sass-indented" --force  
code --install-extension "tanming363.bootstrap-v4" --force  
code --install-extension "timonwong.shellcheck" --force  
code --install-extension "tomzx.emoji" --force  
code --install-extension "TzachOvadia.todo-list" --force  
code --install-extension "VisualStudioExptTeam.vscodeintellicode" --force  
code --install-extension "vscode-icons-team.vscode-icons" --force  
code --install-extension "vscode-snippet.snippet" --force  
code --install-extension "WakaTime.vscode-wakatime" --force  
code --install-extension "wingrunr21.vscode-ruby" --force  
code --install-extension "Wscats.eno" --force  
code --install-extension "yinfei.luahelper" --force  
code --install-extension "yzhang.markdown-all-in-one" --force  
code --install-extension "ZainChen.json" --force
" 2>/dev/null
```
  
## Settings
```json
{
  "sync.gist": "3ef2c13d3ff75fa4f7fe565c46781837",
  "bracket-pair-colorizer-2.colorMode": "Independent",
  "bracket-pair-colorizer-2.forceUniqueOpeningColor": true,
  "bracket-pair-colorizer-2.showBracketsInGutter": true,
  "editor.cursorSmoothCaretAnimation": true,
  "editor.fontFamily": "Fira Code, Hack Nerd Font, Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 15,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.minimap.enabled": false,
  "editor.quickSuggestionsDelay": 5,
  "editor.renderIndentGuides": true,
  "editor.renderWhitespace": "boundary",
  "editor.suggestSelection": "first",
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "editor.wordWrapColumn": 180,
  "editor.linkedEditing": true,
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "git.enableCommitSigning": true,
  "git.enableSmartCommit": true,
  "git.showPushSuccessNotification": true,
  "html.format.endWithNewline": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "markdown.extension.tableFormatter.normalizeIndentation": true,
  "markdown.extension.toc.orderedList": true,
  "php.validate.executablePath": "php",
  "powershell.codeFormatting.autoCorrectAliases": true,
  "search.showLineNumbers": true,
  "shellcheck.exclude": ["1017"],
  "shellcheck.run": "manual",
  "terminal.integrated.fontFamily": "Hack Nerd Font",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "workbench.editor.highlightModifiedTabs": true,
  "workbench.startupEditor": "newUntitledFile",
  "workbench.iconTheme": "vscode-icons",
  "workbench.editor.enablePreview": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "python.defaultInterpreterPath": "python3",
  "redhat.telemetry.enabled": true,
  "editor.inlineSuggest.enabled": true,
  "github.copilot.advanced": {},
  "github.copilot.autocomplete.enable": true,
  "window.zoomLevel": -1,
  "eslint.alwaysShowStatus": true,
  "eslint.format.enable": true,
  "workbench.editor.untitled.hint": "hidden",
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[xml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "cSpell.enabledLanguageIds": [
    "asciidoc",
    "bat",
    "c",
    "cpp",
    "csharp",
    "css",
    "dockerfile",
    "git-commit",
    "go",
    "handlebars",
    "haskell",
    "home-assistant",
    "html",
    "ini",
    "jade",
    "java",
    "javascript",
    "javascriptreact",
    "jekyll",
    "json",
    "jsonc",
    "latex",
    "less",
    "liquid",
    "lua",
    "makefile",
    "markdown",
    "perl",
    "php",
    "plaintext",
    "powershell",
    "pug",
    "python",
    "restructuredtext",
    "ruby",
    "rust",
    "scala",
    "scss",
    "shellscript",
    "text",
    "typescript",
    "typescriptreact",
    "yaml",
    "yml"
  ],
  "liquid.format": true,
  "liquid.rules": {
    "html": {},
    "js": {},
    "css": {},
    "scss": {},
    "json": {}
  },
  "[markdown]": {
    "files.trimTrailingWhitespace": false,
    "editor.quickSuggestions": true,
    "editor.defaultFormatter": "yzhang.markdown-all-in-one"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.markdownlint": true,
    "source.fixAll.eslint": true
  },
  "cSpell.language": "en,en-US",
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".css",
      "savePath": "/assets/css"
    }
  ],
  "liveSassCompile.settings.excludeList": ["**/node_modules/**", ".vscode/**"],
  "scss.lint.unknownAtRules": "ignore",
  "scss.lint.unknownProperties": "ignore",
  "liveSassCompile.settings.autoprefix": [],
  "scss.validate": false,
  "liveSassCompile.settings.generateMap": false,
  "markdownlint.config": {
    "MD012": false,
    "MD013": false,
    "MD033": false,
    "MD041": false
  },
  "better-comments.highlightPlainText": true,
  "cSpell.customUserDictionaries": [],
  "enableTelemetry": true,
  "python.languageServer": "Microsoft",
  "files.autoSave": "onWindowChange",
  "terminal.integrated.env.windows": {},
  "cSpell.userWords": [
    "Centralish",
    "Hellotxt",
    "Miley",
    "casjay",
    "gitmasterconfig",
    "prevrepo",
    "printf"
  ],
  "markdown.extension.print.theme": "dark",
  "markdown.extension.toc.omittedFromToc": {},
  "markdown.preview.breaks": true,
  "[home-assistant]": {
    "editor.insertSpaces": true,
    "editor.tabSize": 2,
    "editor.quickSuggestions": {
      "other": true,
      "comments": false,
      "strings": true
    },
    "editor.autoIndent": "full"
  },
  "cSpell.enabled": false,
  "[shellscript]": {
    "files.eol": "\n"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```
