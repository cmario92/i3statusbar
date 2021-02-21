# Installation Guide

- copy all `.sh` scripts to `~/.config/i3status/`
- ~/.config/i3/config
  - add this block of code at the end
  ```sh
    bar {
        status_command exec ~/.config/i3status/mybar.sh
    }
  ```
