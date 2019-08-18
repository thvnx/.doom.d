# Doom Emacs

## Install Notes

- macOS

``` sh
brew tap d12frosted/emacs-plus
brew install emacs-plus --without-spacemacs-icon
git clone https://github.com/hlissner/doom-emacs.git .emacs.d
cd .emacs.d
./bin/doom quickstart
./bin/doom refresh
./bin/doom refresh -d
```
