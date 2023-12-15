# General

I use the [vim plugin](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) for vim motions and added some keybindings for tab / panel navigation inspired by [NVChad](https://nvchad.com/). Moreover, I use [NeoQwertz](https://www.neo-layout.org/Layouts/neoqwertz/) as my keyboard layout, as it adds a third and fourth layer where special characters sit. This goes very well with vim without using a custom keyboard, as all special characters for navigating vim can be easily reached.

# Keybindings

## Custom bindings for VSCode

| key | what happens |
| --- | --- |
| \<tab> | cycle tabs right |
| \<shift> + \<tab> | cycle tabs left (or cycle terminals, tab is needed for autocomplete) |
| \<ctrl> + hjkl | move panel left, top, down, right |
| \<ctrl> + i | toggle lower panel (terminal, debug output, etc) |
| \<ctrl> + m | comment line (\<ctrl> + k is already in use for panel motions :( )|



## Default bindings on Ubuntu / Windows
| key | what happens |
| --- | --- |
| \<alt-r> + esdf | up, left, down right |
| \<win> + 123... | windows at position in taskbar |
| \<ctrl> + l | focus url bar in browser |
| / | focus search bar in google chrome |
| \<ctrl> + w | close tab in browser |
| \<alt> + 123.. | tabs at position in browser |


## NeoQwertz
| key | what happens |
| --- | --- |
| \<alt-r> + esdf | up, left, down, right |
| \<alt-r> + r | del |
| \<alt-r> + w | backspace |

## New vim commands for me to learn.

| key | what happens |
| --- | --- |
| o | insert mode above | 
| O | insert mode below |
| P | paste above / in front of |
| * | go to next occurence of current word |
| # | go to prev occurence of current word |
| ^ | go to first char in line |
| $ | go to last char in line |
| % | go to corresponding character for character pairs |
| f + \<char> | find char in line after cursor |
| F + \<char> | find char in line before cursor |
| (, ) | jump to beginning of next / previous sentence | 
| {, } | jump to beginning of next / previous paragraph | 

# Open Issues
- [ ] \<ctrl> + hjkl does not work when having a .md preview open and clicked (seems like the tab is not properly focused and vscode does not know the current focus)
