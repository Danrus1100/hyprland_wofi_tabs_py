Python script that helps to switch between workspaces by selecting the desired application in the context menu of wofi

---


https://github.com/user-attachments/assets/30561ba7-e1c9-4827-b2c9-889c71480fa5



---

# Installation
 Put the script in a convenient directory (e.g. `~/.config/hypr/scripts/`) and add this to `hyprland.conf`:
 ```
 ....
 
 bind = ALT, tab, exec, python ~/.config/hypr/scripts/hyprland_wofi_tabs.py
 
 ....

```
