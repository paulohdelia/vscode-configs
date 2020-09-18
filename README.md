# vscode-configs

## List installed extensions

### Linux
```bash
code --list-extensions | xargs -L 1 echo code --install-extension
```

### Windows (Powershell)
```bash
code --list-extensions | % { "code --install-extension $_" }
```

## Install extensions
```bash
code --install-extension bierner.github-markdown-preview
code --install-extension bierner.markdown-checkbox
code --install-extension bierner.markdown-emoji
code --install-extension bierner.markdown-preview-github-styles
code --install-extension bierner.markdown-yaml-preamble
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension dbaeumer.vscode-eslint
code --install-extension DigitalBrainstem.javascript-ejs-support
code --install-extension EditorConfig.EditorConfig
code --install-extension esbenp.prettier-vscode
code --install-extension eseom.nunjucks-template
code --install-extension formulahendry.auto-rename-tag
code --install-extension kamikillerto.vscode-colorize
code --install-extension ms-azuretools.vscode-docker
code --install-extension PKief.material-icon-theme
code --install-extension redhat.java
code --install-extension ricardo-emerson.create-react-tsx-component
code --install-extension ritwickdey.live-sass
code --install-extension ritwickdey.LiveServer
code --install-extension rocketseat.theme-omni
code --install-extension ronnidc.nunjucks
code --install-extension syler.sass-indented
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension vscjava.vscode-java-debug
code --install-extension vscjava.vscode-java-dependency
code --install-extension vscjava.vscode-java-pack
code --install-extension vscjava.vscode-java-test
code --install-extension vscjava.vscode-maven
```
