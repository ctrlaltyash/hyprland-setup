# <h1>Hyprland-Setup for Beginner</h1>
> A beginner-friendly Hyprland rice for EndeavourOS/ Arch — functional out of the box, with room to explore.

This is a heavily customized fork of [Maciejonos/dotfiles](https://github.com/Maciejonos/dotfiles) by **Maciej** ([@Maciejonos](https://github.com/Maciejonos)), with contributions from **chadclancy** and **Eric Yu** ([@yu-eric](https://github.com/yu-eric)). Full credit to them for the foundation — I made it more beginner-friendly and added some quality-of-life tweaks.

---

<img width="1920" height="1200" alt="2026-04-02_18-16-23" src="https://github.com/user-attachments/assets/f7d0a15c-fa39-4fc6-9377-b4ac767fc10e" />
<img width="1920" height="1200" alt="2026-04-02_18-15-51" src="https://github.com/user-attachments/assets/149522b5-9968-4a42-aeb2-8d28a6ad9004" />
<img width="1920" height="1200" alt="2026-04-02_18-13-44" src="https://github.com/user-attachments/assets/5716f63d-c984-4719-9ca6-c8046ce3c715" />
<img width="1920" height="1199" alt="2026-04-02_18-13-01" src="https://github.com/user-attachments/assets/69c242ef-e6ef-49dd-bb3a-6357e2f6e672" />
<img width="1920" height="1200" alt="2026-04-02_18-11-55" src="https://github.com/user-attachments/assets/62e1bd8f-7a3c-4a7a-b2df-b80db26f0ef8" />



## What you get

- **Hyprland** — tiling window manager with smooth animations and blur
- **Waybar** — a clean status bar with working modules
- **Kitty** — terminal emulator
- **Rofi** — app launcher
- **Waypaper** — GUI wallpaper picker (no terminal needed)
- **awww** — wallpaper daemon with transition animations
- **Tokyo Night** color scheme throughout


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

<h2>Then follow the setup instructions from the https://github.com/Maciejonos/dotfiles. </h2>

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


<h3> Maintained by Kalepu Yashvardhan; Please feel free to reach out :) </h3>
