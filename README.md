# i3 Ubuntu Configuration
Some Minor i3 customization with polybar !


Polybar-2:
# ![Polybar-2 Demo image](Demo/polybar.png) 

Internal:-
The Artwork's of many artist are in this wallpaper colletion , i would love to give credit's for each one ~! 
but i kinda don't know who's are which and most of these wallpapers where taken from # https://wallhaven.cc/
sorry ~!in advance

> **Note:**
> This is a personal setup. Use at your own risk — issues may require manual troubleshooting.

## Required Packages
Install with:

```bash
sudo apt install i3 rofi compton nitrogen polybar arandr playerctl dunst fonts-noto lxappearance pulseaudio-utils network-manager network-manager-gnome flameshot git unclutter
```

### Package Overview
* **i3** – Window manager
* **Rofi** – Application launcher
* **Compton** – Compositor for transparency
* **Nitrogen / Feh** – Wallpaper manager
* **Polybar** – Custom status bar
* **Arandr** – Display configuration tool
* **Playerctl** – Media control for Polybar
* **Dunst** – Notifications
* **Fonts-Noto** – Clean, readable font
* **LXAppearance** – Change GTK themes and icons
* **Flameshot** – Screenshot tool
* **Unclutter** – Hides cursor when idle

## Configuration Overview
* **Polybar** replaces i3status for a customizable bar.
* **Nitrogen & Compton** autostart for wallpaper and compositing.
* **Rofi** is themed as the app launcher.
* **Arandr** helps with multi-monitor setups.
* **Dunst** handles notifications.
* **LXAppearance** manages GTK themes and icons.

## Installation Steps
1. **Update system:**

   ```bash
   sudo apt update && sudo apt upgrade
   ```

2. **Install packages:**

   ```bash
   sudo apt install i3 rofi compton nitrogen polybar arandr playerctl dunst fonts-noto feh lxappearance xclip pulseaudio-utils network-manager network-manager-gnome flameshot git unclutter
   ```

3. **Clone the repository:**

   ```bash
   git clone https://github.com/zionnewbie/ubuntu.git
   ```

4. **Copy configurations and as respctive directorys**

   like  
   ```bash
   i3 config : $HOME/.config/i3/
   Rofi      : $HOME/.config/rofi/
   Polybar   : $HOME/.config/Polybar
   ```

5. **Log out and select i3** from your login manager.


## Customization
* Edit `~/.config/i3/config` for keybindings and startup apps.
* Adjust Polybar in `~/.config/polybar/config`.
* Use **LXAppearance** for themes and icons.
* Set wallpapers with **Nitrogen**.
* Modify Rofi themes in `~/.config/rofi/`.


## Troubleshooting
* Check `~/.xsession-errors` for startup issues.
* Install missing fonts/icons if something looks off.
