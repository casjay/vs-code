# My vscode settings for linux  

Download and install from [https://code.visualstudio.com](https://code.visualstudio.com/download)  

## Created using

```shell
code --list-extensions | awk '{print $1}' | sed 's|"||g;s|,||g;s|^|code --install-extension "|g;s|$|" --force|g'
```

## install extensions  

```shell
code --install-extension "1dot75cm.rpmspec" --force
code --install-extension "aaron-bond.better-comments" --force
code --install-extension "bengreenier.vscode-node-readme" --force
code --install-extension "bierner.emojisense" --force
code --install-extension "bierner.github-markdown-preview" --force
code --install-extension "bierner.markdown-checkbox" --force
code --install-extension "bierner.markdown-emoji" --force
code --install-extension "bierner.markdown-footnotes" --force
code --install-extension "bierner.markdown-mermaid" --force
code --install-extension "bierner.markdown-preview-github-styles" --force
code --install-extension "bierner.markdown-yaml-preamble" --force
code --install-extension "bmalehorn.vscode-fish" --force
code --install-extension "compilenix.vscode-zonefile" --force
code --install-extension "compilouit.manpage" --force
code --install-extension "coolbear.systemd-unit-file" --force
code --install-extension "davidanson.vscode-markdownlint" --force
code --install-extension "dbaeumer.vscode-eslint" --force
code --install-extension "denoland.vscode-deno" --force
code --install-extension "devsense.composer-php-vscode" --force
code --install-extension "devsense.intelli-php-vscode" --force
code --install-extension "devsense.phptools-vscode" --force
code --install-extension "devsense.profiler-php-vscode" --force
code --install-extension "dotiful.dotfiles-syntax-highlighting" --force
code --install-extension "dotjoshjohnson.xml" --force
code --install-extension "dracula-theme.theme-dracula" --force
code --install-extension "duniul.dircolors" --force
code --install-extension "dunstontc.viml" --force
code --install-extension "editorconfig.editorconfig" --force
code --install-extension "eiminsasete.apacheconf-snippets" --force
code --install-extension "esbenp.prettier-vscode" --force
code --install-extension "file-icons.file-icons" --force
code --install-extension "formulahendry.auto-rename-tag" --force
code --install-extension "fosshaas.fontsize-shortcuts" --force
code --install-extension "foxundermoon.shell-format" --force
code --install-extension "ginfuru.ginfuru-vscode-jekyll-syntax" --force
code --install-extension "hangxingliu.vscode-nginx-conf-hint" --force
code --install-extension "hexcodetechnologies.vscode-prettydiff" --force
code --install-extension "hogashi.crontab-syntax-highlight" --force
code --install-extension "justusadam.language-haskell" --force
code --install-extension "malmaud.tmux" --force
code --install-extension "mariusalchimavicius.json-to-ts" --force
code --install-extension "mechatroner.rainbow-csv" --force
code --install-extension "mrmlnc.vscode-apache" --force
code --install-extension "ms-azuretools.vscode-docker" --force
code --install-extension "ms-python.debugpy" --force
code --install-extension "ms-python.python" --force
code --install-extension "ms-python.vscode-pylance" --force
code --install-extension "ms-toolsai.jupyter" --force
code --install-extension "ms-toolsai.jupyter-keymap" --force
code --install-extension "ms-toolsai.jupyter-renderers" --force
code --install-extension "ms-toolsai.vscode-jupyter-cell-tags" --force
code --install-extension "ms-toolsai.vscode-jupyter-slideshow" --force
code --install-extension "ms-vscode-remote.remote-containers" --force
code --install-extension "ms-vscode.live-server" --force
code --install-extension "nhoizey.gremlins" --force
code --install-extension "nico-castell.linux-desktop-file" --force
code --install-extension "oderwat.indent-rainbow" --force
code --install-extension "quicktype.quicktype" --force
code --install-extension "redhat.vscode-yaml" --force
code --install-extension "ritwickdey.liveserver" --force
code --install-extension "rpinski.shebang-snippets" --force
code --install-extension "sissel.shopify-liquid" --force
code --install-extension "streetsidesoftware.code-spell-checker" --force
code --install-extension "tamasfe.even-better-toml" --force
code --install-extension "timonwong.shellcheck" --force
code --install-extension "tommasov.hosts" --force
code --install-extension "tzachovadia.todo-list" --force
code --install-extension "visualstudioexptteam.intellicode-api-usage-examples" --force
code --install-extension "visualstudioexptteam.vscodeintellicode" --force
code --install-extension "vue.volar" --force
code --install-extension "wakatime.vscode-wakatime" --force
code --install-extension "wscats.eno" --force
code --install-extension "yinfei.luahelper" --force
code --install-extension "yzhang.markdown-all-in-one" --force
code --install-extension "zainchen.json" --force
```

## Edit Setting

```shell
[ -d "$HOME/.config/Code/User" ] || mkdir -p "$HOME/.config/Code/User"
$EDITOR "$HOME/.config/Code/User/settings.json"
```

## Settings json file

[My linux settings file](https://github.com/casjay/vs-code/blob/main/settings-linux.json)  
  
