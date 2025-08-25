# ASCII / Unicode Tree Builder — Vanilla JS

A simple, **vanilla JavaScript** tool to convert indented outlines into a tree structure with ASCII, Unicode, or minimal symbols. No dependencies, works in any modern browser.

---

## 🔗 Live Demo

[View Live Demo](https://ezmu.github.io/ascii-tree-builder/)

---

## 📝 Usage

1. Type or paste your indented outline in the **input** box.
2. Adjust options:
   - **Indent size**: Spaces per level.
   - **Wrap width**: Line wrap width (0 = no wrap).
   - **Charset**: Unicode, ASCII, or minimal.
   - **Connector style**: Elbow, straight, or none.
   - **Advanced symbols**: Override TEE, ELBOW, PIPE, HLINE, SPACE.
3. Click **Render** to generate the tree.
4. Use buttons to **Copy** or **Download** the output.

---

## 📌 Example Input
Global Enterprise IT Infrastructure
  Core Network
    Routers
      Edge Router 1
      Edge Router 2
      Backbone Router
        Routing Table Updates
        BGP Sessions

---

## 📌 Example Output (Unicode / Elbow)
```
└─Global Enterprise IT Infrastructure
  └─Core Network
    └─Routers
      ├─Edge Router 1
      ├─Edge Router 2
      └─Backbone Router
        ├─Routing Table Updates
        └─BGP Sessions
```
---

## ⚙ Features

- Live preview while typing.
- Adjustable indentation and connector styles.
- Unicode, ASCII, or minimal symbol sets.
- Copy to clipboard or download as `.txt` or `.html`.
- Fully client-side, no backend needed.

---

Made with ❤️ by EzEldeen
