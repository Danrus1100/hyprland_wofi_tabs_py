Python script that helps to switch between workspaces by selecting the desired application in the context menu of wofi

---
![video.mp4]

---

# Installation
 Put the script in a convenient directory (e.g. `~/.config/hypr/scripts/`) and add this to `hyprland.conf`:
 ```
 ....
 
 bind = ALT, tab, exec, python ~/hypr/scripts/hyprland_wofi_tabs.py
 
 ....

```
