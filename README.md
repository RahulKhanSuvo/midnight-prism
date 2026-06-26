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

| Element | Color |
|---|---|
| Background | `#23262E` |
| Sidebar / Panel | `#1e2027` |
| Active Line | `#2a2d3a` |
| Foreground Text | `#D5CED9` |
| Focused Border | `#ff0090` |
| Selection | `#00ffff22` |

### Syntax Colors

| Scope | Color |
|---|---|
| Keywords | `#ff0090` Neon Pink |
| Functions / Properties | `#00ffff` Electric Cyan |
| Types / Constructors | `#bf00ff` Electric Purple |
| Strings | `#39ff14` Neon Green |
| Numbers / Labels | `#ffd700` Electric Gold |
| Constants / Attributes | `#ff6600` Neon Orange |
| Operators / Booleans | `#ff2d78` Hot Pink-Red |
| Tags (HTML) | `#ff2d78` Hot Pink-Red |
| React Components | `#bf00ff` Electric Purple |
| Links / Info | `#0080ff` Electric Blue |
| Comments | `#555a6d` Muted |

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
