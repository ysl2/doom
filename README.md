# Doom Emacs

```bash
# Ref: https://github.com/doomemacs/doomemacs/blob/master/docs/getting_started.org#with-homebrew
brew tap d12frosted/emacs-plus
brew install emacs-plus --with-native-comp
ln -s /opt/homebrew/Cellar/emacs-plus@29/29.4/Emacs.app /Applications/Emacs.app

git clone https://github.com/doomemacs/doomemacs ~/.config/emacs
~/.config/emacs/bin/doom install
~/.config/emacs/bin/doom doctor
~/.config/emacs/bin/doom sync

# Ref: https://github.com/doomemacs/doomemacs/issues/7379#issuecomment-1721756617
M-x nerd-icons-install-fonts
```
