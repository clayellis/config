# Config
A place to store general configuration files

## Files

### [Default.idekeybindings](Default.idekeybindings)
This file contains custom key bindings for Xcode that I like to use. It should be placed under `~/Library/Developer/Xcode/UserData/KeyBindings/`

## Commands

### Key Repeat

I like to decrease both the `InitialKeyRepeat` and `KeyRepeat` speeds via Terminal to move through text quicker.
```shell
defaults write -g InitialKeyRepeat -int 10 # normal minimum is 15 (225 ms)
defaults write -g KeyRepeat -int 1 # normal minimum is 2 (30 ms)
```

## Apps

- [Hand Mirror](https://apps.apple.com/us/app/hand-mirror/id1502839586?mt=12) — Super simple app for previewing FaceTime camera.
