# 🐍 Terminal Snake Game — Fully Styled with Textual CSS

A classic Snake game rendered in the terminal using **Textual**, but with one twist:  
**The entire visual style is controlled through CSS variables**, not Python.

You will learn how to use CSS for colors, animations, state styles, and themes.

---

## 🎯 Core Mechanics

- Move snake with arrow keys (or WASD)
- Eat food to grow
- Game over on collision
- Score HUD at top or sidebar

Example layout:
```
┌────────────────────────────┐
│ ░░░░░░░░░░░░░░░░░░░░░░░░░ │
│ ░■■■■░░░░░░░░░░░░░░░░░░░░ │
│ ░░░■░░░░░░░░○░░░░░░░░░░░░ │
│ ░░░■░░░░░░░░░░░░░░░░░░░░░ │
│ ░░░■░░░░░░░░░░░░░░░░░░░░░ │
└────────────────────────────┘
```

---

## 🖌 CSS-Focused Requirements

| Requirement | Focus |
|-------------|-------|
| Colors use CSS vars | `--snake-color`, `--food-color`, etc. |
| Themes are pure CSS | neon.css, pastel.css, matrix.css |
| Game states styled via classes | `.game.running`, `.game.over` |
| Food pulse animation | `@keyframes pulse` |
| Snake death flash | timed CSS transition or class update |

---

## 🧪 Themes You Can Create

| Theme | Description |
|--------|-------------|
| retro_green | DOS style black + neon green |
| pastel | soft friendly colors |
| synthwave | purple + neon blues |
| matrix | falling green ASCII bg |

---

## 🗂 Suggested Folder Structure

```
snake-css/
    app.py
    game.py
    ui.py
    themes/
        retro.css
        pastel.css
        synthwave.css
        matrix.css
```

---

## ⌨️ Controls

| Key | Action |
|-----|--------|
| ↑ ↓ ← → / WASD | move |
| P | pause |
| R | restart |
| T | cycle themes |

---

## 🧩 Bonus Challenges

| Idea | Skill |
|------|-------|
| Snake speed increases per food | dynamic game speed |
| "Hard mode" with walls | map switching |
| Live theme editor panel | change CSS vars at runtime |
| High score saved to file | persistence |

---

## 📌 Learning Outcome Checklist

✅ CSS variables for theming  
✅ Class-driven UI state styling  
✅ Animated effects using pure CSS  
✅ Responsive layout and fixed-ratio grid  
✅ Clean separation: **Python = logic, CSS = presentation**

---

Have fun and style your snake 🎨🐍