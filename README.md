# Dual Monitor Selector

This python script lets you change your monitor displays. It works only with dual monitors. I you have only one monitor plugged or using only laptop's built-in display, it selects that one.

This program has 5 mod:

1. Mirror display
2. Primary on right
3. Primary on left
4. Only Primary
5. Only Secondary

# Installation

Just copy file called monitor to ~/.config/i3/ location.

And this is the code for assigning this script to a shortcut in i3 config:  

```
bindsym $mod+Shift+p exec ~/.config/i3/monitor
```
