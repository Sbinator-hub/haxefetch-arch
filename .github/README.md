# Official Arch Linux repo for Haxefetch

## How to install this?

1. Add repo into `/etc/pacman.conf`
```ini
[haxefetch] 
SigLevel = Optional TrustAll 
Server = https://sbinator-hub.github.io/haxefetch-arch/x86_64
```
  2. Refresh Arch repos
`pacman -Syu`

3. Install Haxefetch
`pacman -S haxefetch`

> **Note:** Keep in mind that once i push new changes to Haxefetch repo and turn on actions to merge, you have to wait for bit to GitHub fully syncs this in order to install this with no issue
---
