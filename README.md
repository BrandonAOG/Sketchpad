# AOG Drawing Pad — GitHub README

```markdown
# ✏️ Always On Generators — Site Drawing Pad

![AOG Logo](https://raw.githubusercontent.com/BrandonAOG/AOG-Logo/main/logo.png)

A professional, browser-based site drawing tool built for Always On Generators field technicians and estimators. Create accurate site layout drawings directly on a tablet or desktop — no software installation required.

---

## 🌐 Live App

👉 [Launch Drawing Pad](https://brandonaog.github.io/AOG-drawing-pad/)

---

## 📋 Features

### 🖊️ Drawing Tools
| Tool | Key | Description |
|------|-----|-------------|
| Select | `V` | Select, move, and resize objects |
| Pen | `P` | Freehand drawing |
| Line | `L` | Straight line |
| Arrow | `A` | Line with arrowhead |
| Rectangle | `R` | Filled or outlined box |
| Circle | `C` | Ellipse / circle |
| Polygon | `O` | Multi-point shape (double-click to finish) |
| Text | `T` | Add labels and annotations |
| Measure | `M` | Distance measurement with label |
| Eraser | `E` | Remove objects by click |

### ⚡ Symbol Library
Pre-drawn symbols organized by category:

- **Electrical** — Generator, Transfer Switch, Circuit Breaker, Disconnect, GFCI, Ground, Junction Box, Panel Board, Sub Panel, Meter, Transformer, Capacitor, Resistor, Fuse, Switch, Lighting, Motor, Battery
- **Gas / Fuel** — Gas Meter, Propane Tank, LP Tank (Underground), Ball Valve, Check Valve, Regulator, Tee Connection, Elbow 90°
- **Site / Misc** — House Outline, North Arrow, Property Line, Setback Line, Concrete Pad, Underground Line, Conduit Run

### 🎨 Style Controls
- Stroke color picker + 7 preset colors
- Fill color picker
- Stroke width (1 / 2 / 4 / 8 px + custom)
- Line style: Solid / Dashed / Dotted
- Font size (10–20 px)
- Opacity slider (5–100%)

### 📐 Canvas
- Fixed **8.5 × 11 inch** paper (816 × 1056 px at 96 DPI)
- Grid overlay with major/minor lines
- Snap-to-grid toggle
- Zoom in / out / reset
- Multi-layer canvas (grid, main, overlay)

### 🔧 Object Management
- **8-point resize handles** on all selected objects
- Move by drag
- Right-click context menu:
  - Copy / Paste / Duplicate
  - Bring to Front / Send to Back
  - Delete

### 💾 Save & Export
- **PNG export** — full resolution canvas image
- **PDF export** — opens print dialog for PDF save
- **Auto-save** — saves to browser localStorage every 10 seconds

### 🌙 UI / UX
- Light and dark mode toggle
- **Toolbar on/off toggle** (button or press `H`)
- Responsive layout for iPad / tablet use
- Touch-action optimized for stylus and finger input
- Keyboard shortcuts for all major tools

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `V` | Select tool |
| `P` | Pen tool |
| `L` | Line tool |
| `A` | Arrow tool |
| `R` | Rectangle tool |
| `C` | Circle tool |
| `T` | Text tool |
| `M` | Measure tool |
| `E` | Eraser tool |
| `H` | Toggle toolbar |
| `+` | Zoom in |
| `-` | Zoom out |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `Ctrl+C` | Copy selected |
| `Ctrl+V` | Paste |
| `Delete` | Delete selected |
| `Escape` | Cancel / deselect |

---

## 🚀 Usage

### Option 1 — GitHub Pages (Recommended)
No setup needed. Open the live link above on any modern browser.

### Option 2 — Run Locally
```bash
git clone https://github.com/BrandonAOG/AOG-drawing-pad.git
cd AOG-drawing-pad
# Open index.html in any browser
open index.html
```

> No build tools, no dependencies, no server required.  
> Everything runs in a single `index.html` file.

---

## 📱 Device Compatibility

| Device | Support |
|--------|---------|
| iPad (Safari) | ✅ Full touch support |
| iPhone | ✅ Works, best on iPad |
| Android Tablet | ✅ Chrome recommended |
| Desktop (Chrome/Edge/Firefox) | ✅ Full support |
| Apple Pencil | ✅ Pointer events supported |

---

## 🗂️ File Structure

```
AOG-drawing-pad/
│
├── index.html          # Complete single-file application
└── README.md           # This file
```

---

## 🔮 Planned Features

- [ ] Scale bar with real-world unit input (feet / meters)
- [ ] Multi-select with drag box
- [ ] Custom symbol upload
- [ ] Drawing title block / stamp
- [ ] Project save/load (JSON file export)
- [ ] Text edit on double-click
- [ ] Snap-to-object / snap-to-edge

---

## 🏢 About

Built for **Always On Generators** — providing reliable standby power solutions.

- 🌐 [Main Hub](https://brandonaog.github.io/AOG-hub/)
- 📧 Contact: Always On Generators field team

---

## 📄 License

Internal use — Always On Generators © 2025  
Not for public redistribution without permission.
```

---

## 📁 How to Add to Your Repo

1. Create a file called **`README.md`** in the root of your repository
2. Paste the content above
3. Commit and push — GitHub will render it automatically on the repo homepage
