
# Doma ToDoTask

> Clean, focused task management with dark mode, smooth animations, and persistent storage. No signups, no distractions — just your tasks, your way.

**Live app:** [https://modoma8.github.io/ToDoList/](https://modoma8.github.io/ToDoList/)

---

## Features

| Feature | What it does |
|---------|---------------|
| 📋 Task management | Add, edit, complete, and delete tasks |
| 🌙 Dark mode | Toggle light/dark themes — your preference is saved |
| 🎯 Smart filters | All / Active / Completed — one click to focus |
| 📊 Live stats | Total, done, active counts update instantly |
| 💾 Auto-save | Everything stays in your browser (localStorage) |
| ⌨️ Keyboard friendly | Press Enter to add tasks faster |
| 📱 Responsive | Works on desktop, tablet, and mobile |
| ✨ Smooth animations | Subtle motion that feels natural |

---

## How to use

```
1. Type a task → click "Add" or press Enter
2. Click the circle to mark complete
3. Click the pencil to edit
4. Click the trash to delete
5. Use All / Active / Completed to filter
6. Click the moon/sun icon in the header for dark mode
```

That's it. No hidden menus, no complicated setup.

---

## Built with

- HTML5
- CSS3 (gradients, dark mode, animations)
- JavaScript (ES6)
- Font Awesome 6
- Google Fonts (Inter)
- LocalStorage

---

## Project structure

This is a single-file application:

```
ToDoList/
└── index.html     # HTML, CSS, and JavaScript all together
```

Clone it, host it anywhere, or just save and double-click.

---

## How data is saved

Your tasks are stored in your browser's localStorage under the key `doma_tasks_v2`.

**To reset all tasks** – open DevTools (F12) and run:

```javascript
localStorage.removeItem("doma_tasks_v2");
location.reload();
```

---

## Dark mode

- Toggle button in the top-right corner (🌙 / ☀️)
- Theme preference is saved automatically
- All cards, text, borders, and shadows adapt

---

## Responsive behavior

| Screen width | What changes |
|--------------|---------------|
| > 550px | Full layout with button labels |
| ≤ 550px | Compact layout, icon-only buttons |

---

## Tested on

- Chrome (desktop + mobile)
- Firefox
- Safari (macOS + iOS)
- Edge
- Samsung Internet

---

## Customize

All styles and logic are inside one HTML file. Open it and look for:

- **Colors** – search for `body.light` and `body.dark` in the `<style>` section
- **Animation speed** – find `transition: all 0.25s` or `@keyframes fadeOut`

---

## License

MIT – use it freely, modify it, share it.

---

**Live app:** [https://modoma8.github.io/ToDoList/](https://modoma8.github.io/ToDoList/)

---

*"Clear mind · sharp focus" – Doma ToDoTask*

---

Just copy everything above and paste it into your `README.md` file on GitHub. No special formatting needed — it will render properly.
