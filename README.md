# Basel
- This is a fork of end-4's hyprland flake for my own use
- I'm not experienced in nixOS but it'll be my daily driver for the foreseeable future

# Installation
## **CHANGE THE HARDWARE CONFIG**
- This flake includes settings unique to my system and unless you're on my computer you must change them before installing

## Installing the whole system
- This is more of a "just for me" thing but i'll add a guide here in case I get amnesia

```bash
git clone https://github.com/Imerere/Basel.git && cd Basel
IMPURITY_PATH=$(pwd) sudo --preserve-env=IMPURITY_PATH nixos-rebuild switch --flake . --impure
```
