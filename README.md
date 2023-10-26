# ubuntu

## Change hotkey

### Change language

From WIN-Space to Alt-Shift

```bash
gsettings set org.gnome.desktop.wm.keybindings switch-input-source "['<Alt>Shift_L', 'XF86Keyboard']"
```

From Alt+Shift to WIN-Space (Super-Space)

```bash
gsettings set org.gnome.desktop.wm.keybindings switch-input-source "['<Super>space', 'XF86Keyboard']"
```
