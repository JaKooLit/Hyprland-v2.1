# Welcome to my Hyprland help, and tips and tricks #
# If you have questions, or need help you can open issue on my github
# Or you can reach me in or join on Discord that I admin
# Discord link https://discord.gg/FW8C9exCE3 or you can message me directly on my discord JaKooLit#2819
# Github page: https://github.com/JaKooLit

  Super = Windows Key

# common operations
  Super          h        *keyhint* (THIS DOCUMENT)
  Super          Return   *term* (`foot`)
  Super          q        *quit* (kill focused window)
  Super   Shift  q        *quit* (kill focused window)
  Super          d        *show app menu* (`wofi small`)
  Super   Shift  d        *show app menu* (`wofi large`)

# wallpaper / styling stuff
  Super           w       *wallpaper shuffle* (right click on wallpaper   waybar module)
  Super   Shift   w       *waybar style-change* (middle click on wallpaper   waybar module)
  Super   Ctrl    w       *wallpaper switcher* (click on wallpaper waybar    module)
  right click on update   waybar module  *wallpaper cycle using swaybg* (no animations)
  To change permanently the wallpaper edit the file in *~/.config/hypr/configs/exec.conf*
  for the wallpaper styles and configurations, you can watch my video about it *https://youtu.be/6ZGzOjMJBe4*
  scripts for wallpaper stuff are located in *~/.config/hypr/scripts* file names `changeWallpaper` `changeWallpaper2` `wallpaper-switcher` `waybar-style-change` (last one for waybar)


# screenshot
  Super PrintSrc(button)       *full screenshot* you may need to press Fn
  Super Shift PrintSrc(button) *active window screenshot*         
  Super CTRL SHIFT PrintSrc    *full screenshot + timer (5s)*

# applications shortcuts
  Super   T		  *file manager* (`thunar`) - if installed

  Keybindings file is located here *~/.config/hypr/configs/keybinds.conf*
  
# container layout
 
  Super   Shift   Space       *toggle tiling/floating mode*
  Super   left mouse button   *move window*
  Super   right mouse button  *resize window* (note only in float mode)


# workspaces
  Super         1 .. 0    *switch to workspace 1 .. 10*
  Super  Shift  1 .. 0    *move container to workspace 1 .. 10*
  Super   Tab             *cycle through workspaces*


# Hyprland configurations
  - *Hyprland* configuration files are in `~/.config/hypr/`
  - files located in this folder can be edited using editor of your choice.

# notes for nvidia gpu users
  - Do note that you need to enable or disable some items in exec.conf file located in `~/.config/hypr/configs/exec.conf`
  
  - a guide on wiki - https://wiki.hyprland.org/Nvidia/


# other notes
  - *Multimedia keys* - may not work for every keyboard may need to hold down the function (`fn`) key
  - Follow the wiki - https://wiki.hyprland.org/
  - Follow the github - https://github.com/hyprwm/Hyprland



TO CLOSE THIS DOCUMENT - Super q or Super Shift q
