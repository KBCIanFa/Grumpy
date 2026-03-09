# 😤 The Grumpy Old Man Course

> *Australia's Premier Educational Institution for Advanced Whinging & Certified Curmudgeonry*

A tongue-in-cheek, fully interactive single-page web app for learning the ancient Aussie art of having a good whinge — without being a complete muppet about it.

Hosted on GitHub Pages. No server. No database. No nonsense.

---

## 🎓 What Is This?

The Grumpy Old Man Course is a humour project built as a single self-contained HTML file. It covers 12 modules of time-honoured Australian complaining, from the sacred art of the wheelie-bin side-eye to the dark craft of turning a weather forecast into a comprehensive economic critique.

Everything runs in the browser. Progress is saved to `localStorage`. The AI sidekick calls the Groq API directly from the user's browser — no backend required.

---

## ✨ Features

| Feature | Description |
|---|---|
| **12 Course Modules** | Tick off topics as you master them. Progress saved locally. |
| **Grump-O-Meter™** | Paste a rant, get it rated out of 10 by AI with an animated gauge needle. |
| **Spin the Complaint Wheel** | Animated SVG wheel picks today's grievance at random. |
| **Rant Starter Generator** | 8 topics × 4 classic opening lines to get you warmed up. |
| **Polite → Grumpy Converter** | AI rewrites your overly-reasonable text with some backbone. Offline fallback included. |
| **Grumpy Old Man Bingo** | 5×5 bingo card with real win detection and confetti. New card each game. |
| **Old Mate Grump AI Chat** | Full chat interface powered by Groq. Quick-prompt buttons included. |
| **Grumpy Certificate** | Downloadable PDF certificate with your name, grump level, and completed modules. |
| **AI Settings Panel** | Paste your Groq key in the sidebar. Stored in browser only, never leaves your device. |

---

## 🚀 Setup & Hosting

### GitHub Pages (recommended)

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Click **Save** — your site will be live at `https://yourusername.github.io/your-repo-name/`

That's it. The file is completely self-contained.

### Local

Just open `index.html` in any modern browser. No build step, no `npm install`, no drama.

---

## 🤖 AI Setup (Free — Takes 2 Minutes)

The AI features use the **Groq API** — free tier, no credit card required, genuinely fast.

1. Go to [console.groq.com/keys](https://console.groq.com/keys) and sign up
2. Click **Create API Key** and copy it
3. Open the course, paste your key into the blue setup banner at the top (or in the AI Settings panel in the chat section)
4. Hit **Save Key** — the banner disappears and AI goes live

**Your key is stored in the visitor's browser only.** It is sent directly from their browser to Groq's API. It never touches any other server, including GitHub.

> **No key?** No problem. The app runs in demo mode with canned grumpy responses. All non-AI features (bingo, wheel, rant starters, offline converter, certificate) work with no key at all.

### Changing the AI Model

Default model is `llama-3.1-8b-instant` (fast, free). You can change it in the AI Settings panel. Any Groq-hosted model works, e.g.:

- `llama-3.3-70b-versatile` — smarter, slightly slower
- `mixtral-8x7b-32768` — longer context window
- `gemma2-9b-it` — Google's Gemma 2

---

## 📋 Course Modules

1. Neighbours, Bins & Lawns
2. Kids These Days
3. Prices & Cost of Living
4. Government & Bureaucracy
5. Traffic, Utes & Bad Driving
6. Supermarkets & Queues
7. Technology & Gadgets
8. Traditions & Back in My Day
9. Weather & Small Talk
10. Modern Manners & Etiquette
11. Bloody Donald Trump
12. Bloody Fuel Prices

---

## 🛠️ Tech Stack

- **Pure HTML / CSS / JavaScript** — zero dependencies, zero build tooling
- **[Groq API](https://groq.com)** — AI responses (user-supplied key, free tier)
- **[jsPDF](https://github.com/parallax/jsPDF)** — certificate PDF generation (loaded from CDN)
- **[Google Fonts](https://fonts.google.com)** — Playfair Display, Libre Baskerville, Special Elite

No frameworks. No bundlers. No node_modules folder of shame.

---

## 📁 File Structure

```
/
└── index.html       # The entire application — HTML, CSS, and JS in one file
└── README.md        # You're reading it
```

---

## 🎨 Customisation

Everything is in `index.html`. Key sections:

| What | Where in the file |
|---|---|
| Course modules | `const topics = [...]` |
| Rant starter lines | `const starters = {...}` |
| Spin wheel topics | `const WT = [...]` |
| Bingo squares | `const BW = [...]` |
| AI system prompt | `const SYS = \`...\`` |
| Colour scheme | `:root { --ink: ... }` in `<style>` |

---

## ⚠️ Disclaimer

This is satire and humour, not life advice, legal counsel, or therapy. The course celebrates the Aussie tradition of harmless whinging — the kind that ends with a laugh and a cup of tea, not a restraining order.

Any resemblance to real grumpy old men, living or muttering, is entirely deliberate and deeply affectionate.

---

## 👤 Author

**Ian Fraser** — The Grumpy Old Man Project

---

*Use your grump powers responsibly.*
