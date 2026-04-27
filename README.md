<div align="center">

<br/>

# ✦ NoteStudio

**A beautifully crafted, offline-first notes app — built as a single HTML file.**

<br/>

[![PWA Ready](https://img.shields.io/badge/PWA-Ready-b78fff?style=for-the-badge&logo=googlechrome&logoColor=white)](#)
[![Works Offline](https://img.shields.io/badge/Works-Offline-64e0c8?style=for-the-badge)](#)
[![Language](https://img.shields.io/badge/EN%20%7C%20RO-Bilingual-b78fff?style=for-the-badge)](#)
[![HTML](https://img.shields.io/badge/Single-HTML%20File-64e0c8?style=for-the-badge)](#)

<br/>

> 📝 Write. 🎨 Style. 💾 Save. — All on your device, all offline.

<br/>

🔗 **[Privacy Policy](https://gabrielbogdan5.github.io/NoteStudio-web/politica-de-privacitate.html)** · **[Feature Graphic](https://gabrielbogdan5.github.io/NoteStudio-web/grafică-feature.html)** · 📧 **[notestudiocontact@gmail.com](mailto:notestudiocontact@gmail.com)**

<br/>

</div>

---

## ✦ What is NoteStudio?

NoteStudio is a **single-file PWA** note-taking app with a rich text editor, multiple themes, and full offline support via Service Worker.

- ✅ No account needed
- ✅ No data leaves your device
- ✅ Works without internet after first load
- ✅ Installable as a native-like app (PWA)

---

## ✦ Features

| | Feature | Details |
|:---:|---|---|
| 📝 | **Rich Text Editor** | Bold, italic, underline, font colors, headings, lists, alignment |
| 🎨 | **3 Themes** | Dark, Light, Sepia — saved automatically |
| 🔍 | **Instant Search** | Search across all notes in real time |
| 💾 | **Auto-Save** | Notes save as you type |
| 📤 | **Export to .docx** | Download any note as a Word document |
| 📶 | **Offline-First** | Full PWA with Service Worker — works without internet |
| 🌍 | **Bilingual** | English & Romanian — switch anytime in Settings |
| 🎨 | **Color Labels** | Color-code notes for quick visual organization |
| ⌨️ | **Shortcuts** | `Ctrl+S` · `Ctrl+N` · `Ctrl+B` · `Ctrl+I` |
| 📱 | **Mobile Ready** | Collapsible sidebar & toolbar for small screens |

---

## ✦ File Structure

```
NoteStudio-web/
├── index.html                  # The entire app — self-contained
├── sw.js                       # Service Worker (3-strategy caching)
├── manifest.json               # PWA manifest
├── icon-192x192.png            # App icon
├── icon-512x512.png            # App icon (large)
├── politica-de-privacitate.html  # Privacy policy
├── grafică-feature.html          # Google Play feature graphic
└── README.md                   # This file
```

---

## ✦ Offline & PWA Support

The Service Worker uses **3 caching strategies**:

| Strategy | Used For |
|---|---|
| **Cache-First** | App shell (HTML, icons, manifest) — instant load |
| **Stale-While-Revalidate** | Google Fonts & CDN — served from cache, updated silently |
| **Network-First** | Everything else — cache fallback when offline |

Ad network requests (AdMob) are **never intercepted** — they always go directly to the network.

---

## ✦ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + S` | Save note |
| `Ctrl + N` | New note |
| `Ctrl + B` | Bold |
| `Ctrl + I` | Italic |

---

## ✦ Tech Stack

| Technology | Purpose |
|---|---|
| Vanilla HTML / CSS / JS | Core app — zero build tools, zero dependencies |
| `localStorage` | Note & preference persistence |
| Service Worker API | Offline support & caching |
| Web App Manifest | PWA installability |
| docx.js (CDN) | Word document export |
| Google AdMob | Monetization |
| Google Fonts | Typography (DM Sans, Playfair Display) |

---

## ✦ Privacy

Full privacy policy: 👉 [politica-de-privacitate.html](https://gabrielbogdan5.github.io/NoteStudio-web/politica-de-privacitate.html)

- Notes are stored **only on your device**
- The free version uses **Google AdMob** — see [Google's Privacy Policy](https://policies.google.com/privacy)
- No analytics, no tracking, no accounts

---

## ✦ Contact

📧 [notestudiocontact@gmail.com](mailto:notestudiocontact@gmail.com)

---

<div align="center">

© 2025 **NoteStudio** · Made with ♥

</div>
