<div align="center">

# 💌 Six Months of Us

### A little corner of the internet made with love 🤍

A single-page, scroll-through website celebrating a **6-month anniversary** —
sweet love notes, a live "days together" counter, and a playful surprise question at the end.

> 💝 I made this for my love, my amazing husband. 🤍

![HTML5](https://img.shields.io/badge/Built%20with-HTML%20%C2%B7%20CSS%20%C2%B7%20JS-d96c7b)
![No build step](https://img.shields.io/badge/Setup-zero%20build-f7dfe0)
![Made with](https://img.shields.io/badge/Made%20with-🤍-d96c7b)

</div>

---

## 💕 What is this?

**Six Months of Us** is a romantic, animated webpage built as an anniversary gift — because
some things deserve more than a text message. You scroll from top to bottom and the story unfolds
section by section, ending in a sweet little surprise.

It's a **single `index.html` file** — no frameworks, no build tools, no dependencies.
Just open it in a browser and it works.

---

## ✨ What's inside

| Section | What it does |
| --- | --- |
| 🌹 **Hero** | A soft opening — *"Six months of you & me"* with the anniversary date |
| 💌 **Love notes** | Handwritten-style cards with heartfelt messages, each gently tilted |
| ⏳ **Days counter** | Automatically counts the days since the start date and animates as you scroll |
| 💍 **The question** | A playful *"Do you wanna marry me?"* — the **No** button shrinks and runs away while **Yes** grows |
| 🎉 **Celebration** | A confetti-hearts shower and a loving message once **Yes** is tapped |

Little touches throughout: floating background hearts, fade-in-on-scroll animations,
elegant serif + handwritten fonts, and a warm cream-and-rose color palette.

---

## 🚀 How to view it

Just open the page — no installation needed:

```bash
# Option 1: open the file directly
open index.html        # macOS
xdg-open index.html    # Linux

# Option 2: serve it locally
python3 -m http.server 8000
# then visit http://localhost:8000
```

> 💡 It's also ready to host for free on **GitHub Pages**, **Netlify**, or **Vercel** —
> just point them at this repo and share the link.

---

## 🎨 Make it your own

The file is sprinkled with `✏️ EDIT` comments showing exactly what to change:

- **Names & dates** — update the hero text and set your own start date (`const startDate`).
- **Love notes** — rewrite the cards in your own words; add or remove as many as you like.
- **The question & messages** — personalize the question, the playful nudges, and the celebration.
- **Colors** — tweak the palette at the top of the `<style>` block (`--cream`, `--rose`, `--gold`, …).

---

## 🛠️ Tech

- **HTML + CSS + vanilla JavaScript** — one file, zero dependencies
- **Google Fonts** — *Cormorant Garamond* (serif) & *Caveat* (handwritten)
- CSS animations + the `IntersectionObserver` API for scroll effects

---

<div align="center">

Made with 🤍 &nbsp;·&nbsp; *here's to six months — and all the months after*

</div>
