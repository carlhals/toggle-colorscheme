# toggle_colorscheme

This extension implements a toggle between solarized dark and solarized light for URxvt

## Setup

1. Clone the repository and copy the **colorscheme** script to wherever your URxvt extensions live (Sometimes __~/.urxvt/ext__

2. Make sure the following exists somewhere in your .Xresources or .Xdefaults::
```
    URxvt.perl-ext-common:      colorscheme
    URxvt.keysym.Mod4-c:        perl:colorscheme:toggle
```
3. After merging the changes with `xrdb -merge ~/.Xresources` or something similar you can enjoy color switching in a **new** urxvt-terminal by pressing _Super-c_.

