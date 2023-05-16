<br>
<h3 align = "center"> Arch Hyprland Dotfiles and Script Installer</h3>
<br>
### Components:

- Main Component: [`Hyprland`](https://github.com/hyprwm/Hyprland)
 
- Terminal: [`Foot`](https://github.com/r-c-f/foot)
 
- Status bar: [`Waybar`](https://github.com/Alexays/Waybar)
 
- Menu : [`Wofi`](https://hg.sr.ht/~scoopta/wofi)

- FIle Manager: [`Thunar`](https://docs.xfce.org/xfce/thunar/start) (Optional)

### FEATURES or Whats included in the dotfiles:
-  By default, Catpuccin Mocha Theme for Hyprland is added

### Miscellaneous (Optional):
-  Themes: `Catppuccin Mocha GTK Theme`
-  Cursor theme: `Catppuccin Cursors`

### Needed packages:
- (all of the above components) plus
- `swaybg` - for wallpaper
- `swwww` - for wallpaper animation
- `swayidle` - not necessary but you can install
- `swaylock-effects` - or swaylock
- `wlroots` `wlogout` `cava` `polkit-kde-agent`
- `mako` - for notifications
- `grim` `slurp` `wl-clipboard` - for screenshot
- `brightnessctl`  - for monitor and keyboard brightness - not needed for desktop
- `mpv` - for wofi beats to work
- `viewnior` or `swayimg`  
- `pamixer` - for volume control notification. 
- `playerctl` - Keyboard hotkeys multimedia controls
- `xorg-xwayland` - needed to run some non-wayland app especially games
- `fonts` - required awesome fonts. AUR and official repo have... else most of the waybar modules wont work. Most of configs here I used Fantasque Sans Mono. I used Cascadia Code Semibold Italic on foot.
- `pipewire` - needed pipewire pipewire-pulse pipewire-alsa
- `xdg-user-dirs` - by default archinstall script does not install this on "minimal" profile. That is why I have added in script

### ✨ Arch Linux quick Installation:
- A guide to install using the install script:[`Youtube Link`](https://youtu.be/sgDJnaMgtY0) 
- a.) You can install one by one packages above or choose the automatic installer script.
- b.) If you want to add or edit packages, edit install-hyprland script. Ensure packages are present on AUR or official else the script will fail.
- c.) Installation of Asus-ROG-utilities are entirely optional. This is only for Asus Laptop. if you select no, will skip the step.
- d.) Thunar and necessary plugins are entirely optional

### ✨ If upgrading from Hyprland-v2, 
- easy way, ran script, script will create back-up of your files and folders (which needed for the config-dots) so you can easily copy over.
- long way, copy the scripts in config/hypr/scripts and copy to your ~/.config/hypr/scripts . Make sure to make them executable after copied. By running chmod +x filename..
- copy the waybar folder in config/hypr/waybar to your ~/.config/hypr/waybar
- copy the wallpapers to your ~/Pictures . Some scripts are checking those folder. If not, modify the scripts changeWallpaper, changeWallpaper2, dark-light-mode, wallpaper-switcher in your ~/.config/hypr/scripts to your actual wallpapers.

### ✨ Some notes regarding using the install script:
- clone this repo by using git. Change directory, make executable and run the script >cd Hyprland-v2 chmod +× install-sh ./install-sh
- Optional stuff you can do using the script includes choices of the following:
-   a.) you can choose either yay or paru (if they are not installed)
-   b.) whether to install none-nvidia patch hyprland package if nvidia gpu detected, 
-   c.) whether to install Catppuccin GTK themes and cursors (Mocha)
-   d.) whether to install thunar and necessary plugins
-   e.) whether to install bluetooth including blueman
-   f.) whether to install and use SDDM as login manager including catppuccin theme
-   g.) whether to install asusctl and supergfxctl (for ASUS rog laptops)
-   h.) whether to disable wifi powersave
-   i.) whether to install xdg-desktop-portal-hyprland

### ✨ NVIDIA-Hyprland notes:
- kindly note, on configs I added all the nvidia variables from Hyprland wiki [`Link`](https://wiki.hyprland.org/Nvidia/) but by default they are not enabled. I've had issues like OBS not recording, or intermittent crashing etc, on my laptop. Check the ~/.config/hypr/configs/exec.conf and uncomment one by one to try. You can read through Hyprland-Wiki for some guidance.

### ✨ Manual Installation and Notes: 
#### you can copy, create, change, however, would appreciate to submit like a pull request or issues if you have a better solution / changes so we will all improve :)

###Please note, Only provided are configs. Any Hyprland-related issues to be reported on Hyprland Github
- a.) Copy / Move files / folders in your ~/.config
- b.) if you have azerty keyboard [`this`](https://github.com/swaywm/sway/issues/1460?fbclid=IwAR1C8VcY_wWbGhXvT-5ApjJCQuJoJzhOVor6o5fdn0Nj1c6bD9JXoQAPQIg) might help

### ✨ know-issues:
- fractional scaling breaks swww