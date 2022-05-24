# My .files for macOS

Looking for this?
![Terminal](terminal.png)

## Installing iTerm2 with oh-my-zsh

### iTerm2
[Install this](https://www.iterm2.com/) and never use the default Terminal.app again.

### Install Source Code Pro
[Get it here](https://github.com/adobe-fonts/source-code-pro/releases/tag/2.030R-ro%2F1.050R-it). Download the source code zip file, then navigate to the `OTF` folder. Open `SourceCodePro-Regular.otf` and click "Install Font".

### Finalise iTerm2 Settings
 - Preferences → General → "Load preferences from a custom folder or URL:" set to the `iTerm2` folder in this repo.
 - Profiles → Other Actions → "Import JSON profiles..." choose the `profiles.json` file in the `iTerm2` folder.
 - Delete the original "Default" profile and allow your new one to become the default.
 - Install Shell Integration.

### oh-my-zsh
    
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    
When the installation is done, edit `~/.zshrc` based on the `zshrc` file in the `zsh` folder in this repo.

Restart iTerm2 for all changes to take effect.

## Other Programs to Install
 - [Brew](https://brew.sh/)
 - [Docker](https://docs.docker.com/docker-for-mac/install/)
 - [nvm](https://github.com/nvm-sh/nvm)
 - [VS Code](https://code.visualstudio.com/docs?dv=osx)
 - [Crypto Touchbar](https://chrislennon.github.io/Crypto-Touchbar-App/)

## Other Configs
 
### VS Code
 - Open VS Code
 - Go into the User Settings (`⌘` + `,`) and copy in the `settings.json` from the `VSCode` folder.
 - `⌘` + `⇧` + `P`, then type `code` and click `Shell command: install...`
