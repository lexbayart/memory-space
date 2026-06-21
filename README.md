# Memory Space ⛔️ [Beta]

> ⚠️ **Разработка приостановлена на неопределённый срок.**
> Development is paused indefinitely.

![App interface](images/0.jpg)

**[▶ Open in browser — try it now](https://lexbayart.github.io/memory-space/)**
No install. No account. Works offline.

---

## 🔷 What makes this different

Memory Space is built on the principles of **Holographic Memory** from Stanislav Muller's course at **[Город Талантов](https://talentcity.ru/)**. It's not a conventional note-taking app — it's a spatial knowledge environment where time is the primary axis of organization.

The timeline splits into two diverging lines: **past stretches to the left**, **future extends to the right**, with the present moment at the center. This left-right orientation mirrors how we naturally perceive time. The same structure is duplicated along a flat timeline bar at the bottom of the screen for precise navigation.

Every note is a node positioned by its date. Click a node to expand it into a card with full content, tags, and links to related notes. Edit notes inline — change text, colors, emojis, add or remove hashtags. The app remembers everything in localStorage.

Dark and light themes. Zoom mode for focused editing. Clustered views for distant notes that would otherwise clutter the view. Link lines connecting related notes. All of it runs in a single HTML file — no server, no database, no dependencies.

---

## ✨ Features

- 🗺️ **3D spatial timeline** — notes positioned along a perspective grid by date, from deep past to far future
- 🎯 **Interactive navigation** — drag the timeline bar to travel through time; scroll/wheel to move forward and backward
- 📝 **Rich note editing** — edit title, content, date, emoji, color, and hashtags inline with a full editor panel
- 🔗 **Link lines** — visual connections between related notes, drawn as animated SVG lines in 3D space
- 🔎 **Full-text search** — search across titles, content, and tags with an expanding pill interface
- #️⃣ **Hashtag filtering** — two sidebar columns of hashtags (cyan for past, purple for future); click to filter notes
- 🎨 **Color & emoji customization** — per-note color palette and emoji picker for visual organization
- 🌗 **Dark / light theme** — toggle with one keypress; full theme support across all UI elements
- 🔍 **Zoom mode** — focused editing view that hides HUD elements and scales the timeline
- 📦 **Clustered views** — distant notes are grouped into capsule clusters to reduce visual clutter
- ⭐ **Goal creation** — place future goals on the timeline with emoji markers
- ❄️ **Time freeze** — click the present anchor to pause auto-scrolling
- 💾 **Full localStorage persistence** — all edits, new notes, and settings saved locally
- 📱 **Touch support** — works on tablets and phones with touch gestures

---

## 🚀 Open it

**[▶ lexbayart.github.io/memory-space](https://lexbayart.github.io/memory-space/)**

Or download `index.html` from this repo and open it locally —
fully standalone, works without internet after first load.

---

## 📖 Documentation

- [**Complete User Guide**](docs/GUIDE.md) — tools, hotkeys, all features explained

---

## 🛠️ Tech

Vanilla JS · HTML5 Canvas (SVG overlays) · CSS 3D transforms · Web Animations API · localStorage
Single HTML file · Zero dependencies · Zero build step

---

## 💬 Feedback & Contact

⚠️ **Development is paused indefinitely.** This is an archived snapshot.
If you have ideas or want to fork and continue — go ahead (CC BY-NC 4.0).

- **Telegram:** [@lexbayart](https://t.me/lexbayart)
- **GitHub Issues:** [Open an issue](https://github.com/lexbayart/memory-space/issues)

---

## 🧪 Dev Notes

`docs/` contains developer documentation and audit notes from the project's development history.

---

## 📄 License

© 2025 lexbayart — [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)

Free to use and share for non-commercial purposes with credit.
Commercial use requires explicit permission from the author.
