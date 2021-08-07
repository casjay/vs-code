# My vscode settings for chromebook  
Download and install from https://code.visualstudio.com/download 
  
## Created using:

```shell
code --list-extensions | awk '{print $1}' | sed 's|"||g;s|,||g;s|^|code --install-extension "|g;s|$|" --force  |g'
``` 
  
# install extensions  
  
```text
bash -c "
code --install-extension aaron-bond.better-comments
code --install-extension bengreenier.vscode-node-readme
code --install-extension bmalehorn.vscode-fish
code --install-extension christian-kohler.npm-intellisense
code --install-extension Cjay.ruby-and-rails-snippets
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension d9705996.perl-toolbox
code --install-extension DavidAnson.vscode-markdownlint
code --install-extension dbaeumer.vscode-eslint
code --install-extension dnicolson.binary-plist
code --install-extension dotiful.dotfiles-syntax-highlighting
code --install-extension DotJoshJohnson.xml
code --install-extension dsznajder.es7-react-js-snippets
code --install-extension duniul.dircolors
code --install-extension dunstontc.viml
code --install-extension eamodio.gitlens
code --install-extension eiminsasete.apacheconf-snippets
code --install-extension eliostruyf.vscode-front-matter
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-rename-tag
code --install-extension foxundermoon.shell-format
code --install-extension ginfuru.ginfuru-vscode-jekyll-syntax
code --install-extension ginfuru.vscode-jekyll-snippets
code --install-extension GitHub.copilot
code --install-extension hangxingliu.vscode-nginx-conf-hint
code --install-extension HexcodeTechnologies.vscode-prettydiff
code --install-extension HookyQR.beautify
code --install-extension justusadam.language-haskell
code --install-extension keyring.Lua
code --install-extension MariusAlchimavicius.json-to-ts
code --install-extension mechatroner.rainbow-csv
code --install-extension mrmlnc.vscode-apache
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-python.python
code --install-extension ms-vscode-remote.remote-containers
code --install-extension ms-vscode.powershell
code --install-extension ms-vscode.vscode-typescript-tslint-plugin
code --install-extension nepaul.editorconfiggenerator
code --install-extension octref.vetur
code --install-extension oderwat.indent-rainbow
code --install-extension piotrpalarz.vscode-gitignore-generator
code --install-extension quicktype.quicktype
code --install-extension rebornix.ruby
code --install-extension redhat.vscode-yaml
code --install-extension ritwickdey.live-sass
code --install-extension ritwickdey.LiveServer
code --install-extension rohgarg.jekyll-post
code --install-extension rpinski.shebang-snippets
code --install-extension Shan.code-settings-sync
code --install-extension sidneys1.gitconfig
code --install-extension sissel.shopify-liquid
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension syler.sass-indented
code --install-extension tanming363.bootstrap-v4
code --install-extension timonwong.shellcheck
code --install-extension tomzx.emoji
code --install-extension TzachOvadia.todo-list
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension vscode-icons-team.vscode-icons
code --install-extension vscode-snippet.snippet
code --install-extension WakaTime.vscode-wakatime
code --install-extension wingrunr21.vscode-ruby
code --install-extension Wscats.eno
code --install-extension yinfei.luahelper
code --install-extension yzhang.markdown-all-in-one
code --install-extension ZainChen.json
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
