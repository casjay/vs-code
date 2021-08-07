# My vscode settings for linux  
Download and install from https://code.visualstudio.com/download 
  
## Created using:

```shell
code --list-extensions | awk '{print $1}' | sed 's|"||g;s|,||g;s|^|code --install-extension "|g;s|$|" --force  |g'
``` 
  
# install extensions  
  
```shell
code --install-extension "aaron-bond.better-comments" --force  
code --install-extension "ahmadawais.shades-of-purple" --force  
code --install-extension "Angular.ng-template" --force  
code --install-extension "bengreenier.vscode-node-readme" --force  
code --install-extension "bmalehorn.vscode-fish" --force  
code --install-extension "christian-kohler.npm-intellisense" --force  
code --install-extension "Cjay.ruby-and-rails-snippets" --force  
code --install-extension "CoenraadS.bracket-pair-colorizer-2" --force  
code --install-extension "cyrilletuzi.angular-schematics" --force  
code --install-extension "d9705996.perl-toolbox" --force  
code --install-extension "DavidAnson.vscode-markdownlint" --force  
code --install-extension "davidbabel.vscode-simpler-icons" --force  
code --install-extension "dbaeumer.vscode-eslint" --force  
code --install-extension "dnicolson.binary-plist" --force  
code --install-extension "doggy8088.angular-extension-pack" --force  
code --install-extension "donjayamanne.githistory" --force  
code --install-extension "dotiful.dotfiles-syntax-highlighting" --force  
code --install-extension "DotJoshJohnson.xml" --force  
code --install-extension "dsznajder.es7-react-js-snippets" --force  
code --install-extension "duniul.dircolors" --force  
code --install-extension "dunstontc.viml" --force  
code --install-extension "eamodio.gitlens" --force  
code --install-extension "EditorConfig.EditorConfig" --force  
code --install-extension "eiminsasete.apacheconf-snippets" --force  
code --install-extension "eliostruyf.vscode-front-matter" --force  
code --install-extension "esbenp.prettier-vscode" --force  
code --install-extension "formulahendry.auto-close-tag" --force  
code --install-extension "formulahendry.auto-complete-tag" --force  
code --install-extension "formulahendry.auto-rename-tag" --force  
code --install-extension "foxundermoon.shell-format" --force  
code --install-extension "ginfuru.ginfuru-vscode-jekyll-syntax" --force  
code --install-extension "ginfuru.vscode-jekyll-snippets" --force  
code --install-extension "GitHub.copilot" --force  
code --install-extension "glen-84.sass-lint" --force  
code --install-extension "hangxingliu.vscode-nginx-conf-hint" --force  
code --install-extension "HexcodeTechnologies.vscode-prettydiff" --force  
code --install-extension "HookyQR.beautify" --force  
code --install-extension "infinity1207.angular2-switcher" --force  
code --install-extension "johnpapa.Angular2" --force  
code --install-extension "justusadam.language-haskell" --force  
code --install-extension "keesschollaart.vscode-home-assistant" --force  
code --install-extension "keyring.Lua" --force  
code --install-extension "krizzdewizz.refactorix" --force  
code --install-extension "MariusAlchimavicius.json-to-ts" --force  
code --install-extension "mechatroner.rainbow-csv" --force  
code --install-extension "Mikael.Angular-BeastCode" --force  
code --install-extension "mikestead.dotenv" --force  
code --install-extension "mrmlnc.vscode-apache" --force  
code --install-extension "ms-azuretools.vscode-docker" --force  
code --install-extension "ms-python.python" --force  
code --install-extension "ms-python.vscode-pylance" --force  
code --install-extension "ms-toolsai.jupyter" --force  
code --install-extension "ms-vscode-remote.remote-containers" --force  
code --install-extension "ms-vscode-remote.remote-wsl" --force  
code --install-extension "ms-vscode.powershell" --force  
code --install-extension "ms-vscode.vscode-typescript-tslint-plugin" --force  
code --install-extension "ms-vsliveshare.vsliveshare" --force  
code --install-extension "mubaidr.vuejs-extension-pack" --force  
code --install-extension "nepaul.editorconfiggenerator" --force  
code --install-extension "nhoizey.gremlins" --force  
code --install-extension "nico-castell.linux-desktop-file" --force  
code --install-extension "obenjiro.arrr" --force  
code --install-extension "octref.vetur" --force  
code --install-extension "oderwat.indent-rainbow" --force  
code --install-extension "oouo-diogo-perdigao.docthis" --force  
code --install-extension "piotrpalarz.vscode-gitignore-generator" --force  
code --install-extension "PKief.material-icon-theme" --force  
code --install-extension "pranaygp.vscode-css-peek" --force  
code --install-extension "quicktype.quicktype" --force  
code --install-extension "rebornix.ruby" --force  
code --install-extension "redhat.vscode-yaml" --force  
code --install-extension "ritwickdey.live-sass" --force  
code --install-extension "ritwickdey.LiveServer" --force  
code --install-extension "rohgarg.jekyll-post" --force  
code --install-extension "rpinski.shebang-snippets" --force  
code --install-extension "rubbersheep.gi" --force  
code --install-extension "sdras.vue-vscode-snippets" --force  
code --install-extension "Shan.code-settings-sync" --force  
code --install-extension "sidneys1.gitconfig" --force  
code --install-extension "SimonSiefke.prettier-vscode" --force  
code --install-extension "sissel.shopify-liquid" --force  
code --install-extension "steoates.autoimport" --force  
code --install-extension "streetsidesoftware.code-spell-checker" --force  
code --install-extension "stringham.move-ts" --force  
code --install-extension "syler.sass-indented" --force  
code --install-extension "tanming363.bootstrap-v4" --force  
code --install-extension "thomascsd.vscode-readme-pattern" --force  
code --install-extension "timonwong.shellcheck" --force  
code --install-extension "tombonnike.vscode-status-bar-format-toggle" --force  
code --install-extension "tomzx.emoji" --force  
code --install-extension "TzachOvadia.todo-list" --force  
code --install-extension "VisualStudioExptTeam.vscodeintellicode" --force  
code --install-extension "vscode-snippet.snippet" --force  
code --install-extension "WakaTime.vscode-wakatime" --force  
code --install-extension "wayou.vscode-todo-highlight" --force  
code --install-extension "wingrunr21.vscode-ruby" --force  
code --install-extension "Wscats.eno" --force  
code --install-extension "xabikos.JavaScriptSnippets" --force  
code --install-extension "yinfei.luahelper" --force  
code --install-extension "yzhang.markdown-all-in-one" --force  
code --install-extension "ZainChen.json" --force  
