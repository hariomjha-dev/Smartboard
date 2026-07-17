# ✍️ AI Smartboard: Touchpad Handwriting Auto-Designer
visit: https://smartboard-smoky.vercel.app

An interactive, web-based digital smartboard engineered specifically for laptop trackpads and touchpads. Writing on a standard trackpad with a finger naturally results in jagged, messy lines. This application captures those raw coordinate paths, routes them through a native handwriting recognition engine, and instantly substitutes the scribbles with clean, beautiful, formatted typography precisely where you drew it.

---

## ✨ Features

*   **Live Touchpad Optimization:** Uses advanced coordinate tracking designed to interpret loose or shaky trackpad line inputs smoothly.
*   **AI Auto-Correction Engine:** Seamless integration with standard handwriting recognition API models. Pause writing for **1.2 seconds**, and your messy text turns into flawless digital fonts.
*   **Dynamic Typography Customization:** Choose between multiple designer handwriting styles, change colors dynamically, or resize text on the fly.
*   **Complete State Control (Undo / Redo):** Full tracking stack system allowing you to go backward and forward through your notes.
*   **Infinite Layout Canvas:** Every corrected text box is structured into a dynamic element that can be dragged and repositioned anywhere across your digital board.
*   **Responsive Engine:** Built-in viewport scaling that recalibrates canvas positions cleanly without dropping layout coordinates when resizing your browser.

---

## 🛠️ Built With

*   **HTML5 & CSS3:** Semantic markup and a fluid grid interface layout matching modern canvas spaces.
*   **Vanilla JavaScript (ES6+):** Pure, lightweight event tracking framework logic with zero bulky external dependencies.
*   **Google Web Fonts API:** Pre-integrated handwriting typefaces including *Caveat*, *Dancing Script*, and *Shadows Into Light*.
*   **Google Input Tools Engine:** Back-end translation routing for real-time ink matrix analysis.

---

## 🚀 Quick Start

Because this application is packaged entirely inside a **single, standalone HTML file**, running it requires no servers or build configurations:

1. Download or copy the code from `smartboard.html`.
2. Double-click the file to open it in **any modern web browser** (Chrome, Edge, Safari, Firefox).
3. Use your trackpad to draw a word or phrase, lift your finger, and watch it transform!

---

## ⌨️ Laptop & Keyboard Shortcuts

Make changes on your canvas instantly without needing to navigate back to the toolbar layout configuration area:

| Command | Action |
| :--- | :--- |
| `Ctrl + Z` (or `Cmd + Z`) | **Undo** the last converted text action |
| `Ctrl + Y` (or `Cmd + Y`) | **Redo** a previously undone text action |
| **Trackpad Hold & Drag** | Drag inside any active font box to move it anywhere on screen |

---

## 💡 Pro-Tips for Perfect Handwriting Translation

> 📌 **Write Separately:** For optimal recognition accuracy, try writing words clearly on a single baseline space rather than stacking letters vertically on top of each other.
>
> 📌 **Give It Space:** If a word is highly complex or messy, scale up your `Text Size` parameter or draw the letters larger on the touchpad; this provides richer matrix metrics to the translation framework.
