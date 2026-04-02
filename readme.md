# hyprland-setup 🌸
> A beginner-friendly Hyprland rice for EndeavourOS/ Arch — functional out of the box, with room to explore.

This is a lightly customized fork of [Maciejonos/dotfiles](https://github.com/Maciejonos/dotfiles) by **Maciej** ([@Maciejonos](https://github.com/Maciejonos)), with contributions from **chadclancy** and **Eric Yu** ([@yu-eric](https://github.com/yu-eric)). Full credit to them for the foundation — I made it more beginner-friendly and added some quality-of-life tweaks.

---


## What you get

- **Hyprland** — tiling window manager with smooth animations and blur
- **Waybar** — a clean status bar with working modules
- **Kitty** — terminal emulator
- **Rofi** — app launcher
- **Waypaper** — GUI wallpaper picker (no terminal needed)
- **awww** — wallpaper daemon with transition animations
- **Tokyo Night** color scheme throughout

---

## Keybindings (the important ones)

| Keys | Action |
|------|--------|
| `SUPER + Q` | Open terminal |
| `SUPER + W` | Close window |
| `SUPER + R` | Run launcher |
| `SUPER + D` | App launcher (rofi) |
| `SUPER + F` | Fullscreen |
| `SUPER + T` | Toggle floating |
| `SUPER + ALT + SPACE` | Extra interface / scratchpad |
| `SUPER + ALT + W` | Waypaper (wallpaper picker) |
| `SUPER + 1–5` | Switch workspaces |
| `SUPER + SHIFT + 1–5` | Move window to workspace |
| `SUPER + Arrow keys` | Move focus |
| `SUPER + SHIFT + L` | Logout |

---

## Requirements

- EndeavourOS (or any Arch-based distro)
- Hyprland
- Make sure bluetooth and NetworkManager services are enabled:

```bash
sudo systemctl enable --now bluetooth
sudo systemctl enable --now NetworkManager
```

---

## Installation

> ⚠️ Back up your existing configs before doing this.

```bash
git clone https://github.com/ctrlaltyash/hyprland-setup.git ~/.local/share/dotfiles
```

Then follow the setup instructions from the [original repo](https://github.com/Maciejonos/dotfiles).

---

## What I changed

- Added beginner-friendly keybindings
- Set up `waypaper` as a GUI wallpaper picker
- Added `awww` wallpaper daemon with wave transition animations
- Custom blur, rounding, and animation config in `hyprland.conf`
- Fixed empty wallpaper script (`wallpaper.sh`)
- General quality-of-life tweaks for daily use

---

## Credits

| Person | Contribution |
|--------|-------------|
| [Maciejonos](https://github.com/Maciejonos) | Original dotfiles |
| [chadclancy](https://github.com/chadclancy) | Contributions to original |
| [yu-eric](https://github.com/yu-eric) | Contributions to original |
| [ctrlaltyash](https://github.com/ctrlaltyash) | Beginner-friendly fork |

---

## License

MIT — do whatever you want, just keep the credits 🙂
