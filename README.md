# 🖊️ Whiteboard Application

> An interactive whiteboard built with React.js and HTML5 Canvas — featuring 7 drawing tools, real-time state management via Context API, and undo/redo support.

**Live Demo:** [Try it Now 🎨](https://whiteboard-theta-teal.vercel.app/)

---

## ✨ Features

- 7 drawing tools — Brush, Line, Rectangle, Circle, Arrow, Text, and Eraser
- Undo / Redo with full history tracking
- Stroke color, fill color, and brush size customization per tool
- Freehand drawing powered by `perfect-freehand`
- Text input directly on the canvas
- Real-time drawing state managed via React Context API
- Smooth canvas interactions optimized for 1000+ drawing actions

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Framework | React.js |
| Rendering | HTML5 Canvas |
| Styling | Tailwind CSS |
| State Management | React Context API + useReducer |
| Drawing | perfect-freehand |
| Deployment | Vercel |

---

## 📦 Getting Started

```bash
git clone https://github.com/nishant-2111/whiteboard-app.git
cd whiteboard-app
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
src/
├── components/
│   ├── Board.js          # Canvas rendering & event handling
│   ├── Toolbar.js        # Undo, redo, and tool controls
│   └── Toolbox.js        # Stroke, fill, and size options
├── store/
│   ├── BoardProvider.js      # Drawing state & actions
│   ├── board-context.js      # Board context definition
│   ├── ToolboxProvider.js    # Toolbox state & actions
│   └── toolbox-context.js    # Toolbox context definition
├── utils/
│   └── element.js        # Element creation & geometry helpers
├── constants.js          # Tool types, colors, action constants
└── App.js
```

---

## 🎨 Available Tools

| Tool | Description |
|---|---|
| ✏️ Brush | Freehand drawing |
| ➖ Line | Straight lines |
| ▭ Rectangle | Outlined or filled rectangles |
| ⭕ Circle | Outlined or filled circles |
| ➡️ Arrow | Directional arrows |
| 🔤 Text | Type directly on canvas |
| 🧹 Eraser | Erase elements by proximity |

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |

---

## 📄 License

This project is open source. Feel free to explore, fork, and contribute!
