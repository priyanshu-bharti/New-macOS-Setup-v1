# New-macOS-Setup-v1
Helps you quickly setup macOS for software and web development with some apps and other things.

# Changing default settings

- [ ] Change Input Source to ABC Only
- [ ] Change 3 finger gesture
- [ ] Change autocorrect settings
- [ ] Change the Scaling
- [ ] Change Dock and Menubar settings
- [ ] Rearrange The Apps in Launchpad
- [ ] Remove crap from dock
- [ ] Change Finder settings
- [ ] Change Default Folder
- [ ] Change the statusbar, pathbar, and preview settings in Finder
- [ ] Add another fingerprint

# Install Some Apps from App Store

- [ ] Amphetamine
- [ ] DevSwatch
- [ ] Foldor
- [ ] Notability
- [ ] QuickShade
- [ ] Tot
- [ ] XCode (If Required)

# Install Some Apps from their Websites

- [ ] Amphetamine Enhancer
- [ ] Oracle SQL Developer (If Required)

# Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

# Install Homebrew Packages

### Desktop Applications

```bash
brew install alt-tab
brew install android-file-transfer
brew install figma
brew install github
brew install discord
brew install java
brew install google-chrome
brew install balenaetcher               # if required
brew install intellij-idea-ce
brew install iterm2
brew install megasync
brew install microsoft-excel
brew install microsoft-powerpoint
brew install microsoft-word
brew install microsoft-teams            # if required
brew install onedrive
brew install mos
brew install motrix
brew install notion
brew install raycast
brew install telegram
brew install the-unarchiver
brew install tomighty
brew install visual-studio-code
brew install whatsapp
brew install zoom                       # if required
```

Or you can just use the 1 line command as shown below:

```bash
brew install alt-tab android-file-transfer java discord figma github google-chrome intellij-idea-ce iterm2 megasync microsoft-excel microsoft-powerpoint microsoft-word microsoft-teams onedrive mos motrix notion raycast telegram the-unarchiver tomighty visual-studio-code whatsapp zoom
```

### Command Line Tools

```bash
brew install neofetch
brew install bat
brew install brew-cask-completion
brew install cmake
brew install composer
brew install ffmpeg
brew install eslint
brew install htop
brew install markdown
brew install youtube-dl
brew install thefuck
brew install noti
brew install prettyping
brew install gh
brew install tldr
brew install nvm
brew install pyenv
```

Or you can just use the 1 line command as shown below:

```bash
brew install neofetch bat brew-cask-completion cmake composer ffmpeg eslint htop markdown youtube-dl thefuck noti prettyping gh tldr nvm pyenv
```

# Install Other Developer Tools and IDE

```bash
brew install android-studio
brew install android-ndk
brew install android-sdk
brew install android-platform-tools
brew install flutter
```

Download Liberica JDK from the [this link](https://bell-sw.com/pages/downloads/) and place it in the following directory

```bash
/Library/Java/JavaVirtualMachines
```

# Fonts, Extensions and more

### VSCode Extensions

```bash
auto-close-tag
auto-rename-tag
bracket-pair-toggler
code-runner
code-settings-sync
color-highlight
comment-divider
es7-react-js-snippets
github-markdown-preview
github-vscode-theme
gitlens
icons-carbon
jupyter
jupyter-keymap
jupyter-renderers
live-sass
LiveServer
markdown-checkbox
markdown-emoji
markdown-footnotes
markdown-mermaid
markdown-preview-github-styles
markdown-yaml-preamble
moxer-icons
pdf
prettier-vscode
python
python-environment-manager
remove-comments
sass-indented
tabnine-vscode
vscode-choosealicense
vscode-pylance
vscode-tailwindcss
vscodeintellicode
vscodeintellicode-completions
vsliveshare
```

### IntelliJ Plugins

- Github Theme (Dark Dimmed)
- VSCode Keymap
- Rainbow Brackets
- Nyan Progress Bar

### Chrome Extensions

- Adblock Plus
- Adblocker for youtube
- Whatfont
- Fireshot
- Notion-Enhancer
- Udemy Reset
- CSS Peeper
- Site Palette
- I don’t care about cookies
- JSON Formatter

### iTerm Settings

- Use system window restore policy
- Quitting without confirm
- Profile Settings
  - Minimum Contrast = 50
  - Colors ⇒ Github Theme
  - Text ⇒ SourceCodePro+Powerline+Awesome+Regular
  - Fontsize = 14
  - Window ⇒ Transparency = 40 + Blur (Radius = 20)
  - Window Columns = 100
  - Profile ⇒ Key ⇒ Mapping ⇒ Natural Text Editing

### PyENV Commands

```bash
pyenv install -l # List all the python versions
pyenv global <version>
pyenv local <version>
```

### NVM Commands

```bash
nvm install <version> # install specific version of node
nvm use <version> # Change the node version

node --version
```

### Fonts

- Hasklig
- Ubuntu Mono
- SourceCodePro+Powerline+Awesome+Regular
- Lexend
- Nunito
- Poppins
- Inter
