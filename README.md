# New mac developer setup guide

## Applications to install && relevant config:

- LastPass: https://lastpass.com/misc_download2.php
  - Install the chrome plugin and login
  
- Google Chrome: https://www.google.com/chrome/browser/

- Spotify: https://www.spotify.com/us/download/mac/

- Karabiner Elements: https://pqrs.org/osx/karabiner/
  - Enable "Vi Mode, left_control + hjkl. shift/option/command + arrow working." in complex modifications
  - Map Caps locks to escape in simple modifications

- Iterm2: https://www.iterm2.com/downloads.html

- VsCode: https://code.visualstudio.com/download

- Rectangle: https://rectangleapp.com/
  - Configure shortcuts to your liking
  
- Alfred: https://www.alfredapp.com/
  - Map *Cmd + Space* to Alfred
    - Deactive the shortcut for spotlight search
    - Go to Alfred Preferences -> General -> Hotkey

## OS Configuration:

- Enable tap with one finger in Trackpad Settings
- Enable "three finger drag": https://support.apple.com/en-us/HT204609
- In Keyboard settings, set *Key Repeat* and *Delay Until Repeat* to the highest setting
- Only show running apps in the dock: `defaults write com.apple.dock static-only -bool true; killall Dock`

## Terminal Configuration:

- Install homebrew: https://brew.sh/
- Install zsh and ohmyzsh: http://sourabhbajaj.com/mac-setup/iTerm/zsh.html
  - to fixture the question marks in the theme: https://github.com/robbyrussell/oh-my-zsh/issues/1906#issuecomment-252443982
- Install python3 w/ `brew install python`


