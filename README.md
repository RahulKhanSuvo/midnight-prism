# Midnight Prism

> A deep dark cyberpunk theme for [Zed](https://zed.dev) — built for long coding sessions with neon-lit syntax, high contrast, and zero eye strain.

---

## Preview

```
 ██████╗██╗   ██╗██████╗ ███████╗██████╗ ██████╗ ██╗   ██╗███╗   ██╗██╗  ██╗
██╔════╝╚██╗ ██╔╝██╔══██╗██╔════╝██╔══██╗██╔══██╗██║   ██║████╗  ██║██║ ██╔╝
██║      ╚████╔╝ ██████╔╝█████╗  ██████╔╝██████╔╝██║   ██║██╔██╗ ██║█████╔╝
██║       ╚██╔╝  ██╔══██╗██╔══╝  ██╔══██╗██╔═══╝ ██║   ██║██║╚██╗██║██╔═██╗
╚██████╗   ██║   ██████╔╝███████╗██║  ██║██║     ╚██████╔╝██║ ╚████║██║  ██╗
 ╚═════╝   ╚═╝   ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝      ╚═════╝ ╚═╝  ╚═══╝╚═╝  ╚═╝
                          MIDNIGHT  PRISM
```

---

## Color Palette

### UI Colors

| Element | Color | Preview |
|---|---|---|
| Background | `#23262E` | ![](https://via.placeholder.com/14/23262E/23262E.png) |
| Sidebar / Panel | `#1e2027` | ![](https://via.placeholder.com/14/1e2027/1e2027.png) |
| Active Line | `#2a2d3a` | ![](https://via.placeholder.com/14/2a2d3a/2a2d3a.png) |
| Foreground Text | `#D5CED9` | ![](https://via.placeholder.com/14/D5CED9/D5CED9.png) |
| Focused Border | `#ff0090` | ![](https://via.placeholder.com/14/ff0090/ff0090.png) |
| Selection | `#00ffff22` | ![](https://via.placeholder.com/14/00ffff/00ffff.png) |

### Syntax Colors

| Scope | Color | Preview |
|---|---|---|
| Keywords | `#ff0090` Neon Pink | ![](https://via.placeholder.com/14/ff0090/ff0090.png) |
| Functions / Properties | `#00ffff` Electric Cyan | ![](https://via.placeholder.com/14/00ffff/00ffff.png) |
| Types / Constructors | `#bf00ff` Electric Purple | ![](https://via.placeholder.com/14/bf00ff/bf00ff.png) |
| Strings | `#39ff14` Neon Green | ![](https://via.placeholder.com/14/39ff14/39ff14.png) |
| Numbers / Labels | `#ffd700` Electric Gold | ![](https://via.placeholder.com/14/ffd700/ffd700.png) |
| Constants / Attributes | `#ff6600` Neon Orange | ![](https://via.placeholder.com/14/ff6600/ff6600.png) |
| Operators / Booleans | `#ff2d78` Hot Pink-Red | ![](https://via.placeholder.com/14/ff2d78/ff2d78.png) |
| Tags (HTML) | `#ff2d78` Hot Pink-Red | ![](https://via.placeholder.com/14/ff2d78/ff2d78.png) |
| React Components | `#bf00ff` Electric Purple | ![](https://via.placeholder.com/14/bf00ff/bf00ff.png) |
| Links / Info | `#0080ff` Electric Blue | ![](https://via.placeholder.com/14/0080ff/0080ff.png) |
| Comments | `#555a6d` Muted | ![](https://via.placeholder.com/14/555a6d/555a6d.png) |

### Status & Git Colors

| State | Color |
|---|---|
| Error | `#ff2d78` Neon Pink-Red |
| Warning | `#ffd700` Electric Gold |
| Success | `#39ff14` Neon Green |
| Info | `#0080ff` Electric Blue |
| Modified | `#ffd700` Electric Gold |
| Added / Created | `#39ff14` Neon Green |
| Deleted | `#ff2d78` Neon Pink-Red |
| Conflict | `#ff6600` Neon Orange |
| Renamed | `#bf00ff` Electric Purple |

---

## Installation

### Via Zed Extension Store *(recommended)*

1. Open Zed and press `Ctrl+Shift+X` to open Extensions
2. Search for **Midnight Prism**
3. Click **Install**
4. Go to `Zed → Settings → Theme` and select **Midnight Prism**

### Manual Install

1. Copy `themes/midnight-prism.json` to your Zed themes folder:

```sh
cp themes/midnight-prism.json ~/.config/zed/themes/
```

2. Open `~/.config/zed/settings.json` and set:

```json
{
  "theme": {
    "mode": "dark",
    "dark": "Midnight Prism"
  }
}
```

---

## Features

- **Cyberpunk-inspired neon palette** — vivid, saturated accent colors on a deep dark background
- **Comfortable dark backgrounds** — easy on the eyes during long coding sessions
- **Full semantic color coverage** — error, warning, success, git status, and conflict states all properly themed
- **Neon-pink active line number** — instantly know which line your cursor is on
- **Cyberpunk terminal colors** — matching neon ANSI palette for the integrated terminal
- **8 player cursors** — distinct neon colors for collaborative editing

---

## Contributing

Found a bug or want to suggest an improvement? Open an issue or PR on [GitHub](https://github.com/RahulKhanSuvo/midnight-prism).

---

## License

MIT © [Rahul](https://github.com/RahulKhanSuvo)
