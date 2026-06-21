# Memory Space — Complete User Guide

> A beginner's guide to navigating, editing, and organizing your personal knowledge in 3D space.

---

## 🖱️ Getting Started

Memory Space opens directly in your browser. No installation needed.

**To open:**
- Visit [lexbayart.github.io/memory-space](https://lexbayart.github.io/memory-space/)
- Or download `index.html` and open it in any modern browser

**What you see:**
- A 3D perspective grid stretching into the distance
- Floating circular nodes — each represents a note, positioned by date
- A timeline bar at the bottom with a green marker at "today"
- Two hashtag columns on the left and right edges of the screen
- A search pill at the top center

---

## 🧭 Navigation

### Moving through time

- **Drag the timeline bar** — click and drag the green marker or the bar itself to jump to any date
- **Scroll wheel / swipe** — scroll forward to move into the future, backward to move into the past
- **Click a timeline tick** — each date marker on the bar is clickable

### The present anchor

- The green diamond at center of the timeline marks "today"
- **Click the present anchor** to toggle time freeze — when frozen (white square), the view stops auto-scrolling
- Click again to resume

### Zoom mode

- Enter zoom mode to get a closer, focused view of the timeline for editing
- In zoom mode, the HUD (search, date) slides away and the timeline scales up
- Exit zoom mode to return to the full view

---

## 📝 Working with Notes

### Opening a note

- **Click any node** on the timeline to open its card
- The card shows: emoji, type label, date, title, subtitle, full content, tags, and linked notes
- **Click the ✕ button** or click empty space to close the card

### Editing a note

- Click the **edit button** (top-left of the card) to enter edit mode
- In edit mode you can change:
  - **Title** — text field
  - **Content** — rich text area with formatting toolbar (bold, italic, etc.)
  - **Date** — draggable date field; also shows a grab cursor
  - **Emoji** — click the emoji to open the emoji picker with search
  - **Color** — click the color swatch to open the color palette
  - **Hashtags** — click hashtags from the sidebar columns to add/remove them from the note
- Click **Save** to confirm changes (saved to localStorage automatically)

### Linking notes

- Notes can be linked to each other — links appear as animated SVG lines in 3D space
- When you hover a note, its connections light up
- Linked notes are shown as clickable buttons at the bottom of the card

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `T` | Toggle dark / light theme |
| `D` | Toggle debug panel (developer info) |
| `K` | Toggle debug mode (shows pixel offsets on timeline) |
| `Escape` | Close search / close card / exit current mode |

---

## 🔎 Search

- **Hover or click the search pill** (🔎 icon at top center) to expand the search bar
- Type to search across all note titles, content, and tags
- Active search results are highlighted; non-matching notes fade out
- Press `Escape` to clear search and close the pill
- Search hashtags appear as colored badges in the expanded pill

---

## #️⃣ Hashtag Filtering

Two hashtag columns flank the screen:
- **Left column (cyan)** — tags from past notes
- **Right column (purple)** — tags from future notes

**To filter:**
- Click any hashtag to filter notes by that tag
- Multiple hashtags can be active simultaneously (AND filter)
- Active hashtags appear as badges in the search pill
- Click a badge to remove that filter
- In edit mode, all hashtags are always visible and clickable

---

## ⭐ Goals

- In zoom mode, you can create a **goal** — a future marker on the timeline
- Goals appear as golden squares on the timeline bar
- Click a goal to see its details
- Goals help you visualize future milestones alongside past notes

---

## 🎨 Themes

- **Dark theme** (default) — neon cyan and purple on deep black
- **Light theme** — soft blues and purples on white
- Press `T` to toggle at any time
- Theme preference is remembered

---

## ⚠️ Known Limitations

- All data is stored in browser localStorage — clearing browser data will delete your notes
- No cloud sync or cross-device support
- No user accounts or authentication
- Single-file app — all code, styles, and data in one HTML file
- Development is paused — no updates planned at this time

---

*This guide covers Memory Space v15. The app is archived — development paused indefinitely.*
