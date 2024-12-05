# My Visual Studio settings for code-server

Download and install from [https://code.visualstudio.com](https://code.visualstudio.com/#alt-downloads)  

## Created using

```shell
code-server --list-extensions | awk '{print $1}' | sed 's|"||g;s|,||g;s|^|code-server --install-extension "|g;s|$|" --force|g'
```

## install extensions  

```shell
code-server --install-extension "Extensions" --force
code-server --install-extension "aaron-bond.better-comments" --force
code-server --install-extension "bierner.emojisense" --force
code-server --install-extension "bierner.markdown-mermaid" --force
code-server --install-extension "bierner.markdown-preview-github-styles" --force
code-server --install-extension "bmalehorn.vscode-fish" --force
code-server --install-extension "coolbear.systemd-unit-file" --force
code-server --install-extension "davidanson.vscode-markdownlint" --force
code-server --install-extension "dbaeumer.vscode-eslint" --force
code-server --install-extension "denoland.vscode-deno" --force
code-server --install-extension "devsense.composer-php-vscode" --force
code-server --install-extension "devsense.intelli-php-vscode" --force
code-server --install-extension "devsense.phptools-vscode" --force
code-server --install-extension "devsense.profiler-php-vscode" --force
code-server --install-extension "dotjoshjohnson.xml" --force
code-server --install-extension "dracula-theme.theme-dracula" --force
code-server --install-extension "dunstontc.viml" --force
code-server --install-extension "editorconfig.editorconfig" --force
code-server --install-extension "esbenp.prettier-vscode" --force
code-server --install-extension "file-icons.file-icons" --force
code-server --install-extension "formulahendry.auto-rename-tag" --force
code-server --install-extension "foxundermoon.shell-format" --force
code-server --install-extension "hangxingliu.vscode-nginx-conf-hint" --force
code-server --install-extension "justusadam.language-haskell" --force
code-server --install-extension "mechatroner.rainbow-csv" --force
code-server --install-extension "mrmlnc.vscode-apache" --force
code-server --install-extension "ms-azuretools.vscode-docker" --force
code-server --install-extension "ms-python.debugpy" --force
code-server --install-extension "ms-python.python" --force
code-server --install-extension "ms-toolsai.jupyter" --force
code-server --install-extension "ms-toolsai.jupyter-keymap" --force
code-server --install-extension "ms-toolsai.jupyter-renderers" --force
code-server --install-extension "ms-toolsai.vscode-jupyter-cell-tags" --force
code-server --install-extension "ms-toolsai.vscode-jupyter-slideshow" --force
code-server --install-extension "ms-vscode.live-server" --force
code-server --install-extension "nico-castell.linux-desktop-file" --force
code-server --install-extension "oderwat.indent-rainbow" --force
code-server --install-extension "redhat.vscode-yaml" --force
code-server --install-extension "ritwickdey.liveserver" --force
code-server --install-extension "rpinski.shebang-snippets" --force
code-server --install-extension "sissel.shopify-liquid" --force
code-server --install-extension "streetsidesoftware.code-spell-checker" --force
code-server --install-extension "tamasfe.even-better-toml" --force
code-server --install-extension "timonwong.shellcheck" --force
code-server --install-extension "vue.volar" --force
code-server --install-extension "wakatime.vscode-wakatime" --force
code-server --install-extension "wscats.eno" --force
code-server --install-extension "yzhang.markdown-all-in-one" --force
```
