Sure, here is a sample `skhdrc` file for `yabai` window manager:

```
# Move focus to the left window
alt - h : yabai -m window --focus west

# Move focus to the right window
alt - l : yabai -m window --focus east

# Move focus to the top window
alt - k : yabai -m window --focus north

# Move focus to the bottom window
alt - j : yabai -m window --focus south

# Move window to the left
shift + alt - h : yabai -m window --warp west

# Move window to the right
shift + alt - l : yabai -m window --warp east

# Move window to the top
shift + alt - k : yabai -m window --warp north

# Move window to the bottom
shift + alt - j : yabai -m window --warp south

# Resize window to the left
ctrl + alt - h : yabai -m window --resize left:5

# Resize window to the right
ctrl + alt - l : yabai -m window --resize right:5

# Resize window to the top
ctrl + alt - k : yabai -m window --resize top:5

# Resize window to the bottom
ctrl + alt - j : yabai -m window --resize bottom:5

# Make window full screen
alt - f : yabai -m window --toggle zoom-fullscreen

# Toggle window float
shift + alt - space : yabai -m window --toggle float

# Toggle window split
shift + alt - s : yabai -m space --toggle split

# Toggle window parent split
shift + alt - d : yabai -m display --toggle split

# Toggle window sticky
shift + alt - t : yabai -m window --toggle sticky

# Toggle window border
shift + alt - b : yabai -m window --toggle border

# Toggle window grid
shift + alt - g : yabai -m window --grid 3:2:0:0:0:0

# Toggle window stack
shift + alt - a : yabai -m window --toggle stack

# Toggle window mirror
shift + alt - m : yabai -m window --toggle mirror

# Toggle window rotate
shift + alt - r : yabai -m window --rotate 90

# Toggle window layout
shift + alt - e : yabai -m space --toggle layout

# Toggle window layout
shift + alt - c : yabai -m space --toggle padding

# Toggle window layout
shift + alt - n : yabai -m space --toggle gap

# Toggle window layout
shift + alt - x : yabai -m window --toggle idempotent

# Toggle window layout
shift + alt - z : yabai -m window --toggle split type:vertical

# Toggle window layout
shift + alt - v : yabai -m window --toggle split type:horizontal

# Toggle window layout
shift + alt - q : yabai -m window --toggle split ratio:-0.05

# Toggle window layout
shift + alt - w : yabai -m window --toggle split ratio:+0.05

# Toggle window layout
shift + alt - u : yabai -m window --toggle split ratio:-0.01

# Toggle window layout
shift + alt - i : yabai -m window --toggle split ratio:+0.01

# Toggle window layout
shift + alt - o : yabai -m window --toggle split ratio:0

# Toggle window layout
shift + alt - p : yabai -m window --toggle split ratio:1

# Toggle window layout
shift + alt - y : yabai -m window --toggle split ratio:-0.1

# Toggle window layout
shift + alt - t : yabai -m window --toggle split ratio:+0.1

# Toggle window layout
shift + alt - g : yabai -m window --toggle split ratio:-0.01

# Toggle window layout
shift + alt - h : yabai -m window --toggle split ratio:+0.01

# Toggle window layout
shift + alt - j : yabai -m window --toggle split ratio:-0.001

# Toggle window layout
shift + alt - k : yabai -m window --toggle split ratio:+0.001

# Toggle window layout
shift + alt - l : yabai -m window --toggle split ratio:0.5

# Toggle window layout
shift + alt - ; : yabai -m window --toggle split ratio:0.6

Source: Conversation with Bing, 1/15/2024
(1) julian-heng/yabai-config - GitHub. https://github.com/Julian-Heng/yabai-config.
(2) yabai and skhd configs · GitHub. https://gist.github.com/samundra/495827fb58cbb636786795c13fcbaff2.
(3) GitHub - Shammyshanks/Yabai-SKHD-Config: My personal Yabai and SKHD .... https://github.com/Shammyshanks/Yabai-SKHD-Config.
(4) ⚙️ My yabai and skhd configuration files. · GitHub. https://gist.github.com/armand1m/4094b37d8969fd365fdcc215277e9e67.
(5) undefined. https://github.com/Julian-Heng/yabai-config.git.
