# st-build
My build of suckless' Simple Terminal (st) with the following patches applied:

- **st-scrollback**: allows to scroll back the terminal using Shift-Page Up/Page Down.
- **st-scrollback-mouse**: allows to scroll back the terminal using Shift-MouseWheel.
- **st-alpha**: adds transparency support.
- **st-xresources**: adds support for dynamic colors via Xresources file.
- **st-clipboard**: locks the select/paste buffer to the system clipboard to avoid issues pasting from/to other programs.
- **st-font2**: allows st to load a second font to fix powerline/Nerd  font compatibility

For more information, look at the man page `st(1)`.
