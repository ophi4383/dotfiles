![hyprland](https://github.com/ophi4383/dotfiles/blob/main/repo/2023-03-12T14%3A09%3A34%2C102775199%2B01%3A00.png)

# **`DOTFILES`**
my hyprland dotfiles on my endeavouros install :3 

**NOTES:** 
- if there are any instances of `/home/ophi/[...]`, be sure to replace them with *your* username
- i am unsure if these dotfiles work on other distros, so if you'd like to use these dotfiles then i'd recommend getting arch before hand (or any derivative : ) )

# **`INSTALLATION`**
*NOTE: This is a very loose installation guide*
1. Install yay (if not installed already)
2. Use yay to install all dependencies you need (see below)
3. Copy everything from `sddm` to `/usr/share/sddm/themes/`
4. Copy everything from `rofi` to `~/.local/share/rofi/themes`
5. Copy everything from `.config` to `~/.config` (MAKE SURE TO BACKUP BEFOREHAND)
6. Reboot
7. Enjoy :3

# **`DEPENDENCIES`**
- Hyprland (window manager)
	- xdg desktop portal hyprland
- waybar (status bar)
- mako (notification daemon)
- cliphist (clipboard manager)
- rofi lbonn wayland fork (application menu / clipboard viewer)
- dex (autostart stuff)
- kitty (terminal)
- neofetch (neofetch)
- gnome polkit authentification agent
- swaybg (background manager)
- swaylock effects fork (lockscreen)
- grimshot (screenshotting)
	- grim
	- slurp
- firefox (browser)
- dolphin (file manager)
- micro (text editor)
- zsh (used shell)
- sddm (display manager)
- jetbrains mono nerd font (used font in most of the configs)
- themes:
	- catppuccin frappe (gtk, rofi, kvantum)
	- qogir (icons)
	- powerlevel10k (shell theme)
- qt5ct (for qt application themes)
	- Kvantum (for the above as well)
- nwg-look, lxappearance (for gtk application themes)
- sddm config editor (for configuring sddm)

# **`CREDITS`**:
- [EndeavourOS](https://endeavouros.com/) for making the [setup](https://github.com/endeavouros-team/endeavouros-i3wm-setup) which I based these dotfiles on
- [redoverflow](https://github.com/redoverflow) for making the original waybar config (which I based my current waybar config) on hypr
