# Install command-line tools and apps using Homebrew
# Usage: `brew bundle install`
# Manish Parashar
# Updated: 20171226

# Install location; export HOMEBREW_CASK_OPTS="--appdir=/Applications"
cask_args appdir: "/Applications"

# Taps
tap "caskroom/cask"
tap "caskroom/fonts"
tap "caskroom/versions"
tap "homebrew/bundle"
tap "homebrew/core"

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
brew "coreutils"
# Install some other useful utilities like `sponge`
brew "moreutils"
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed
brew "findutils"
# Install GNU `sed`, overwriting the built-in `sed`
brew "gnu-sed", args: ['default-names']
# Install Bash 4
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before running `chsh`.
brew "bash"
brew "bash-completion"

# git
brew "git"
brew "git-flow"

# App Store cli
brew "mas"

# Install ZSH
brew "zsh"
brew "zsh-completions"
brew "zsh-syntax-highlighting"

brew "wget", args: ['enable-iri']
brew "vim", args: ['override-system-vi']
brew "tree"
brew "youtube-dl"
brew "neofetch"
brew "tmux"

# casks
cask "alfred"
cask "spectacle"
cask "appcleaner"
cask "cleanmymac"
cask "coconutbattery"
cask "firefox"
cask "google-chrome"
cask "gimp"
cask "vlc"
cask "iina"
cask "iterm2"
cask "macvim"
cask "sublime-text"
cask "visual-studio-code"
cask "dropbox"
cask "spotify"
cask "spotify-notifications"
#cask "slack"
#cask "the-unarchiver"

# Quicklook
cask "qlcolorcode"
cask "qlstephen"
cask "qlmarkdown"
cask "quicklook-json"
cask "qlprettypatch"
cask "quicklook-csv"
cask "qlimagesize"
cask "webpquicklook"
cask "suspicious-package"
cask "quicklookase"
cask "qlvideo"

# Fonts
cask "font-source-code-pro-for-powerline"
cask "font-source-code-pro"
cask "font-source-sans-pro"
cask "font-source-serif-pro"
cask "font-consolas-for-powerline"
cask "font-fira-code"
cask "font-fira-mono-for-powerline"
cask "font-fira-mono"
cask "font-fira-sans"
cask "font-firacode-nerd-font-mono"
cask "font-firacode-nerd-font"
cask "font-firamono-nerd-font-mono"
cask "font-firamono-nerd-font"
cask "font-menlo-for-powerline"

# Install Mac App Store apps
#mas "Numbers", id: 409203825
#mas "Pages", id: 409201541
mas "The Unarchiver", id: 425424353
mas "Amphetamine", id: 937984704
mas "CleanMyDrive 2", id: 523620159
