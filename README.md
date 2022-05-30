# VS Code
Download [Visual Studio Code](https://code.visualstudio.com/download) for your platform

### Install Extensions
- [C/C++ Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)
- [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Intellicode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Live Share Extension Pack](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack)
- [Live Share Whiteboard](https://marketplace.visualstudio.com/items?itemName=lostintangent.vsls-whiteboard)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [PERL](https://marketplace.visualstudio.com/items?itemName=richterger.perl)
- [PHP Extension Pack](https://marketplace.visualstudio.com/items?itemName=xdebug.php-pack)
- [PlatformIO IDE](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide)
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
- [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)
- [Rust](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust)
- [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

### Install [Nerd Fonts](https://www.nerdfonts.com/)
- [Hack Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Hack.zip)
```
# On Windows, download, extract, select all TTF files, "right click" --> "Install"
# On Raspberry Pi
ssh pi@YourPi
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Hack.zip
unzip Hack.zip -d ~/.fonts
fc-cache -fv
```

### Enable "Auto Save" for file editing
```
# Click: "File" --> "Auto Save"
```

### Enable Font Ligatures using [Cascadia Code](https://github.com/microsoft/cascadia-code)
- Manual download is also available via [Cascadia Code Releases](https://github.com/microsoft/cascadia-code/releases) (Cascadia comes with VS Code)
```
# Click: "File" --> "Preferences" --> "Settings"
# Search for (type): "Font"
# Change "Editor: Font Family" to: "Hack Nerd Font Mono" <--Keep the quotes around that!
# Click: "Edit in settings.json" link and add this code:
    "terminal.integrated.scrollback": 100000000,
    "json.maxItemsComputed": 500000000,
    "workbench.startupEditor": "none",
    "liveshare.audio.startCallOnShare": true,
    "security.workspace.trust.untrustedFiles": "open",
    "explorer.confirmDragAndDrop": false,
    "editor.fontLigatures": true,
    "terminal.integrated.fontFamily": "Hack Nerd Font Mono",
    "editor.fontFamily": "\"cascadia code\"",
    "editor.fontSize": 18,
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": "active",
    "cmake.configureOnOpen": true
```
